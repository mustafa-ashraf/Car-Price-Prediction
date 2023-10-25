# Car Price Prediction Project

![Car](https://thinkingneuron.com/wp-content/uploads/2020/09/Car-price-prediction-case-study.png)
## Project Overview

This project is designed to predict car prices by utilizing regression techniques. It focuses on three primary regression models: Linear Regression, Ridge Regression, and Lasso Regression, aiming to find the best approach for accurately estimating car prices based on various car attributes.

## Dataset

The dataset used in this project, named "CarPrice_Assignment.csv," contains detailed information about car attributes such as car length, car width, engine size, and more. Notably, it is well-prepared with no missing values or duplicate entries, making it suitable for modeling.

## Data Preprocessing

The data preprocessing phase includes several important steps:

1. Data Exploration: An initial examination of the dataset to understand its structure and contents. We check for data types, uniqueness, and the presence of null values.

2. Data Cleaning: No missing values are found in the dataset, and there are no duplicates to remove.

3. Data Encoding: The categorical features are encoded using Label Encoding to convert them into a numerical format that can be used in regression models.

4. Data Scaling: The data is scaled using Robust Scaling to ensure that all features have the same scale.

## Regression Models

### Linear Regression

The Linear Regression model provides the following performance metrics:

- R2 Score: 0.7968
- Root Mean Squared Error (RMSE): 1,374,978.57

### Ridge Regression

The Ridge Regression model offers these performance metrics:

- R2 Score: 0.7959
- Root Mean Squared Error (RMSE): 1,380,603.66

### Lasso Regression

The Lasso Regression model performance is measured by:

- R2 Score: 0.7967
- Root Mean Squared Error (RMSE): 1,375,275.10

## Model Evaluation

The evaluation of models involves two key metrics:

- R2 Score: This metric indicates the proportion of the variance in the target variable that is predicted by the independent variables. Higher R2 scores indicate better model fit.

- Root Mean Squared Error (RMSE): RMSE measures the average error between predicted and actual values. Lower RMSE values are preferred as they represent more accurate predictions.

## Conclusion

All three regression models—Linear Regression, Ridge Regression, and Lasso Regression—demonstrate strong performance with R2 scores close to 0.80. This suggests that these models can effectively estimate car prices based on the provided car attributes.

While the project has achieved its primary goal, there are opportunities for further improvements, such as feature selection, hyperparameter tuning, and exploring more advanced regression techniques. These enhancements could potentially enhance the model's accuracy and predictive power.
