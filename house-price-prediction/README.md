# House Price Prediction

## Overview

This project implements a Linear Regression model to predict house prices based on 13 different features.

## Dataset

The dataset contains 506 observations and 13 features describing different characteristics of houses and their surrounding areas. 
The target variable is MEDV, which represents the median value of owner-occupied homes.


## Methodology

The following steps were performed:

1. Load and inspect the dataset
2. Explore the relationships between the features and the target variable
3. Split the data into training and test sets
4. Train a Linear Regression model
5. Generate predictions on the test set
6. Evaluate the model using RMSE and R²
7. Visualize the predictions using an Actual vs. Predicted plot
8. Analyze the residuals using a residual plot


## Model

A Linear Regression model from scikit-learn was used for the prediction.


## Evaluation

The model was evaluated using:

- **RMSE** (Root Mean Squared Error): measures the average prediction error in the same units as the target variable.
- **R²** score: measures how well the model explains the variance in the target variable.


## Visualizations

The project includes visualizations of:

- Feature-target relationships
- Actual vs. predicted house prices
- Residuals vs. predicted values

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Google Colab
