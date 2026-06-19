# Customer Conversion Prediction using Machine Learning

## Overview

This project predicts whether a customer will convert based on historical customer behavior and marketing interaction data.

The goal is to build a machine learning classification model that helps businesses identify high-potential customers and improve marketing conversion rates.

---

## Problem Statement

Customer conversion prediction is a binary classification problem:

- 1 → Customer converted
- 0 → Customer did not convert

The dataset contains customer demographics, engagement metrics, and behavioral features.

---

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Data Cleaning
4. Handling Missing Values
5. Feature Encoding
6. Train-Test Split
7. Model Training
8. Model Comparison
9. Threshold Optimization
10. Model Evaluation

---

## Machine Learning Models Used

- Logistic Regression
- Random Forest
- CatBoost Classifier
- XGBoost Classifier

---

## Model Evaluation

Since conversion datasets are usually imbalanced, F1-score was selected as the main evaluation metric.

Results:

| Model | F1 Score |
|---|---|
| Logistic Regression | 0.549 |
| Random Forest | 0.566 |
| XGBoost | 0.560 |
| CatBoost | 0.575 |

Best Model:

CatBoost Classifier

---

## Techniques Used

- Missing value handling
- One-hot encoding
- Class balancing
- Ensemble learning
- Hyperparameter tuning
- Probability threshold optimization

---

## Results

The final CatBoost model achieved:

F1 Score: 0.575

Optimized decision threshold improved conversion detection compared to the default 0.5 threshold.

---

## Technologies

Python

Libraries:
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Matplotlib
- Seaborn

---

## Future Improvements

- Deploy using Flask/FastAPI
- Add Streamlit dashboard
- Perform SHAP explainability analysis
- Hyperparameter optimization using Optuna

---

## Author

Kristan
