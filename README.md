# Mercedes-Benz Greener Manufacturing ---Simplilearn Project

## Introduction
Mercedes-Benz Greener Manufacturing is a project dedicated to optimizing the testing process for Mercedes-Benz cars, with the goal of reducing the time cars spend on the test bench. This initiative not only upholds Mercedes-Benz's high standards for safety and reliability but also contributes to lower carbon emissions.

## Problem Statement
The dataset provided contains various permutations of features in a Mercedes-Benz car. The project aims to predict the time it takes for a car to pass testing based on these features. The focus is on leveraging algorithmic approaches to optimize testing speed and enhance overall efficiency.

## Actions Taken

### 1. Importing Necessary Libraries
Libraries such as NumPy, Pandas, Seaborn, Matplotlib, and XGBoost were imported for data manipulation, visualization, and model building.

### 2. Loading and Exploring Data
Train and test datasets were loaded into Pandas DataFrames (train_df and test_df). Basic exploratory data analysis was performed to understand the dataset.

### 3. Data Preprocessing
Columns 'ID' and 'y' were removed from the training data, and numerical and categorical features were separated for further processing.

### 4. Handling Zero Variance Features
Columns with zero variance were identified and removed to enhance model efficiency.

### 5. Label Encoding for Categorical Features
Categorical features were label-encoded to convert them into a numerical format for model training.

### 6. Concatenating Features
Categorical and numerical features were concatenated to create the final dataset.

### 7. Train-Test Split
The dataset was split into training and testing sets.

### 8. Model Building and Evaluation
An XGBoost regression model was built using the training set. Model performance was evaluated using metrics such as RMSE and R-squared.

### 9. Visualizing the Distribution of Actual and Predicted Values
A distribution plot was created to visualize the actual and predicted values on the test set.

### 10. Hyperparameter Tuning Using Grid Search
Grid Search was performed to find the best hyperparameters for the XGBoost model.

### 11. Predictions on Test Data
The model was used to make predictions on the test set, and predictions were stored in a CSV file.

### 12. K-fold Cross Validation with RandomizedSearchCV
RandomizedSearchCV was employed to perform K-fold cross-validation and find optimal hyperparameters.

### 13. Final Predictions on Test Data Using XGBoost
The tuned XGBoost model was used to make final predictions on the test set, and predictions were stored in a CSV file.

## Conclusion
This project provides a comprehensive example of building, tuning, and evaluating an XGBoost regression model for predicting a continuous target variable in a tabular dataset. The use of various preprocessing techniques and hyperparameter tuning contributes to achieving optimal model performance.

## Author
**Divya Pardeshi**

