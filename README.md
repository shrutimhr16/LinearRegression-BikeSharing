# Bike Sharing Assignment
> A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Business objective
The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<br>

## Problem Solving Methodology
* Data Understanding-
> Understanding and working with data dictionary and getting good knowledge of all the columns and their domain specific uses.
* Data Visualization-
> Perform EDA to understand various variables.
> Check the correlation between the variables.
* Data Preparation-
> Create dummy variables for all the categorical features.
> Divide the data to train & Test.
> Perform Scaling.
> Divide data into dependent & Independent variables.
* Data Modelling & Evaluation-
> Create Linear Regression model using mixed approach (RFE & VIF/p-value).
> Check the various assumptions.
> Check the Adjusted R-Square for both train & Test data.
> Report the final model.

<br>

## Conclusions
*We can see that the equation of our best fitted line is: <br>
cnt = 0.1910 + 0.2343 * yr + 0.4799 * temp - 0.1499 * windspeed + 0.0613 * season_summer + 0.0951 * season_winter + 0.0853 * month_sep - 0.0462 * weekday_sun -0.0570 * season_spring - 0.2865* weathersit_Light_snow_rain - 0.0803 * weathersit_Mist

Three key feature variables - temp, yr, and weathersit_Light_snow_rain exhibit the highest coefficient values, indicating their significant impact.

Significant variables to predict the demand for shared bikes are : 
>temp , Year ,windspeed , Season - (Summer, Spring and Winter) , months(July, September) , weathersit (Light_snow_rain and Mist

## Technologies Used
- Python - version 3.x

## Libraries Used
- Pandas , Numpy , Matplotlib , Seaborn , sklearn , statsmodels

## Contributors
* Shruti Mehra
