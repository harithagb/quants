Project Title: Predicting Corporate Bankruptcy Risk Using Financial Ratios

Overview:
This project predicts bankruptcy risk using supervised learning models applied to a labeled dataset of companies with financial indicators. The objective is binary classification: bankrupt vs. non-bankrupt firms.

Project Structure:

bankruptcy_oya.ipynb: Main notebook with EDA, feature selection, model building, and evaluation.

bankruptcy_helper.py: Functions for scaling, feature engineering, model scoring.

Uses ensemble methods, logistic regression, and neural nets for comparison.

Core Techniques:

SMOTE for class imbalance

Feature selection (correlation, domain relevance)

Logistic Regression, Random Forest, XGBoost, MLP

Cross-validation, confusion matrix, F1 score

How to Run:

Install required packages (scikit-learn, xgboost, imblearn).

Open bankruptcy_oya.ipynb and run all cells.

Modify helper functions as needed in bankruptcy_helper.py.

Extensions:

Explainability with SHAP or LIME

Time-series modeling for financial health tracking

Deploy in financial risk dashboards

