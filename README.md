# Customer Transaction Prediction

## Overview
This project predicts whether a customer will make a future transaction using machine learning. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model building, handling class imbalance, and performance evaluation.

## Dataset
- Santander Customer Transaction Prediction
- ~200,000 records
- 200 anonymized numerical features
- Binary target variable (Transaction / No Transaction)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM
- SMOTE

## Models Implemented
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM

## Key Techniques
- Data Preprocessing
- Feature Scaling
- SMOTE for Class Imbalance
- Hyperparameter Tuning
- Feature Selection
- Cross Validation
- Model Evaluation

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results
Ensemble models outperformed the baseline Logistic Regression model. SMOTE improved minority class prediction, while feature selection and cross-validation improved model reliability.
