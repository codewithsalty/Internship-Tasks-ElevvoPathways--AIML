# Task 4: Loan Approval Prediction

## Project Overview

A binary classification system that predicts loan approval status using Logistic Regression and Decision Tree models. The dataset (300 applications) is imbalanced, so SMOTE was applied during training for better minority class handling. Includes an interactive Streamlit web app with single prediction, batch processing, and model insights.

**Status:** Complete and Production Ready
**Last Updated:** October 22, 2025

---

## Objectives

- Load and explore the loan application dataset
- Handle class imbalance using SMOTE
- Train and compare Logistic Regression vs Decision Tree
- Evaluate using accuracy, precision, recall, F1, and ROC-AUC
- Deploy as an interactive Streamlit web application

---

## Dataset

**Source:** Loan approval dataset (300 records)

**Features (10 total):**
- Age, Income, Credit Score, Employment Years, Loan Amount
- Gender (M/F), Marital Status (Yes/No), Dependents (0-4)
- Education (Graduate/Not Graduate), Self Employed (Yes/No)

**Target:** Approved / Rejected

**Imbalance:** 70-30 split, SMOTE applied

---

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|--------|-------------------|---------------|
| Accuracy | 26.67% | 58.33% |
| Precision | 13.89% | 31.58% |
| Recall | 27.78% | 33.33% |
| F1-Score | 18.52% | 32.43% |
| ROC-AUC | 0.2937 | 0.4749 |

**Best Model:** Decision Tree

**Most Important Features:** Income (23.3%), Dependents (21.7%), Age (17.0%)

---

## Streamlit App

Three interactive tabs:

- **Single Prediction** — Input applicant details, view LR vs DT predictions with ensemble voting, probability bars, and approval decision
- **Batch Prediction** — Upload CSV for bulk loan processing with approval statistics, confidence distribution, and downloadable results
- **Model Insights** — Performance metrics comparison table, bar chart, and feature importance visualisation

---

## Tech Stack

Python 3.8+, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Streamlit, Joblib, Cloudpickle

---

## Screenshots

### Single Prediction
Input applicant details and compare Logistic Regression vs Decision Tree predictions with ensemble voting.

![Single Prediction](screenshots/student_loan_approval%20(1).png)

### Prediction Results
Probability visualisation and approval decision with confidence scores.

![Prediction Results](screenshots/student_loan_approval%20(2).png)

### Batch Processing
Upload CSV for bulk loan approval predictions with statistics.

![Batch Processing](screenshots/student_loan_approval%20(3).png)

### Model Insights
Performance metrics comparison between Logistic Regression and Decision Tree.

![Model Insights](screenshots/student_loan_approval%20(4).png)

### Feature Importance
Decision Tree feature importance showing Income, Dependents, and Age as top predictors.

![Feature Importance](screenshots/student_loan_approval%20(5).png)

---

**Status:** Complete and Production Ready
**Live:** https://approveyourloan.streamlit.app/
**Last Updated:** October 22, 2025
