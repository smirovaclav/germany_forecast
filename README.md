# Macroeconomic Forecasting and Shock Propagation in Germany

This repository contains the data, R scripts, and analysis for the term paper "Macroeconomic Forecasting and Shock Propagation in Germany"[cite: 1]. The project was authored by Václav Šmíro for the course Tools for Modern Macroeconometrics at the Institute of Economic Studies, Faculty of Social Sciences, Charles University[cite: 1, 2].

## Project Overview

The main objective of this project is to create short- to medium-term forecasts of real Gross Domestic Product (GDP) and inflation for Germany, starting from the first quarter of 2026[cite: 1]. Furthermore, the empirical analysis identifies how macroeconomic shocks spread through the export-oriented and commodity-dependent German economy[cite: 1]. 

## Methodology

To understand the data-generating processes and structural interactions, the project applies both univariate and multivariate time series frameworks:
* **Univariate Models:** Autoregressive Integrated Moving Average (ARIMA) models are applied to historical macroeconomic indicators to establish statistical baselines[cite: 1]. The data undergoes logarithmic transformations, differencing, and TRAMO-SEATS seasonal adjustment[cite: 1].
* **Multivariate Models:** Vector Autoregressive (VAR) models are estimated to capture external shocks[cite: 1]. The baseline models incorporate two exogenous transmission channels: a global commodity supply shock and monetary policy shocks[cite: 1].
* **Advanced Structural Frameworks:** The analysis extends to recursive Structural VARs (SVAR) identified through Cholesky ordering[cite: 1]. It also includes Bayesian VAR (BVAR) models with hierarchical Minnesota priors and structural sign restrictions, alongside Vector Error Correction Models (VECM) for trend analysis[cite: 1].

## Data Sources

The empirical models are built using the following macroeconomic variables and data portals:
* **Real GDP:** Quarter-on-quarter and year-on-year data from the Federal Reserve Bank of St. Louis Economic Data (FRED) database[cite: 1].
* **Inflation:** Harmonized Index of Consumer Prices (HICP) from the European Central Bank (ECB) Data Portal, alongside national CPI data for robustness[cite: 1].
* **Monetary Policy Proxy:** A synthesized short-term interest rate that captures the Zero Lower Bound (ZLB) period by utilizing the shadow interest rate methodology by Wu and Xia[cite: 1].
* **Commodity Cost Shocks:** Global spot price of Brent crude oil sourced from the U.S. Energy Information Administration (EIA)[cite: 1, 2].



## Key Findings

* **Macroeconomic Forecast:** The primary SVAR model projects a "soft landing" for the German economy, with inflation falling below the ECB's 2% target and Real GDP returning to a modest expansionary path following a short-run contraction[cite: 1].
* **Output Paradox:** Unconstrained models reveal that positive global oil price shocks generate a temporary expansion in German Real GDP growth[cite: 1]. This paradox is explained by strong international demand driving both commodity prices and German industrial exports[cite: 1].
* **Price Puzzle Resolution:** A short-run "price puzzle" in the baseline VAR (where a restrictive monetary shock counterintuitively increases inflation) is successfully eliminated by imposing explicit New Keynesian sign restrictions onto the Bayesian VAR framework[cite: 1].
