# Bengaluru-House-Price-Prediction

This repository contains a machine learning model developed in Python for predicting house prices in Bengaluru. 
The model is built using various libraries such as pandas, matplotlib, seaborn, numpy, and scikit-learn. 
Additionally, a front-end website has been created using HTML, CSS, and JavaScript, with Flask used as the backend server.

**Table of Contents**

1. Introduction
2. Dataset
3. Model Development
4. Front-end Website


**Introduction**

The goal of this project is to develop a machine learning model that can predict house prices in Bengaluru based on various features. 
The model is trained using the Bengaluru House Price dataset, and the predictions are made using a linear regression algorithm. 
Additionally, hyperparameter tuning techniques are applied to optimize the model's performance.

**Dataset**

The dataset used in this project is the Bengaluru House Price dataset, which contains information about houses in Bengaluru, such as the total square feet area, the number of bedrooms, the number of bathrooms, the location, and other relevant features. 
The dataset is provided in a CSV format and is included in the repository.

**Model Development**

The machine learning model is developed using Python and scikit-learn. 
The Notebook.ipynb script contains the code for preprocessing the dataset, training the linear regression model, and saving the trained model to disk. 
The model is trained on a training set and evaluated using a separate test set. 
The evaluation metrics used include mean absolute error (MAE), mean squared error (MSE), and R-squared value.

**Hyperparameter Tuning**

The model's hyperparameters are tuned to optimize its performance. The Notebook.py script uses scikit-learn's GridSearchCV to perform a grid search over a predefined set of hyperparameters. The best hyperparameters are then used to retrain the model.

**Front-end Website**

A front-end website has been developed to provide a user-friendly interface for predicting house prices. 
The website is built using HTML, CSS, and JavaScript. 
Flask is used as the backend server to handle requests and serve the predictions made by the machine learning model. 
The website allows users to input various features of a house and obtain the predicted price.



