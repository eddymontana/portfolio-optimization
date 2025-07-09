# portfolio-optimization
Leveraging Python, this project fetches, analyzes, and visualizes historical stock data to construct and optimize investment portfolios. It applies Modern Portfolio Theory to identify the efficient frontier and determine optimal asset allocations for maximized risk-adjusted returns


Stock Market Portfolio Optimization
Project Overview
This project provides a comprehensive quantitative analysis pipeline for a set of Indian equities, culminating in the simulation of an efficient frontier for portfolio optimization. Developed using Python, this system efficiently fetches, processes, analyzes, and visualizes historical stock market data, offering actionable insights for investment decision-making. It demonstrates the application of key financial concepts such as moving averages, daily returns, correlation analysis, and the Sharpe Ratio to identify optimal portfolio allocations based on Modern Portfolio Theory (MPT).

Features
Automated Data Acquisition: Fetches historical stock data (Adjusted Close, Open, High, Low, Volume) for specified tickers from Yahoo Finance using yfinance.

Robust Data Preprocessing: Cleans and reshapes raw financial data into a structured, analysis-ready format using pandas for efficient manipulation.

Exploratory Data Analysis (EDA):

Visualizes historical price trends of multiple stocks.

Generates technical analysis charts including 50-day and 200-day Simple Moving Averages (SMA) and trading volumes.

Plots the distribution of daily returns for each stock to understand individual risk characteristics.

Correlation Analysis: Computes and visualizes the correlation matrix of daily returns to understand inter-stock relationships and aid in diversification strategies.

Portfolio Optimization (Modern Portfolio Theory - MPT):

Calculates annualized expected returns and volatility for individual assets.

Simulates thousands of random portfolio weight combinations to explore the risk-return spectrum.

Identifies and plots the "Efficient Frontier," showcasing portfolios that offer the highest expected return for a given level of risk.

Determines the optimal portfolio with the maximum Sharpe Ratio, indicating the best risk-adjusted return.

Clear Visualizations: Utilizes matplotlib and seaborn to create intuitive and informative plots for all analyses.
