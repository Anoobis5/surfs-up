# Surfs-Up Weather Analysis

## Project Overview

Before opening an Ice Cream & Surf sop in Hawaii, the client wants to gather more information regarding temperature trends. The client specifically wants to analyze temperature data for the months of June and December in Oahu. By analyzing weather data during these months, we will have a better idea at how to create a sustainable business model year-round for our surf and ice cream shop. 

## Results

We ran analyses to examine the temperature statistics in both the months June and December.

#
Please see the table below for the summary of June's temperature statistics:

![June_Temp_Dataframe](https://user-images.githubusercontent.com/84881187/128449652-64007bdc-7510-43fe-8f16-e6bd7e8ac94b.PNG)

Looking at this table, Oahu had a mean temperature of 74.9, a min/low 64.0 and a max/high 85.0. We had a total of 1700 counts of data.

#


Please see below for the summary of December's temperature statistrics:

![Dec_Temp_Dataframe](https://user-images.githubusercontent.com/84881187/128449704-e0ad12a0-5eed-4e19-905f-ad3222b8219e.PNG)


Looking at this table, in December, Oahu had a mean of 71.0, with a min/low of 56.0, and a max/high of 83.0. We had a total of 1517 counts of data. 
#

The data that we gathered shows us that:

  1. The Average temperature difference between June and December is about 4 degrees, with June's Average being 74.9 (75) degrees, and December's Average being 71 degrees. This shows us that there is very little fluctuation between the average temperature at these two times of the year. 
  2. The maximum temperature difference between June and December also has a minimal difference of 2 degrees with June's maximum temperature being 85 and Decembers maximum being 83.
  3. The greatest variance in temperature is shown in the minimum temperatures between the two months. The minimum temperature in June is 64, and the minimum temperature in December is 56. 

Please see the table below for table comparison:
![June_Dec_Summary_Table](https://user-images.githubusercontent.com/84881187/128603394-f5c5744b-1c50-4dd7-88cb-fc49e350ac29.PNG)


## Summary of Findings

Our client wants to open an Ice Cream & Surf shop in Oahu, Hawaii. We were tasked with analyzing the weather trends in the months of June and December to help gauge how sustainable is it to open the shop. By analyzing our summary statistics of the two months, we can observe that the temperature patterns tend to stay relatively steady throughout the year. When we look at the frequency of temperatures recorded in June they appear to have a more regular bell curve distribution. Please see below for a visual of June's temperature data:

![JUne_Temp_Visual](https://user-images.githubusercontent.com/84881187/128604008-ca3ae32c-72ff-44fa-8fd9-852f8772bc0c.PNG)


In comparison, if we look at December's data, the temperatures seem to be much more variable than those in June given its larger range in recorded temperatures (given the variane between the max vs min temp of each month). Please see below for a visualization of December's temperature data:

![Dec_Temp_Visual](https://user-images.githubusercontent.com/84881187/128604046-f9ee2dde-6715-45b5-8020-d30de440950a.PNG)



However, there is quite a bit more data we could collect to help give us a better picture of how sustaiable the months of June and December are for opening the Ice Cream & Surf shop in Oahu. Although temperatures may be relatively predictable throughout the year, precipitation at different times of the year could have a significant impact of the sustainability of the business. By generating a statistical summary of the precipitation during the months of June and December, we can get more information of how the weather will affect the business at different times of year. Please see below for our table and code for displaying the Precipitation Summaries for June and December merged into a readable table:

![Prcp_Summary_Code](https://user-images.githubusercontent.com/84881187/128604533-470262e7-99eb-4c95-81dd-128e108aff1d.PNG)


A brief look at our data shows that the average precipitation in Oahu is on average 0.08 higher in December than in June, an almost neglible difference. However, the Max rainfall in December is higher by 2. With the lower temps and potentially higher precipitation that could affect business revenue, we have yet another factor that could affect the business' sustainability in December. It would be most beneficial if we also collected data comparing the Temperature Data and Precipitation data to see if there is a correlation between the average precipitation occurences and the high-low temperature ranges during each month. This will help us determine whether high temperatures still equate to good business sustainability for the business. We historgram plot comaring the Weather Temperature with the occurences of Precipitation would be beneficial data.

#

Another query that can help strength our analysis is to compare the most active stations to the weather patterns. This can help us examine the best prospective location to open by comparing the variances in temperatures and frequency at each station. Please see below for a table summary of Station Temperature Data and a snip-it of our Station Temperature data by month:

![station_temps_summary](https://user-images.githubusercontent.com/84881187/128605107-705c69f9-650f-4a9b-b2d1-2559871bb03d.PNG)


![station_temps_list](https://user-images.githubusercontent.com/84881187/128606116-8d301991-bd0c-489a-9e40-eaa1627f3ac7.PNG)

#

Looking at our overall data, the weather in both June and December are  more-or-less similar. However, the lack of December data at 1517 counts to June's 1700 counts could be a limiting factor in giving us an accurate assessment of the differences in weather. There are many other variables we could analyze that would give us a more accurate picture as to whether opening a Ice Cream & Surf shop in Oahu would be sustabable during the months of June and December. Apart from the variables of Precipitation and weather pattterns around certain Weather Stations we described above, it would also be advisable to gather data on factors such as: tourism density, wave swell patterns, wind conditions, population density of similar businesses, and sun presence. These are all different variables that could affect prospective customers patronage to the business, and how appealing the business' products are. I personally would definitely not want to go surfing on a dark day, with limited wave swells and breaks, and unfavorable wind directions. 

To briefly summarize our analysis, though temperatures recorded in December seem to vary more than those of June, December could still provide appropriate weather conditions for both surfing and ice cream. There are many other variables we would need to consider to determine if opening an Ice Cream and Surf shop in Oahu would be sustainable before making any business decisions about acquiring a location.
