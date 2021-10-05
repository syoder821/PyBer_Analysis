# PyBer_Analysis

## Project Overview
Client has requested the team generate a summary DataFrame of the ride-sharing data by city type using the supplied data located in the resources folder. Also, a multiple-line graph showing the total weekly fares for each city type (urban,suburban,rural) is provided for visualization.  An analysis is provided of how the data differs by city type and recomendations on how these differences can be used by decision-makers at PyBer.   

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Anaconda virtual environment Python Jupyterlab Pandas

## Results:
### Ride-sharing by city type DataFrame:

![Alt Text](https://github.com/syoder821/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

### Total fare by city type:

![Alt Text](https://github.com/syoder821/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

One key oberservation of the data is that the number of urban drivers is greater than the number of total rides.  Urban city type has the greatest total fare dollar amount but has the lowest average fare per ride.  The rural city type has the lowest total fare but has the highest average fare per ride.  The urban city type has ~ 5X the number of drivers as the suburban city type with just ~2X the total fare dollar amount. 

## Summary
Increasing the number of drivers in suburban areas provides potential growth opportunites in total fare amount.  To optimize efficiency allocating some of the excess drivers in the urban area to the suburban area could increase total fares without increasing costs.  A reduction in the number of drivers in the urban area should be studied further to determine if costs can be reduced without impacting the total fare amount.   
