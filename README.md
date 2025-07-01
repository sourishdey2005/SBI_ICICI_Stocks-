# SBI_ICICI_Stocks




# 📊 ICICI vs SBI NIFTY Stock Analysis (2011–2021)

A comprehensive, data-driven, and statistically robust comparison of ICICI Bank and State Bank of India (SBI) using over a decade of NIFTY stock market data. This project explores financial metrics, time-series behaviors, econometric modeling, macroeconomic context, ESG scores, digital banking transformations, and trading strategy implications.

---

## 🧾 Project Overview

This project analyzes and compares two of India's most influential banks—ICICI Bank (private sector) and SBI (public sector)—through multiple lenses:

- Financial performance and returns
- Risk metrics and volatility modeling
- Econometric forecasting (VAR, GARCH, Copulas, Markov Switching Models)
- Technological adoption and digital transformation
- ESG (Environmental, Social, Governance) profiling
- Macroeconomic impact (demonetization, COVID-19, IL&FS crisis)
- Strategic investment insights
- Global benchmarking
- Sentiment and behavioral finance analysis

---

## 🗃️ Dataset

**Source:** National Stock Exchange (NSE) via historical `.csv` or API (e.g., `yfinance`)

- **Period**: June 1, 2011 – April 30, 2021
- **Frequency**: Daily
- **Features**:
  - Open, High, Low, Close, VWAP, Last Price
  - Total Volume, Deliverable Volume, % Delivery
  - Turnover, Number of Trades

---

## 📌 Features and Highlights

### 🔹 Statistical Analysis
- Descriptive statistics (mean, median, skewness, kurtosis)
- Return distribution and quantile analysis
- Correlation matrix (Pearson, Spearman, Kendall)
- Rolling volatility and moving averages

### 🔹 Time-Series Modeling
- Stationarity testing (ADF, Hurst Exponent, Variance Ratio)
- GARCH(1,1) and DCC-GARCH for volatility modeling
- Granger Causality and Vector Autoregression (VAR)
- Markov Regime Switching Model (HMM)
- Copula modeling for joint tail dependence

### 🔹 Financial Performance
- CAGR, Sharpe, Sortino, Drawdowns
- Net Interest Margins, CASA ratios, Tier 1 capital adequacy
- Cost-to-income ratios and liquidity coverage

### 🔹 Stress Testing
- Monte Carlo simulations over 10,000 iterations
- Value-at-Risk (VaR), Expected Shortfall (CVaR)

### 🔹 Strategic Analysis
- Sector spillover impacts using IRFs
- ESG scoring and comparison (MSCI, green bond issuance)
- Sentiment analysis using NLP (news + Twitter)

### 🔹 Trading Strategy
- Pairs trading using hedge ratio and Z-score mean reversion
- Optimal entry/exit thresholds and half-life estimation

