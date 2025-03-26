
# Time Series Forecasting (ARIMA and SARIMAX) - README

## Description:
This section implements time series forecasting models (ARIMA and SARIMAX) to predict future visitor arrivals in Qatar. The models are trained on monthly data and forecast future arrivals.

## Dependencies:
- statsmodels
- pandas
- numpy
- matplotlib

## How to Run:
1. Install the required libraries:
   ```bash
   pip install statsmodels pandas numpy matplotlib
   ```
2. Run the script `time_series_forecasting.py` to train the ARIMA and SARIMAX models on the dataset.
3. The script will output performance metrics (MAE, MSE, RMSE) and visualize the forecast results.

## Steps:
1. **Data Preprocessing**: Aggregate the data monthly for time series analysis.
2. **Model Training**: Train ARIMA and SARIMAX models on the historical data.
3. **Model Evaluation**: Evaluate the forecast performance using MAE (Mean Absolute Error), MSE (Mean Squared Error), and RMSE (Root Mean Squared Error).
4. **Forecasting**: Generate predictions for future months or years.
5. **Visualization**: Plot the actual vs. forecasted values.
