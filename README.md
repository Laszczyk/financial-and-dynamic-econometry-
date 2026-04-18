# Financial and Dynamic Econometrics – Project Portfolio

This repository contains a collection of laboratory projects, simulations, and analytical reports focused on time series analysis, volatility forecasting, and advanced econometric modeling. 

## Project Overview

### 1. Financial Data Properties & Normality Testing (`lab1.ipynb`)
Statistical analysis of financial time series data (Open, High, Low, Close, Volume). The project implements and compares various statistical tests for distribution normality, including Shapiro-Wilk, D'Agostino-Pearson, and Kolmogorov-Smirnov tests.

### 2. MA(1) Model Simulation & Estimation (`lab2.ipynb`, `lab2b.ipynb`)
Monte Carlo simulation of the Moving Average MA(1) process ($X_t = \theta_0 + \theta_1\varepsilon_{t-1} + \varepsilon_t$). The study focuses on estimating model parameters, analyzing the empirical distribution of these estimators through histograms and boxplots, and testing their asymptotic normality.

### 4. Advanced Volatility Modeling (`lab_4A_grupa_4_NST.ipynb`, `lab_4B_grupa_4_NST.ipynb`)
Comprehensive volatility forecasting using the ARMA-GARCH framework. 
* Evaluates various model specifications including standard GARCH, EGARCH, and GJR-GARCH.
* Compares error distributions (Normal, Student's t, Skewed t).
* Features a robust rolling-window analysis (100, 200, and 500 observations) to track the best-fitting models (based on AIC) across different years.

### 5. VAR(1) Models & HC Estimators (`lab5_5A.ipynb`, `lab_5B_grupa_4_NST.ipynb`)
Simulation-based study of Vector Autoregression VAR(1) models evaluating the performance of Heteroskedasticity-Consistent (HC) standard errors. The project analyzes the empirical size and power of Granger causality tests under classical OLS versus various HC estimators.

### 6. European Stock Market Interdependencies: COVID-19 Impact (`Sprawozdanie_6AB...pdf`)
A comprehensive empirical study analyzing the transmission of shocks across six major European stock exchanges (DAX, AEX, BEL20, OMXS, OMXV, WIG20). 
* Utilizes Vector Autoregressive (VAR) models and Granger causality tests.
* Employs Chow tests and Likelihood Ratio (LR) tests to identify and confirm structural breaks and shifts in market dynamics caused by the outbreak of the 2020 pandemic.

---

## Tools & Technologies
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `statsmodels`, `scipy`, `matplotlib`, `arch`
* **Formats:** Jupyter Notebook (`.ipynb`), PDF Reports
* **Key Methodologies:** Time Series Analysis, Monte Carlo Simulations, GARCH Volatility Forecasting, VAR Modeling, Granger Causality, Structural Break Testing.

## Authors
* Jakub Laszczyk
* Małgorzata Leszczyńska
* Aleksandra Wajda
* Mateusz Chojecki
