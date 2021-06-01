# PyBer with Matplotlib

## Overview of the analysis
The goal is to perform an analysis on a ride-share dataset from January to early May of 2019 completed with visualized analysis for PyBer, a ride-sharing application company. By grouping the data based on city type (urban, suburban and rural), this analysis could provide the company's some insights for decision making, such as, improving access to ride-sharing services and determining affordability for underserved neighborhoods. 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Jupyter Notebook 6.3.0, Python 3.7.10
- Library: Pandas, Matplotlib

## Results
As expected, urban cities had a high concentration of drivers and total rides compared to suburban and rural cities. As shown below, in the time period of January to early May of 2019, rural cities had a total of 125 rides by 78 drivers with a total of $4,328 in fares.  The small data size for rural cities resulted in the highest average fare per ride and average fare per driver compared to the other two city types due to artifical inflation.  Additionally, it could also be caused by the typical rural settings with residential homes/buildings being farther apart and fewer in numbers, thus, resulting in longer driving distances and higher fare per ride. 

![summary_data](https://github.com/junepwk/pyber-analysis/blob/main/Resources/summary_data.png)

Based on the multiple line plot below, urban cities experienced the highest spike in late February and early March.  For suburban cities, the only spike is in late February and it appears to pick up significantly as it approaches May. For rural cities, it appears the demand for ride-sharing services is highest in April.

![pyber_fare_summary](https://github.com/junepwk/pyber-analysis/blob/main/analysis/pyber_fare_summary.png)

#### Data for the sum of the fares for each week
![weekly_fares_type](https://github.com/junepwk/pyber-analysis/blob/main/Resources/weekly_fares_type.png)

## Summary
Based on the summary data, urban cities had a total of 2,405 drivers and 1,625 total rides.  There seems to be slightly more supply than demand so I would suggest a thorough evaluation or further analysis on whether there needs to be a reduction of drivers in urban areas or maintain the number of drivers in case of a high influx of demand during holidays. Beside this observation from the data gathered, the overall analysis could provide deeper insights on any other disparities among the city types if we accounted for the population of each city and distances driven per ride.  This could further explain the high average fare rate in rural cities and in turn determine affordibility in these areas. Furthermore, it could be beneficial to consider major holidays and/or events that could have taken place during the high spikes shown in the multiple line plot.  For example, the potentional spike for suburban cities as time approaches May could be due to summer breaks for many students. 
