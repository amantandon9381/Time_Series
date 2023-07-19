# Time_Series
Time Series Forecasting



- Read the data as an appropriate Time Series data and plot the data.
- Perform appropriate Exploratory Data Analysis to understand the data and also perform decomposition.
- Split the data into training and test. The test data should start in 1991.
- Build all the exponential smoothing models on the training data and evaluate the model using RMSE on the test data. Other models such as regression,naïve forecast models and simple average models. should also be built on the training data and check the performance on the test data using RMSE.
- Check for the stationarity of the data on which the model is being built on using appropriate statistical tests and also mention the hypothesis for the statistical test. If the data is found to be non-stationary, take appropriate steps to make it stationary. Check the new data for stationarity and comment. Note: Stationarity should be checked at alpha = 0.05.
- Build an automated version of the ARIMA/SARIMA model in which the parameters are selected using the lowest Akaike Information Criteria (AIC) on the training data and evaluate this model on the test data using RMSE.
- Build a table (create a data frame) with all the models built along with their corresponding parameters and the respective RMSE values on the test data.
- Based on the model-building exercise, build the most optimum model(s) on the complete data and predict 12 months into the future with appropriate confidence intervals/bands.
- Comment on the model thus built and report your findings and suggest the measures that the company should be taking for future sales.
