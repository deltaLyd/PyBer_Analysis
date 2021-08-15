# PyBer_Analysis

## Analysis of Ride-Sharing Data by City Type

**Purpose & Overview**:

The purpose of this project is to analyze PyBer ride-sharing data to gain actionable intelligence and present related visuals to decision-makers at the company, specifically my client V. Isualize, that she and others may make informed business decisions.
The analysis groups the data into 3 cohorts, based on city-type: Urban, Suburban, and Rural, and provides relevant statistics on each cohort, by city-type: total number of rides, total number of drivers, total fares charged/collected, the average fare per ride and per driver, and the total fare by city type over the 4-month time-span January through April.
My client is interested in understanding and addressing any disparities that exist in the ride-sharing data, which these statistics inform.

## Results

**Disparities Between City Types**

![Total Rides DataFrame.PNG](https://github.com/deltaLyd/PyBer_Analysis/blob/main/Resources/Total%20Rides%20DataFrame.PNG)

This table, created as a summary DataFrame during the analysis, clearly displays relevant information that is the basis for several of my recommendations to V. Isualize. 

While informative, the summary table does not display any major surprises.  The data output is logical based on the population density of different city types and the mechanics of supply and demand for a service in the economy:

• Urban cities have the most drivers, followed by Suburban, than Rural.
    While this is not a guarantee, it is mathematically unlikely to impossible for a rural city to field 2,405 drivers to match the count of Urban city drivers, as many               small towns (rural cities) have populations that are smaller than 2,405 people.
    
• Urban cities have the most rides, followed by Suburban, than Rural. 
    Again, this is not guaranteed to be the case, but the average Suburban and Rural drivers would have to complete significantly more rides than the average Urban driver             to equal or exceed the total rides for the largest memeber of the city-type cohort.
        
• Urban cities have the most greatest total fares collected, followed by Suburban, than Rural.
    Though the average fare per ride in Urban cities is lower than Rural or Suburban, the volume of rides leads to the greatest total fares collection.
    
• Rural cities have the highest average fare per ride, followed by Suburban, and then Urban.
    This makes sense, as the lower supply of drivers should push up the price for a ride to meet demand.

• Rural cities also have the highest average fare per driver, followed by Suburban, and then Urban.
    While this may make Rural areas look the most attractive for being a driver, there are very few total rides, so the drivers can only earn a large fare on a small volume of         rides, relative to other city types.
    
This data can also be viewed graphically, from the January through April time frame.  While there is fluctuation in the number of rides for a given week, all 3 city types stay in roughly the same band of the graph.  There is strong growth in Urban and Suburban Total Fares over the time period, and Rural is largely flat.
    
![PyBer_fare_summary.png](https://github.com/deltaLyd/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)

## Summary, Data Limitations & Recommendations

Overall, this analysis is straightforward.  With that in mind, I have the following 3 recommendations for my client, V.  Isualize, as she considers addressing disparities between the city types:

1) I suggest thinking about the three city types as three disctinct business environments, and understanding that there are factors which will not allow for a one-size-fits-all approach.  If the goal was to simply achieve the same average rate per ride, there would need to be many more drivers hired in Rural and Suburban cities to lower the price to that of Urban cities.  If that was done, however, the average fare per driver would also decrease in these areas, and it may reach a point where drivers no longer find the rate high enough to justify driving, leading to driver attrition that, all else equal, will limit supply and again push up prices.

2) PyBer should provide me with a larger dataset, or--if this is the first months of operation, purely focus on growth to capture market share, as there is clearly strong demand for the service being offered, and good rates are being earned in each city cohort. As I was only provided date-data for 4 months of 2019, I cannot conduct any year-over-year or even quarter-over-quarter data analysis, which would inform what the growth rates for total number of drivers and rides is in each city-type, and then assess that growth vs. the amount of money PyBer has spent building out its business in different city-types, to determine what the best investment for the given dollar is. 
Furthermore, the January through April timeframe is mostly winter months, and having this narrow view does not allow me to analyze how much seasonality may effect the total number of rides and the other related PyBer ride statistics. 

3) Similar to competitor Uber, I suggest that PyBer apply pricing multipliers based on demand-surges, both to incentivize more drivers to accept rides and to earn greater fees for the company by capitalizing on short-term mismatches of supply and demand.  Rather than trying to flatten disparities between dissimilar markets, the focus should be on growing the total ride volume capacity by expanding the driver volume in each respective market, while capitalizing on demand mis-matches to earn additional revenues at peak ride-demand times.  The key metric that V. Isualize should focus on managing is the driver volume in each market relative to ride-demand, to balance achieving profitability with capturing market share.
