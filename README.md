# CIND820-Capstone-Project

This respository for my CIND 820 Capstone Project - Credit Card Fraud Detection, consists of codes, data, and technical reports branches.

Project dataset available on Kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud. The dataset contains 284,807 transactions made by credit cards in September 2013 by European cardholders. 492  out of 284,807 transactions are frauds. Unfortunately, due to confidentiality issues, the original features were not provided, but only numerical input variabls as the results of a PCA transformation were provided.

Tentative project stages:
1. Problem definition and data collection. Problem for this project is defined as developing high-performance machine learning models for credit card fraud detection. Dataset is obtained from Kaggle.com (see above). Many research papaers use stimulated datasets. To ensure the authenticity of the dataset and the resarch project, this dataset is chosen as it contains real transaction data.
2. Exploratory analysis, including checking data structure, any missing values and outliners, ploting feature distributions and feature correlation.
3. Preprocessing, including replacing missing values and eliminating outliners (if neccessary), rescaling/normalizing features, and feature selection based on feature correlation and subject matter knowledge.
4. Preparation of subsets with different sampling methods for training the models - undersampling of majority, oversampling of minority, and combining undersampling with oversampling.
5. Model training, including data split for training & testing and cross-validation, regularization if necessary (model overfitting), and hyperparameter tuning.
- Logistic Regression
- Random Forest
- Support Vector Machine
6. Model evaluation, using metrics suitable for the context of the issue and imbalanced datasets.
- f1 score (precision and recall)

Structure of the repository:
1. Data
2. Codes, contains ipynd notebooks with results.
3. Technial reports, contains results in PDF.
