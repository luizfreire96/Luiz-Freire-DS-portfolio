# [Wind Behaviour Prediction](https://github.com/luizfreire96/Wind-energy-data-curve-fit)

In this repository a wind speed prediction is made using probability density functions (PDF) and time series models.
The data is grouped in bins of 0.1 and 0.05 m/s to fit the probability density function.
The time series models used were the persistence model and auto ARMA, that autmaticaly find the best hyperparameters for that data.
The PDFs used were the normal and weibull distributions.
It seen the weibull mean value have the lowest RMSE error for long term prediction, but for prediction made up to 6 hours the best model can vary.

