# Oil Temperature Prediction Using Time-Series Data

## Project Overview
This project aims to build a predictive model for oil temperature using time-series data from the ETDataset. The dataset provides various parameters related to the operation of transformers, with a focus on oil temperature, which is essential for monitoring transformer health.

## Files
- `ett.csv`: This file contains time-series data with multiple features, including oil temperature (OT) and several operational limits (HUFL, HULL, MUFL, etc.).
- `code.ipynb`: This Jupyter Notebook analyzes the data and applies machine learning techniques to predict oil temperature.

## Analysis Steps

### 1. Exploratory Data Analysis (EDA)
- Analyze the trends and seasonality of oil temperature and other features.
- Visualize patterns and anomalies in the time-series data.

### 2. Data Preprocessing
- Handle missing values and normalize the data.
- Engineer features that may improve model performance, such as time-based or lagged variables.

### 3. Model Selection and Training
- Implement machine learning models to predict oil temperature.
- Fine-tune hyperparameters for optimal performance.

### 4. Model Evaluation
- Assess the model's performance using metrics like Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE).
