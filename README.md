# Market-Data-PnL-Modeling


## Overview
This project builds a foundational quantitative analysis pipeline to evaluate equity market performance and portfolio risk. Using real historical market data, the project computes returns, profit-and-loss (PnL), volatility, drawdowns, and correlation structures, and visualizes key risk metrics commonly used in professional trading and asset management environments.

The project emphasizes clean data handling, reproducible analysis, and interpretable risk diagnostics.

---

## Objectives
- Download and clean historical equity price data
- Compute daily returns and cumulative PnL
- Analyze volatility and drawdowns
- Construct an equal-weighted portfolio
- Visualize equity curves, risk metrics, and correlations

---

## Data
- **Assets:** AAPL, MSFT, SPY  
- **Source:** Yahoo Finance (via `yfinance`)
- **Frequency:** Daily
- **Period:** 2020–2024

---

## Methodology
1. Download adjusted close prices and handle missing data
2. Compute daily percentage returns
3. Construct cumulative equity curves
4. Calculate annualized volatility and Sharpe ratios
5. Measure drawdowns and maximum drawdowns
6. Build an equal-weighted portfolio
7. Visualize performance and risk metrics

---

## Key Metrics
- Daily & cumulative returns
- Annualized volatility
- Sharpe ratio (risk-free rate assumed 0)
- Maximum drawdown
- Rolling volatility
- Asset correlations

---

## Visualizations
- Normalized price series
- Asset and portfolio equity curves
- Portfolio return distribution
- Rolling volatility
- Drawdown curves
- Correlation heatmap

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- yfinance

---

## Results & Insights
- Diversification reduces portfolio volatility relative to individual stocks
- Drawdowns highlight downside risk not visible from volatility alone
- Rolling volatility reveals time-varying risk dynamics
- Correlation structure explains portfolio risk behavior during stress periods

---

## Project Structure
```text
market-data-pnl-modeling/
│
├── market_data_pnl_modeling.py
├── README.md
└── outputs/
    └── charts/
