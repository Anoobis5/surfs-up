# Surfs-Up Weather Analysis

## Project Overview

Before opening a surf shop in Hawaii, the client wants to gather more information regarding temperature trends. The client specifically wants to analyze temperature data for the months of June and December in Oahu. By analyzing weather data during these months, we will have a better idea at how to create a sustainable business model year-round for our surf and ice cream shop. 

## Results

Please see the table below for the summary of June's temperature statistics:

![June_Temp_Dataframe](https://user-images.githubusercontent.com/84881187/128449652-64007bdc-7510-43fe-8f16-e6bd7e8ac94b.PNG)

Looking at this table, Oahu had a mean temperature of 74.9, a min/low 64.0 and a max/high 85.0. We had a total of 1700 counts of data.




Please see below for the summary of December's temperature statistrics:

![Dec_Temp_Dataframe](https://user-images.githubusercontent.com/84881187/128449704-e0ad12a0-5eed-4e19-905f-ad3222b8219e.PNG)


Looking at this table, in December, Oahu had a mean of 71.0, with a min/low of 56.0, and a max/high of 83.0. We had a total of 1517 counts of data. 


The data that we gathered shows us that:

  1. The Average temperature difference between June and December is about 4 degrees, with June's Average being 74.9 (75) degrees, and December's Average being 71 degrees. This shows us that there is very little fluctuation between the average temperature at these two times of the year. 
  2. The maximum temperature difference between June and December also has a minimal difference of 2 degrees with June's maximum temperature being 85 and Decembers maximum being 83.
  3. The greatest variance in temperature is shown in the minimum temperatures between the two months. The minimum temperature in June is 64, and the minimum temperature in December is 56, showing that the low temperature level in December may not be ideal for having an ice cream & surfing shop open. 


## Summary of Findings
(rewrite)

By comparing the statistic summary of the two months, we can conclude that temperature patterns remain steady throughout the whole year. However, there are two more queries that we need to include to get a better understanding of the weather on Oahu. Although temperatures may remain about the same throughout the year, precipitation may not and would also have a significant impact of the business's sustainability. Doing a statistically summary of the precipitation patterns during the months of June and December will give us a better picture of the overall weather pattern.

Another query that can be created to help us further our analysis is comparing the most active stations to the weather patterns. This can help us narrow down the best location by giving us the most popular station combined with the most stable weather patterns.
Overall the weather in December and June are historically very similar, although December has a wider range of results, with its high being close to June's but its low well below June's.

Additional queries that could be run include: Precipation difference between June and December to determine is one has more rainy weather, as well as a comaparison by weather station, as we may see higher/lower temperatures and precipitation levels at different locations. We would be primarily interested in the weather station closest to our prospective location, which would narrow the results and provide the best data for us to consider.


The lack of data in December, 2017 may cause less reliable of data. The database should generate more recently winter data to compare summer and winter precipitation.

In addition of statistical summery, various features and plots may help us better analyze the seasonal weather. For example, line plots would be able to provide quick and easy way to show time-varying. Histogram plots would tell us frequency of precipitation as well as temperature for both December and Jane.

For seasonal analysis, we need filter more detail precipitation and temperatures for Spring and Autumn.


I would summize that even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees, and looking at the December histogram, I feel more confident in this decision--December's median temperature, with the highest frequency recorded across a span of years, is about 72 degrees, at least double the frequency of the next highest recorded temperatures, 75 and 67 respectively. It would be ill advised to not open the surf and ice cream shop based on at first clance temperature minimums.

Before making a final deicision though, I would want to perform some additional queries to get more color on weather conditions in these two months.

1. For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.
Stations vs Temps for June and December Starting Point

[INSERT CODE AND PICTRURE OF DATA]

2 Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Sunch varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business.
About
Advanced Data Storage and Retrieval with `Jupyter Notebook`, `SQLite` and `SQLAlchemy`




