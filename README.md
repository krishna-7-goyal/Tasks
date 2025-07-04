# Task 1
Welcome to **Day 1**. This repository contains a python Notebook that walks through key data preprocessing, cleaning, and transformation steps—commonly used as the foundation in data science or machine learning workflows.

## Contents
 - Data loading
  - Handling missing values
  - Encoding categorical variables
  - Outlier detection
  - DataFrame manipulations and conversions
  - Exploratory operations


## Topics Covered
   - Pandas DataFrame operations
     -Encoding: LabelEncoding, OneHotEncoding
     -Handling missing data
     -Outlier detection techniques
     -Converting between NumPy arrays and DataFrames
     -Using ColumnTransformer and understanding output format

     

# Task 2

## Key Operations:

 - Importing and cleaning the dataset.
 - Handling missing values
 - Visualizing relationships (e.g., using pairplot, heatmap, etc.)
 - Statistical summaries and grouping
 - Feature-wise survival analysis

## File:
- day2.ipynb: Main Jupyter notebook containing EDA on the Titanic dataset.
- Contents: Information about passengers such as age, class, gender, fare, and survival status.



# Task 3

## Key Features
 - Data loading and exploration
 - Data preprocessing with ColumnTransformer (OneHotEncoder for categorical features, StandardScaler for numeric features)
 - Implementation of Ridge regression with regularization
 - Hyperparameter tuning using GridSearchCV
 - Model evaluation with metrics (MSE, MAE, R²)
 - Visualization of predictions vs actual values

 ## Dataset
 The dataset contains 545 entries with the following features:
 - Numerical Features: price, area, bedrooms, bathrooms, stories, parking
 - Categorical Features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

## Best Parameters from GridSearchCV
 - alpha: 10
 - fit_intercept: True
 - solver: 'sparse_cg'


# Task 4

## Overview

- Dataset: Breast Cancer Wisconsin (Diagnostic)
- Algorithm: Logistic Regression
- Goal: Classify tumors as malignant or benign

## Features covered

- Exploratory Data Analysis (EDA)
- Label Encoding
- Data normalization
- Heatmap visualization using seaborn
- Model training using sklearn
- Evaluation using:
   - Confusion Matrix
   - Precision, Recall, F1 Score
   - ROC-AUC Curve
- Threshold tuning for classification

# Task 5
## Heart Disease Analysis
This repository contains a Jupyter Notebook with Decision Tree and Random Forest algorithm implemented and compared. 

## Notebook Content
- Initial Exploration: Missing values, data cleaning, finding correletion
- Training a Decision Tree Classifier and visualize the tree.
- Analyzing overfitting and finding the suitable max depth of the tree having mac score/accuracy.
- Training random forest classifier on the dataset and comparing the accuracy
- Finding the important features of both the classifiers after fitting them.
- Evaluating the algorithms using cross validation for better results.


# Task 6
## K-Nearest Neighbors on Iris Dataset

## Overview
- Dataset: Iris flower dataset (150 samples, 3 classes)
- Task: Classification using KNN
- Dimensionality Reduction: PCA (2D transformation)
- Model Evaluation: Accuracy, decision boundaries
- Visualization: Matplotlib decision region plotting


## Features
- Data preprocessing and train-test split
- PCA for 2D feature projection
- Training KNN classifiers with different k values
- Meshgrid-based visualization of decision boundaries
- Performance comparison across multiple k values


# Task 7
## Breast Cancer Classification with SVM
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



# Task 8
## Mall Customer Segmentation Using K-Means

## Mall Customer Segmentation
This notebook applies K-Means Clustering to segment mall customers into distinct groups based on their Annual Income and Spending Score. It demonstrates essential unsupervised learning techniques using the Mall Customer Dataset.

## Objective
To cluster customers into distinct groups using K-Means algorithm, and evaluate clustering effectiveness using Elbow Method and Silhouette Score.


## Key Steps
- Load & Preprocess: Cleaned the dataset and scaled numeric features.
- PCA: Reduced dimensions to 2D for easy visualization.
- K-Means Clustering: Fitted K-Means and assigned cluster labels.
- Elbow Method: Identified optimal number of clusters (k).
- Visualization: Plotted clusters using PCA-reduced data.
- Evaluation: Measured clustering quality with Silhouette Score.


## Results
- Optimal Clusters (k): 5 (based on Elbow Method)
- Silhouette Score: ~0.40 (indicating moderately good clustering)
- Identified meaningful customer segments based on income and spending behavior.
