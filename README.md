# Financial Econometrics: Volatility, VaR, EVT and Intraday Return Analysis

## Overview

This repository contains a financial econometrics project on volatility dynamics, tail risk measurement, and intraday return geometry.

The work is organised around three complementary topics:

1. **COVID-19 and market volatility**  
   Comparison of pre- and post-COVID volatility dynamics for the S&P 500 and CSI 300 using GARCH(1,1) models and bootstrap-based inference.

2. **Volatility and risk management for daily time series**  
   Construction of daily return and realised variance series from intraday data, AR(1)-GARCH(1,1) modelling, volatility forecasting, EVT/POT-GPD tail estimation, and comparison of VaR / Expected Shortfall measures.

3. **Functional data analysis of intraday cumulative returns**  
   Representation of intraday cumulative return curves as functional observations, dimensionality reduction via FPCA, and score-based forecasting with AR(1) models.

The repository contains the original project files exactly as produced for the course.

## Main contents

### Report

* `report/Report_Rakotovao_Bertrand.pdf`
  Final written report presenting the methodology, empirical results, discussion, and conclusion.

### Python notebooks

* `notebooks/Exploratory_data_analysis_out28_RAKOTOVAO_BERTRAND.ipynb`
  Exploratory analysis of the intraday dataset `out28.csv`.

* `notebooks/EcoFin_2_Volatility_risk_management_for_daily_time_series_RAKOTOVAO_BERTRAND.ipynb`
  Daily return construction, realised variance, AR(1)-GARCH(1,1), EVT/POT-GPD, and VaR / ES analysis.

* `notebooks/EcoFi_3_Functional_data_analysis_for_intraday_cumulative_log_returns_RAKOTOVAO_BERTRAND.ipynb`
  Functional representation of intraday cumulative returns, FPCA, score analysis, and forecasting.

### R Markdown file

* `r/EcoFi_1_Covid19volatility.Rmd`
  Study of the COVID-19 impact on volatility for the US and Chinese equity markets.

### Data

* `data/out28.csv`
* `data/S&P 500 Historical Data.csv`
* `data/S&P_CITIC300 Historical Data.csv`

## Methods used

* Exploratory data analysis
* Log-return construction
* Realised variance
* AR(1) modelling
* GARCH(1,1)
* Extreme Value Theory (POT / GPD)
* Value at Risk (VaR)
* Expected Shortfall (ES)
* Functional Principal Component Analysis (FPCA)
* AR(1) forecasting on FPCA scores
* Bootstrap-based inference

## Languages and tools

* Python
* R
* Jupyter Notebook
* R Markdown
* NumPy
* pandas
* SciPy
* matplotlib

