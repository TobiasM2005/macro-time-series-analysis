# macro-time-series-analysi

# Applied Macroeconometrics & Time Series Analysis

## Project Overview
This repository contains a collection of empirical macroeconomics projects implemented in Stata. The analyses focus on time series econometrics, macroeconomic forecasting, and the evaluation of fiscal and monetary policy.

##  Core Projects & Methodology

### 1. Okun's Law & The Consumption Function
*   Estimation of the Keynesian consumption function and Okun's Law for the US.
*   Application of first differences and the Hodrick-Prescott (HP) filter to address spurious regression and isolate cyclical components.

### 2. Time Series Theory & Oil Price Shocks
*   Identification of ARMA(p,q) structures using ACF/PACF and Information Criteria (AIC/BIC).
*   Analysis of WTI oil price shocks and volatility using ARIMA models and Hamilton's Net Oil Price Increase (NOPI).
*   Residual diagnostics utilizing the Ljung-Box test for autocorrelation and normality tests.

### 3. Fiscal, Monetary Policy & ADL Modeling
*   Estimation of fiscal reaction functions for Germany and France, comparing OLS and GLS to correct for autocorrelation.
*   Modeling the ECB's Taylor Rule, incorporating interest rate smoothing and utilizing Chow-tests to identify structural breaks, such as the 2008 financial crisis.
*   Testing the Permanent Income Hypothesis versus the Absolute Income Hypothesis via Autoregressive Distributed Lag (ADL) models.

## Repository Structure
*   `ps1_okuns-law-and-consumption/`: Scripts and outputs concerning HP-filters and consumption models.
*   `ps2_oil-price-shocks/`: Scripts and outputs for ARMA modeling and historical shock identification.
*   `ps3_fiscal-and-monetary-policy/`: Scripts and outputs analyzing central bank reactions and debt sustainability.

## Data Sources
The analyses rely on macroeconomic datasets, primarily sourced from the Federal Reserve Economic Data (FRED) database and the AMECO database.

## author
Tobias Morgenstern
