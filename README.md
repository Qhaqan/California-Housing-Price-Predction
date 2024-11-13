## California Housing Price Prediction using Linear Regression
This project demonstrates how to predict housing prices in California using the California Housing dataset and a Linear Regression model from Scikit-Learn.
It explores the relationships between various factors like median income, house age, population, and more, to predict the median house value.

## Project Overview
In this project, we use Scikit-Learn's LinearRegression model to predict house prices in California based on various features such as:

Median Income
House Age
Average Rooms per House
Population
Latitude & Longitude
The dataset is used to train the model and evaluate its performance using metrics such as Mean Squared Error (MSE) and R² Score. We also plot the predicted vs. actual values to visualize how well the model performs.

Key Features:
Data Preprocessing: Cleaned and prepared the dataset for model training.
Linear Regression: Used Scikit-Learn's Linear Regression model for prediction.
Evaluation Metrics: Calculated MSE and R² to evaluate model performance.
Visualization: Plotted actual vs predicted values to visualize the model's accuracy.
Dataset Information
The California Housing Dataset contains information about California’s housing prices in various districts in 1990. This dataset includes features such as:

MedInc: Median income in the block.
HouseAge: Median age of houses.
AveRooms: Average number of rooms per house.
AveBedrms: Average number of bedrooms per house.
Population: Population in the block.
AveOccup: Average household size.
Latitude: Latitude of the block.
Longitude: Longitude of the block.
The target variable (MedHouseVal) is the median house value for a California district, and the model aims to predict this value based on the features.

## Getting Started Prerequisites
Make sure you have the required libraries installed:
pip install numpy pandas scikit-learn matplotlib




