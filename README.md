# Bike sharing assignment 
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## General infromation

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Below mentioned methods have been used to draw the conclusions : 
1. Reading and understanding the data-sets
2. Analysis - Univariate, Bivariate and Multivariate Analysis
3. Data preparation and creation of dummy variables
4. Splitting the Data into Training and Testing Sets
5. Building a linear model - Using RFE and Manual(VIF+P-value)
6. Residual Analysis of the train data and validation
7. Making Predictions and Model Evaluation

## technologies-used

numpy - version: 1.26.4
pandas - version: 2.2.2
matplotlib - version: 3.9.2
seaborn - version: 0.13.2
statsmodels - version: 0.14.2
sklearn - version: 1.5.1

  
## conclusions

Variables which can be used for predications as per the final models :
 Year, Temperature, Holiday, windspeed, Spring, Winter, Light snow and Mist cloudy 

 - Temperature : +3540 per unit increase. Warmer temperature shows more bike bookings. People prefer booking bike in hot weather rather than walking
 - Year : +2003 per year. Bike booking trend has increased from 2018 to 2019. It shows bike booking trend is increasing each year.
 - Holiday : -705 rentals on average. Bike booking less on holiday, it shows people might not be going out as much on holidays.
 - Windspeed : -790 bookings per unit increase in wind speed. People don't use bikes in high winds
 - Spring  : Spring season sees a Drop in Rentals (-1268 bookings). People prefer staying in home rather than using bike. It might be due to rainy weather during early Spring.
 - Winter : There is increase in bike Rentals (+434 bookings). Surprisingly, winter sees more rentals than other seasons, possibly due to commuter demand. It might be possible biking helps in keeping people warm due to increase in pysical movement
 - Light snow :Snow and cloudy weather reduces bike rentals. People prefer to stay at their places rather than going out. Maybe they are using other sources of commutes. 
- Mist/cloudy - It shows causes a huge drop (-2198 bookings). People are staying at their places rather than going out.


## Contact
Created by [@saloni454] - feel free to contact me!

