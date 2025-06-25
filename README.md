# Dream-Housing-Finance-Loan-Prediction-Project

## Overview
This project focuses on building a predictive model to determine loan eligibility for applicants of Dream Housing Finance. It aims to reduce manual effort and decision errors by using a machine learning model to predict whether a customer should be approved or rejected for a loan.

## Project Objective
To automate the loan eligibility process for Dream Housing Finance by building a predictive model that can accurately determine whether a customer should be approved or rejected for a home loan based on their personal and financial details.

## Tools 
- Pandas, NumPy for data manipulation
- Scikit-learn for machine learning
- Matplotlib, Seaborn for visualization

## Features
- Data cleaning and preprocessing
- Feature engineering
- Predictive Modelling
- Model evaluation metrics (accuracy, precision, recall, F1-score)
- Confusion matrix visualization

## Dataset
The dataset contains 614 loan applications with features including:
- Applicant income
- Credit history
- Loan amount
- Property area
- And other relevant financial/personal details
Source: Kaggle - Loan Prediction Dataset
Target Variable: Loan_Status (Y/N)

## Key Features & Insights
- Cleaned and preprocessed the data (handled missing values, label encoding).
- Performed exploratory data analysis to identify significant patterns.
- Trained and compared several machine learning models:
  Decision Tree
  Support Vector Machine (SVM)
  Random Forest
- Best performance achieved with Random Forest (accuracy ~80%).
- Identified credit history and income as key predictors of loan approval.

## Impact
This model helps Dream Housing Finance:
- Speed up the loan approval process.
- Reduce human error and bias.
- Make informed decisions based on customer profiles and risk levels

##  Future Improvements
1. Tune hyperparameters to further boost model performance.

2. Deploy the model as a simple web app using Streamlit or Flask.

3. Connect to a real-time loan application dashboard for live use.
