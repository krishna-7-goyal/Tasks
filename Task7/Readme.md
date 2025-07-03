# Breast Cancer Classification with SVM
## This notebook applies Support Vector Machine (SVM) to classify breast cancer tumors as benign or malignant using the Breast Cancer Wisconsin dataset.

## Overview
- Performed Exploratory Data Analysis (EDA) to understand class distribution.
- Preprocessed data by dropping irrelevant columns and scaling features using StandardScaler.
- Trained SVM models with different kernel types: linear, rbf, poly, and sigmoid.
- Applied GridSearchCV to tune hyperparameters like C, gamma, and kernel.
- Evaluated and compared model performance to identify the best configuration.

## Result
- The tuned SVM model achieved high accuracy on the test set.
- Best parameters were selected using grid search.
