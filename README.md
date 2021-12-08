# Business_Forecasting_Fish_Production
Analysis and forecasting of fishing in the United States
=
 
Overview:
----
- Our goal is to predict the amount of fish in metric tons that needs to be captured to suffice the needs of population for United States.
- We plan to do a long forecast of 3 years to predict the same.
- This forecast will help understand the amount of fishing that needs to be done to suffice the need of the population. 
- The forcasts will be very useful to the regulatory body to set a cap on the fishing to preserve the enviroment which going ahead will impact the fisheries that are into aquaculture.
- We are using various forecasting techniques such as Naïve, Simple Moving Average, Holt-Winters, Regression, Arima, Exponential Smoothing and Random Walk Forest to achieve the goal.
- We are going to consider MAPE as a good accuracy measure since it is scale independent and can be used to compare different forecast scenarios. 
- After analysing all models and comparing the MAPE value, we figured that Arima proved to be the best model with the lowest MAPE value as 2.19.
- The point forecast identified us that 4931017 metric tons fishes need to captured every year from 2017 to 2019 to suffice the need of the population in United States.

Data Description:
----
- The data consists of the amount of fishes captured in metric tons on yearly basis from 1960 to 2016. 
- We can see that there was a sudden hike in the fish capture till 1988. 
- This could be due to the advancement in technology where row boats were replaced with motors and fishing increased across the coast. 
- It could have reduced the price of fishes and made them easily available in the market.
- It can be seen that the graph started stabilzing after 1988.
- Thus we are considering the values from 1988 onwards for our analysis. 
- We converted the values of the fishe captures in to a time series with frequency 1 as it is yearly data.
- The new time series does not show seasonality but it does shows some trend.


Forecasting models used:
----
- Naïve
- Simple Moving Average
- Holt-Winters
- Regression
- Arima
- Exponential Smoothing
- Random Walk Forest

Output :
----
- Best Model : Arima
- Point Forecast : 4931017 
- lo95 : 4156536
- hi95 : 5705498


Files :
----
1) [Data file](https://github.com/VallabhSawant/Business_Forecasting_Fish_Production/blob/master/Data/Fish_Production_UnitedStates.xlsx)
2) [Code](https://github.com/VallabhSawant/Business_Forecasting_Fish_Production/tree/master/Project)
3) [Presentation](https://github.com/VallabhSawant/Business_Forecasting_Fish_Production/blob/master/Presentation/Analysis%20and%20forecasting%20of%20fishing%20in%20the%20United%20States.pdf)

Project Team Member:
----
1. [GauravKumar Vishwakarma](https://github.com/Gaurav-Vish)
2. [Vallabh Sawant](https://github.com/VallabhSawant)
3. [Rakshit Karera](https://github.com/Rakshit-Karkera)
