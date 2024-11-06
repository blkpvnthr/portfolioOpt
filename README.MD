# SP500 Portfolio Optimization

This repository contains a Python script for performing portfolio optimization on S&P 500 stocks using historical data from Yahoo Finance. The project leverages the `yfinance` library for data retrieval and `PyPortfolioOpt` for portfolio optimization, calculating various metrics, expected returns, risk, and covariance matrices. 

## Project Overview

The main objectives of this project are to:
1. **Download and Analyze S&P 500 Stock Data:** Retrieve historical adjusted close prices, calculate daily returns, and analyze key metrics (Expected Return, Standard Deviation, and Variance).
2. **Optimize Portfolio:** Using portfolio optimization techniques to find an optimal allocation of weights that maximize the Sharpe Ratio and minimize portfolio volatility.
3. **Generate Custom Covariance Matrix:** Calculate the covariance matrix between stocks based on their historical returns.
4. **Identify Optimal Portfolio Candidates:** Select stocks with positive expected returns that outweigh their variance for a balanced risk-reward portfolio.

## Files Included
- `sp500_stock_metrics.csv`: Contains metrics for each stock in the S&P 500.
- `optimal_portfolio_candidates.csv`: Contains candidates for the optimal portfolio based on expected returns and risk.
- `custom_covariance_matrix.csv`: Covariance matrix for selected stocks in the optimal portfolio.
- `mvp_info.csv`: Information on the Minimum Variance Portfolio (MVP).
- `optimal_weights.csv`: Weights for the Minimum Variance Portfolio.
- `optimal_portfolio.csv`: Detailed stock list and weights in the optimal portfolio.
- `mvp_and_optimal_portfolio.csv`: Combined MVP information and optimal portfolio stock weights.

## Requirements

- Python 3.7+
- Required libraries: `pandas`, `numpy`, `yfinance`, `PyPortfolioOpt`

Install dependencies via:
```bash
pip install yfinance pandas numpy PyPortfolioOpt
