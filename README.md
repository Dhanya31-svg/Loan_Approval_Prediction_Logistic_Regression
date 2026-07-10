# 🏦 Loan Approval Prediction using Logistic Regression

## 📌 Project Overview

This project demonstrates an end-to-end Machine Learning workflow for predicting whether a customer's loan application is likely to be **Approved** or **Rejected** using **Logistic Regression**.

The project simulates a real-world banking scenario where customer financial information is analyzed to assist loan approval decisions. A synthetic dataset is created to mimic real customer records, followed by data preprocessing, feature engineering, model training, evaluation, hyperparameter tuning, and prediction on new customer data.

The notebook is designed to explain every step in a beginner-friendly yet interview-ready manner.

---

## 🎯 Business Problem

Banks receive thousands of loan applications every day. Manually evaluating every application is time-consuming and can lead to inconsistent decisions.

The objective of this project is to build a machine learning classification model that predicts whether a loan should be approved based on customer financial and personal information.

---

## 📊 Dataset

A synthetic dataset was generated using NumPy to simulate realistic banking data.

### Features

* Age
* Annual Income
* Credit Score
* Loan Amount
* Employment Years
* Existing Loans
* Savings
* Debt-to-Income Ratio
* Marital Status
* Home Ownership

### Engineered Features

* IncomePerLoan
* FinancialStrength
* CreditIncomeScore
* HighDebt

### Target Variable

* **1** → Loan Approved
* **0** → Loan Rejected

---

## ⚙️ Project Workflow

### 1. Data Generation

* Created a realistic synthetic banking dataset.
* Generated a binary target variable representing loan approval status.

### 2. Exploratory Data Analysis (EDA)

* Dataset inspection
* Statistical summary
* Missing value analysis
* Duplicate detection
* Class distribution
* Histograms
* Boxplots
* Correlation matrix

### 3. Data Preprocessing

* Missing value handling
* Duplicate removal
* Feature engineering
* Feature selection
* Train-test split
* Feature scaling using StandardScaler

### 4. Logistic Regression

* Sigmoid Function
* Probability prediction
* Decision boundary
* Model training

### 5. Model Evaluation

* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report
* ROC Curve
* ROC-AUC Score
* Threshold tuning

### 6. Regularization

* L1 Regularization (Lasso)
* L2 Regularization (Ridge)
* Elastic Net

### 7. Model Optimization

* Cross Validation
* GridSearchCV
* Hyperparameter tuning

### 8. Feature Interpretation

* Coefficient analysis
* Odds Ratio analysis
* Feature importance

### 9. Model Deployment Preparation

* Model saving using Joblib
* Scaler saving
* Prediction on new customer records

---

## 📈 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## 📊 Machine Learning Concepts Covered

* Binary Classification
* Logistic Regression
* Sigmoid Function
* Probability Estimation
* Feature Engineering
* Feature Scaling
* Model Evaluation Metrics
* Regularization
* Cross Validation
* Hyperparameter Tuning
* Model Persistence

---

## 🎯 Learning Outcomes

This project demonstrates the complete lifecycle of a binary classification machine learning project, from data generation to model deployment preparation. It provides practical experience with data preprocessing, feature engineering, classification algorithms, evaluation metrics, regularization techniques, and model optimization while following an industry-style workflow.

---

## 🚀 Future Improvements

* Deploy the model using Streamlit
* Add a web-based loan prediction interface
* Use real banking datasets
* Handle imbalanced datasets using SMOTE
* Build an ensemble classification model
* Compare Logistic Regression with Decision Tree, Random Forest, XGBoost, and Support Vector Machine

---

## 👩‍💻 Author

Developed as part of a Machine Learning portfolio to demonstrate practical implementation of Logistic Regression for a real-world binary classification problem.
