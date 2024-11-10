# AQI_Detection
Air Pollution Level Prediction

This project is aimed at predicting the Air Quality Index (AQI) based on various atmospheric pollutants. Using machine learning models, we aim to provide an accurate prediction of AQI, which is critical for monitoring air quality and informing the public about environmental conditions.

Objectives
Train different machine learning models to accurately predict AQI.
Compare models based on multiple error metrics to identify the best performing model.
Use these models to build a robust prediction tool for real-time air quality monitoring.
Dataset
The dataset used for training includes air quality measurements from various locations and times, featuring pollutant concentrations and corresponding AQI values.

Features
Pollutants: PM2.5, PM10, NO2, NH3, SO2, CO, O3
Target: AQI (Air Quality Index)
The dataset was pre-processed to handle missing values and encode any categorical data.

Models Used
Four machine learning models were implemented and tested:

Linear Regression
Polynomial Regression
Support Vector Regression (SVR)
Decision Tree Regression
Each model was evaluated based on its predictive performance on the AQI values.

Evaluation Metrics
To evaluate each model’s performance, we calculated the following error metrics:

R² Score: Indicates the proportion of variance explained by the model. Higher values indicate better model performance.
Root Mean Squared Error (RMSE): Measures the average magnitude of error, with higher sensitivity to large errors.
Mean Absolute Error (MAE): Provides the average absolute difference between predictions and actual values.
Mean Squared Log Error (MSLE): Captures the relative differences between predicted and actual values, which is useful for data with large range differences.

