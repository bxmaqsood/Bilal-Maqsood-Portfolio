# Bilal-Maqsood-Portfolio

# [Project1: Stock Prize prediction using time series forecasting:](https://colab.research.google.com/drive/10wQH6oIfCs1MvEB8xrlL7w3wJnSy0mm3#scrollTo=YPjtv24XYD_7)

(Stock Prizes prediction for the 3 Big Tech Companies (Microsoft, Google and Meta) for the last 3 months of 2022 using Auto regression, Moving Average and grid search ARIMA), [Dataset dowloaded from Yahoo Finance](https://finance.yahoo.com/quote/META/history?p=META)

Project Overview:
* Did Exploratory Data Analyis, looked for outliers and extreme values and removed the extreme values after visualizing them using boxplots.
* Achieved Stationarity after finding the time series non stationary using AD Fuller test, and differencing it to make it stationary.
* Built a persistence model to get a bench mark for the comparison of the results, plotted Auto correlation plot and partial Auto correlation plot to decide for the optimum number of lags for the Auto regression and moving average model.
* Trained Auto regression model, moving average model and grid search ARIMA and compared the RMSE for 3 of them to decide for the best.
* Integrated the 3 time series back to get the actual predictions and plotted it to compare with the actual results and drew insights.
* Look for the insights from the predictions and analysed the differnce in investment decision that we might have made on the basis of predicted data vs the actual data.
