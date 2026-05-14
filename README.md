# Credit Risk Modeling

## Business Problem
This project focuses on developing a machine learning-based credit risk model to predict customer default probability and support data-driven credit approval decisions. Using historical customer behavior, payment activity, spending patterns, and balance information, the objective was to optimize credit approval strategies while balancing portfolio risk and expected revenue.

## Work Performed
The project involved large-scale data preprocessing, feature engineering, one-hot encoding, feature selection using XGBoost, hyperparameter tuning, SHAP explainability analysis, neural network modeling, and strategy optimization. Multiple machine learning models were evaluated using AUC metrics, and conservative versus aggressive approval strategies were analyzed using predicted default probabilities and expected portfolio revenue.

## Repository Contents

- `Credit Risk Modeling.ipynb`  
  Complete end-to-end workflow including preprocessing, feature engineering, modeling, SHAP analysis, and strategy evaluation.

- `Credit Risk Project PPT.pptx`  
  Final project presentation summarizing methodology, model performance, and business strategy recommendations.

## Note
The original dataset used in this project is publicly available through the AMEX Default Prediction competition on Kaggle and is not included in this repository.
(Download the data from https://www.kaggle.com/competitions/amex-default-prediction/data. 
Use “train_data.csv” and “train_labels.csv”. 
“train_labels.csv” shows default status of customers as of April 2018 (target variable). 
“train_data.csv” shows their activity in the last 13 months (April 2017 to April 2018). These characteristics are used to define independent variables)
