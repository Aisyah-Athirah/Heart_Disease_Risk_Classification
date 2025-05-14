# 🫀 Heart Disease Risk Prediction with Random Forest

This project presents a machine learning solution for predicting heart disease risk using a **Random Forest Classifier** trained on data from the CDC. It showcases the full ML pipeline: from data preprocessing and feature selection to model training and evaluation.

## 📊 Project Overview

- Dataset: CDC Heart Disease Indicators (2022)
- Goal: Predict risk of heart disease from personal, lifestyle, and clinical factors
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)

## 🔧 Methodology

- Data Cleaning: Handled missing values using random and KNN imputation
- Outlier Handling: IQR and Z-score methods
- Feature Selection: LassoCV (cross-validation)
- Data Balancing: SMOTE (Synthetic Minority Oversampling Technique)
- Model Training: Random Forest Classifier (`scikit-learn`)
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC

## 📈 Results

| Metric       | Score   |
|--------------|---------|
| Accuracy     | 97.40%  |
| Precision    | 97.98%  |
| Recall       | 96.79%  |
| F1-Score     | 97.38%  |
| ROC AUC      | 99.60%  |

## 📊 Visuals

- Confusion Matrix showing true/false predictions
- ROC Curve indicating excellent model discrimination

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
