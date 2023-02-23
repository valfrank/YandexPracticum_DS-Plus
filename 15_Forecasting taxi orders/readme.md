# Forecasting taxi orders

## Project description

The Taxi company has collected historical data on taxi orders at airports. To attract more drivers during the peak period, you need to predict the number of taxi orders for the next hour.

Metric: RMSE 

The value of the metric on the test sample should not exceed 48.

## Data
The data is in the taxi.csv file. The number of orders is in the num_orders column.

## Resume
1. A brief analysis was carried out and features were added for training the model
2. Hyperparameters were selected for two models XGBoostRegressor and LightGBMRegressor
3. The best quality on cross-validation was shown by the LGBMRegressor model with RMSE=40.2

## Skills and tools
- python
- pandas
- seaborn
- sklearn
- XGBoost
- LightGBM
- Time Series forecasting
- Seasonal decompose, lagging values, calendar features, rolling mean
