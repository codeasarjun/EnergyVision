# 🔍 EnergyVision : Forecasting of Energy Demand



📊 Objective: The objective of this project is to perform seasonal analysis on a time series dataset of energy demand and develop a forecasting model to predict future energy demand.

🔧 Tools and Libraries Used:

                              Python
                              Pandas
                              NumPy
                              Matplotlib
                              Statsmodels<br>
📈 Data Description:<br>
Dataset containing historical energy demand data, typically recorded at hourly or daily intervals, along with timestamps. Features: 'Datetime' (timestamp) and 'PJME_MW' (energy demand).<br>

Target Variable: 'PJME_MW' (energy demand).<br>


🔍 Exploratory Data Analysis (EDA): <br>

Visualizing Time Series: visualizing the time series data to observe any trends, seasonality, or irregularities.<br>

🔄 Seasonality Analysis:<br>

Seasonal Decomposition: We decomposed the time series into its trend, seasonal, and residual components using the seasonal decomposition of time series (STL) method.<br>
Seasonal Subseries Plot: We created a seasonal subseries plot to visualize the seasonal patterns for each month.<br>
Seasonal Index: Calculated the seasonal indices to quantify the relative strength of each month's seasonal pattern compared to the overall average.<br>

📊 Modeling and Forecasting:<br>

We split the data into training and test sets, with the training set used to fit the ARIMA model. Model Evaluation: We evaluated the performance of the ARIMA model on the test set using appropriate evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Forecasting: We utilized the trained ARIMA model to make predictions for future energy demand. <br>

ARIMA Model: We initially fit an ARIMA model to the time series data to capture any non-seasonal patterns and trends.

Model Evaluation: Evaluated the model's performance using metrics such as Mean Absolute Percentage Error (MAPE), Mean Absolute Scaled Error (MASE), and Symmetric Mean Absolute Percentage Error (SMAPE).

Forecasting: Generated forecasts for future energy demand using the SARIMA model.<br>

📉 Results and Insights:

Seasonal analysis revealed strong monthly seasonality in energy demand, with higher demand during certain months of the year.
We split the data into training and test sets, with the training set used to fit the ARIMA model. Model Evaluation: We evaluated the performance of the ARIMA model on the test set using appropriate evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Forecasting: We utilized the trained ARIMA model to make predictions for future energy demand.

🔮 Future Work:

Explore additional features or exogenous variables that may influence energy demand, such as weather data, economic indicators, or special events.
Investigate alternative modeling techniques like machine learning models (e.g., LSTM, XGBoost) for forecasting energy demand.

