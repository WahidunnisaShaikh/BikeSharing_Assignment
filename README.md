# Bike Sharing Assignment
> To build a Multiple Linear Regression Model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.
  
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal:**
  You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands 
  vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will 
  be a good way for management to understand the demand dynamics of a new market. 
  
**Bike Sharing dataset** is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Analysing the final model, the comapany should focus on the following features:
- Company should focus on expanding business during Spring. 
- Company should focus on expanding business during September.
- There would be less bookings during Light Snow or Rain, they could probably use this time to service the bikes without having business impact.

Hence when the situation comes back to normal, the company should come up with new offers during spring when the weather is pleasant and also advertise a little for September as this is when business would be at its best.

Significant variables to predict the demand for shared bikes are:
- temp
- Year (2019)
- windspeed
- Season(Spring and Winter)
- months(March, September, November, December)
- Saturday
- weathersit(LightSnow, Mist)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python & jupyter notebook
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodels.api


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This assignment is done as a part of AI and ML executive PG programme (as part of Upgrad course). It is a individual assignment which give an idea about how to develope a  Multiple Linear Regression Model for a business in Real time. 

## Contact
Created by @WahidunnisaShaikh


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
