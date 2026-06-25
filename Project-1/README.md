# Credit Scoring Model

## Overview

The **Credit Scoring Model** is a machine learning project that predicts a customer's **creditworthiness** based on their financial and credit history. The model classifies customers into three credit score categories—**Poor, Standard, and Good**—helping financial institutions assess credit risk and make informed lending decisions.

---

## Objectives

* Build a machine learning model for credit score classification.
* Perform comprehensive data cleaning and preprocessing.
* Analyze customer financial behavior using Exploratory Data Analysis (EDA).
* Compare multiple classification algorithms.
* Evaluate model performance using standard metrics.
* Predict credit scores for new customer data.

---

## Dataset

The project uses the **Credit Score Classification Dataset** from Kaggle, containing customer financial and credit-related information.

### Features

* Age
* Occupation
* Annual Income
* Monthly Inhand Salary
* Number of Bank Accounts
* Number of Credit Cards
* Interest Rate
* Number of Loans
* Type of Loan
* Delay from Due Date
* Number of Delayed Payments
* Changed Credit Limit
* Number of Credit Inquiries
* Credit Mix
* Outstanding Debt
* Credit Utilization Ratio
* Credit History Age
* Payment of Minimum Amount
* Total EMI per Month
* Amount Invested Monthly
* Payment Behaviour
* Monthly Balance

**Target Variable:** Credit Score *(Poor, Standard, Good)*

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Credit Score Prediction

---

## Data Preprocessing

The dataset was prepared using several preprocessing techniques:

* Missing value handling
* Duplicate record removal
* Cleaning invalid numerical values
* Label Encoding for categorical features
* Feature Scaling using **StandardScaler**
* Train-Test Split

---

## Exploratory Data Analysis

The following analyses and visualizations were performed:

* Credit Score Distribution
* Annual Income Analysis
* Correlation Heatmap
* Feature Importance Analysis
* Confusion Matrix
* Model Performance Comparison

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

Among all models, the **Random Forest Classifier** achieved the best overall performance and was selected as the final model.

---

## Project Structure

```text
Credit-Scoring-Model/
│
├── Credit_Scoring_Model.ipynb
├── train.csv
├── test.csv
├── README.md
```

---

## Applications

* Credit Risk Assessment
* Loan Approval Systems
* Banking & Financial Services
* Credit Card Eligibility Prediction
* FinTech Solutions

---

## Future Enhancements

* Hyperparameter Optimization (GridSearchCV)
* XGBoost & LightGBM Models
* Explainable AI using SHAP/LIME
* Streamlit Web Application
* Real-Time Prediction API

---

## Conclusion

This project demonstrates an end-to-end machine learning pipeline for credit score prediction, including data preprocessing, exploratory analysis, model training, evaluation, and prediction. The developed model can assist financial institutions in making faster and more reliable credit decisions.

---

## Author

**Mohan Chandra Appana**

B.Tech – Artificial Intelligence & Machine Learning

Vishnu Institute of Technology
