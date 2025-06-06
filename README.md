## VAR Analysis: U.S. Housing and Labor Market
This project uses Vector Autoregression (VAR) to analyze the dynamic relationships between U.S. unemployment rates, housing starts, and housing completions. The analysis includes lag selection, model estimation, forecasting, Granger causality testing, impulse response functions (IRF), and forecast error variance decomposition (FEVD).

# Features
- Time series visualization of unemployment, housing starts, and completions
- VAR model with optimal lag selection via BIC
- Granger causality tests to explore directional relationships
- 12- and 24-month ahead forecasts
- Impulse Response Function (IRF) plots
- Forecast Error Variance Decomposition (FEVD)

# Data
Time series data includes:
- UNEMP: Unemployment rate
- STARTS: New housing starts
- COMPS: Housing completions

# Outputs
- Visualizations of raw and forecasted time series
  ![image](https://github.com/user-attachments/assets/4d235bd6-b942-4ecf-86ad-7ebe11b12026)

- IRF plots for each variable combination
  ![image](https://github.com/user-attachments/assets/a0881114-c68e-4cb5-bd87-f147c0c4cbf0)

- Granger causality results
  ![image](https://github.com/user-attachments/assets/7f0b4b27-bb60-4dd0-b836-54b47fe13f54)

- Forecast error variance contributions
  ![image](https://github.com/user-attachments/assets/68846022-84f6-4bed-92f8-015893f6ebbf)
