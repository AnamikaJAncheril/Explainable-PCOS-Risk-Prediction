# 🩺 Explainable AI-Based PCOS Risk Assessment System

## 📌 Project Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common hormonal disorders affecting women of reproductive age. Early diagnosis is challenging because symptoms vary significantly among individuals.

This project leverages Machine Learning and Explainable AI (XAI) to predict PCOS risk using clinical and lifestyle factors. In addition to making predictions, the system explains which features contribute most to the prediction, making the model more transparent and trustworthy.

---

## 🎯 Objectives

- Predict the likelihood of PCOS using patient health data.
- Compare and analyze important clinical features.
- Build a high-performance machine learning model.
- Apply Explainable AI techniques to interpret predictions.
- Support early screening and healthcare awareness.

---

## 📊 Dataset

The dataset contains information related to:

- Age
- Weight
- BMI
- Menstrual Cycle Information
- Follicle Count
- Hormonal Levels
- Hair Growth
- Skin Darkening
- Weight Gain
- Fast Food Consumption
- Other clinical indicators

### Dataset Files

- `PCOS_data_without_infertility.xlsx`
- `PCOS_infertility.csv`

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- Joblib

### Machine Learning
- Random Forest Classifier
- GridSearchCV Hyperparameter Tuning

---

## 🔄 Project Workflow

### 1. Data Preprocessing

- Data Loading
- Dataset Merging
- Missing Value Handling
- Data Cleaning
- Feature Engineering

### 2. Exploratory Data Analysis (EDA)

- Correlation Analysis
- Heatmaps
- Feature Distribution Analysis
- PCOS vs Non-PCOS Comparison

### 3. Feature Selection

Features with significant impact on PCOS prediction were identified through:

- Correlation Analysis
- Feature Importance Analysis
- SHAP Explainability

### 4. Model Building

Random Forest Classifier was trained on the processed dataset.

### 5. Hyperparameter Tuning

GridSearchCV was used to identify the best-performing model parameters.

### 6. Model Evaluation

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7. Explainable AI

SHAP (SHapley Additive Explanations) was used to explain model predictions and identify the most influential features.

---

## 📈 Results

### Model Performance

| Metric | Score |
|----------|----------|
| Accuracy | 92.4% |
| Precision | 95% |
| Recall | 79% |
| F1-Score | 86% |

---

## 🧠 Most Important Features

According to Feature Importance Analysis and SHAP:

1. Follicle No. (R)
2. Follicle No. (L)
3. Weight Gain (Y/N)
4. Hair Growth (Y/N)
5. Skin Darkening (Y/N)
6. Fast Food Consumption (Y/N)
7. Cycle Length
8. Pimples (Y/N)
9. Cycle Regularity
10. AMH Level

These features contributed most significantly to PCOS prediction.

---

## 🔍 Explainable AI (SHAP)

SHAP was used to understand how each feature influences the model's predictions.

Benefits:

- Improves model transparency
- Identifies key contributing factors
- Enhances trust in predictions
- Supports healthcare decision-making

---

## 📂 Repository Structure

```text
Explainable-PCOS-Risk-Prediction/
│
├── PCOS_data_without_infertility.xlsx
├── PCOS_infertility.csv
├── pcos_project.ipynb
├── pcos_project.py
├── pcos_model.pkl
└── README.md
```

---

## 🚀 Future Improvements

- Streamlit Web Application
- Personalized Health Recommendations
- Risk Score Visualization
- Patient Report Generation
- Real-time Prediction Dashboard
- Integration with Healthcare Systems

---

## 👩‍💻 Author

**Anamika J Ancheril**

B.Tech Computer Science & Engineering (AI)

Passionate about:
- Artificial Intelligence
- Machine Learning
- Healthcare Technology
- Women's Health Innovation

---

## ⭐ Project Highlights

✅ Random Forest Classification

✅ Hyperparameter Tuning using GridSearchCV

✅ Explainable AI using SHAP

✅ 92.4% Accuracy

✅ Feature Importance Analysis

✅ Healthcare-focused Machine Learning Solution

---

### If you found this project useful, consider giving it a ⭐ on GitHub.
