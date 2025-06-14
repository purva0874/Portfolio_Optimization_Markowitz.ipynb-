# Portfolio Optimization using Markowitz Model

This project implements the Markowitz Mean-Variance Optimization model to construct an optimal portfolio of Indian stocks using historical data.

## Overview

- Stocks used: RELIANCE, TCS, INFY, HDFC Bank
- Data from Yahoo Finance via `yfinance`
- Objective: Maximize Sharpe Ratio (return vs risk)
- Output: Optimal stock allocation + efficient frontier plot

## Key Metrics

- **Expected Annual Return**: ~22.32%
- **Volatility (Std Dev)**: ~22.08%
- **Sharpe Ratio**: 1.01
- **Optimal Allocation**:
  - RELIANCE: 36.25%
  - INFY: 38.86%
  - TCS: 20.46%
  - HDFCBANK: 4.42%

## Efficient Frontier

Visualizes 10,000 random portfolios and highlights the optimal risk-return point.

![Efficient Frontier](./efficient_frontier.png)

## Tech Stack

- Python
- yfinance
- numpy, pandas
- matplotlib
- scipy.optimize

## 📄 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
