# Project Name - Bike Sharing Assignment
> A US bike-sharing provider BoomBikes  aspires to understand the demand for shared bikes among the people  in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- The plan is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.
- BoomBikes have contracted a consulting company who have gathered a large dataset on daily bike demands across the American market based on some factors. 


## Conclusions
- We have chosen top 15 features to predict the target variable. After converting the categorical variables into dummy variables, we are fitting the model using RFE. The target varaible 'cnt' variable which indicates the total number of bike rentals, including both casual and registered, can be explained by the selected features well and r2-score is 0.81.


## Technologies Used
- Pandas     - version 1.4.4
- Numpy      - version 1.21.5
- Seaborn    - version 0.11.2
- Matplotlib - version 3.5.2
- sklearn - version 1.0.2
- statsmodels - version 0.13.2





## Contact
Created by [@karishma6636]- feel free to contact me!