# Stock_Portfolio_Risk_Analysis
In this project, I developed a comprehensive risk analysis tool using Python to evaluate the performance and risk-return profile of a diversified stock portfolio consisting of Mastercard, Visa, Coinbase, and Robinhood.

The analysis integrates quantitative finance techniques and leverages historical market data to assess both systematic and unsystematic risk exposures. The key metrics computed include:

Simple and Log Returns for accurate return decomposition

Volatility as a measure of total risk

Sharpe Ratio, Sortino Ratio, and Calmar Ratio for risk-adjusted performance

Treynor Ratio to evaluate returns relative to systematic risk

Alpha & Beta to understand excess returns and market sensitivity

Maximum Drawdown to quantify worst historical losses

Value at Risk (VaR) at 90%, 95%, and 99% confidence levels to estimate potential losses

Conditional VaR (Expected Shortfall) at the same levels to capture tail-end risk exposure beyond the VaR threshold

This end-to-end analysis was built using NumPy, Pandas, and Matplotlib/Plotly for computation and visualization. The result is a robust framework that not only quantifies the risk and performance of each stock but also captures the behavior of the portfolio under various market stress scenarios, helping inform better investment decisions.
