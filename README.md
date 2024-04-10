# LinearRegressionAssignment
> This is the assignment for Linear Regression module of Upgrad AI ML course


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this assignment, we have to build a multiple linear regression model for the prediction of demand for shared bikes.

  # Problem Statement
        A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled     wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


        A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


        In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


        They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

          * Which variables are significant in predicting the demand for shared bikes.
          * How well those variables describe the bike demands
          * Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


  # Business Goal:
        You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
- The linear regression params are as follows.
cnt = 0.311 +0.236yr -0.091holiday +0.384atemp -0.146windspeed -0.066Dec -0.043Feb -0.080Jan -0.055July -0.056Nov +0.054Sep -0.093Spring +0.062Winter -0.298Light Snow or Rain -0.084Misty, Cloudy sky +0.011Sat-0.48Sun

R-squared of train set = 0.844
R-squared adjusted of training set = 0.839
R-squared of test set = 0.823
R-squared adjusted of = 0.811
This shows our linear regression model is performant and can be used for predictions.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- seaborn
- pyplot
- sklearn
- statsmodel
- python3



## Contact
Created by [@hari-ar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
