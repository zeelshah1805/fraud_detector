# fraud_detector
Fraud Detection System

## Overview
This project aims to detect fraudulent credit card transactions using machine learning. The dataset contains anonymized features (`V1-V28`), transaction amounts, and labels (`Class`) indicating fraud (1) or legitimate transactions (0).

## Key Steps

1. **Data Preprocessing**:
   - Handle missing values
   - Standardize features
   - Split data into training and testing sets
   - Balance data using SMOTE (Synthetic Minority Oversampling Technique)

2. **Model Training**:
   - Train multiple classifiers: Logistic Regression, Random Forest, and XGBoost.
   - Evaluate performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

3. **Model Selection**:
   - Based on evaluation metrics, the best-performing model (XGBoost) is selected.

4. **Hyperparameter Tuning**:
   - Perform Grid Search for hyperparameter optimization of the Random Forest model.

5. **Model Serialization**:
   - Save the trained model using `joblib` for future predictions.

## Conclusion
The project successfully identifies fraudulent credit card transactions using a variety of machine learning techniques. After preprocessing the data and balancing the dataset, multiple models were trained and evaluated. The XGBoost classifier performed the best, with optimal performance metrics across the board. The model can be deployed in real-time systems to detect fraud efficiently.


