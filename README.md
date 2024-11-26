# Bike Sharing Assignment - Linear Regression - Case Study
> To model the demand for shared bikes with the available independent variables using linear regression to understand the following: 
> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
####  Problem Statement 

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.   
#### Aim 
To model the demand for shared bikes with the available independent variables using linear regression to understand the following: 
 -    Which variables are significant in predicting the demand for shared bikes.
 -    How well those variables describe the bike demands
#### Goal 
The model will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- Dataset            : Historical data on Bike renting days details , including season, weather situations, temperature etc.

## Conclusions
 - `atemp` – Feeling Temperature is the most important factor in renting a bike. When temperature is warm, bike renting will be high
 - `Weather` – If there is snow or rain, bike renting will be considerably lesser than the Misty day
 - `Season` – Winter time will attract more bike renters than in Summer time
 - `Wind Speed` – When windspeed is high bike renting will be less
 - `Workingday` – Bike renting will be slightly more  during working days than in weekends or holidays
 - `Year` – 2019 is having higher number of bike renting than in 2018.

## Technologies Used
        Python:       Programming language for data analysis and manipulation.
        Pandas:       Library for data structures and analysis.
        NumPy:        Library for numerical operations.
        Matplotlib:   Library for data visualization.
        Seaborn:      Library for statistical data visualization.
        sklearn:      Library for Linear Regression, splitting the dataset into Training and Test, applying Normalization scalar and feature selection using RFE
        statsmodels:  Library for generating models and getting the statistical parameters and to calculate VIF



## Acknowledgements
    Data:             Day Data Set and Data Definitions
    Tools:            Jupyter Notebook, GitHub 
    Collaborator:     K Lalithabai Sobha 


## Contact
Created by [@SobhaSubhash] - feel free to contact me!

