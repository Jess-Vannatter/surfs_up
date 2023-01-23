# Surfs_Up

## Overview of Statistical Analysis
* For this project we focused on a weather analysis of Oahu, Hawaii to determine if opening a surf and Ice cream shop would flourish as a possible business in this area. The analysis was prompted by a business partner who has experience in the field and wanted to be sure that the weather in Oahu would be conducive in allowing a business like this to flourish and be successful. Int eh module work we were able to provide data that supported our venture in that for most of the days throughout the year the weather was sunny and warm. You can see the data that supports this information in the images provided below. Please reference Table one  for Descriptive analytics on the precipitation amounts for the year of 2017 in Oahu, Hawaii and Graph One which plots the number of days throughout the year that the temperature was within a range of 60 to 85 degrees Fahrenheit. [(climate_analysis.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Module_work/climate_analysis.ipynb).

##
   - **Table 1**
  
   ![image](https://user-images.githubusercontent.com/117245167/213165618-cbb1607a-251d-48af-9631-ff9874cf81b4.png) 
     
   - **Graph 1**
 
  ![image](https://user-images.githubusercontent.com/117245167/213165705-dfb50234-9821-4cf4-a88b-5def5c7bcead.png)

##

* As for the second part of our analysis, we were tasked with digging deeper into the weather Data we were provided for Oahu, Hawaii and providing an analysis of the temperatures for the months of JUNE and DECEMBER. Where this differed from the module work (referenced above) that focused on the year 2017. The Challenge requested to have a deeper analysis of just JUNE and DECEMBER months throughout all the years of the provided data which ranged from 2010 to 2017. So essentially, we looked to provided statistical analysis for all the days in JUNE for that 7-year period and all the days in DECEMBER for that 7 year period to extract the descriptive figures (Count, Mean, Standard Deviation, Minimum, Maximum and Quartile ranges) for our analysis. Please refer to the images of the summary statistics we generated for the months of JUNE and DECEMBER below. [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb).


<div align="center">

**JUNE**        |   **DECEMBER**
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/117245167/213167409-67369714-4203-4f24-ab5c-7e20f2662e5a.png)  |  ![image](https://user-images.githubusercontent.com/117245167/213167471-4d91c4aa-577e-4c52-8a25-e5a0a25909ca.png)

</div>

##

## Results
- After reviewing the summary statistics generated for the two months referenced above, we have listed a couple of takeaways from this data. 

   1. These months are considered opposites in terms of seasons but comparatively the temperature averages are not extremely different. The June Average temperature according to our tables was ~75 Degrees (74.94). While the average temperature for DECEMBER was 71 degrees. there is a less than 4-degree difference in average        temperature for these months which is ideal for a location being probed for a surf business. Meaning there is not an extreme amount of variance between the two        months even though they are on either ends of the spectrum (in terms of seasons). [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb).

   2. The same can be said regarding the Maximum temperatures recorded for JUNE and DECEMBER. Where the Max JUNE temperature is 85.00 degrees, while the MAX temperature in DECEMBER was 83.00. Again, this indicates that there is not a lot of variances in temperatures in that specific location. 

   3. The main item to point out in terms of differing aspects would be the Minimum temperatures reported for JUNE and DECEMBER. There is a clear difference in these    two numbers where the minimum temperature recorded in JUNE is 64.0 degrees and the Minimum temperature in DECEMBER is 56.00 degrees. Based on the averages, this    shouldn’t be an issue i would assume because 56.00 degrees is well below the 25% quartile according to the table above. meaning this temperature (56) is likely to be   pretty rare and possible reaching the area of an outlier. Where the Minimum temperature in JUNE is 64.00. What this does tell us is there is a slightly higher amount   of temperature fluctuation in the month of DECEMBER as compared to JUNE. You can also see this in the STD section of the tables above, here the standard deviation for   DECEMBER is 3.74 and 3.25 for JUNE, respectively. The Lower percentiles in DECEMBER are decently lower than in JUNE as well which does indicate that there is a   consistent temperature drop for this month but the differences in temperatures between JUNE and DECEMBER seem to follow the same pattern. There is a range of about 3- 5-degree difference between the quartile temperature ranges for the 2 months. [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb). 

   4. Another item to point out is that the Count of recorded temperatures for these months do different. There are 1,700 recordings for the month of JUNE. While there are only 1,517 for the month of DECEMBER. I would say this shouldn’t create and issues with our analysis but with there being less recordings in the month of DECMEBER the summary statistics could be slightly less accurate. [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb). 

##

## Summary
- Based on the information provided and extracted, i would suggest that Oahu, Hawaii is an ideal location to open an ice cream/ surf shop. it is safe to say that the temperatures, on average throughout the whole year will be above 70 degrees and sunny. Even though I feel it is safe to come to that conclusion based off of this analysis, there are a couple of short comings to this report and there may be some additional items to take into consideration to further investigate the climate. 

  1. It would probably be best to re-run this analysis with the same data but adding the remaining recordings for DECEMNBER so that the recording Counts match at        1,700.00. this would allow us to have more accurate information and be able to compare the two months with less error [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb).

  2. In addition to above, it might be best to take into consideration other weather factors like wind specifically.  I have a limited understanding of Surfing, but wind may play a huge factor in generating waves for surfing or creating the ideal setting for surfing. A location that may be too windy to surf may not be ideal to open a surf shop. Taking into consideration wind, just in General would be great. But then it would be even better to break it down further like we did the temperatures to determine which months are windier than others or if say December is Windier than JUNE. Also it might be a good idea to dig deeper in to the precipitation numbers and determine which months out of the year are considered "rainier" than the others [(SurfsUp_Challenge.ipynb)](https://github.com/Jess-Vannatter/surfs_up/blob/main/Challenge/Starter_Code/SurfsUp_Challenge.ipynb).


