# Monte-Carlo-Stock-Price-Prediction-GBM-with-Real-Data
Monte Carlo simulation of stock prices using Geometric Brownian Motion (GBM) driven by historical market data — forecasting, visualization, and risk metrics.

This project uses historical stock price data to fit a Geometric Brownian Motion model and run Monte Carlo simulations to generate possible future price paths. It produces visualizations (simulated trajectories, confidence bands, distribution of terminal prices), and computes simple risk metrics like expected return, median outcome, and Value-at-Risk (VaR). Designed for learning, backtesting simple hypotheses, and exploratory scenario analysis — not financial advice.

# Key Features
(1) Fetches and ingests real historical price data (CSV or API-compatible input).
(2) Estimates GBM parameters (drift μ and volatility σ) from log-returns.
(3) Runs thousands of Monte Carlo simulations of future price trajectories.
(4) Produces plots: simulated paths, mean + quantile bands, histogram of terminal prices.
(5) Outputs summary statistics: expected price, median, standard deviation, VaR at chosen confidence levels.
(6) Lightweight, clear code structure suitable for extension (stochastic volatility, jump-diffusions, portfolio simulation).
