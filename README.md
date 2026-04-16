# STOCK MARKET ANALYSIS 

Stock Market Analysis means analyzing the past and current trends in stock prices to help inform future buying and selling
decisions. This project demonstrates how to fetch and visualize stock market data using python, focusing on Google's stock as 
an example 

## Project Overview 

This repository contains a python-based stock market analysis workflow that:
- Downloads historical stock price data using the 'yfinance' API
- Computes basic statistics (open, high, low, close, volume)
- Visualizes price trends and moving averages over time.
- Provdies insights that can be extended to more advanced trading strtegies. 


## Key Analysis 
* Trend and Price Behaviour
    - The closing price trend shows whether the stock is generally moving up,down, or sideways over the chosen period.
    - Moving averages help smooth noise and highlight underlying trends; when the price is above the moving average, it often
      signals an uptrend and vice versa.
      
* Volatility & Risk
    - Large swings between high and low prices and frequent spikes in trading volume indicate higher volatility and risk.
    - Technical analyst use this behaviour to assess whether the stock is in a 'calm' or 'chaotic' phase and to decide entry/exit points.

* Support and Resistance Levels
    - Repeated price bounces near certain price levels suggest support, while repeated reversals downard suggest resistance.
    - These levels, visible from the plotted price chart, are often used to set stop-loss or profit-target zones.

* Short-term vs Long-term Signals
    - Short-term moving averages react quickly to price changes and can signal short-term momentum.
    - Long-term moving averages show the broader trend and are useful for long-term investors.

* Pratical Implications
    - The analysis supports technical trading strategies such as "buy when price crosses above moving average" or "sell when
      volatility spikes.
    - However, this project is combined with fundamental adn macroeconomic analysis before taking any real-world trading actions.
