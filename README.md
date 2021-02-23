# Surfs_up

## Overview of the analysis: <br>
The purpose of this analysis is to provide insight on weather trends in Oahu for starting a new business venture; a Surf and Shake shop.  In order for this business venture to be successful and to ensure this is the right investment, invetors would need factual evidence to determine if the Surf and Shake shop can operate throughout the year before financially backing up this venture. <br>
For this analysis, weather data has been gathered from the 9 weather stations on the island.  The data provides temperatures and precipitations per day.<br>

#### Resources: <br>

Python 3.7
VS Code 1.53
Jupyter Notebook
Data resource - [hawaii.sqlite](https://github.com/taranahassan/Surfs_up/blob/main/hawaii.sqlite)


## Results: <br>
![June_temps.png](https://github.com/taranahassan/Surfs_up/blob/main/Resources/June_temps.png?raw=true)
![Dec_temps.png](https://github.com/taranahassan/Surfs_up/blob/main/Resources/Dec_temps.png?raw=true)

The statistical analysis was created based on the weather data from the years 2010 to 2017, specifically for the months of June and December. <br>
Based on the images above:<br>
  1.  The maximum temperature in the past 7 years for June has been an average of 85 °F and 83 °F for December.  Not much of a difference in the temperature between a summer month and a winter month. <br>
  2.  The minimum temperature for June has been an average of 64 °F and for December, an average of 56 °F.  December being a winter month, it would be natural to assume cooler temperatures. <br>
  3.  Looking at stats for both months, the average temperature for June is typically 74.9 °F.  December being in winter, still has a warm enough weather with an average of 71 °F.  The standard deviation for both months range in the 3 °F mark.<br>


## Summary: <br>
The analysis results provides us details in the weather temperatures for June and December.  Statistics show the weather is always warm enough to Surf and eat Ice cream!  However it is not conclusive enough to understand if it will rain and if it would hinder the business to sustain.<br>
Below are the plots comparing temperature and precipitation for June and December using the same time frame as the results. <br>
![June_data.png](https://github.com/taranahassan/Surfs_up/blob/main/Resources/June_data.png?raw=true)
![Dec_data.png](https://github.com/taranahassan/Surfs_up/blob/main/Resources/Dec_data.png?raw=true)

Above plots were based on new queries that filter out the temperatures and precipitation.  By reading the plots, it shows that it typically rains heavier when temperatures have been around 69°F in June and between 69°F - 73°F in December.  The other times during either months have been moderate rain of 4mm or less.<br>
Since the average temperatures for June is 74.9°F, there are more chances of the shop operations to be successful.  This can be determined by viewing the statistical analysis for June and noting that 50% of the time the temperatures are at 75°F. <br>
For December the average temperatures are 71°F which only provides 50% chances for the shop to operate during rain.  Again, this can be determined by viewing the statistics for December and noting that 50% of the time the temperatures are 71°F.  If we look further, it also mentions that 75% of the time the temperates are at 74°F .  So it would be safe to assume there may be a little bit more rain than the rest of the year however not enough to negatively impact the business.


* *New queries noted in summary can be found in [SurfsUp_Challenge_D3_queries](https://github.com/taranahassan/Surfs_up/blob/main/SurfsUp_Challenge_D3_queries.ipynb)*
** *Rain measurement categories and description found in https://water.usgs.gov/edu/activity-howmuchrain-metric.html#:~:text=Moderate%20rain%3A%20Greater%20than%200.5,than%208%20mm%20per%20hour.&text=Heavy%20shower%3A%20Greater%20than%2010,than%2050%20mm%20per%20hour.*
