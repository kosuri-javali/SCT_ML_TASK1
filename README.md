Linear Regression for House Price Prediction
This project implements a Linear Regression model to predict house prices using key numerical features from a real estate dataset.

Objective:
Predict the SalePrice of houses based on:

GrLivArea: Above-ground living area (square footage)

BedroomAbvGr: Number of bedrooms above ground

FullBath: Number of full bathrooms

Approach:
Data Loading: Imported training, test, and sample submission files using pandas.

Feature Selection: Chose GrLivArea, BedroomAbvGr, and FullBath as predictors.

Model Training: Fitted a LinearRegression model from scikit-learn on the training set.

Prediction: Used the model to predict house prices in the test set.

Submission File: Generated a .xlsx file containing the predicted values in the required format.

Outcome:
A simple yet effective regression model was built to estimate house prices based on fundamental housing features. The project lays a strong foundation for applying machine learning to real-world datasets.

