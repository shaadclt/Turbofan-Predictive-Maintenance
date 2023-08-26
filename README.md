# Predictive Maintenance with Machine Learning

This repository contains code for a predictive maintenance project using machine learning. The goal of this project is to predict the Remaining Useful Life (RUL) of aircraft engines based on sensor data and other operational parameters.

## Table of Contents

- [Introduction](#Introduction)
- [Getting Started](#Getting-Started)
- [Data](#Data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Predictive maintenance is a critical task in many industries, including aviation. This project focuses on predicting the Remaining Useful Life (RUL) of aircraft engines. It uses various machine learning models, including Linear Regression, Support Vector Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost, to make these predictions.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries, including pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, and tensorflow.
3. Download the dataset files (`train_FD001.txt`, `test_FD001.txt`, `RUL_FD001.txt`) and place them in the project directory.

## Data

The data used in this project consists of sensor readings and operational settings for aircraft engines. It is divided into training and testing sets. Additionally, the "Remaining Useful Life" (RUL) values are provided for the testing set.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to understand the data better. This includes visualizations of sensor data distributions, correlations, and the distribution of RUL values.

## Data Preprocessing

Data preprocessing steps include feature selection and scaling. Relevant features are selected based on correlation with RUL, and data is standardized using StandardScaler.

## Model Building

Several machine learning models are built and evaluated, including Linear Regression, Support Vector Regression, Decision Tree Regressor, Random Forest Regressor, and XGBoost. Hyperparameter tuning is also performed.

## Model Evaluation

The performance of each model is evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared (R2) on both the training and testing datasets.

## Results

The results of each model are summarized in a table, including RMSE and R2 scores on the training and testing datasets.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear and concise messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

