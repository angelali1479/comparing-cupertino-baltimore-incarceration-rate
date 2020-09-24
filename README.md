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
