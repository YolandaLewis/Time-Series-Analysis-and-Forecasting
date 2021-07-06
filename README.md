# Time-Series-Analysis-and-Forecasting

This specific dataset was originally acquired from Zillow.com research data and includes 23,396 observations with 293 variables. The variables in the dataset include a region ID, size rank of a city and state, region name, state, surrounding metro city name, county name, and date columns with housing prices as values.

Exploratory analysis on Chicago,IL 2 bedroom housing was completed by plotting the time series which was determined to be a multiplicative and a random walk.The normality of the series was explored using histograms, qqplots, and the Jarque-Bera test. Stationarity was tested using ACF, PACF and performing Dickey-Fuller and KPSS tests. The null hypothesis was rejected that the series is non-stationary. A final SARIMA model of (1,0,3)(0,0,1)[12] was determined. 

Chicago and Mineapolis were compared for a large versus small housing market comparison. They were found to be co-integrated and found to have similiar growth patterns despite  Minneapolis being a smaller market.
