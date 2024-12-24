# CarPricePredictor-USA
This project aims to predict car prices in the US market using various regression algorithms, including Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Regression. It analyzes key factors affecting car pricing and performs hyperparameter tuning for model optimization.


# Car Price Prediction in the US Market
# Project Overview
This project focuses on predicting the prices of cars in the United States market based on various independent variables such as car attributes, features, and market factors. The goal is to understand the key drivers behind car pricing and develop a predictive model using multiple regression algorithms. This model can be useful for companies looking to optimize their pricing strategies and for further analysis of the US automobile market.
Introduction
The project explores the factors affecting car prices in the US market and implements different regression algorithms to predict these prices. The following algorithms are employed:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor
Each model is evaluated based on its performance using R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE). Hyperparameter tuning is also performed to optimize the model's performance.

Dataset
The dataset contains a variety of car attributes such as:

Car brand and model
Engine size
Number of doors
Car age
Fuel type
Mileage
Transmission type
Color
Other market-specific features
This data is gathered from market surveys and used to predict the car's price.

Model Implementation
The following regression algorithms are implemented in the project:

1. Linear Regression
A simple linear approach to model the relationship between independent variables and the target price.
2. Decision Tree Regressor
A decision tree model that splits the data into subsets based on the most significant variables for predicting car prices.
3. Random Forest Regressor
An ensemble learning method that uses multiple decision trees to improve the accuracy and robustness of predictions.
4. Gradient Boosting Regressor
A boosting algorithm that builds trees sequentially, with each tree correcting the errors of the previous one to improve predictions.
5. Support Vector Regressor
A regression model based on the Support Vector Machine algorithm, aiming to find the optimal hyperplane for regression.
Model Evaluation
After training each model, the following evaluation metrics are used to compare their performance:

R-squared (R²): Measures the proportion of variance explained by the model.
Mean Squared Error (MSE): Calculates the average of the squared errors between predicted and actual values.
Mean Absolute Error (MAE): Computes the average absolute differences between predicted and actual values.
These metrics help in selecting the best-performing model for predicting car prices.

Feature Importance Analysis
Feature selection is performed to identify which variables are most influential in predicting car prices. By examining feature importances, we can understand how different attributes (e.g., car brand, mileage, fuel type) contribute to the price prediction.

Hyperparameter Tuning
Hyperparameter tuning is carried out using GridSearchCV to optimize the models. The most important hyperparameters, such as the number of trees (for ensemble methods), learning rate, and depth of trees, are tuned to improve model accuracy.
