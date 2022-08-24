# [Project 1: Photovoltaic grid malfunction detector](https://github.com/luizfreire96/photovoltaic-grid-malfuncction-detector)

In this repository a exploratory analysis is made from solar energy production and ambient conditions data. <br>
Then a linear model is created to predict if the grid have a malfunction based in the error of the model. <br>
If the residual error is outside of the 95% confidence interval, probably is a unusual error that indicate malfunction in the grid or the instrumentation<br>
Flask is used to create the app and docker to create an environment with the dependencies to run the app.<br>
To access the application click [here](https://pv-malfunction-detector.herokuapp.com/)<br>

![](images/pvplot.png) <br>

<div id="image-table">
    <table>
	    <tr>
    	    <td style="padding:10px">
        	    <img src="images/correlation-pv1.png" width="400"/>
      	    </td>
            <td style="padding:10px">
            	<img src="images/corralatiopv2.png" width="400"/>
      	    </td>
        </tr>
    </table>
</div>


# [Project 2: Telecom churn predictor](https://github.com/luizfreire96/Telecom-Churn-analysis)

In this repository a end-to-end application was created to predict if a telecom company customer will churn. <br>
The data is unbalanced and some work has been done to get a better recall.<br>
Random Forest Classifier has been used to make this application<br>
The application was deployed in heroku using docker. Click [here](https://laff-churn-predictor.herokuapp.com/) to access the aplication<br>


<div id="image-table">
    <table>
	    <tr>
    	    <td style="padding:10px">
        	    <img src="images/cramercorrelation.png" width="280"/>
      	    </td>
            <td style="padding:10px">
            	<img src="images/confusion1.png" width="280"/>
            </td>
            <td style="padding:10px">
            	<img src="images/confusio2.png" width="280"/>
            </td>
        </tr>
    </table>
</div>



# [Project 3: Wind Behaviour Prediction](https://github.com/luizfreire96/Wind-energy-data-curve-fit)

In this repository a wind speed prediction is made using probability density functions (PDF) and time series models.<br>
The data is grouped in bins of 0.1 and 0.05 m/s to fit the probability density function.<br>
The time series models used were the persistence model and auto ARMA, that autmaticaly find the best hyperparameters for that data.<br>
The PDFs used were the normal and weibull distributions.<br>
It seen the weibull mean value have the lowest RMSE error for long term prediction, but for prediction made up to 6 hours the best model can vary.<br>

![](images/comparacaoentremodelos.png)<br>

<div id="image-table">
    <table>
	    <tr>
    	    <td style="padding:10px">
        	    <img src="images/weibull.png" width="400"/>
      	    </td>
            <td style="padding:10px">
            	<img src="images/normal.png" width="400"/>
      	    </td>
        </tr>
    </table>
</div>



# Tableau Visualizations
Click [here](https://public.tableau.com/app/profile/luiz.alberto.freire.filho4023) to access my tableau profile

![](images/Potencial-biogas.png)

# Minor Projects and Exercises
[Python](https://github.com/luizfreire96/br-python-challenges)<br>
[SQL](https://github.com/luizfreire96/SQL-Exercises)<br>
[Szeged-Weather-linear-regression](https://github.com/luizfreire96/Szeged-Weather-linear-regression)<br>
[Greenhouse-Gases-Influence-in-Temperature](https://github.com/luizfreire96/Greenhouse-Gases-Influence-in-Temperature)<br>
[Car-industry-70-82](https://github.com/luizfreire96/Car-industry-70-82)<br>
[Rent-web-scraping](https://github.com/luizfreire96/Rent-web-scraping)
