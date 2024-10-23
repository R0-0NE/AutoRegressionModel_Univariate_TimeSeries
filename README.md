# AutoRegressionModel_Univariate_TimeSeries

This project demonstrates the application of an autoregression model to predict future values in a univariate time series dataset. The dataset used consists of daily minimum temperatures.

Steps Included:
Data Loading:

The dataset, containing daily minimum temperature records, is loaded using pandas.
A quick visualization of the data is created using matplotlib to understand the trend over time.
Data Preparation:

To implement the autoregression model, the data is prepared by shifting values to create a lagged dataset where the previous day's temperature (t-1) is aligned with the current day's temperature (t+1).
The correlation between t-1 and t+1 is calculated to analyze the relationship between consecutive days' temperatures.
Visualizations:

A plot of the temperature trend over time is generated to visualize the patterns in the dataset.
