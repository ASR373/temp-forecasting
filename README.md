# Temperature Forecasting Using ARIMA Model

## Overview
This project focuses on forecasting daily average temperatures using the Autoregressive Integrated Moving Average (ARIMA) model. The dataset, sourced from "MaunaLoaDailyTemps.csv", contains daily temperature records indexed by date.

## Key Steps and Findings
- **Data Preparation and Visualization:** Initial exploration involved loading and visualizing the average temperature trends over time to understand seasonal patterns.
  
- **Stationarity Check:** The Augmented Dickey-Fuller (ADF) test was employed to assess the stationarity of the temperature data, ensuring it meets the prerequisite for time series modeling.
  
- **Model Selection and Evaluation:** Auto ARIMA was employed to automatically determine optimal ARIMA model parameters. The selected model (`order=(1,0,5)`) was trained on a subset of the data and evaluated using Root Mean Squared Error (RMSE) against a held-out test set.

- **Forecasting:** The trained ARIMA model was used to forecast future temperatures beyond the existing dataset. Predictions indicated trends and potential deviations in temperature patterns.

## Conclusion and Recommendations
- The ARIMA model demonstrated effective forecasting capabilities for daily average temperatures.
- Future applications could involve refining the model with additional data sources or exploring other advanced time series techniques for enhanced accuracy.

## Tools Used
- **Python Libraries:** Pandas, NumPy, Matplotlib, Statsmodels, pmdarima.
- **Techniques:** Time series analysis, ARIMA modeling, stationarity testing, and model evaluation.

## Next Steps
- Further refinement of the model parameters for improved accuracy.
- Integration of real-time data for ongoing forecasting and monitoring.

## Files Included
- `arima_beg.ipynb`: Initial exploration and stationarity testing.
- `Temperature_Forecast_ARIMA.ipynb`: Model training, evaluation, and forecasting.
- `MaunaLoaDailyTemps.csv`: Dataset used for analysis.

## Instructions for Use
1. Ensure Python and necessary libraries are installed.
2. Clone the repository.
3. Open and execute notebooks (`arima_beg.ipynb` and `Temperature_Forecast_ARIMA.ipynb`) in Jupyter environment.
4. Explore detailed analysis, visualizations, and results.

**Explore the provided notebooks for a detailed view of the analysis and results.**
