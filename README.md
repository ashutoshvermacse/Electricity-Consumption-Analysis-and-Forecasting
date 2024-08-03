This project focuses on analyzing electricity consumption over a span of approximately 14 years using the PJM Hourly Energy Consumption Data from Kaggle. The objective is to explore patterns, trends, and seasonality in the data, and to build predictive models to forecast future consumption.

**Key Analyses Performed:**

1. **Visualization of Daily Electricity Consumption:**
   - Graph displaying daily usage patterns to identify high and low consumption periods.

2. **Visualization of Monthly Electricity Consumption:**
   - Monthly consumption trends highlighted through visual plot.

3. **Seasonality Check using ACF Plot:**
   - Autocorrelation Function (ACF) plot of monthly electricity consumption to assess seasonality.

4. **Comparison of Monthly Consumption Trends:**
   - Examination of monthly electricity consumption trends in the years 2005, 2010, and 2015.

5. **Decomposition of Monthly Electricity Consumption:**
   - Breaking down monthly consumption data into seasonal, trend, and residual components.

**Model Building and Forecasting:**

Four different models were developed to predict electricity consumption:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **SARIMAX (Seasonal AutoRegressive Integrated Moving-Average with eXogenous factors)**
- **Exponential Smoothing**
- **RNN (Recurrent Neural Network)**

Among these, the Exponential Smoothing model provided the best results. Using this model, electricity consumption was forecasted for the next 24 months with a high degree of accuracy.
