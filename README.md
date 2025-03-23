# Modern Portfolio Theory

## Introduction

Modern Portfolio Theory (MPT) is an investment framework that optimizes asset allocation to maximize expected return for a given level of risk. This project implements MPT using Python to analyze stock market data, calculate portfolio risk and return, and optimize asset allocation.

## Features

- **Data Collection**: Retrieves historical stock prices using `yfinance`.  
- **Portfolio Return Calculation**: Computes daily and expected returns.  
- **Risk Assessment**: Estimates volatility and covariance between assets.  
- **Portfolio Optimization**: Uses Monte Carlo simulation to find optimal asset weights.  
- **Investment Strategy Simulation**: Tests a rebalancing strategy over time.  
- **Visualization**: Generates interactive plots for price trends, correlation matrices, and efficient frontiers using `plotly`.

## Steps

1. **Collect Data**  
2. **Compute Portfolio Returns**  
3. **Compute Covariance and Correlation Matrices**  
4. **Optimize Portfolio**  
5. **Backtesting Investment Strategy**

## Result
Over the backtesting period, the portfolio **with strategy** reached a final value of **1256**, compared to **1143** without strategy — an improvement of approximately **+10%**.

![portfolio evolution](https://github.com/user-attachments/assets/774b6de1-2725-47ac-b43b-0d83b928fbde)
