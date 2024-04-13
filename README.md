# Customer Churn Prediction

## Overview

This repository contains code and documentation for predicting customer churn in a business scenario. Customer churn, or customer attrition, refers to the phenomenon where customers cease doing business with a company. Predicting churn is vital for businesses to identify at-risk customers and take proactive measures to retain them.

## Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Models](#models)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)


## Data

The dataset used for this project is a [kaggle dataset](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers) contains information about customers, including their demographics, transaction history, and churn status. The data is stored in `data.csv`.

## Models

Three machine learning models are implemented for predicting customer churn:

- Logistic Regression
- Random Forest
- XGBoost

Each model is trained and evaluated using cross-validation to determine its performance.

## Evaluation

Model performance is evaluated using various metrics, including accuracy, precision, recall, and F1-score. Additionally, ROC curves and AUC scores are plotted to assess the models' ability to distinguish between churn and non-churn instances.

## Conclusion

Based on the evaluation results, the Random Forest model is identified as the preferred choice for predicting customer churn due to its superior performance metrics. The repository provides valuable insights and recommendations for businesses to mitigate churn and retain valuable customers.
