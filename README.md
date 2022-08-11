# surfs_up
Performing analysis on Oahu's (Hawaii) precipitation levels to determine if its shop business is sustainable year-round


## Overview of Project

W. Amy is concerned about the amount of precipation on Oahu. There needs to be enough rain to keep everything green, but not so much that you lose out on the ideal surfing and ice crean weather. With the last 12 months of precipitation data loaded into the SQLite database, we analyze the weather data to determine if Oahu is the perfect place to surf. For this analysis, we are using the tools-- *SQLite*, *SQLAlchemy*, and *Flask* to build on knowledge of SQL database structures and querying methods. The purpose of this project was to provide (in addition with our original weather analysis), more information about temperature trends before opening the surf shop. Specifically, temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.


## Results

Below is a screenshot of the June Temperature (summary statistics):

![](https://github.com/dewong1/surfs_up/blob/main/Resources/June%20Temps%20(summary%20statistics).png)

Below is a screenshot of the December Temperature (summary statistics):

![](https://github.com/dewong1/surfs_up/blob/main/Resources/December%20Temps%20(summary%20statistics).png)

### Three major points from the two analysis deliverables 

* Based on the two month's temperature analysis, it shows that June had more count (1700) than December (1517), which may indicate that some of the dates are missing temperature recordings. However, since this data is already a large sample size, the analysis is still relatively representative. 

* The low standard deviation number implies a relatively small spread across the temperature observations, which means that the weather does not fluctuate tremedously. 

* Based on the summary statistics table, both months' (June & December) *average*, *maxiumum*, and *minimum* temperature were close in numbers. (June's numbers were slightly higher than December's). 


## Summary

Overall, by comparing statistic summary of the two months (June & December), we can conclude that the temperature patterns remain pretty steady throughout the year. However, more data/information can be collected to gain better understanding of the weather in Oahu. Precipation is referring to rain, snow, sleet, or hail that falls to the ground. As average temperatures at the Earth's surface rise, more evaporation occurs, which, in turn, increases overall precipitation. Warming climate is expected to increase precipitation in many areas. Two additional queries to perform to gather more weather data include-- 1) Precipitation pattern summary statistics during the months of June and December (picture for overall weather pattern); and 2) Comparing the most active weather stations (this provide more accurate and reliable data) to the weather patterns. This will help us determine the best location for the surf shop. 


