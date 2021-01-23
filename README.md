# PyBer_Analysis

Performing an exploratory analysis and creating visualizations using rideshare data and other tools to help improve access to rideshare services and determine the usability in different types of cities.

### Overview of the analysis

The PyBer overview provides a comparison of PyBer's ridesharing services in three types of cities: Rural, Surburban and Urban. The summary demonstrates how the number of drivers, number of rides and the fares affect the overall working of PyBer. This analysis will help us summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.
For this analysis we have used Anaconda(python data) 4.8.5 Python 3.7.6 Pandas, numpy and matplotlib for python using Jupyter notebook.


### Results

![Summary](https://user-images.githubusercontent.com/75771291/105615740-74262080-5d98-11eb-8af2-fae0ed744d14.png)

In terms of costs, it appears that riders in rural cities pay on average almost $10 more for PyBer than riders in urban cities. The average fare per ride is about $35 in rural cities whereas the average fare per ride is about $25 in urban cities. Suburban cities' average fare per ride falls just in between - at about $31. The average fare per driver is about $55 in rural cities, whereas the average fare per driver is about $17 in urban cities. Suburban cities' average fare per driver is about $40.



![Fare_by_city_type](https://user-images.githubusercontent.com/75771291/105615755-9455df80-5d98-11eb-86ca-5a0d67a6e6c6.png)


The multiple-line chart "Total Fare by City Type" further supports the PyBer Summary DataFrame by providing trends of total fares in Rural, Suburban, and Urban cities between January 2019 and April 2019. The yellow trend shows how fares in urban cities totaled from around $1,600 to $2,300 from beginning to end during this five-month period. In contrast, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. The red trend shows how the total fares in suruban cities fall in between urban and rural cities: around $700 to $1,300 from beginning to end during this time. The chart further demonstrates similar peak times in all these types of cities.


### Summary

The following are the three business recommendations for the CEO which can be addressed for disparities among the city types.

1.Drivers in rural cities are earning more than drivers in urban cities. This could discourage the potential drivers from working with PyBer in Urban, given the low average fare per driver. The average fare per ride and average fare per driver should be reduced as it is highest for the rural city type, this could possibly be a reason for less number of total rides as compared to the urban city type. If we compare the total rides of Urban and rural cities there is a huge difference in both. Even with the lowest average fare per driver in the urban city type, it has highest number of total rides.
2. As we can see that the number of total rides and number of total drivers is moderately less in Suburban cities compared to Urban cities, but the average fare per ride and average fare per driver are high. Reduce the average fare per ride and average fare per driver for the suburban city type, this could possibly increase the total fare for suburban city type.
3.Increase the number of drivers for rural city type. As we see the number of drivers for rural city type are the lowest, employing more drivers could increase the service avaiability and possibly increase the number of rides which could increase the total fares for rural city type as they are directly proportional.
