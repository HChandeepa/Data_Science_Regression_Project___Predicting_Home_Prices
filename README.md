# Real Estate Price Prediction Website
This project demonstrates the end-to-end process of building a real estate price prediction website. It consists of three main components:

### Project Overview
Model Building with Sklearn and Linear Regression

We begin by building a predictive model using the Bangalore home prices dataset from Kaggle. The model leverages sklearn and linear regression to predict home prices based on features such as square footage, number of bedrooms, etc.
During the model-building phase, we cover essential data science concepts, including:
Data Loading and Cleaning
Outlier Detection and Removal
Feature Engineering
Dimensionality Reduction
Hyperparameter Tuning using GridSearchCV
Model Evaluation with K-Fold Cross-Validation
Python Flask Server

The second step involves creating a Python Flask server that serves HTTP requests using the trained model. The server processes incoming requests, retrieves the model, and returns the predicted home price based on user inputs.
Website Development

The final component is a user-friendly website built using HTML, CSS, and JavaScript. The website allows users to enter home features such as square footage, number of bedrooms, etc. It then calls the Python Flask server to get the predicted price and displays it to the user.
