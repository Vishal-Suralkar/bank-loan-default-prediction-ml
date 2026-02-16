# 🏦 Bank Loan Default Prediction (End-to-End ML Project)

This project focuses on predicting whether a loan applicant is likely to default using machine learning classification models.

The goal is to help financial institutions reduce risk and improve credit approval decisions.

---

## Problem Statement

Loan defaults can lead to significant financial losses for banks.  
This project builds a predictive model that classifies applicants as high-risk or low-risk based on historical data.

---

## Dataset Overview

The dataset includes:

- Applicant Income
- Loan Amount
- Credit History
- Employment Details
- Demographic Information
- Loan Default Status (Target Variable)

Target:
- 0 → No Default  
- 1 → Default  

---

## Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Comparison
6. Evaluation using:
   - Confusion Matrix
   - Precision, Recall, F1 Score
   - ROC Curve & AUC
7. Feature Importance Analysis

---

## Models Used

- Logistic Regression
- Random Forest Classifier

---

## Results

- Accuracy: ~98%
- High Recall to minimize missed default cases
- ROC-AUC close to 1.0
- Random Forest performed best overall

The model effectively distinguishes between high-risk and low-risk loan applicants.

---

## Key Insights

- Credit history and income are major indicators of default risk.
- Model maintains strong performance even with class imbalance.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deployment using Streamlit or Flask
- Real-time loan risk scoring

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

##  Author

Vishal Suralkar  
Aspiring Data Analyst / Data Scientist
