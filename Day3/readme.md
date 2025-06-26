# Day3

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
