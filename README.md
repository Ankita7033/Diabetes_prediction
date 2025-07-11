# Diabetes Prediction Project

**Overview:**

This project focuses on predicting diabetes using machine learning techniques. The notebook demonstrates the entire workflow from data preprocessing to model evaluation, with a particular emphasis on handling imbalanced datasets and feature selection.

**Key Features**

Data preprocessing and feature engineering

Handling class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

Feature selection to identify the most important predictors

Hyperparameter tuning for Random Forest classifier

Model evaluation with optimal classification threshold selection

Performance metrics including accuracy, ROC AUC, precision, recall, and F1 score

**Results**

The optimized Random Forest model achieved:

Accuracy: 80.30%

ROC AUC: 0.8799

Precision: 0.7581

Recall: 0.8900

F1 Score: 0.8188

**Requirements**

The notebook shows the installation of the following Python packages:

imbalanced-learn

xgboost

lightgbm

**How to Use**

Install the required packages

Run the notebook cells sequentially

The notebook demonstrates the complete workflow from data loading to model evaluation

**Selected Features**

The model identified these important features:

DiabetesPedigreeFunction

Age

Glucose_BMI_Interaction

Age_Glucose_Ratio

BMI_Age_Interaction

Glucose_squared

**Best Parameters**

The hyperparameter tuning resulted in these optimal parameters for Random Forest:

bootstrap: True

class_weight: {0: 1, 1: 2}

max_depth: 20

max_features: 0.7

min_samples_leaf: 2

min_samples_split: 3

n_estimators: 400

Optimal Threshold
The classification threshold was optimized to 0.4444 for best performance.
