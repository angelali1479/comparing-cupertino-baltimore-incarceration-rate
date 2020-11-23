# Comparing the Effects of Income Level on Incarceration Rate in Cupertino and Baltimore
## Background
Considering the differences in demographics and type of city that Cupertino and Baltimore are, with Cupertino being mostly a suburb while Baltimore being more urban, it would be interesting to explore the relationship between household income levels and the incarceration rate. While I recognize before conducting the analysis that Cupertino and Baltimore are very different and the conclusions may be predictable, I believe that the visuals will be interesting to compare.
## Business Question
How might household income levels impact the incarceration rate of the next generation in Cupertino and Baltimore?
## Data Question - Open Data
I used open data from [Opportunity Atlas](https://www.opportunityatlas.org).
 - the raw data directly downloaded from Opportunity Atlas is contained in all the files starting with shown_tract in the repository. Those with a -c at the end of the file name are the files for the Cupertino data, and the ones without are the files for the Baltimore data.
## Data Question - Analysis
 - How do the incarceration rates compare between Cupertino and Baltimore?
 - Is there a correlation between incarceration rate and income levels in these two cities?
## Data Answer
### What is the average incarceration rate of both cities?

![alt text](https://github.com/angelali1479/comparing-cupertino-baltimore-incarceration-rate/blob/master/cup-balt.png)

Here we can see that even though the incarceration rate overall in Baltimore is about ten times the rate in Cupertino, the actual difference between the two rates is not too large.

### How does incarceration rate distribution compare at different income levels?

![alt text](https://github.com/angelali1479/comparing-cupertino-baltimore-incarceration-rate/blob/master/cupertino.png)

Looking at the Cupertino data comparing the incarceration rates across different income levels, we can see that for the vast majority of the data points, low income level has the highest incarceration rate, middle income level has the second highest incarceration rate, and high income level has the lowest incarceration rate. All income level incarceration rate is included just as a baseline comparison for the other income levels and we can see that for the most part, it is about the same incarceration rate as the high income level rate.

![alt text](https://github.com/angelali1479/comparing-cupertino-baltimore-incarceration-rate/blob/master/baltimore.png)

Looking at the Baltimore data comparing the incarceration rates across different income levels, we can see that it follows a similar to the Cupertino data pattern for the vast majority of the data points, low income level has the highest incarceration rate, middle income level has the second highest incarceration rate, and high income level has the lowest incarceration rate. There are a few important differences to note. First, since the Baltimore neighborhood area is larger than the Cupertino neighborhood area, there are a lot more data points to analyze in this graph. we can also see that there is a lot more variability in the incarceration rates across the board, with the highest being in the 80-90% range and the lowest in the 0s.


## Python Data Visualization (Mini Project 4)
### Cupertino

![alt text](https://github.com/angelali1479/comparing-cupertino-baltimore-incarceration-rate/blob/master/pythonplot-cupertino.png)
For the Python data visualization of the data, I chose to sort the data in ascending order of incarceration rates on average for all income levels as we can see in the graph above. Through this method, it is easier to see the smallest and largest values for the incarceration rate as well as to see how the 25th percentile incarceration rates often are outliers across the different locations and generally tend to be the highest regardless of the overall incarceratino rate for the location.

### Baltimore

![alt text](https://github.com/angelali1479/comparing-cupertino-baltimore-incarceration-rate/blob/master/pythonplot-baltimore.png)
For the Python data visualization of the data, I chose to sort the data in ascending order of incarceration rates on average for all income levels as we can see in the graph above. Through this method, it is easier to see the smallest and largest values for the incarceration rate as well as to see how the 25th percentile incarceration rates often are outliers across the different locations and generally tend to be the highest regardless of the overall incarceratino rate for the location. This was particularly important for the Baltimore data because it has many more data points in comparison to the Cupertino data, making it difficult to see what was important in this visual. Here we can see the smallest and largest values as well as the outliers. Similar to the Cupertino data, the lowers (25th) percentile is most often the outlier, showing that incarceration rates tend to be the highest amongst the poorer population regardless of the location and overall incarceration rate.

### Comparison to Excel
Python was useful in seeing the order of the steps performed in sorting through the data and creating the visualizations. I also changed the visualizations time by sorting them in ascending order rather than the random order in Excel. This made it easier to see the trend across the different percentiles. In addition, I did not alter the axes this time, so there is not any excess white space above the bars of the graph. I wanted to highlight the lowest and highest incarceration rates in each city (which can easily be found by looking at either end of the x-axis) as well as the very high incarceration rates in the 25th percentile in both cities. 

I found that Python was actually more difficult to use for data analysis and data visualizations in comparison to Excel. This is because Excel is much more intuitive, especially for someone who isn't well versed in coding in any language. I found it difficult to figure out how to edit certain parts of the data visualization through code. Particularly for this project, since the dataset is not so large that it would cause issues in Excel, it would probably be more easy and more useful to use Excel for this analysis and visualization.


## Concluding Summary
We can see from the data trends in the graphs for both Baltimore and Cupertino that the lower the income level, the higher incarceration rate. It is clear that income level does indeed make a sizable impact on incarceration rate regardless of location. Although the Cupertino graph appears to have unnecessary space left at the top of the graph, this was actually done on purpose to highlight the significant difference in the incarceration rates by making the y-axis range the same for both graphs. The difference in the incarceration rate across individual income levels is much greater than the average of all the income levels. We can also see that the middle income and high income level incarceration rates in general do appear higher than that of the Cupertino data set. We can conclude that there is clearly another factor causing the difference in incarceration rates between Cupertino and Baltimore that was not considered in the analysis here. Some possible variables to consider are overpolicing and race demographics. These additional variables are important to consider because incorporating these variables into the data could provide valuable insight on what is truly causing the significant difference in incarceration rates across the baord and would help us better narrow down a comprehensive policy or solution to help with the problem

## Additional Analysis on Summary (Mini Project 4)

In addition to the summary above, there are additional factors that may be causing the difference in incarceration rates between Cupertino and Baltimore that was not considered before. Race demographics plays a huge role in incarceration rates. Systemic racism (particularly against Black Americans) is pervasive across the entire United States and is present in all sections of the criminal justice system, such as police profiling, biased jury selection, and the school-to-prison pipeline [(Washington Post)](https://www.washingtonpost.com/graphics/2020/opinions/systemic-racism-police-evidence-criminal-justice-system/). Based on US Census data, the largest demographics in Cupertino are 27.1% White and 67.7% Asian with only 0.8% Black [(US Census)](https://www.census.gov/quickfacts/cupertinocitycalifornia) while the largest demographics in Baltimore are 76.3% White and 13.4% Black [(US Census)](https://www.census.gov/quickfacts/fact/table/baltimorecitymaryland,US/PST045219).
