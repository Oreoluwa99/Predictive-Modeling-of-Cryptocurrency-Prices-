# Predictive-Modeling-of-Cryptocurrency-Prices-
This project aims to analyze and predict Bitcoin prices using various time series and machine learning techniques. We implemented and evaluated models including ARIMA, LSTM, and Random Forest to identify the most effective method for forecasting Bitcoin prices.

# Project Structure
# 1. Data Preparation:
  Load and preprocess Bitcoin price data.
  Calculate daily returns and handle missing values.
  Split the data into training and testing sets.
# 2. Model Implementation:
  ARIMA Model: Time series analysis and forecasting.
  LSTM Model: Recurrent neural network for sequential data.
  Random Forest Model: Ensemble learning method for regression.
# 3. Model Evaluation:
  Evaluate models using RMSE, MAE, and R-squared metrics.
  Compare the performance of different models.
# 4. Feature Importance and Model Interpretation:
  Analyze feature importance for the Random Forest model.
  Use SHAP values to interpret the model's predictions.

# Getting Started
## Prerequisites
* Python 3.x
* Required Python packages:
* pandas
* numpy
* scikit-learn
* statsmodels
* tensorflow
* matplotlib
* yfinance
* shap

# Installation

# Clone the repository:
git clone https://github.com/yourusername/Predictive-Modeling-of-Cryptocurrency-Prices-.git
cd Predictive-Modeling-of-Cryptocurrency-Prices-

# Load and preprocess the data:
Ensure your Bitcoin price data is in the correct format and located in the specified path.

# Run the model implementations:
Execute the scripts to train and evaluate ARIMA, LSTM, and Random Forest models.

# Evaluate and compare models:
Analyze the output metrics to determine the best-performing model.

# Results
## ARIMA Model:
RMSE: 9472.13
MAE: 8001.88
R-squared: -0.0058

## LSTM Model:
RMSE: 41615.49
MAE: 40529.57
R-squared: -18.41

## Random Forest Model:
RMSE: 0.71
MAE: 0.057
R-squared: 0.999999994

The Random Forest model demonstrated exceptional performance, making it the most reliable model for Bitcoin price prediction in this study.

# Conclusion
This project successfully demonstrates the application of various predictive modeling techniques to forecast cryptocurrency prices. The Random Forest model's superior performance highlights its capability in capturing the underlying patterns in the data, providing reliable predictions.




