# surfs_up
Using SQLlite and Jupyter Notebook for Python to analyze weather data for the surfing business
## The first part of the project was to obtain data to determine whether or not the temperature was conducive to starting a surfing business. After completing the initial analysis, the results seemed satisfactory. However because the primary investor had gotten burned in a prior venture involving surf boards, the investor wanted specific temperure data for the months of June and December. 

### June Data 
To obtain June data, we did queries via SQLite and SQLAlchemy. We set up a query to obtain date and temperature data for June of all years in the data. The results are as captured in the below link. 

https://github.com/cwbyrd/surfs_up/blob/main/Resources/June%20temperature%20Stats.PNG


### December Data
Similar to June, we queried date and corresponding temperature data from SQL for the months of December for all years in represented by the data. See below for the link to stats for the December temperatures. 

https://github.com/cwbyrd/surfs_up/blob/main/Resources/Dec%20temperature%20Stats.PNG

## Analysis
### In comparing June and December data, there are some differences. 
1. June had slightly more obervations for temperature than December (1700 vs 1517). 
2. The mean and median temperature were about 4 degrees higher in June vs December. 
3. In December, the minimum temperature was about 8 degrees higher in June than December (64 vs 56 degrees), thus the range (max - min) was wider for December (difference of 27 degrees vs 21 degrees for June. This is also reflected in the fact that the standard deviation for December is slightly higher than in June. 

## Recommendations: 
To obtain further data from this exercise, I might 
1. Query additional months to see if the trend truly remained the same, so I might in addition to June and December, I might query March and September to get a quarterly view. 
2. In addition to temperature, precipitation by month would be important information to understand, given that if there were any kind of rainy season, those are months where demand might be lower except for the most hard core surfers. 

## Conclusion
In comparing June and December data, it would appear that though there are slight differences with respect to temperature (e.g. minimum temperature in December is a bit lower than in June), the data seems to point to all months be fairly temperate for setting up a surfing business. One could hypothesize that December mornings are likely slightly colder. 
