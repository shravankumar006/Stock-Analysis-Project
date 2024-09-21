
                                                             ** Stock Analysis Project **

# Overview
This project performs a comprehensive analysis of tech company stock prices using historical data fetched via the yfinance library. The analysis includes visualizations of closing prices, stock trading volume, moving averages, daily returns, and correlations between major tech stocks (Apple, Google, Microsoft, Amazon). Additionally, the project demonstrates how to preprocess data and train machine learning models for predicting future stock prices.

# Features
Historical Stock Data Visualization: Plots the closing price and trading volume for major tech stocks.
Moving Average Calculation: Computes and visualizes 10-day, 20-day, and 50-day moving averages for stock prices.
Daily Return Analysis: Displays daily percentage changes for each stock.
Correlation Analysis: Analyzes and visualizes the correlation between tech stocks' daily returns and closing prices.
Stock Price Prediction: Prepares data for machine learning model training to predict future stock prices using a LSTM (Long Short-Term Memory) model.
# Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib: For data visualization.
Seaborn: For statistical data visualization.
yfinance: For fetching historical stock data.
sklearn: For data preprocessing and scaling.
TensorFlow/Keras:  For deep learning model training (if included).
# Data Analysis Steps
Fetching Stock Data: Stock data is fetched using the yfinance library for the tech companies (Apple, Google, Microsoft, Amazon) from the past year.
Data Visualization: Various visualizations like closing prices, trading volumes, moving averages, and daily returns are generated.
Machine Learning : The project includes a machine learning section to predict stock prices using an LSTM model. The data is preprocessed by scaling and reshaping for model input.
# Key Visualizations
Closing Price History: Line plot showing the stock price trend over time.
Stock Volume: Shows the volume of stock traded daily.
Moving Averages: 10-day, 20-day, and 50-day moving averages plotted on stock closing prices.
Daily Return: Histogram showing daily stock returns.
Correlation Heatmap: Heatmap showing correlation between stocks.
# Future Enhancements
Integrate more stocks for broader analysis.
Experiment with different machine learning models for stock prediction.
Deploy the model using a Flask web app to make live predictions.
# Conclusion
This project offers a powerful tool to visualize stock trends and relationships between tech companies, as well as using machine learning to predict future prices. It provides key insights for investors and financial analysts.

# Author
Shravan Kumar
GitHub: shravankumar006



