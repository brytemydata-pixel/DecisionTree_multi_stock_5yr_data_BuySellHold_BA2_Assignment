# DecisionTree_multi_stock_5yr_data_BuySellHold_BA2_Assignment
Five years of daily stock prices (Oct 2019 – Oct 2024) for AAPL, TSLA, GOOGL, MSFT, JPM, NVDA, AMZN, META, and BRK-B. Designed for ID3 decision tree simulations to generate Buy, Sell, or Hold signals, with features like returns and moving averages, supporting model evaluation and trading strategy analysis.
Overview

This repository contains 5 years of historical daily stock prices (Oct 2019 – Oct 2024) for nine tickers: AAPL, TSLA, GOOGL, MSFT, JPM, NVDA, AMZN, META, BRK-B.

It is designed for ID3 decision tree simulations to generate Buy, Sell, or Hold signals based on key features like daily returns and moving averages. Users can train models, evaluate performance, and visualize trading signals.

Dataset

File: multi_stock_5yr.csv

Columns: Date, <Ticker> (daily adjusted close prices)

Source: Retrieved via Python's yfinance library

Features & Target

Features: Daily Return, MA10, MA30

Target: Signal (Buy, Sell, Hold)

Usage

Load the CSV from GitHub in a Colab notebook.

Preprocess data and create features/target.

Train ID3 decision tree models (Entropy & Gini).

Evaluate performance (accuracy, classification report).

Visualize decision trees, feature importance, and Buy/Sell signals.

Requirements

Python 3.x

Libraries: pandas, numpy, yfinance, scikit-learn, matplotlib, seaborn
