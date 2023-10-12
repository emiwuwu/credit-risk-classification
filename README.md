# Credit Risk Classification

## Overview

In this challenge, the goal is to build a model that evaluates loan risk and borrower creditworthiness. Utilizing data science and machine learning techniques, I'll create a precise binary classification model to categorize borrowers into two distinct groups.

## Features

### Data Preprocessing
- I initiate the data preprocessing by importing the "lending_data.csv" dataset from the "Resources" folder and converting it into a Pandas DataFrame.
- The labels (y) are created from the "loan_status" column, where 0 signifies a healthy loan, and 1 indicates a high risk of default.
- The features (X) are constructed from the remaining dataset columns.
- I optimize model development by splitting the data into training and testing sets using the `train_test_split` function from scikit-learn.

### Model Development
- I employ the scikit-learn's `LogisticRegression` class to construct a logistic regression model.
- The model is honed through training, utilizing the features (X_train) and corresponding labels (y_train).
- Subsequently, predictions on the testing data (X_test) are generated to evaluate the model's predictive capabilities.
- In consideration of potential data imbalance, I explore implementing a resampling technique.

### Model Evaluation
- I assess the model's performance by employing essential evaluation metrics, including accuracy, precision, recall, and F1-score.

## Credit Risk Analysis Report

For a comprehensive analysis of my credit risk classification models, please refer to the [Credit Risk Analysis Report](Credit_Risk/Analysis_Report.md).
