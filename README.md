📈 Stock Market Price Prediction using LSTM
This project uses a Long Short-Term Memory (LSTM) deep learning model to predict the next-day closing price of a stock based on its historical price data.
It demonstrates how machine learning can be applied to time-series forecasting using real financial data.

🧠 Project Overview
- Stock prices are influenced by multiple factors and follow complex, time-dependent patterns.
- This project focuses on learning those patterns from past 60 days of closing prices to forecast the next day’s price.
- The project was implemented in Python using Jupyter Notebook, with data fetched directly from Yahoo Finance via the yfinance API.

🚀 Features
📥 Fetches real-time stock data using Yahoo Finance API (yfinance)
⚙️ Preprocesses and scales data for deep learning models
🧩 Builds an LSTM-based neural network for time-series prediction
📈 Visualizes Actual vs Predicted stock prices for performance comparison
📏 Evaluates model using Root Mean Squared Error (RMSE)
🔮 Predicts the next day’s closing price for any stock (default: AAPL)

🛠️ Technologies Used
Category	                      Tools / Libraries
Programming Language	          Python
Data Source	                    Yahoo Finance
Libraries	                      yfinance, pandas, numpy, matplotlib, scikit-learn, tensorflow
IDE / Environment	              Jupyter Notebook 
Model Type	                    LSTM (Long Short-Term Memory) Neural Network
