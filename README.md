# Bike Sharing Assignment
> ## Multiple Linear Regression

The aim of this work is to build a multiple linear regression model for the prediction of demand for shared bikes.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- #### Problem Statement:

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know

- The dataset used was 'day.csv'. Ref: [1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.


## Conclusions
- **Impact of weather on bike demand:**
*   Riding weather conditions have strongest impact on bike demand.
*   Bike demand increases with increasing temperature, signifying clear sunny weather.
*   Bike renting decreases with windspeed 
*   During snowfall bike demand reduces, could be due to the  challenge of riding on a snow-filled road 
*   Mist reduces bike demand as well (not as much as snow), probably due to reduced visibility.

**Impact of seasons on bike demand:**
*   The bike demand in the spring is lesser  
*   During winter, again the demand for bike increases

**Impact of time/year on bike demand:**
*   Bike demand is increasing year over a year strongly. **Caution!**, only two years data is not enough to predict

### Recommendations

**On the impact of weather on bike demand:**
- During the higher windspeed try to provide the right type of cycle which sustain under those conditions 
- During snow season, replace the summer wheels/thin one with a snow sustainable wheels/ thicker one
- During misty days provide bikes with good quality fog-lamps 

**On the impact of seasons on bike demand:**
- Spring season is the right time for annual maintenance of the vehicles, are there will be lesser demand
- Discounted rates may increase the demand, which indeed needs to be studied  

**On the impact of time/year on bike demand:**
- If the trend continuous the demand for bike sharing will increase, so the enough supply of bikes in good quality may increase the revenue


## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.23.5
- matplotlib - version 3.7.0
- matplotlib-inline - version 0.1.6
- seaborn - version 0.12.2
- Scikit-learn - version 0.20
- statsmodels - version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@https://github.com/pvbalajimol] - feel free to contact me!
