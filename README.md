# PyBer Analysis

## Overview
#### The CEO of a ride sharing service requested assistance in analyzing the data of the service from different cities. Data from two separate sources were merged to create a data frame to hole all the values necessary for the analysis including the city, date, fare, ride ID, number of drivers, and type of city. The aim of this specific analysis was to highlight the relationship between the different city types and the fares, rides, and drivers from the corresponding cities. After calculating the data for the various city types, the fares by city type were analyzed by the average weekly fares from 1/1/19 to 4/28/19 to provide greater insight to PyBer trends.

## Resources Utilized
##### Data Source: city_data.csv, ride_data.csv
##### Software: Python 3.7.6; Anaconda 4.10.3

## Results
#### 
The PyBer data synthesized from the files indicates some differences between rural, suburban, and urban cities. Looking at the image of the data below, the most obvious differences amongst the city types is the Total Ride and Total Drivers for each city type. A classification for city types involves the number of people in the population, it is logical that urban cities have the most rides and drivers, suburban cities have the next highest rides and drivers, and rural cities have the fewest rides and drivers. Similarly, the total fares are significantly higher for urban cities with decreasing values for suburban cities and even more decreased values for rural cities.

![Summary DataFrame](https://user-images.githubusercontent.com/99554642/159813559-06ec30ad-db39-4270-9d0a-6f373ef09099.png)

Two of the most interesting aspects of the data are the Average Fare per Ride and Average Fare per Driver. For these two calculations, the rank of city types appears to be inversed, with rural cities having the greatest values and urban cities having lowest values. While the Average Fare per Ride only had a $10 difference between rural cities and urban cities, the Average Fare per Driver had a difference of about $40. 

![PyBer_Fare_summary](https://user-images.githubusercontent.com/99554642/159813574-22b4b9e8-d877-4cee-9fc2-ac8137136292.png)

The graph above highlights the Total Fares by City Type for every week from 1/1/19-4/28/19. The average fares of rural cities remained relatively constant with slight peaks at the end of February and the beginning of April. Suburban cities had an increase in average fare in January, February, and the end of April. Conversely, Urban cities had peaks in fare throughout the month of March with deceasing fares through April.

## Summary
In order to minimize disparities between the different city types, one recommendation is to provide incentives for drivers in rural and suburban areas as a means to attract more drivers to the service. While having more drivers than rides may not be ideal (as is the case with urban cities), utilizing more drivers could increase the amount of rides provided and ultimately total fares. Another recommendation is to run promotions in areas for riders based on the month and city type. For example, running a promotion for slightly discounted rides in March and April in Suburban cities would hopefully increase rides, which in turn could increase total fares. The last recommendation for the CEO of PyBer would be to add a rewards system for PyBer users to encourage more regular rides. Both urban and suburban cities experience large dips and peaks in their total fares but a rewards program might prompt riders to order more rides, which would decrease the varying levels of fares.
