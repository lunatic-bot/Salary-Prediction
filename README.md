# Salary Prediction Using Linear Regression

## Overview

This repository contains a simple Machine Learning model that predicts salary based on various input features using a **Linear Regression** algorithm. Linear Regression is one of the most fundamental algorithms used for regression problems, where we aim to predict a continuous output variable (in this case, salary) based on input data such as experience, education, or other features.

The model is implemented using **Scikit-Learn**, a powerful and widely used machine learning library in Python, and **Matplotlib** for data visualization.

---

## What is Linear Regression?

Linear Regression is a supervised learning algorithm used for predicting a target variable by learning linear relationships from the input features. In this model, the relationship between the dependent variable (salary) and one or more independent variables (input features) is modeled by fitting a straight line, also known as the regression line.

The general equation for a simple linear regression model is:

\[ y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_nx_n \]

Where:
- \( y \) is the predicted output (salary)
- \( \beta_0 \) is the intercept
- \( \beta_1, \beta_2, \dots, \beta_n \) are the coefficients for the input features
- \( x_1, x_2, \dots, x_n \) are the input features

For more details, refer to the official documentation:  
[Scikit-Learn: Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)

---

## Libraries Used

### 1. **Scikit-Learn**
The model is built using **Scikit-Learn** (`sklearn`), which provides a variety of machine learning algorithms, including linear regression. The Linear Regression algorithm provided by `sklearn` fits the regression model to the training data, and then we use this trained model to predict salaries based on new input features.

Some key functions used from `sklearn`:
- `LinearRegression()`: Used to initialize the linear regression model.
- `fit()`: Used to train the model on the provided dataset.
- `predict()`: Used to make salary predictions based on input features.

Learn more about Scikit-Learn [here](https://scikit-learn.org/stable/).

### 2. **Matplotlib**
For visualizing the relationship between features and predicted values, we use **Matplotlib**. This library helps in creating plots that demonstrate how well the linear regression model is performing by comparing actual and predicted salaries.

Some key functions used from `Matplotlib`:
- `plot()`: To plot the regression line.
- `scatter()`: To plot the actual data points.

Learn more about Matplotlib [here](https://matplotlib.org/).

---
