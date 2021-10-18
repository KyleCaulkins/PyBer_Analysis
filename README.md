# PyBer Analysis

## Overview

The purpose of this analysis is to provide a summary of ride-sharing data by city type, to decision-makers at Pyber. Pyber is a python-based ride sharing app company, with CEO V. Isualize. A goal of PyBer is to improve access to ride sharing services and determine affordability for underserved neighborhoods. Part of making decisions for the future is understanding where total rides, drivers, and fares currently are for each city type. The following analysis is provided, per request of V. Isualize, to aid in making the PyBer goal a reality.  

## Results

A table for the ride sharing data, by city type, is shown below. The number of rides, drivers, and total fares appears to trend with population density. Rural cities have the least rides, drivers, and total fares while urban cities have the most. Average fare per per ride and average fare per driver trend inversly with population density; rural fares are high than urban fares on average. Suburban city results fall between rural and urban cities in all categories. These results seem intuitive considering rural cities likely have a lower demand, with lower population, and likely have a longer average ride, when compared to an urban city. 

![PyBer_Ride_Sharing](/analysis/ride_sharing_by_city_type.png)

A graph of total weekly fares by city is shown below. The fare totals are plotted against time for January through April. The total weekly fares have some variability but nothing that is extreme, or overtly concerning. None of the city types appear to be heavily trending towards an increase or a decrease in total fares. The graph shows that on a weekly basis the total fares for urban cities is larger than suburban, which is larger than rural cities. These findings hold true for every week in the the time sample.  

![PyBer_Fare_Summary](/analysis/PyBer_fare_summary.png)


The code used to perform the analysis can be found in detail, in the *Complete Python Script*.

![Complete_Python_Script](PyBer_Challenge.ipynb)

## Summary

Overall, the analysis provides clarity to the differences in PyBer business between city types. Using this clarity, here are three business recommendations for addressing disparities among the city types. The first recommendation is to perform a market analysis and determine if there is a need for more drivers in the three city types. If the market analysis shows room to expand in rural and suburban cities, this should be pursued. There is significantly higher average fare per driver and average fare per ride in these city types. It is likely these city types are under served. 

Another recommendation is to encourage or incentivize drivers, operating in urban cities, to consider offering rides in suburban or even rural cities. Some of these drivers may be local to urban-suburban or suburban-rural transitions and they could operate in a lower population density city to help improve access. This shift could help lessen the divide of total drivers and average fare per driver based on city type. The final recommendation is to evaluate the current pricing model. The data did not include the distance of each ride but cost per mile should be considered. To make sure affordability is not a limiting factor, the average fare by city type should be investigated further.
