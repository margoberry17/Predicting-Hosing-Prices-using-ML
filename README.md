# Predicting Hosing Prices using ML

## Introduction
By leveraging machine learning to predict home value prices, stakeholders can make more informed decisions, mitigate risks, and contribute to the overall efficiency and stability of the real estate market.

## Problem Statement
The residential housing market in America can be opaque, complex, and inconsistent across geographic lines. We are hoping to ameliorate this situation by using a machine learning model to find correlation between different components of a house and a house’s value. 

## Variables that can affect house price
Housing market, neighborhood, area, number of rooms, number of bathrooms, stories, location, etc.

## Data Source/Cleaning
https://www.kaggle.com/datasets/tmthyjames/nashville-housing-data
Preprocess the dataset as needed, including handling missing values, encoding categorical variables, and scaling numerical features.
The original dataset was a CSV 
We used mongoDB to remove null values/ unnecessary columns

## Linear Regression
We used the linear regression model from SciKit Learn to be able to predict price based on the finished Area (sqft). 
Using the formula below we then plugged in a theoretical house with a finished area of 2000 and we got the price prediction of $291,408.64
- Model's formula: y = -95434.8202867586 + 193.42172790824736 * 2000
- Predicted price for a house with 2000 sq ft would be: $291408.64

![linear_regression](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/fc52b43e-93eb-4d91-b06a-fd78f9174f62)

## Training
Train the linear regression model on the training set and assess its accuracy on the testing set using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), or R-squared (R^2) coefficient.
Compare the performance of different models and identify the best-performing model(s).

![Training1](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/378bf5da-34ad-43cb-8d3d-1e9e26e425c2)


![Training2](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/687f6b7c-70cb-498b-880a-d03e223f158c)

## Correlation Matrix
![Correlation Matrix](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/bbb881a6-0cc7-458a-8c26-adbaadfe2619)


## Tableau Link
https://public.tableau.com/app/profile/margo.berry/viz/NashvilleHousing2013-2016/MonthYearvsAvg_SalePrice?publish=yes


![Tableau1](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/45d8941b-c83b-40f4-b977-6e7d5bc8e4c8)


![Tableau2](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/153215b6-4b3f-4b07-a39a-c30e5e216a32)


![Tableau3](https://github.com/margoberry17/Predicting-Hosing-Prices-using-ML/assets/136475202/c28a2407-167c-454e-966a-2b0232b141f1)


