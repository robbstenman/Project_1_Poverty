# Poverty in Colorado

A study on homelessness in Denver, Colorado.

## Authors

- [Beau Dunavant IV](https://github.com/Buford4)
- [Michael Bolens](https://github.com/bolens)
- [Robb Stenman](https://github.com/robbstenman)

## Course Number

DU-VIRT-AI-PT-02-2024-U-LOLC

## Project Purpose

The past two or three decades have witnessed a startling rise in the number of Americans living in poverty. This complex issue has a multitude of contributing factors, but our team will zero in on five key areas to explore potential correlations: Income, poverty, employment, housing, and homelessness/hunger. While there may be a surface-level inclination to believe a strong "yes" exists between poverty and each of these factors, a more nuanced approach is required. Before jumping to conclusions or perpetuating stereotypes, we must meticulously analyze the data and translate it into clear visualizations. It's crucial to remember that correlation does not imply causation. Just because two factors appear to be linked doesn't necessarily mean one causes the other. Through rigorous analysis and objective data exploration, we hope to paint a clearer picture of the multifaceted relationship between poverty and these specific areas of our society.

## Questions to be addressed

Our overarching question is "How did we get here"?

Poverty 

- Is there a relationship between poverty and employment?
  - What about for the five most and least populated counties?

Housing:

- Is income keeping pace with the average price of rent?
- Is there a correlation between the cost of rent, the value of home ownership, and the average monthly housing expense with a mortgage?
- Is there a correlation between the average year of homes built and the population of the five largest counties (by population) and the five smallest counties (by population)?

Employment:

- Is there a correlation between employed people over the age of 16 and unemployed people over the age of 16?
- Is there a correlation between median household income and per capita income?
- Is there a relationship between poverty and employment?
  - What about for the five most and least populated counties?

Income

- Do the income levels and cost of living differ between large, populous counties and smaller, less populated counties?
  
Homelessness

- Does the Homeless Students and PIT data correlate?
  - What about for the five most and least populated counties?

## Overview of data collection, cleanup and exploration process

## Approach taken to achieve goals

## Housing Observation:

Is income keeping pace with the average price of rent?

The analysis of income trends compared to the average price of rent involved plotting data on median household income, the average cost of rent and utilities, and all data combined. This data was sourced from the U.S. Census, providing a comprehensive view of income and housing cost dynamics over time. Through visualizations and numerical analysis, we aimed to determine whether income growth is in line with the rise in average rent and utilities.

The findings from the analysis provide insights into the relationship between income and housing costs. By examining the plotted data, we can discern whether income levels are keeping pace with the increasing average price of rent and utilities. A consistent or increasing trend in income aligned with a similar pattern in rent and utilities would suggest that income is indeed keeping pace with housing costs. On the other hand, if the trend in housing costs outpaces income growth, it indicates potential challenges in housing affordability.

![Graph Title](./Beau/Housing/Median_Houshold_Income.png)
![Graph Title](./Beau/Housing/Average_Cost_of_Rent_and_Utilities.png)
![Graph Title](./Beau/Housing/Question_1.png)

## Housing Observation:

Is there a correlation between the cost of rent, the value of home ownership, and the average monthly housing expense with a mortgage?

To assess the correlation between the cost of rent, the value of home ownership, and the average monthly housing expense with a mortgage, data was gathered from the U.S. Census focusing on variables such as "Average Monthly Housing Expense with Mortgage," "Median Contract Rent," and "Average Value of Owner-occupied Home." The data was then processed using grouping and averaging the relevant variables by year. This approach allowed for a comprehensive analysis of trends over time and facilitated the examination of potential correlations between these housing-related metrics.

The analysis revealed interesting insights into the relationships between housing costs, home values, and mortgage expenses. There was a strong positive correlation between the cost of rent and average monthly housing expenses with a mortgage, indicating that as rental prices increase, so do mortgage expenses for homeowners. Additionally, a moderate positive correlation was observed between home values and average monthly housing expenses with a mortgage, suggesting that higher home values are associated with higher mortgage payments. These findings emphasize the interconnectedness of housing and homeownership expenses.

![Graph Title](./Beau/Housing/Average_Monthly_Housing_Expense_with_Mortgage.png)
![Graph Title](./Beau/Housing/Median_Contract_Rent.png)
![Graph Title](./Beau/Housing/Average_Value_of_OwnerOccupied_Home.png)
![Graph Title](./Beau/Housing/Question_2.png)

## Housing ation:

Is there a correlation between the average year of homes built and the population of the five largest counties (by population) and the five smallest counties (by population)?

The analysis aimed to determine if there is a correlation between the average year of homes built and the population of the five largest counties and the five smallest counties, both categorized by population size. The data for this analysis was gathered from the U.S. Census, focusing on variables such as "Average Year Home Built," "Total Population," "County," and "Year." We were able to extract and group the data, separating it into urban and rural areas based on the counties' population sizes.

Upon analyzing the data, distinct trends were ed between the average year of homes built and the population of counties. In the five largest counties, there appeared to be a correlation between population size and newer home construction, indicated by a trend of decreasing average year of home construction as population size increased. Conversely, in the five smallest counties, there was a different trend, suggesting that smaller populations were associated with older homes on average. These findings highlight potential patterns in housing development and population distribution, which can be valuable for urban planning, real estate, and demographic studies.

![Graph Title](./Beau/Housing/Average_Year_Home_Built_Rural.png)
![Graph Title](./Beau/Housing/Total_Population_Rural.png)
![Graph Title](./Beau/Housing/Question_3_Rural.png)

![Graph Title](./Beau/Housing/Average_Year_Home_Built_Urban.png)
![Graph Title](./Beau/Housing/Total_Population_Urban.png)
![Graph Title](./Beau/Housing/Question_3_Urban.png)

## Employment ation:

Is there a correlation between employed people over the age of 16 and unemployed people over the age of 16?

The analysis delved into determining if there exists a correlation between employed individuals over the age of 16 and unemployed individuals over the age of 16. To conduct this analysis, data was gathered from the U.S. Census, specifically focusing the variables "Number of Employed (16+)" and "Number of Unemployed (16+)" over a specified time period. The data was then processed by grouping and averaging the number of employed and unemployed individuals by year, offering a comprehensive view of employment trends over time.

Upon analyzing the data, it was ed that there is indeed a correlation between employed individuals over the age of 16 and unemployed individuals over the age of 16. The visualizations of the data showed an inverse relationship between these two variables, where periods of higher employment rates corresponded to lower unemployment rates, and vice versa. This correlation underscores the dynamic nature of the labor market, where changes in employment opportunities directly impact the level of unemployment within a population. Such insights are crucial for policymakers, economists, and workforce development initiatives in understanding and addressing labor market trends and dynamics.

![Graph Title](./Beau/Employment/Number_of_Employed.png)
![Graph Title](./Beau/Employment/Number_of_Unemployed.png)
![Graph Title](./Beau/Employment/Question_1.png)

## Employment ation:

Is there a correlation between median household income and per capita income?

The analysis aimed to investigate whether there exists a correlation between median household income and per capita income. To conduct this analysis, data was gathered from the U.S. Census, focusing on the "Median Household Income" and "Per Capita Income" over a specified time period. The data was then processed by grouping and averaging the median household income and per capita income by year, allowing for a comparative analysis of income trends.

Upon analyzing the data, it was ed that there is indeed a correlation between median household income and per capita income. The visualizations of the data depicted a positive relationship between these two variables, where periods of higher median household income were associated with higher per capita income, and vice versa. This correlation underscores the interplay between household income levels and individual income within a population. It suggests that as household incomes rise, there is a tendency for individual incomes to also increase, reflecting overall economic prosperity and well-being. These findings are essential for understanding income distribution patterns and socioeconomic trends, providing valuable insights for policymakers, economists, and social researchers in addressing income inequality and improving economic opportunities for individuals and households.

![Graph Title](./Beau/Employment/Median_Household_Icome.png)
![Graph Title](./Beau/Employment/Per_Capita_Income.png)
![Graph Title](./Beau/Employment/Question_2.png)


### Is the supply of available beds for the homeless population keeping up with the number of homeless individuals?

One of the most visible signs of poverty is homelessness. We looked at the Point in Time Count (PIT), which is an actual count of homeless people on a single night each January. We compared this to the Housing Inventory Count (HIC), which is a count of beds provided through agencies and non-profits to the homeless. The Department of Housing and Urban Development is responsible for creating the definitions of who qualifies and compiling the data.

The data has two anomalies. First, in Colorado, the methodology for how to count homeless changed between 2012 and 2013. This caused the reported number of homeless to drop from 16,768 in 2012 to 9,754 in 2013. This was not an actual decrease in the number of homeless, just a change in how the count was done. The second anomaly was in 2021. The PIT count took place in January, and this was at the height of the Covid pandemic. The data suggests that there were more beds available than homeless people. However, the reality is that the PIT Count underrepresented the homeless population.

A third possible anomaly is the 2023 PIT Count. At this point, it is not clear what caused the number to increase from 10,397 to 14,439. It could be a one-year exception, or it could be the new normal.

When analyzing the overall data set, a concerning trend emerges there are not enough beds available to accommodate the current homeless population. The fluctuations in both the PIT Count and HIC data make it difficult to identify a clear trend, but the underlying issue remains: the need for housing and support services for the homeless population exceeds the current capacity.

![Graph Title](./robb_images/pit_hic.png)

### How does Colorado’s Self-Sufficiency Standard compare with the Federal Poverty Level?

The Self-Sufficiency Standard (SSS) and the Federal Poverty Level (FPL) are two different approaches to measuring the cost of living and determining poverty thresholds.

The SSS was developed by the Center for Women’s Welfare at the University of Washington. It considers a variety of cost factors, such as housing, childcare, healthcare, transportation, food, and other necessities to determine a “living wage” for different geographic areas and family sizes. This provides a much better picture of what is necessary to meet people’s basic needs based on where they live.

The FPL is determined by the US Census Bureau and is used by several federal agencies to determine eligibility for benefits. The FPL is an amount that is the same across the lower 48 states. It does account for family size, but not for regional cost differences. The SSS is calculated every 4 years while the FPL is calculated annually.

We were curious how the SSS compared to the FPL in Colorado. We looked at the SSS data for 4 people (2 adults and 2 school-age) vs the FPL for 4 people. Across the data sets, the SSS amount was over twice as much as the FPL for Colorado. More concerning is that the gap between the SSS and FPL is widening over time. This means that people living in Colorado will be disadvantaged when receiving government aid based on a formula that only looks at FPL.

![Graph Title](./robb_images/fpl_sss.png)

### Has the number of SNAP recipients increased steadily over time?

The Supplemental Nutrition Assistance Program (SNAP), formerly known as Food Stamps, is a federal program that provides low-income households with Electronic Benefit Cards (EBT) to purchase food. We thought data on the monthly SNAP recipients would provide a good indicator of the number of people struggling with food insecurity.

From 2010 to 2013, the number of SNAP recipients in Colorado was increasing, potentially as a consequence of the 2008 financial crisis. However, from 2013 to 2020 the number of SNAP recipients in Colorado fell significantly. From a high of 513,483 recipients in March of 2013 to 431,397 recipients in February 2020.

Then Covid happened. The data becomes more ambiguous after this point and continues to be difficult to understand through June 2022, when our data set ends. There are 3 spikes in the number of recipients: July 2020, August 2021, and December 2121, where the number of monthly recipients exceeded 550,000. It is unclear to us what caused these spikes.

Given the number of people who appear to be struggling with food insecurity, we thought the time-series data would have shown a steady increase in SNAP recipients. However, the opposite was true. SNAP recipients were decreasing until Covid. It is unclear at this point if the number of recipients will remain elevated or if it will return to pre-Covid levels.

![Graph Title](./robb_images/snap.png)

### Do the income levels and cost of living differ between large, populous counties and smaller, less populated counties?

We started by looking at per capita income for the five largest and five smallest counties in Colorado. In 2012, the per capita incomes were comparable. However, from 2011 to 2017 incomes in the smallest counties were trending downwards, while the largest counties saw their per capita income increasing steadily. In 2017, the small counties’ income started rising, but not at the same rate as large counties. In 2021, the average per capita income in the largest counties was $43,218 while the smallest counties’ average was $33,648, a difference of $9,750.

We also looked at per capita income compared against the Self-Sufficiency Standard (SSS). In the five largest counties, the SSS is increasing relative to per capita income. However, in the five smallest counties, the SSS appears to be closing the gap with per capita income. This could be a concerning trend if it continues.

![Graph Title](./robb_images/income_counties.png)
![Graph Title](./robb_images/income_sss_large.png)
![Graph Title](./robb_images/income_sss_small.png)

## Does the Homeless Students and PIT data correlate?

- [Point in Time (PIT) Data](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/)
- [Homeless Students](https://www.cde.state.co.us/studentsupport/homeless_data)

### Overall Homeless in Colorado

First, we will look at the overall homeless population in Colorado from 2011 to 2021 from our PIT (Point in Time) Homeless data set. The data shows that the overall homeless population has been decreasing over the years. The line chart shows a sharp decrease from 2012 to 2013, followed by a steady increase in the homeless population from 2013 to 2017, with a slight decrease in 2018. The homeless population then increased again from 2019 to 2020, and end with another rapid decrease from 2020 to 2021.

|                                         Bar Chart                                         |                                         Line Chart                                          |
| :---------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------: |
| ![Overall Homeless in Colorado 2011-2021 Bar Chart](./images/michael/co_homeless_bar.png) | ![Overall Homeless in Colorado 2011-2021 Line Chart](./images/michael/co_homeless_line.png) |

### Homeless Students

Next we will need to look at the data for homeless students in Colorado.

#### Average Homeless Students in Colorado

We will now look at the average homeless students across all of Colorado from 2011 to 2021 from our Homeless Students data source. The data shows that the average homeless students have also been decreasing over the years. The line chart shows an increase in the average homeless students from 2011 to it's peak in 2014. From 2014 to 2020 we see a downard trend with the most notible drop from 2019 to 2020, but then we see a slight increase in 2021.

|                                                  Bar Chart                                                   |                                                   Line Chart                                                   |
| :----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| ![Average Homeless Students in Colorado 2011-2021 Bar Chart](./images/michael/avg_homeless_students_bar.png) | ![Average Homeless Students in Colorado 2011-2021 Line Chart](./images/michael/avg_homeless_students_line.png) |

#### Average Homeless Students in Rural Counties

Looking at the same data across rural counties we can see that homeless students have been increasing steadily from 2011 to 2021. The line chart shows a sharp drop from 2016 to 2017 followed by a rapid rise to 2018. Since then the average homeless students in rural counties have been decreasing. This trend does not seem to conform to the trends of Colorado as a whole except for a general rise from 2011 to 2014 but it continues to rise as Colorado as a whole falls the subsequent two years until 2016. This could be due to the fact that the rural counties have a smaller population and the data is more volatile.

|                                                        Bar Chart                                                         |                                                         Line Chart                                                         |
| :----------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
| ![Average Homeless Students in Rural Counties 2011-2021 Bar Chart](./images/michael/rural_avg_homeless_students_bar.png) | ![Average Homeless Students in Rural Counties 2011-2021 Line Chart](./images/michael/rural_avg_homeless_students_line.png) |

#### Average Homeless Students in Urban Counties

The overall trends of homeless students in urban counties seems to most strongly correlate with Colorado as a whole. This is somewhat expected as the urban counties make up the majority of the population of Colorado. The line chart shows a sharp drop from 2016 to 2017 followed by a rapid rise to 2018. Since then the average homeless students in urban counties have been decreasing. This trend does not seem to conform to the trends of Colorado as a whole except for a general rise from 2011 to 2014 but it continues to rise as Colorado as a whole falls the subsequent two years until 2016.

|                                                        Bar Chart                                                         |                                                         Line Chart                                                         |
| :----------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
| ![Average Homeless Students in Urban Counties 2011-2021 Bar Chart](./images/michael/urban_avg_homeless_students_bar.png) | ![Average Homeless Students in Urban Counties 2011-2021 Line Chart](./images/michael/urban_avg_homeless_students_line.png) |

### Overall Homeless vs. Average Homeless Students

Knowing the trends of our PIT homeless data and our Average Homeless Student data, we can now start to compare the two and see if there is any correlation. Comparing between Colorado overall and the top 5 most and least populated counties, we can see that the overall homeless population and the average homeless students in Colorado do not share the same trends. While overall homeless population has been decreasing over the years, the average homeless students have been decreasing too but they seem to be unrelated. This could be due to the fact that the overall homeless population includes all homeless individuals, while the average homeless students only includes homeless students.

|                                                                      Bar Chart                                                                      |                                                                      Line Chart                                                                       |
| :-------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
|  ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Bar Chart](./images/michael/co_homeless_vs_avg_homeless_students_bar.png)   |  ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Line Chart](./images/michael/co_homeless_vs_avg_homeless_students_line.png)   |
| ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Bar Chart](./images/michael/rural_homeless_vs_avg_homeless_students_bar.png) | ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Line Chart](./images/michael/rural_homeless_vs_avg_homeless_students_line.png) |
| ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Bar Chart](./images/michael/urban_homeless_vs_avg_homeless_students_bar.png) | ![Overall Homeless vs. Average Homeless Students in Colorado 2011-2021 Line Chart](./images/michael/urban_homeless_vs_avg_homeless_students_line.png) |

