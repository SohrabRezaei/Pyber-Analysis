# Pyber_Challenge

## Overview of the analysis

* Creating a new dataframe based on type of city for a ride sharing company. Total rides, total drivers, total fare,average fare per ride and average fare per driver is collected in this dataframe as a summmary for pyber. Then, I create a chart to display the total fares of each city type weekly with [resample](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.resample.html)

## Results

The total amounts are low for rural city type compared to others,while urban being the highest. However, the average of fares are higher for Rural type while Urban being lowest. Then, a pivot table is created in order to create the resampling of fares dataframe for each week from early 2019 till 28th April. The total fare has many peaks for each city type thoughout the given time. The urban city is around 2000-2500$, the suburban city type is around 1000$ and the rural city type is lower than 500$.[![snip.jpg](https://i.postimg.cc/YCq5CNZ5/snip.jpg)](https://postimg.cc/6ygjHZ9c) ![image](https://user-images.githubusercontent.com/95439555/152699986-af29db21-3f4a-40b9-9738-d510020a8b9e.png)


## Summary

In the rural type, they could lower the fares by increasing the drivers and rides, while lowering the fare to decrease the average. In the suburban type, they could decrease the fares by lowering the rides and drivers. 



 
