Real Estate Price Prediction

This project aims to predict house prices per unit area based on various features such as house age, distance to the nearest MRT station, number of convenience stores, latitude, and longitude.


Table of Contents

Project Overview
Dataset
Installation
Usage
Model Training
Evaluation
Results


Project Overview

This project involves building and evaluating different machine learning models to predict house prices. The models include Linear Regression, Decision Tree, Random Forest, and Gradient Boosting. The best-performing model is saved for future predictions.


Dataset

The dataset used in this project includes the following features:
House age
Distance to the nearest MRT station
Number of convenience stores
Latitude
Longitude
House price of unit area (target variable)

The data is stored in a CSV file named Real_Estate.csv.


Installation

To get started, clone this repository and install the necessary dependencies.

 https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt


Make sure you have Python 3.x installed along with the following libraries:

pandas
numpy
seaborn
matplotlib
scikit-learn
joblib


Usage

1.Load the dataset: The dataset is loaded from the CSV file using pandas.

2.Data Analysis: The data is analyzed for null values, descriptive statistics, and visualizations such as histograms and scatter plots.

3.Model Training: Various regression models are trained on the scaled dataset.

4.Evaluation: The models are evaluated using Mean Absolute Error (MAE) and R² metrics. The best-performing model is saved as a .pkl file.

5.Prediction: The saved model is used to make predictions on new data.


Model Training

The training process involves the following steps:

1.Data Preparation: Features are selected, and the dataset is split into training and testing sets.
2.Scaling: The features are scaled using StandardScaler.
3.Model Selection: Linear Regression, Decision Tree, Random Forest, and Gradient Boosting models are trained.
4.Evaluation: Models are evaluated, and the best one is selected.


Evaluation

The evaluation metrics used in this project include:

- Mean Absolute Error (MAE)
- R² Score

The results of the evaluation are displayed in a DataFrame for easy comparison.


Results

The best model is saved as a .pkl file and can be used for future predictions.