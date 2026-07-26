# Commodity Market Dynamics

## Overview
This Python-based project analyses the impact of oil and gas price movements on agricultural commodity prices, integrating econometric modelling with quantitative commodity market analysis. The objective is to identify statistically significant relationships across commodity markets, bridging economic theory with practical applications in market analysis and trading.

## Motivation
Energy prices influence agriculture through production costs, transportation expenses and input markets (e.g., fertilisers). Understanding these linkages can uncover relative value opportunities, improve market forecasting and inform hedging decisions in global commodity markets.

## Technologies
- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib

## Data Sources
- World Bank – Monthly commodity price indices
- Yahoo Finance – Historical futures prices for energy and agricultural contracts
- Quandl – Supplementary market and macroeconomic data

## Methodology
- **Exploratory Data Analysis (EDA):** Time-series visualisation, descriptive statistics and correlation analysis.
- **Econometric Modelling:** Linear regression, lagged regression and Ridge regression to analyse cross-commodity relationships.
- **Feature Engineering:** Construction of explanatory variables and lagged market indicators.
- **Signal Generation:** Identification of mean-reversion and momentum patterns.
- **Backtesting:** Evaluation of historical trading signals using performance metrics and out-of-sample testing.

## Progress & Findings *(Work in Progress)*
- Developed a data pipeline integrating energy and agricultural commodity price series.
- Preliminary analysis suggests significant relationships across most agricultural commodities, with European sugar and U.S. natural gas displaying comparatively weaker correlations.
- Initial modelling indicates potential long-term relationships between crude oil prices and several grain markets.
- Regional crude oil benchmarks exhibit highly similar price dynamics, suggesting that an aggregate oil price may serve as an effective modelling proxy.
- Natural gas markets in the United States, Europe and Japan display substantially different price dynamics and should therefore be modelled separately.








