# Online-Shoppers-Purchasing-Intention
## Predicting Online Shoppers' Purchasing Intention
# Business Problem
The goal of this project is to predict whether a visitor to an e-commerce website will make a purchase or not. This helps online retailers optimize their marketing strategy and increase revenue.

# Data
The dataset is from the UCI Machine Learning Repository containing 12,330 sessions with 18 features like time spent, pages visited, operating system etc. The target variable is 'Revenue' indicating if a purchase was made.

# Methods
The analysis methodology follows these key steps:

Exploratory Data Analysis: Visualizations to understand feature relationships
Data Preprocessing: Handling missing values, encoding categorical variables, balancing class imbalance with SMOTE
Feature Engineering: Scaling and dimensionality reduction using PCA
Modeling: Training and evaluating Logistic Regression, Decision Tree, Random Forest, Naive Bayes, XGBoost models
Evaluation: Comparing model performance using Accuracy, F1 Score, ROC AUC and selecting the best model
# Key Results
Random Forest performed the best with 90% accuracy and 0.923 ROC AUC
Tuning hyperparameters and early stopping reduced model overfitting
Time spent on product pages highly correlated with purchase intention
# Repository Contents
Notebooks for EDA, data preprocessing, feature engineering, ML modeling and evaluation
Model files, encoded dataset pickles, documentation


The repository contains the full machine learning workflow from data ingestion to model deployment for predicting online shoppers' purchasing intention.
