# PyBer_Analysis

## Overview

### The Job

Our ficticious manager V. Isualize has asked for some analysis of our ride-sharing data.  We looked over ride and city data, merging them into a single dataframe and then using groupby and loc functions in Pandas for some statistical analysis for Urban, Suburban, and Rural areas.  We potted these statistics, especially the overal fares collected from each from January to April, in order to note any trends.  We also looked at average fare per driver, per ride, and per city for each type of area.

## Results

It was no surprise to see that urban ride-share income was greater than suburban, and that suburban was, in turn, greater than rural.  This was true for total fares for the year of data (2019) and for each week along the way.  For the cost per ride and for the cost per driver, the results are opposite- fares go down in more populated areas with more drivers and options available.  With urban areas representing 10 times more rides than rural (and almost triple the suburban), it makes sense that people would take shorter rides at lower costs, perhaps even offered at lower rates, due to increased supply for the demand.

### Supporting Line Plot

![Summary Information for PyBer, by City Type](analysis/PyBer_fare_summary.png)

## Summary
### 3 Business Recommendations/Suggestions
After doing this little bit of analysis, V. Isualize could be encouraged to consider any of the following:
1. At $10 more per ride, investing in more rural drivers could raise revenue while being worth the added cost.
2. With more than twice the number of drivers compared to rides in urban areas, decreasing drivers (and/or relocating them to suburban or rural areas) could cut costs.
3. With suburban areas showing some great income totals overall- with '19 highs almost reaching urban lows, continued expansion here could be warranted.
