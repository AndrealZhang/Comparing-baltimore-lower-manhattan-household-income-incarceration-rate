# Comparing the household income and incarceration rates in Baltimore, MD and Lower Manhattan, NY
## Background
1. Analyzing the differences between household income for the lowest 25th percentile of people (all races, all genders) in Baltimore and Lower Manhattan. 
2. Looking at if there is a relationship between incarceration rates and household income in the two locations. 

## Household Income
### Baltimore, MD
After downloading the data for household income by census tract from [Opportunity Atlas](https://www.opportunityatlas.org), filter the county name for Baltimore, MD and calculate the average household income among the tracts in Baltimore. Using this data, create a Pivot Table and Pivot Chart displaying the household incomes and average household income.

![alt_text](https://github.com/AndrealZhang/Comparing-baltimore-lower-manhattan-household-income-incarceration-rate/blob/master/Baltimore_Pivot.png)

From this bar chart with the average line, we can see that the average household income for the lowest 25th percentile of those in Baltimore is around $32,626. 

### Lower Manhattan, NY
After filtering the household incomes for the tracts within Lower Manhattan and calculating the average household income, we can create a Pivot Table and Pivot Chart for household income in Lower Manhattan.

![alt_text](https://github.com/AndrealZhang/Comparing-baltimore-lower-manhattan-household-income-incarceration-rate/blob/master/Manhattan_Pivot.png)

From this Pivot Chart, we can see that the average household income for the lowest 25th percentile is around $38,607 - $6,000 higher than the average in Baltimore.


## Incarceration Rates
### Baltimore, MD
Download the incarceration rates data by census tract from [Opportunity Atlas](https://www.opportunityatlas.org) and filter for Baltimore, MD. Use VLookup to paste this data into the same sheet as the data with household income and highlight the two rows to create a scatterplot to find the relationship between household income and incarceration rates for the lowest 25th percentile in Baltimore.

![alt_text](https://github.com/AndrealZhang/Comparing-baltimore-lower-manhattan-household-income-incarceration-rate/blob/master/Baltimore_scatterplot.png)

