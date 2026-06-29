# 📚 Educational Gap Analysis in Punjab

A Data Science and Machine Learning project that analyzes educational inequality between **North/Central Punjab** and **South Punjab** using statistical analysis, feature engineering, predictive modeling, and explainable AI.

---

## 📖 Project Overview

This project investigates the educational gap across Punjab districts by analyzing enrollment and literacy rates. It combines traditional statistical techniques with machine learning models to determine whether enrollment indicators can accurately classify a district's region.

The project also demonstrates explainable AI using SHAP to understand which educational factors contribute most to the model's predictions.

---

## 🎯 Objectives

- Analyze literacy and enrollment disparities between North/Central Punjab and South Punjab.
- Perform statistical hypothesis testing.
- Engineer meaningful educational features.
- Train and compare machine learning and deep learning models.
- Explain model predictions using SHAP.
- Support Sustainable Development Goal 4 (Quality Education).

---

## 📂 Dataset

The dataset contains **641 district-year records** with educational statistics from Punjab.

### Features include:

- District
- Region
- Year
- Overall Enrollment Rate
- Girls Enrollment Rate
- Boys Enrollment Rate
- Rural Enrollment Rate
- Urban Enrollment Rate
- Overall Literacy Rate
- Girls Literacy Rate
- Boys Literacy Rate

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- TensorFlow / Keras
- SHAP

---

## 🛠️ Methodology

### 1. Data Preprocessing

- Missing value imputation using regional medians
- Handling infinite values
- Data cleaning

### 2. Feature Engineering

Created two additional features:

- Gender Parity Index
- Urban-Rural Enrollment Disparity

### 3. Exploratory Data Analysis

- Distribution plots
- Bar charts
- Correlation heatmaps
- Regional comparisons

### 4. Statistical Analysis

Performed Welch's t-test to verify whether literacy differences between regions are statistically significant.

### 5. Machine Learning Models

- Random Forest Classifier
- LSTM Neural Network

### 6. Explainable AI

Used SHAP values to explain the Random Forest model's predictions.

---

## 📊 Results

| Model | AUC | Accuracy |
|------|------|-----------|
| Random Forest | 0.949 | 86% |
| LSTM | 0.947 | 85% |

### Key Findings

- South Punjab has significantly lower literacy and enrollment rates.
- The educational gap is statistically significant.
- Random Forest achieved the best overall performance.
- SHAP analysis identified the most influential educational indicators.

---

## 📁 Project Structure

```
Educational-Gap-Analysis/
│
├── dataset/
│   └── Educational_Gap_Punjab.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── models/
│
├── figures/
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Educational-Gap-Analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📈 Visualizations

The project includes:

- Literacy distribution by region
- Enrollment comparison charts
- Correlation heatmap
- ROC curves
- SHAP summary plots

---

## 🎓 Course Information

**Course:** Programming for AI (AI2151)

**Program:** BS Artificial Intelligence

**University:** University of Management and Technology (UMT), Lahore

---

## 👩‍💻 Author

**Maryam Jamshed**


---

## 📜 License

This project is developed for academic purposes.
