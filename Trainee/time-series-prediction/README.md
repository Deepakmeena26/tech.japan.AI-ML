# Stock Price Prediction Using LSTM

## Project Overview
This Jupyter notebook performs a time series analysis and stock price prediction using machine learning, particularly focusing on NTT stock price data. It involves multiple approaches, including LSTM (Long Short-Term Memory) models.

## Key Steps

### 1. Environment Setup
- Essential libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn` are imported.
- The dataset is loaded, checked for missing values, and visualized.

### 2. Data Preprocessing
- The date column (`日付け`) is converted to `datetime` format and set as the index.
- The closing price (`終値`) and other relevant metrics are plotted over time to visualize stock trends.

### 3. Modeling
- A **univariate LSTM model** is built to predict the closing stock prices.
- An **improved LSTM model** is created with additional optimizations.
- A **multivariate LSTM model** is developed, incorporating additional features for improved accuracy.

### 4. Model Evaluation
- Models are evaluated using RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
- Actual vs. predicted closing prices are plotted for better visual comparison.

### 5. Results
- The performance of different models (Original LSTM, Improved LSTM, and Multivariate LSTM) is compared, and results are displayed.

## Usage

### Load the dataset
- The dataset is loaded, and the `日付け` (Date) column is converted into a `datetime` object for proper time series analysis.

### Data Visualization
- The notebook visualizes the trends of the NTT stock, particularly focusing on the closing prices.

### Modeling
Three models are implemented:
- **Original LSTM**: Basic univariate LSTM model.
- **Improved LSTM**: Enhanced version of the original model with additional optimizations.
- **Multivariate LSTM**: Incorporates multiple features for better prediction accuracy.

### Evaluation
- The models are evaluated using RMSE and MAE metrics.
- A comparison is made between actual and predicted stock prices using the multivariate LSTM.

## Results
- The results of the models are compared, with RMSE and MAE being the key metrics.
- The multivariate LSTM model outperforms the univariate models in terms of prediction accuracy.

## Conclusion
This project showcases the application of LSTM models in financial time series forecasting, highlighting the advantages of multivariate models over simpler univariate approaches.
