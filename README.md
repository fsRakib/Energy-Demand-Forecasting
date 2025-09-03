# Energy Demand Forecasting

This project analyzes and forecasts energy demand and solar generation using time series data and ARIMA models.

## Project Structure

- `energy-demand-forecasting.ipynb`: Main Jupyter notebook with data analysis, visualization, and forecasting steps.
- `TimeSeries_TotalSolarGen_and_Load_IT_2016.csv`: Dataset containing timestamps, load, and solar generation data for Italy in 2016.
- `requirements.txt`: List of required Python packages.

## Features

- Data cleaning and preprocessing
- Visualization of load and solar generation over time
- Stationarity testing using Augmented Dickey-Fuller (ADF) test
- ARIMA model building and evaluation for both load and solar generation
- RMSE calculation for model performance

## Requirements

Install dependencies with:

```
pip install -r requirements.txt
```

## Usage

1. Open `energy-demand-forecasting.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to:
   - Load and visualize the data
   - Test for stationarity
   - Build and evaluate ARIMA models
   - Visualize actual vs predicted values

## Results

The notebook provides RMSE values and plots comparing actual and predicted values for both load and solar generation.

## License

This project is for educational and research purposes.
