# PyBer Analysis

## Overview of the analysis

For this analysis, we are working at Pyber as a data analyst conducting an exploratory analysis on ridesharing data. The purpose of the analysis is to quantify the differences between cities so that business changes may be implemented to improve the overall rating of PyBer. 

We will examine three city types: Rural, Urban, and Suburban.  
Within those categories we will look at:
  - Total Rides
  - Total Fares
  - Total Drivers
  - Average Fare per Ride
  - Average Fare per Driver

We will also create a new Dataframe to show the fares between January 1st, 2019 and April 29th, 2019. With this information, we will create a line chart depicting the differences in fare by city type.
 
- Resources:
  - Python, Pandas Library, Matplotlib
  - ride_data.csv and city_data.csv
  
 
## Results
The image below shows the City Types and the differences in their data. 

<p align="center">
    <img src=pyber_summary_screenshot.png> 
</p>

Looking at this data we can see that Urban cities have more rides and drivers, which pushes the cost of the fare down. The reverse is true for Rural towns; With fewer rides and drivers, the cost per ride and per drivers is much higher than the Urban cities. Suburban cities aren't exactly in the middle with their data; they lean closer to Rural towns since they have 1000 less rides than Urban cities. 

The biggest difference between these city types are the  Average Fare per Driver. Drivers in Urban cities make roughly $40 less per ride than Rural drivers. Despite high driver fare, Rural towns don't bring in as much revenue as the low fare per ride and driver that Suburban and Urban cities bring in. 

*insert total fare by city type line chart when I figure out how to make it work*

## Summary
After looking at the data and results, we can conclude that:
  - Urban cities bring in the most revenue
  - Increasing rides in Suburban and Rural towns is a necessity.

We suggest increasing ridership in Suburban and Rural towns by:
  - Incentivize riders to venture out into these towns by offering a discounted ride for every fifth ride.
  - Create a partnership with local businesses to create the desire to ride into these areas.
  - Offer a monthly bonus to drivers to complete a certain amount of rides in Suburban and Rural areas. 

