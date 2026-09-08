# Predictive Analytics Using Historical Data

## Project Overview
This project builds a predictive time-series forecasting model using historical sales data from the Superstore dataset. The goal is to forecast future daily sales trends using machine learning.

## Key Features & Workflow
- **Data Preprocessing:** Cleaned historical records, handled daily aggregation, and continuous date indexing.
- **Feature Engineering:** Extracted temporal signals (Day, Month, Year, Day of Week, Quarter) and generated historical lag metrics (`Lag_1`, `Lag_7`, `Rolling_Mean_7`).
- **Modeling:** Trained a `RandomForestRegressor` on chronological train-test splits.
- **Evaluation:** Evaluated predictions on an unseen 60-day test window using standard regression metrics.

## Model Evaluation Results
- **Mean Absolute Error (MAE):** $1,970.18
- **Root Mean Squared Error (RMSE):** $2,716.46

## Visualizations
The model forecasts future sales trajectory against actual ground truth records, saved in `superstore_forecast_plot.png`.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib
