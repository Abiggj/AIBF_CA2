# Real-Time Forex Price Prediction with Moving Averages

This project focuses on AI-driven real-time forex price prediction, utilizing technical indicators like moving averages, RSI, and MACD to generate automated trading signals. It implements a systematic approach to forex trading, eliminating emotional biases and providing an objective, data-driven strategy for traders.

## Project Overview
Foreign exchange (forex) is one of the largest financial markets, with significant complexity and volatility. This project leverages Artificial Intelligence (AI) and Machine Learning (ML) to predict future forex price movements and automate trading decisions. The core focus is on integrating technical indicators into a real-time forex price prediction model, allowing for backtesting and optimized trading strategies.

## Features

Real-time forex data analysis using AI-based technical indicators (Moving Averages, RSI, MACD).
Automated buy/sell signal generation based on short-term and long-term moving averages (crossover strategy).
Backtesting: Test trading strategies on historical data to optimize performance.
Predictive models: Machine learning algorithms (Random Forest Classifier) trained to predict future price movements.
Customizable currency pairs: Supports various currency pairs like EUR/USD, GBP/USD, and USD/JPY.
Visualizations: Provides insights into market trends through visual representations of technical indicators.

## Architecture

- Data Collection: Fetches real-time and historical forex data using the yfinance library.
- Data Preprocessing: Cleans and preprocesses historical data to focus on relevant features like closing prices.
- Machine Learning Model: A Random Forest Classifier is used for price prediction based on technical indicators.
- Feature Engineering: Technical indicators such as SMA (Simple Moving Averages), RSI, and MACD are used as features for prediction.
- Backtesting: Allows users to evaluate strategies on historical data, comparing results with a basic buy-and-hold approach.

### Technical Indicators
- 20-day and 50-day Simple Moving Averages (SMA)
- Relative Strength Index (RSI)
- Moving Average Convergence Divergence (MACD)
- MACD Signal Line

### How It Works
- Moving Average Crossover Strategy: Generates buy/sell signals when a short-term moving average crosses a long-term moving average.
- Momentum Indicators: RSI and MACD are used to identify overbought or oversold conditions and reinforce trading decisions.
- Backtesting: Test your strategies on historical data to fine-tune parameters and maximize profitability.

## Usage
This application is designed for:

- Forex traders: Automating trading decisions and optimizing strategies.
- Financial analysts: Fine-tuning trading models based on proven technical indicators.
- Educational purposes: Understanding how AI and technical indicators work in a practical trading system.

## Conclusion
This project offers a comprehensive solution for automating forex trading decisions using AI-driven technical analysis. It simplifies the process, enhances decision-making speed, and removes emotional bias from trading, making it an ideal tool for traders and financial analysts alike.

