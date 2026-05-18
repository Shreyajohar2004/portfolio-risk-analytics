# Portfolio Risk & Performance Analytics
![Portfolio Dashboard](portfolio_dashboard.png)

End-to-end Python pipeline for analysing a 15-stock equity portfolio across 
five sectors. Computes return, volatility, Sharpe ratio, maximum drawdown, 
correlation structure, and a covariance-based risk decomposition.

## Methods
- 5-year daily returns from Yahoo Finance via yfinance
- Equal-weighted construction across Tech, Financials, Energy, Healthcare, 
  Consumer Staples and Industrials
- Annualisation: 252 trading days; volatility scaled by √252
- Risk decomposition: component contribution = w · (Σw) / σ²ₚ

## Key Outputs
- Cumulative return path
- Drawdown timeline  
- Return correlation matrix
- Risk-contribution vs capital-weight comparison

## Tools
Python · pandas · numpy · matplotlib · seaborn · yfinance
