# Time_series_Analysis-
Time series analysis of the all share index of the nigeria stock exchange 2009 -2020
This repository was created out the codes I used for my final Year Project
The topic was Time series analysis of the all share index of the nigeria stock exchange 2009 -2020 using the Box-Jenkins Method
i tried to fit an ARIMA model to the the all share index of NSE for 2009 -2020. after modelling I then tried to make forecast with the best fit model.
Pardon The lack of comments in my code.
when i wrote the codes, I barely used comments A habbit I have finally overcome.
              A brief rundown of the steps taken
first the neccessary packages where imported, then the dataset was also imported.
A brief statistical description of the data was done while cleaning the data. 
After cleaning the data several plots where done to check for the stationarity of the data. 
Stationarity is a neccessary condition before carryingout a time series analysis.
the data wasn't stationary so it was made stationary by differencing the data. Then the stationarity condition was checked again and confirmed stationary.
Then the data was then modelled, the best model was selected and used for the forecasting.
I have a statistical background so i understand what i was doing i tried to skip the some statistical stuff like ACF, PACF, LJUNG-BOX etc for people with non - statistical background.
