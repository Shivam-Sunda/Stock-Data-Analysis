# Stock-Data-Analysis
Stock Price Prediction using Gradient Boosting and ARIMA

📌 Project Overview

This project explores stock price prediction using Gradient Boosting Regression (GBR) and ARIMA models. The goal is to analyze historical stock prices, apply machine learning techniques, and evaluate their performance in predicting future prices.

🔍 Methodology

The project follows a structured pipeline:


1️⃣ Data Collection & Preprocessing:

Historical stock price data was collected, cleaned, and feature-engineered.
Added moving averages (SMA_7, SMA_50, SMA_30) and lag features (Close_Lag_1, Close_Lag_3, Close_Lag_7).


2️⃣ Exploratory Data Analysis (EDA):

Visualized trends, seasonality, and price fluctuations.
Checked stationarity using the Augmented Dickey-Fuller test.


3️⃣ Model Development:

Gradient Boosting Regression (GBR): A machine learning model trained on lag features and moving averages.
ARIMA: A time-series statistical model for capturing stock trends.


4️⃣ Model Evaluation:

Metrics used:
Mean Absolute Error (MAE)
Mean Absolute Percentage Error (MAPE)
Root Mean Squared Error (RMSE)
R² Score (for GBR)

5️⃣ Results & Comparison:


Model	MAE	MAPE	RMSE	Accuracy
Gradient Boosting	5.3895	1.62%	11.7057	98.38%
ARIMA	11.3675	4.85%	3.2061	-
Observations:

✅ GBR captures short-term fluctuations better and achieves higher accuracy.
📉 ARIMA is more suited for long-term trend forecasting but lacks precision for short-term predictions.

6️⃣ Future Improvements:

Integrate deep learning (LSTM, Transformer models) for better time-series predictions.
Apply hybrid modeling (combining GBR, ARIMA, and LSTM).
Implement real-time stock price prediction and trading bot integration.
