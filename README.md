# time_series_analysis
Forecasting the data for the upcoming time is always a better idea in order to drive buisnesses on a leading path. Time series analysis and forecast is a great measure for predicting the future (in a nutshell). Here in this repository I am managing the projects and ideas about the time series analysis using different datasets. 
<p>
Some notebooks are uploaded here as my work with time series data. I have used two datasets for the analysis.
<ol>
  <li>Lynx trapping dataset includes data of number of lynx trappings since 1821 to 1934. This dataset has univariate data with no seasonality therefore I have used ARIMA model for forecasting. </li>
  <li>Nottingham temperature dataset which has a monthwise temperature recording since 1920. This datasets consists of univariate data with seasonality. Hence for forecasting I have used pmdarima package to automatically select best parameters for the ARIMA model. Along with this I have used STLDecompose model and as a result both have worked very well with the dataset.</li></ol>
<p>
  Apart from this I have used simple and exponential smoothing on both the datasets.
