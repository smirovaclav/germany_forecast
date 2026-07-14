# Macroeconomic Forecasting and Shock Propagation in Germany

This repository contains R scripts, and analysis for the term paper in course Tools for Modern Macroeconometrics at the Institute of Economic Studies, Charles University

## Project Overview

The main objective of this project is to create short- to medium-term forecasts of real Gross Domestic Product (GDP) and inflation for Germany

## Contents


* **Univariate Models:** Autoregressive Integrated Moving Average (ARIMA) models are applied to historical macroeconomic indicators to establish statistical baselines. The data undergoes logarithmic transformations, differencing, and seasonal adjustment.
* **Multivariate Models:** Vector Autoregressive (VAR) models are estimated to capture external monetary and oil. 
* **Advanced Structural Frameworks:** The analysis extends to recursive Structural VARs (SVAR) identified through Cholesky ordering. It also includes Bayesian VAR (BVAR) models with hierarchical Minnesota priors and structural sign restrictions, alongside Vector Error Correction Models (VECM) for trend analysis etc.
  

## Key Findings

* **Macroeconomic Forecast:** The primary SVAR model projects a "soft landing" for the German economy, with inflation falling below the ECB's 2% target and Real GDP returning to a modest expansionary path following a short-run contraction.
* **Output Paradox:** Unconstrained models reveal that positive global oil price shocks generate a temporary expansion in German Real GDP growth. This paradox could be explained by international demand driving both commodity prices and German industrial exports. This hypothesis needs to by verify in furthure research by adding additional variables.
* **Price Puzzle:** The models reveal the presence of a short-run price puzzle in the German economy.
