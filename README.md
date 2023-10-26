# Customer Credit Risk Prediction

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Introduction
This project aims to predict the credit risk of customers using various machine learning algorithms. We will analyze the dataset, preprocess the data, build predictive models, and evaluate their performance.

## Data
We have used two datasets for this project:
- [FinanKu Data All](https://raw.githubusercontent.com/brainspopper/dataset/main/FinanKu%20Data%20All.csv): Contains customer information and financial data.
- [FinanKu Data Validasi](https://raw.githubusercontent.com/brainspopper/dataset/main/FinanKu%20Data%20Validasi.csv): Validation dataset for testing the models.

## Data Understanding
- We explored the distribution of customers based on location and identified those with unpaid bills.
- Analyzed customer age distribution for both all customers and those with unpaid bills.
- Calculated the average annual and quarterly balances of customers.
- Examined the average product ownership of customers.

## Data Preparation
We performed data preprocessing and feature engineering:
- Checked for duplicate and missing data.
- Calculated relevant variables such as mean balance and balance change over the observation period.
- Determined customer activity periods.
- Added or subtracted product holdings.
- Calculated the duration of credit card ownership.

## Modeling
We built predictive models using three different algorithms:
- Logistic Regression
- Gradient Boosting (XGBoost)
- Random Forest

Hyperparameters were tuned using GridSearchCV for each algorithm and each experiment.

## Evaluation
We evaluated the models using various metrics, including accuracy and recall. The results showed that the models had reasonable accuracy but lower recall, indicating room for improvement.

## Conclusion
In this project, we aimed to predict customer credit risk using various machine learning models. While the models showed promise, further improvements are needed to enhance the recall and better identify potential credit risks. Possible future steps include increasing the dataset, oversampling the minority class, expanding the time horizon, trying different feature combinations, exploring more hyperparameter combinations, and experimenting with other machine learning algorithms.