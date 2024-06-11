# Bitcoin-Trading-Analysis-with-Simple-Moving-Averages
This project aims to analyze Bitcoin price movements using Simple Moving Averages (SMA) and generate buy/sell signals to inform trading decisions. The analysis is based on historical price data of Bitcoin.

# Overview
The project utilizes Simple Moving Averages (SMA) to analyze Bitcoin price trends and generate trading signals. SMAs are widely used technical indicators that help identify potential buy and sell opportunities based on historical price data.

# Methodology
1. Data Preparation: Historical price data of Bitcoin is collected and preprocessed. This includes cleaning the data, calculating the typical price, and organizing it for analysis.

2. Simple Moving Averages (SMA): SMAs are calculated for short-term and long-term periods to identify trends in Bitcoin prices. Common SMA periods include 20 days for short-term and 50 days for long-term analysis.

3. Signal Generation: Buy and sell signals are generated based on the crossover of short-term and long-term SMAs. A buy signal occurs when the short-term SMA crosses above the long-term SMA, indicating a potential uptrend. Conversely, a sell signal occurs when the short-term SMA crosses below the long-term SMA, indicating a potential downtrend.

4. Visualization: The closing prices of Bitcoin are plotted along with the short-term and long-term SMAs. Buy and sell signals are highlighted on the plot to visualize trading opportunities.

# Project Structure
The project repository contains the following files:
- README.md: This readme file providing an overview of the project.
- 'BTC.csv' : Historical price data of Bitcoin. Data are from: https://www.kaggle.com/datasets/svaningelgem/crypto-currencies-daily-prices/data
