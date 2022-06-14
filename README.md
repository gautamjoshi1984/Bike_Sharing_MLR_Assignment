# Project Name
> Bike Sharing Linear Regression Assignment


## Table of Contents
* [General Info](#general-information)
* [Business Objectives](#business-objectives)
* [Methodology Used](#methodology-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Dataset used

- day.csv - https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv
- Data dictionary - https://drive.google.com/file/d/1x4Vi_FF0DEmTN1Cf6BnPHUuQP9p0s0Pz/view

## Business Objectives
The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Methodology Used
- First step we imported the dataset, understood and visualized the dataset for basic information
- Next we did and Exploratory data analysis on the dataset to clean the dataset and prepare the dataset for modelling. 
- After that we used a hybrid model for feature selection i.e. automatic + manual to arrive at a final linear regression model with Adjusted R2 of 0.827
- After that we did residual analysis, prediction on the test data and model evaluation. 
- Finally we identified the most important features impacting the target variable. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- IDE - Jupyter notebook
- Language - Python 3.0
- libraries
    - Pandas
    - Numpy
    - Matplotlib
    - Seaborn
    - Statsmodels
    - Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Most important features that impact the demand

- temp ~ For every unit increase in temperature, demand rises by .548 times, which is very significant
- year ~ With each year the demand can rise by .23 times, year is also a significant variable and for a startup company the
    starting years are years of growth
- windspeed ~ Windspeed is negatively impacting the demand, for unit rise in windspeed the demand decreases by .153
- season_2 (Spring) and season_4(Winter) are also significantly impacting the demand i.e. .0881 & .1293 respectively
- weathersit_2 (Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) and weathersit_3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain +  
  Scattered clouds) are also negatively impacting the demand by 0.0784 and 0.2829 respectively.

It is recommended that the above factors are considered in particular while planning to cater the demand.

## Acknowledgements
Give credit here.
- This project was inspired by the knowledge and learning provided to us during our live sessions and couse provied by UpGrad and IIIT(B)


## Contact
Created by [@gautamjoshi1984] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
