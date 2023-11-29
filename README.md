# Time_Series_Forecasting
With enbw 

Dataset: 
In the dataset daily, weekly and monthly seasonalities have been ploted to analyze the dataset provided to us.

Seasonalities:
Seasonal_decompose method has been used to check the seasonal patterns in the dataset. 

Preprocessing:
In preprocessing step I only used fillna which is not the best method as we have a huge gap in the dataset. In the next step we will have to find some other methods. 

Model: (could be any)
Used Darts library to train the model (ExponentialSmoothing) for timeseries dataset, darts provide some global model to train for multiple files so that I chose this one but obviously it could be any other model.  