### Does the Homeless Students and PIT data correlate?: Conclusion

So to answer our question of "Does the Homeless Students and PIT data correlate?" we can say that the overall homeless population and the average homeless students in Colorado do not correlate. The overall homeless population has been decreasing over the years, while the average homeless students have been decreasing too but they seem to be unrelated. This could be due to the fact that the overall homeless population includes all homeless individuals, while the average homeless students only includes homeless students.

## Is there a relationship between poverty and employment?

- [U.S. Census Bureau](https://www.census.gov/)

### Poverty Count in Colorado

In order to compare poverty to employment, we should first look at poverty counts in Colorado as a whole, then we will compare that to urban and rural county trends. We can see that overall, Colorado saw a steady increase in povety from 2011 to 2014 but since then it has been devreasing. We can see this trend mimiced in our urban counties but in our rural counties we can almost see a seasonal trend every few yeard where the poverty count will rise and fall; though overall, rural counties have also trended downward.

|                                              Bar Chart                                               |                                               Line Chart                                               |
| :--------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------: |
|       ![Poverty Count in Colorado 2011-2021 Bar Chart](./images/michael/poverty_count_bar.png)       |       ![Poverty Count in Colorado 2011-2021 Line Chart](./images/michael/poverty_count_line.png)       |
| ![Poverty Count in Rural Counties 2011-2021 Bar Chart](./images/michael/rural_poverty_count_bar.png) | ![Poverty Count in Rural Counties 2011-2021 Line Chart](./images/michael/rural_poverty_count_line.png) |
| ![Poverty Count in Urban Counties 2011-2021 Bar Chart](./images/michael/urban_poverty_count_bar.png) | ![Poverty Count in Urban Counties 2011-2021 Line Chart](./images/michael/urban_poverty_count_line.png) |

### Employment in Colorado

Next we will look into employment trends in Colorado. Similarly to poverty count, we will also look at Colorado as a whole, then compare that to urban and rural county trends. We can see that overall, Colorado saw a steady increase in employment from 2011 to 2021. It appears that unemployment has followed a similar trend, though we see what looks to be a plateau from 2020 to 2021. As with poverty, we see the rural counties not matching our overall trends or our urban county trends. We see that rural counties have seen a steady decrease in employment from 2011 to 2021. Urban counties have seen a steady increase in employment from 2011 to 2021.

|                                        Bar Chart                                         |                                         Line Chart                                         |
| :--------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------: |
|    ![Employment in Colorado 2011-2021 Bar Chart](./images/michael/employment_bar.png)    |    ![Employment in Colorado 2011-2021 Line Chart](./images/michael/employment_line.png)    |
| ![Employment in Colorado 2011-2021 Bar Chart](./images/michael/rural_employment_bar.png) | ![Employment in Colorado 2011-2021 Line Chart](./images/michael/rural_employment_line.png) |
| ![Employment in Colorado 2011-2021 Bar Chart](./images/michael/urban_employment_bar.png) | ![Employment in Colorado 2011-2021 Line Chart](./images/michael/urban_employment_line.png) |

### Poverty Count vs. Employment Ages 16+ in Colorado

Now that we have seen the trends of poverty and employment in Colorado, we can now compare the two to see if there is any correlation. We can see that the poverty count and employment trends in Colorado as a whole do seem to correlate. We seem to see a reverse correlation between the two, as poverty count decreases, employment increases. This trend is not as clear in our rural counties, but it is very clear in our urban counties.

|                                                                 Bar Chart                                                                  |                                                                  Line Chart                                                                  |
| :----------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|       ![Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Bar Chart](./images/michael/poverty_count_vs_employment_bar.png)       |       ![Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Line Chart](./images/michael/poverty_count_vs_employment_line.png)       |
| ![Rural Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Bar Chart](./images/michael/rural_poverty_count_vs_employment_bar.png) | ![Rural Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Line Chart](./images/michael/rural_poverty_count_vs_employment_line.png) |
| ![Urban Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Bar Chart](./images/michael/urban_poverty_count_vs_employment_bar.png) | ![Urban Poverty Count vs. Employment Ages 16+ in Colorado 2011-2021 Line Chart](./images/michael/urban_poverty_count_vs_employment_line.png) |

### Is there a relationship between poverty and employment?: Conclusion

To answer our question of "Is there a relationship between poverty and employment?" we can say that there is a relationship between poverty and employment in Colorado. We seem to see an inverse correlation between the two, as poverty count decreases, employment increases. This trend is not as clear in our rural counties, but it is very clear in our urban counties. There also seems to be no noticable effect on employment or poverty count from the early COVID-19 pandemic window that we are able to see.

## Data Challenges

There were four major challenges we faced with the date:

Covid - The biggest challenge in analyzing the data was the presence of anomalies caused by the Covid pandemic. The PIT Count data for 2021 showed more beds available than homeless, which we know is not accurate. The SNAP data had unexplained peaks during Covid. This Covid era data will cause data analysis issues for years to come.

Understanding Data Collection Methodologies – It took time to research the methodology for gathering each data set. There are different definitions for each variable, and it is important to understand the method and purpose of data collection.

Changes to Methodologies – When a major change is made to the method or definition it can significantly affect the data. If one did not know there was a change in method, one could easily draw the wrong conclusion.

Granularity or Amount of Detail – It was surprising how much detail was included in some data sets. One source we considered had over 400 fields of data to categorize types of housing.

## Summary/Conclusion

We saw two different stories in our data sets. Before 2020, most indicators were moving in a positive direction. Incomes were rising, employment was increasing, rent was stable, and SNAP recipients were decreasing. However, the Covid pandemic changed that outlook. We don’t have up-to-date data for all areas, but where the data is available, it shows that the poorer populations need more help.

It will be interesting in the coming years to revisit this data to see if the challenges caused by Covid are permanent or only temporary.

## Future Considerations

There is an abundance of data sets dealing with poverty, income, housing, homelessness, and employment. We would recommend limiting the data sets to one type of data. This would allow for a deeper investigation into the data. We would also recommend focusing on one or two counties. We used different data sets with overlapping date ranges. This caused some comparisons to be lacking as we did not have complete data for all years.

It would be beneficial to look at both private sources of data along with government-provided data.

## Help is Available

One encouraging thing we learned from this exercise is that help is available. Several organizations are dedicated to helping the poor. Here are some representative organizations and government departments.

- Hunger Free Colorado
- 2 1 1 Colorado
- Colorado Coalition for the Homeless
- Colorado Department of Human Services
- Colorado Department of Local Affairs

## Data Sources

[Center for Women’s Welfare at the University of Washington](https://selfsufficiencystandard.org/colorado/)

[Colorado Department of Education - Homeless Education Data](https://www.cde.state.co.us/studentsupport/homeless_data)

[Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/series/BRCO08M647NCEN)
Economic Research - Federal Reserve Bank of St. Louis

[HUD Exchange](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/)

[US Census Data](https://www.census.gov/en.html)

## Additional Research Sources

[Colorado Coalition for the Homeless](https://www.coloradocoalition.org/sites/default/files/2024-01/2023%20StateOfHomelessness_CCH_F_0.pdf)

[Colorado Department of Human Services](https://cdhs.colorado.gov/snap)

[Hunger Free Colorado](https://hungerfreecolorado.org/)

[Urban Institute](https://www.urban.org/sites/default/files/publication/25626/412613-SNAP-s-Role-in-the-Great-Recession-and-Beyond.PDF)

[9News](https://www.9news.com/article/news/colorados-homeless-population-is-increasing-so-why-does-this-hud-report-say-otherwise/73-497483910)
