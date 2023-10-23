# Sales Forecasting with Random Forest Regression

This repository contains a Python script for sales forecasting using a Random Forest Regressor. The script reads historical sales data, preprocesses the data, trains a Random Forest model, and evaluates its performance using Mean Squared Error (MSE).

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Getting Started](#getting-started)
3. [Data Collection and Preprocessing](#data-collection-and-preprocessing)
4. [Data Exploration and Analysis (EDA)](#data-exploration-and-analysis-eda)
5. [Feature Selection](#feature-selection)
6. [Train-Test Split](#train-test-split)
7. [Model Training and Validation](#model-training-and-validation)
8. [Evaluate the Model](#evaluate-the-model)
9. [Forecasting (Optional)](#forecasting-optional)
10. [Mean Squared Error (MSE)](#mean-squared-error-mse)

## Prerequisites
- Python 3.x
- Pandas
- Scikit-Learn

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install pandas scikit-learn`.
3. Download the dataset and place it in the same directory as the script. The dataset should be named `Traindata.csv`.

## Data Collection and Preprocessing
The script reads the historical sales data from `Traindata.csv`, preprocesses the data, and extracts relevant features.

## Data Exploration and Analysis (EDA)
You can perform exploratory data analysis and feature engineering on the dataset.

## Feature Selection
The script selects the following features for training the model: 'year', 'month', 'day', 'store_id', 'sku_id', 'total_price', 'base_price'.

## Train-Test Split
The dataset is split into a training set and a test set for model validation. By default, 80% of the data is used for training, and 20% is used for testing.

## Model Training and Validation
A Random Forest Regressor is trained on the training data. You can modify the hyperparameters as needed.

## Evaluate the Model
The model's performance is evaluated using Mean Squared Error (MSE). The lower the MSE, the better the model's performance.

## Forecasting (Optional)
If you want to use the trained model for forecasting, you can do so by providing new data to the model.

## Mean Squared Error (MSE)
The Mean Squared Error (MSE) is printed to assess the model's performance.



