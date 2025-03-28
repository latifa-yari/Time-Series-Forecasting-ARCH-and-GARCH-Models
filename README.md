# Bitcoin Price Volatility Modeling using ARCH & GARCH

## Project Overview
This project applies advanced volatility modeling techniques — ARCH (Autoregressive Conditional Heteroskedasticity) and GARCH (Generalized ARCH) — to forecast the volatility of Bitcoin price returns. Due to the highly volatile and non-linear nature of cryptocurrency markets, these models help us understand the behavior of market risk over time.

The project explores the distribution, volatility clustering, and time-varying variance of Bitcoin prices, making it relevant for financial analysts, cryptocurrency investors, and risk managers.

## Dataset
- Source: Public cryptocurrency data source (e.g., Kaggle or CoinMarketCap)
- Time Frame: Historical daily prices of Bitcoin
- Variable of Interest: Daily log returns of Bitcoin closing price

## Methods & Models
ARCH & GARCH:
- Used to model heteroskedasticity (time-varying volatility) in financial time series
- ARCH Model: Captures volatility clustering in error terms.
- GARCH Model: Adds lagged conditional variances to improve long-term volatility forecasts.

## Implementation Details
- Libraries used: pandas, numpy, arch, statsmodels, matplotlib, seaborn
- Steps:
  1. Calculated daily returns from price data.
  2. Visualized return series and squared residuals to detect volatility clustering.
  3. Fit multiple ARCH/GARCH models.
  4. Selected best-fit model using AIC/BIC.
  5. Forecasted volatility and interpreted confidence intervals.

## Results
- The GARCH(1,1) model effectively captured the volatility clustering in Bitcoin prices.
- Volatility forecasts provided insight into the risk exposure of future trading days.
- Residuals analysis confirmed model assumptions and fitness.

## Files Included
- ARCH_GARCH _Updated.ipynb – Jupyter Notebook with full analysis
- bitcoin_prices.csv – Dataset used (replace with your actual filename)

## Takeaway
This project demonstrates the practical use of volatility modeling in financial data science. It serves as a solid foundation for roles in quantitative analysis, risk forecasting, or cryptocurrency research.

## Author
Latifa Yari – Data Analyst 