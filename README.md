# Victorian Electricity Demand Forecasting

A time series forecasting project analysing and predicting electricity demand in Victoria, Australia, using data from the Australian Energy Market Operator (AEMO) National Electricity Market (NEM).

**[View the full rendered report](https://mel-fitz.github.io/electricity-demand-forecasting/NEM_demand_forecast.html)**

## Overview

This project explores historical electricity demand patterns and implements statistical time series forecasting models to project future demand, as an independent exercise to build hands-on experience with Australian energy market data ahead of a move to Melbourne.

The analysis covers:

- **Data cleaning and validation** of historical hourly demand data
- **Exploratory data analysis** to identify seasonal, weekly, and daily demand patterns
- **Forecasting**, including a Seasonal Naive baseline for benchmarking
- **Model comparison** between ETS (Exponential Smoothing State Space) and ARIMA (AutoRegressive Integrated Moving Average) models
- **Visualisation** of forecasts against actual demand

## Data

Historical electricity demand data was sourced from AEMO's publicly available NEM data for Victoria.

## Tools

Built in R using Quarto. Key packages:

- `fpp3` (tidyverts ecosystem — includes `tsibble`, `fable`, `feasts`) and `forecast`, for time series modelling and forecasting
- `dplyr`, `stringr`, `lubridate`, `janitor`, for data cleaning and wrangling
- `ggplot2`, `hexbin`, for visualisation

## Contents

- `NEM_demand_forecast.html` — the full rendered report, including code, plots, and analysis
