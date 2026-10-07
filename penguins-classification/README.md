# Palmer Penguins Classification

## Overview

This project implements a Logistic Regression model to classify penguins into two different species based on their physical characteristics and categorical features.

## Dataset

The dataset is a binary classification version of the Palmer Penguins dataset. It contains **274 observations** and features describing physical characteristics, the island, and the year of each observation.
The target variable is `species`, which contains two classes: `Adelie` and `Gentoo`.

The features include:

* `island`
* `bill_length_mm`
* `bill_depth_mm`
* `flipper_length_mm`
* `body_mass_g`
* `year`

The dataset is downloaded from Kaggle using the `kagglehub` library and is not included directly in this repository.

## Methodology

The following steps were performed:

1. Load and inspect the dataset
2. Explore the relationships between the numerical features using a pairplot
3. Analyze the categorical features using count plots
4. Split the data into training and test sets
5. Apply one-hot encoding to the categorical features
6. Standardize the numerical features using `StandardScaler`
7. Train a Logistic Regression model
8. Generate predictions on the test set
9. Evaluate the model using accuracy
10. Visualize the predictions using a confusion matrix

## Model

A Logistic Regression model from scikit-learn was used for the binary classification task.

Categorical features were transformed using `OneHotEncoder`, while numerical features were standardized using `StandardScaler`. A `ColumnTransformer` was used to apply the appropriate preprocessing to each type of feature.

## Evaluation

The model was evaluated using its classification accuracy and a confusion matrix.

The confusion matrix shows the number of correctly and incorrectly classified samples for each species. On the test set, the model correctly classified all samples, resulting in an accuracy of **100%**.

## Visualizations

The project includes visualizations of:

* Pairwise relationships between numerical features
* Species distributions across islands
* Species distributions across years
* Confusion matrix

The pairplot already shows a clear separation between the two species, particularly for features such as flipper length and body mass.

## Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* scikit-learn
* KaggleHub
* Google Colab
