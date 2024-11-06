# SP500 Portfolio Optimization

This repository contains a Python script for performing portfolio optimization on S&P 500 stocks using historical data from Yahoo Finance. The project leverages the `yfinance` library for data retrieval and `PyPortfolioOpt` for portfolio optimization, calculating various metrics, expected returns, risk, and covariance matrices. 

## Project Overview

The main objectives of this project are to:
1. **Download and Analyze S&P 500 Stock Data:** Retrieve historical adjusted close prices, calculate daily returns, and analyze key metrics (Expected Return, Standard Deviation, and Variance).
2. **Optimize Portfolio:** Using portfolio optimization techniques to find an optimal allocation of weights that maximize the Sharpe Ratio and minimize portfolio volatility.
3. **Generate Custom Covariance Matrix:** Calculate the covariance matrix between stocks based on their historical returns.
4. **Identify Optimal Portfolio Candidates:** Select stocks with positive expected returns that outweigh their variance for a balanced risk-reward portfolio.


## Requirements

- Python 3.7+
- Required libraries: `pandas`, `numpy`, `yfinance`, `PyPortfolioOpt`

Install dependencies via:
```bash
pip install yfinance pandas numpy PyPortfolioOpt
