# Time Series Analysis Project: ARIMA and ETS Models

## Overview

This project involves the application of time series forecasting techniques, specifically ARIMA (AutoRegressive Integrated Moving Average) and ETS (Error-Trend-Seasonality) models. The dataset used for analysis contains air quality index (AQI) data, and the goal is to predict future AQI values based on historical observations.

## Code

```R

## Steps

1. **Data Loading and Exploration:**
   - Load necessary libraries and read air quality data from an Excel file using tidyverse, lubridate, and other relevant packages.
   - Inspect the structure of the dataset to understand its format and variables.

2. **Data Visualization:**
   - Visualize the time series data using the `timePlot` function to gain insights into AQI value patterns over time.

3. **Calculating Monthly Means:**
   - Calculate monthly means of AQI values by grouping the data by month for each year.

4. **Model Fitting:**
   - Fit two time series models, ARIMA and ETS, to the monthly mean AQI values using the `fable` package.
   - Create an average model by combining predictions from both ARIMA and ETS models.

5. **Forecasting:**
   - Use the models to forecast future AQI values, applying a bootstrap approach for uncertainty estimation.
   - Plot the forecasted data alongside historical monthly mean AQI values to visualize predictions.

6. **Appendix:**
    - [Link to Interactive Plots](insert_link_here)


