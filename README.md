# Pharma sales data analysis and forecasting
 
 The objective of the analysis is to:
 - validate different methods and approaches related to sales time series data preparation, 
 - sales analysis & forecasting, with aim to facilitate recommending pharmaceutical products sales and support marketing strategies.
 - all these analyses and forecasts are made on a small scale, for a single distributor, pharmacy chain or even individual pharmacy. 
 - measuer effectiveness of three forecasting methods, namely ARIMA, Facebook’s Prophet and Long-Short Term Memory (LSTM) neural networks. 
 - each method has two optimization and validation approaches, relevant for short-term (so called rolling forecast scenario) and long-term forecasting.
 
### Data Source: Six years data (2014-2019) on sales of drugs classified in 8 ATC categories
- Sales data are resampled to the hourly, daily, weekly and monthly periods. 
- Data is already pre-processed, where processing included outlier detection and treatment and missing data imputation.

![Seasonability Analysis - Trend](https://github.com/jhenvi/Pharma-sales-data/blob/main/graphs/seasonalityTrend.png.png)
![Seasonability Analysis - Daily Data](https://github.com/jhenvi/Pharma-sales-data/blob/main/graphs/seasonalityAnalysis1.png)
![Seasonability Analysis - Daily Data](https://github.com/jhenvi/Pharma-sales-data/blob/main/graphs/seasonalityAnalysis2.png)
