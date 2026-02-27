# codeAlpha_Credit_Scoring_Model


## Project Overview
This project builds a machine learning model to predict whether a credit card client will default next month.

## Dataset
Default of Credit Card Clients Dataset (UCI Taiwan 2005)
Kaggle Link: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

## Project Steps
- Data Cleaning (duplicates & null check)
- Feature Engineering
- Class Imbalance Handling (SMOTE)
- Feature Scaling
- Model Training (Logistic Regression, Random Forest)
- Hyperparameter Tuning
- Model Evaluation (Precision, Recall, F1, ROC-AUC)
- Model Export for Deployment

## Best Model
Random Forest with tuned hyperparameters.

## Deployment
Model and scaler exported using joblib:
- credit_risk_model.pkl
- scaler.pkl
