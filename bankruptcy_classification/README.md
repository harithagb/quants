# Bankruptcy Risk Prediction

## Project Title  
Predicting Corporate Bankruptcy Risk Using Financial Ratios

## Overview  
This project predicts the risk of bankruptcy for companies based on financial ratios. The dataset is highly imbalanced, and the modeling pipeline includes preprocessing, SMOTE for oversampling, feature selection, and multiple classification models.


## Key Techniques  
- Feature selection and transformation
- Handling class imbalance with SMOTE
- Ensemble models: Random Forest, XGBoost
- Evaluation metrics: ROC-AUC, F1, Confusion Matrix

## How to Run  
1. Open `bankruptcy_oya.ipynb` in a Jupyter environment.
2. Ensure dependencies are installed (`xgboost`, `imbalanced-learn`, `sklearn`).
3. Execute cells sequentially to preprocess, train, and evaluate models.

## Possible Extensions  
- Add SHAP/LIME for feature explainability
- Incorporate macroeconomic indicators
- Train time-aware models (e.g., survival models, LSTMs)
