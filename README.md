# AQI_Detection
Air Pollution Level Prediction

This project is aimed at predicting the Air Quality Index (AQI) based on various atmospheric pollutants. Using machine learning models, we aim to provide an accurate prediction of AQI, which is critical for monitoring air quality and informing the public about environmental conditions.

**Objectives**:
Train different machine learning models to accurately predict AQI.
Compare models based on multiple error metrics to identify the best performing model.
Use these models to build a robust prediction tool for real-time air quality monitoring.
Dataset
The dataset used for training includes air quality measurements from various locations and times, featuring pollutant concentrations and corresponding AQI values.

**Features**
Pollutants: PM2.5, PM10, NO2, NH3, SO2, CO, O3

Target: AQI (Air Quality Index)

The dataset was pre-processed to handle missing values and encode any categorical data.

**Models Used**
Four machine learning models were implemented and tested:

1. Linear Regression

2. Polynomial Regression

3. Support Vector Regression (SVR)

4. Decision Tree Regression

Each model was evaluated based on its predictive performance on the AQI values.

**Evaluation Metrics**
To evaluate each model’s performance, we calculated the following error metrics:

1. **R² Score**: Indicates the proportion of variance explained by the model. Higher values indicate better model performance.

2. **Root Mean Squared Error (RMSE):** Measures the average magnitude of error, with higher sensitivity to large errors.

3. **Mean Absolute Error (MAE):** Provides the average absolute difference between predictions and actual values.

4. **Mean Squared Log Error (MSLE):** Captures the relative differences between predicted and actual values, which is useful for data with large range differences.

**Results**
The following table summarizes the performance of each model based on the chosen metrics:
![Screenshot 2024-11-10 155031](https://github.com/user-attachments/assets/d516ed9c-1343-44cd-ba65-a9f15966e400)

Regression between PREDICTED AQI and ACTUAL AQI is shown below using 4 different Machine Learning Models:


![LR](https://github.com/user-attachments/assets/23fd15be-00b0-460f-a898-fb35b3d7c045)
![PR](https://github.com/user-attachments/assets/a021d438-50d9-459e-b98d-9ba753d95871)
![DT](https://github.com/user-attachments/assets/5cf8b9ca-c9d0-4e57-bb1f-36ce156aa1da)
![SVR](https://github.com/user-attachments/assets/921b9d79-e554-4f97-94ae-aee1063ab677)






