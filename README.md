
# Real Estate Price Prediction

This project implements machine learning models to predict house prices based on various features like location, proximity to MRT stations, and number of convenience stores. The project uses several regression algorithms to find the best performing model for price predictions.


##  Table of Contents

* About
* Features
* Dataset
* Installation
* Usage
* Models
* Results
* Dependencies
* Contributing

## About

This project aims to predict real estate prices per unit area using machine learning algorithms. It includes data analysis, visualization, and model training to provide accurate price predictions based on various property features.
## Features



* Data preprocessing and analysis
* Exploratory Data Analysis (EDA) with visualizations
* Multiple regression models comparison
* Model evaluation and selection
* Feature importance analysis
* Prediction visualization
## Dataset

The dataset includes the following features:

* House age
* Distance to the nearest MRT station
* Number of convenience stores
* Latitude
* Longitude
* Transaction date
* House price of unit area
## Installation

    #Clone the repository
    git clone https://github.com/kairoentity/RealEstatePricePridiction.git

    #Navigate to the project directory

    cd RealEstatePricePridiction

    #Install required packages

    pip install -r requirements.txt
## Usage

1. Open the Jupyter notebook:

    jupyter notebook housePricePrediction.ipynb

2. Run all cells in the notebook to:

* Load and preprocess the data
* Generate visualizations
* Train and evaluate models
* Make predictions




## Models

The project implements and compares the following models:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
## Results

The models are evaluated using:

* Mean Absolute Error (MAE)
* R² Score

The best performing model is selected based on the R² score and saved for future use.
## Dependencies

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* joblib
## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

