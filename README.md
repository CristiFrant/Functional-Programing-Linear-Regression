# Functional-Programing-Linear-Regression
This project implements a linear regression model using the Gradient Descent algorithm in Scala. The goal is to predict a target variable (e.g., house price) based on a set of input features (e.g., size, number of rooms).
    Data Loading & Selection: Load a dataset with multiple features, select relevant columns using the Dataset class, and split the data into training and validation sets.

    Input Matrix Creation: Construct a matrix X from the training set with feature values, adding a bias term for easier computation in the regression formula.

    Coefficient Initialization: Initialize a coefficient vector W to zeros, representing the weights for each feature.

    Gradient Descent Algorithm: Iteratively update W using Gradient Descent by computing predictions, calculating the error, determining the gradient, and adjusting W based on a learning rate.

    Model Validation: After training, evaluate the model on a validation set, calculating prediction errors and returning the final regression coefficients and error metrics.

This project demonstrates the practical application of linear regression using a simple and efficient optimization technique.
