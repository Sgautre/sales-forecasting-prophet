
# Sales Forecasting Using Prophet

## Project Overview
This project analyzes historical sales data and forecasts future sales
using the Prophet time-series forecasting model.

## Objectives
- Analyze historical sales trends.
- Visualize sales patterns over time.
- Forecast future sales.
- Compare actual sales with predicted sales.
- Evaluate the model using MAE, RMSE, and MAPE.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Facebook Prophet
- Scikit-learn
- Joblib

## Methodology
1. Load and inspect the sales dataset.
2. Clean missing and invalid values.
3. Visualize historical sales.
4. Train a Prophet forecasting model.
5. Generate future sales predictions.
6. Evaluate predictions on a chronological test set.
7. Save the forecast, evaluation metrics, and trained model.

## Evaluation Metrics
- MAE: Mean Absolute Error
- RMSE: Root Mean Squared Error
- MAPE: Mean Absolute Percentage Error

See `results/evaluation_metrics.csv` for the calculated values.

## Project Files
- `results/sales_forecast.csv`: Forecast output.
- `results/evaluation_metrics.csv`: Model evaluation metrics.
- `results/test_predictions.csv`: Actual and predicted test-period sales.
- `models/prophet_sales_model.joblib`: Saved forecasting model.

## Limitations
Forecast quality depends on the dataset's length, quality, and patterns.
Predictions are estimates and should not be treated as guaranteed sales.

## Author
CodeTech Internship Project
