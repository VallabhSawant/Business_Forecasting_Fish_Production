# Business_Forecasting_Fish_Production
Analysis and forecasting of fishing in the United States
=
 
Overview:
----
- Our goal is to predict the amount of fish in metric tons that need to be captured to suffice the needs of the population for the United States.
- We plan to do a long forecast of 3 years to predict the same.
- This forecast will help understand the amount of fishing needed to suffice the population's needs from 2017 to 2019.
- The forecasts will be beneficial to the regulatory body to set a cap on fishing to preserve the environment. This will also impact the aquaculture business.
- We are using various forecasting techniques such as Naïve, Simple Moving Average, Holt-Winters, Regression, Arima, Exponential Smoothing, and Random Walk Forest to achieve the goal.
- We will consider MAPE as a good accuracy measure since it is scale-independent and can be used to compare different forecast scenarios.
- After analysing all models and comparing the MAPE value, we figured that Arima proved to be the best model with the lowest MAPE value as 2.19.
- The point forecast identified us that 4931017 metric tons fishes need to captured every year from 2017 to 2019 to suffice the need of the population in United States.

Data Description:
----
-	The data consists of the number of fishes captured in metric tons on a yearly basis from 1960 to 2016.
-	We can see a sudden hike in the fish capture till 1988.
-	The hike could be due to technological advancement where rowboats were replaced with motors and fishing increased across the coast.
-	It could have reduced the price of fish and made them readily available in the market.
-	The graph started stabilizing after 1988.
-	Thus, we are considering the values from 1988 onwards for our analysis.
-	We converted the values of the fish captures into a time series with frequency one as it is yearly data.
- The new time series does not show seasonality but it does show some trend.


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
