📈 Stock Price Prediction Using LSTM
Developed a deep learning model utilizing Long Short-Term Memory (LSTM) networks to predict stock prices using historical market data. This project aims to improve stock price forecasting accuracy for better portfolio management, algorithmic trading, and financial risk assessment.

Dataset: Historical stock price data (open, high, low, close, volume)
Tech Stack: Python, TensorFlow/Keras, Yahoo Finance API, NumPy, Pandas
Methods Used:
Data fetching, preprocessing (standardization, normalization, sequence generation)
Feature engineering with log transformations, interaction terms
Time-series modeling using LSTM & Bidirectional LSTM
Hyperparameter tuning with grid search and cross-validation
The final Bidirectional LSTM model outperformed baseline models, achieving a Mean Squared Error (MSE) of 0.0002 and demonstrating strong predictive capability despite high volatility periods. Future enhancements include integrating market indicators and exploring 
transformer-based architectures for improved accuracy. 
