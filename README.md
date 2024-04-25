# Gold Price Forecasting using Time Series Analysis

This repository contains code for forecasting gold prices using time series analysis techniques. The forecasting models implemented include Exponential Smoothing and Linear Regression.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Contributing](#contributing)

## Introduction

Gold price forecasting is a crucial task for investors and traders to make informed decisions. This repository provides code for forecasting gold prices using different time series analysis methods. The implemented models include Exponential Smoothing and Linear Regression.

## Installation

To run the code in this repository, you need to have Python installed on your system. You can install the required packages using pip:
pip install -r requirements.txt

## Usage

1. Clone the repository to your local machine:

git clone https://github.com/RudaibaHaque/Time_series_Analysis_Using_Python.git

2. Navigate to the project directory:

cd gold-price-forecasting

3. Run the Jupyter notebook or Python scripts to execute the forecasting models.

## Models

### Exponential Smoothing

Exponential Smoothing is a popular time series forecasting method that assigns exponentially decreasing weights to past observations. It is suitable for data with no clear trend or seasonality.

For Exponential Smoothing model, the Mean Absolute Percentage Error (MAPE) on the test data is 17.24%.

### Linear Regression

Linear Regression is a simple machine learning algorithm that fits a linear equation to the observed data. It can be used for time series forecasting when there is a linear relationship between the predictor variables (e.g., time) and the target variable (gold price).

For Linear Regression model, the MAPE on the test data is 29.76%.

### Naive Model

A Naive Model is a simple forecasting method that uses the last observed value as the prediction for future time periods.

For the Naive Model, the MAPE on the test data is 19.38%.

The Exponential Smoothing model was chosen for the final prediction due to its lower MAPE compared to the other models, indicating better performance in forecasting gold prices.


## Contributing

Contributions to this project are welcome! Feel free to open issues or pull requests to suggest improvements, report bugs, or add new features.




