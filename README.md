# Time-Series-Linear-Regression
### Project Overview
In this notebook, we will attempt to forecast using linear regression. Linear regression is a simple and efficient model that is well-suited for beginners. However, it cannot be used to forecast non-stationary time series data. In this notebook, we will learn how to handle non-stationary time series data so that we can use linear regression to forecast it.
### Data
The data was obtained via kaggle (https://www.kaggle.com/datasets/podsyp/time-series-starter-dataset)https://www.kaggle.com/datasets/podsyp/time-series-starter-dataset or you can see it on `Month_Value_1.csv`
### Methodology
- Exploratory Data: overview of data distribution, seasonal decomposite, stationary test
- Modeling: using Fourier Transform to handle non-stationary data
- Model Evaluation: evaluation metrics and visualization forecast
### Result and Evaluation
MAE: 2265643.3

RMSE: 3055079.4

MAPE: 7.93%
![image](https://github.com/andreetanjung/Time-Series-Linear-Regression/assets/123824152/1622d3ac-ebb4-4c02-922d-d06f6bb56a43)

Based on the forecast, we can see that there is still an uptrend in revenue, with a decrease at the beginning of the year and a peak at the end of the year. However, the MAE and MAPE results are high, which suggests that the model is not good enough. The MAE of 2265643. means that the model's predictions are off by an average of 2,265,643 or 8% from the actual revenue. In a business setting, this kind of difference can have a significant impact on revenue and profitability.Therefore, it is important to explore other models that may be more accurate. There are a number of different time series forecasting models available, each with its own advantages and disadvantages. By comparing the MAE, RMSE, and MAPE values for different models, we can determine which model is the most accurate for our data.
### Project Insight on Real Life Business
By knowing the forecast of the revenue above, some implementation for the real life business are:
- inventory planning: help businesses to optimize their inventory levels on storage costs and prevent stockouts.
- marketing: revenue will decrease in the next quarter, they may decide to increase marketing efforts to try to boost sales.
- financial planning: business forecasts that revenue will increase in the next year, they may decide to take out a loan to invest in new equipment or hire more employees.
### Directory Structure and Brief Description of Files
`timeseries_linear_regression.ipynb` is a Jupyter notebook that contains the complete project code, including exploratory data with model, and evaluation.
