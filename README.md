# Commodity Markets Dynamics

## Overview
This Python-based project analyses the impact of oil and gas price movements on agricultural commodity prices, integrating econometric analysis with systematic trading logic.
The objective is to detect, model and test tradeable relationships across commodity markets, bridging economic theory with practical trading strategies.

## Motivation
Energy prices influence agriculture through production costs, transportation expenses and input markets (e.g., fertilizers). Understanding these linkages can uncover relative value opportunities and inform hedging decisions in global commodity trading.

## Data sources
- World Bank – Monthly commodity price indices
- Yahoo Finance – Historical futures prices for energy and agricultural contracts
- Quandl – Supplementary market and macroeconomic data

## Methodology
- Exploratory Data Analysis (EDA) – Time-series visualisation, correlation matrices
- Econometric Modelling – Linear regression and lagged regression
- Signal Generation – Detecting mean-reversion and momentum patterns
- Backtesting – Evaluating strategies using historical futures data with performance metrics

## Progress & Findings (Work in Progress)
- Data pipeline set up for energy and agricultural price series
- Preliminary analysis suggests strong relation between most commodities, European sugar and American gas being exceptions
- Early tests indicate potential long-term relationships between oil and certain grains
- Crude oil from different regions follow similar price patterns, average oil price can be used as proxy for all oil
- Gas prices in USA, Japan and Europe are much less correlated and should be studied separately 









