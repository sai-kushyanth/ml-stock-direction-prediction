# ml-stock-direction-prediction
ML &amp; LSTM-based stock direction prediction with backtesting
# ML-Based Stock Direction Prediction & Backtesting

## Overview
This project implements an end-to-end machine learning pipeline to predict next-day stock price direction using historical financial time-series data. The system includes data preprocessing, feature engineering, model training, and strategy-level backtesting.

## Dataset
- Historical stock market data (OHLC, Adjusted Close, Volume)
- Source: Yahoo Finance / NSE
- Example stock: Reliance Industries

## Features Engineered
- Daily Returns
- Moving Averages
- Volatility (Rolling Standard Deviation)
- Momentum Indicators
- Volume Change

These features capture market trend, risk, and participation behavior.

## Models Implemented
- Logistic Regression (baseline model)
- Random Forest (non-linear patterns)
- LSTM (time-series deep learning using PyTorch)

## Evaluation Metrics
- Classification Accuracy (direction prediction)
- Strategy-Level Backtesting (profitability simulation)

The project highlights the difference between predictive accuracy and real trading performance.

## Key Learnings
- Accuracy alone does not guarantee profitable trading.
- Strategy logic and risk awareness are critical in financial ML systems.
- Time-series models like LSTM help capture temporal dependencies.

## Future Improvements
- Implement ensemble predictions by combining ML and LSTM model outputs.
- Add position sizing and transaction cost modeling.
- Incorporate advanced risk management techniques (stop-loss, Sharpe ratio).

## Tech Stack
- Python
- Pandas, NumPy, Scikit-learn
- PyTorch
- Matplotlib

## Disclaimer
This project is for educational purposes only and does not constitute financial advice.
