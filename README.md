# surfs_up

## Overview
The analysis was performed in order to determine if the ice cream shop business sustainable year round by comparing weather data of June and December.

## Results
The two sets of data are the result of the analysis, which are statistical summary indicators for temperature readings from all weather stations on June and December of all years. Here are mentioned tables: [June_Temps](https://github.com/andgerashchenko/surfs_up/blob/e75d7ed5bc7e542bac843124480e80f6ffabbe96/Challenge/Resources/June_Temps.png
[December_Temps](https://github.com/andgerashchenko/surfs_up/blob/e75d7ed5bc7e542bac843124480e80f6ffabbe96/Challenge/Resources/December_Temps.png)
Comparing this data we can define the following statements:
- Total count of readings for June is slightly higher, even considering that there are 1 day less in June then in December. 
- Average temperature for June is almost 4 degrees higher then in December, which is confirming by maximum temperature and its median.
- The difference in minimum temperature is quite greater and this is confirming by higher standard deviation in December.

## Summary
The analysis data performed shows that average temperature during the year on the islands changes insignificantly. However there are possible slowing the season in winter because of cloudy days, overall weather has minor changes.
Difference in data count is about 14%, which indicates on incompleteness of data and this can influence the result. In order to exclude that inaccuracy we can filter out meteo station with lost readings and leave the most reliable station for the analysis.
Comparing the other indicators we can see that max temperatures are slightly differ, but minimum ones have 8 degrees difference. Also standard deviation in December is higher, which means that colder days change warmer days frequently. And this can indicate that cloudiness and precipitation cause temperature drops. Therefore we can add precipitation query to the analysis for the clarification. 
