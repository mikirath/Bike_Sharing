# Project Name: Bike Sharing Assignment
>  This project is used to understand the factors that affect the demand for bike so that the service provider can provide the adequate amount of bikes at the right location and at the right time and earn huge profit.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- What is the background of your project?

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- What is the business probem that your project is trying to solve?

The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

- What is the dataset that is being used?

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 : The equation of best fitted line is mentioned below:

count = 0.0875 + 0.2334 * year + 0.5682 * temperature + 0.0812 * summer + 0.1261 * winter + 0.0895   * september - 0.0867 * holiday - 0.1455 * windspeed - 0.2535 * lightrain 

- Conclusion 2 : Temperature has highest positive impact on bike demand
- Conclusion 3 : The demand for bike has increased over the year i.e. demand is more in 2019 as      compared to 2018.
- Conclusion 4 : The demand for bike decreases in rainy weather

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- seaborn
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the steps performed by the instructor in Upgrad learning platform.
- References if any... (Not Applicable)
- This project was based on [this tutorial](https://www.example.com). 
- The subjective question answers were based on the below references.
    a) https://stackoverflow.com/questions/63661560/drop-first-true-during-dummy-variable-creation-in-pandas#:~:text=drop_first%3DTrue%20is%20important%20to,correlations%20created%20among%20dummy%20variables.
    b) https://en.wikipedia.org/wiki/Anscombe%27s_quartet
    c) https://www.programsbuzz.com/interview-question/what-q-q-plot-explain-use-and-importance-q-q-plot-linear-regression
    d) 


## Contact
Created by [@mikirath] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->