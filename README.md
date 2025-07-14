# Energy Demand Forecasting using ARIMA

## Overview
This notebook demonstrates time series analysis using the ARIMA (AutoRegressive Integrated Moving Average) model to forecast energy demand and solar generation. The analysis includes data loading, visualization, and modeling to predict future trends based on historical data.

## Dataset
The dataset contains the following columns:
- `utc_timestamp`: Timestamp in UTC.
- `IT_load_new`: Energy load data for Italy.
- `IT_solar_generation`: Solar energy generation data for Italy.

## Dependencies
To run this notebook, ensure you have the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`

## Usage
1. **Import Libraries**: The necessary libraries are imported at the beginning of the notebook.
2. **Load Data**: The dataset is loaded from a CSV file.
3. **Data Visualization**: The data is visualized to understand trends in energy load and solar generation over time.
4. **ARIMA Modeling**: The notebook implements ARIMA model for forecasting.

## Results
The visualization shows the trends in energy load and solar generation over time, providing insights into seasonal patterns and correlations between the two variables. Further analysis with ARIMA can help forecast future energy demands.
