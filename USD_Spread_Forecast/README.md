# USD Spread Forecasting Using Cointegration and AR Models

This project models and forecasts the spread between U.S. Treasury instruments using macroeconomic time series and statistical techniques.

## Objective
To identify cointegrated relationships among U.S. Treasury yields and use these to forecast yield spreads through autoregressive modeling, with the goal of informing potential relative value trading signals.

## Methodology
- **Data**: Historical U.S. Treasury yields from the FRED database.
- **Preprocessing**: Stationarity checks (ADF test), first differencing, log transformations.
- **Cointegration Analysis**: Johansen test to identify long-run equilibrium relationships between yield curves of different maturities.
- **Spread Forecasting**:
  - Construct stationary spread series from cointegrated pairs.
  - Fit AR(p) models to forecast short-term spread movements.
- **Evaluation**: Forecast accuracy is assessed via residual analysis and visual diagnostics.

## Highlights
- Statistical rigor in identifying stable long-term relationships.
- Reproducible pipeline for building cointegrated signals.
- Foundation for potential mean-reversion trading strategies.

## Files
- `usd_spread_forecasting.ipynb`: Main analysis notebook
- `data/`: Directory where input time series are expected (add instructions if data not included)

## Dependencies
- Python 3.9+
- `pandas`, `numpy`, `matplotlib`, `statsmodels`

---

This project was completed as part of academic research and is based entirely on public data sources.
