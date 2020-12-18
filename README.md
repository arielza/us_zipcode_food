# The hidden taste of US zip codes

## background

The goal of this research is to explore if we can utilize food venues and sort of cuisine to understand a pattern in the test people across zip codes. 
During the research, data was collected from three different sources and organized for analysis. 
The analysis has not found a way to segment the zip codes by food categories in a significant way.

A second analysis was done to check whether or not we can predict the price of a house,
or at least if the types of restaurants around have any correlation with it; 
The analysis found a small correlation and almost zero correlation between the number of food venues and the price of houses around.

Hopping to find a better way for business owners in the restaurant business to identify best areas by the type of cuisine, 
Or helping house owner understand the true values of food venues around.

## Findings

The research tried to answer a question whether or not we can identify a different food taste across zip codes in the US. and while doing so it tested if any correlation between the food venues categories and price of a house in the same zip code exists.
-Clustering
	The research couldn't identify any good way to partition the zip codes by different restaurant types. It is found out the American and Fast food are leading the top on almost all zip codes but this doesn’t help us to identify different preferences. 
-Regresion
	Trying to understand if a price of house can be dependent on the type of a restaurant seems to be more promising. We have found out that there are few coefficients which represent the categories and have a positive or negative impact on pricing, but I will not look at them with any significance since the results of all the different regression models found to be low.


## File Structures
1. Raw data -> Data/Raw
2. Clean data -> Data
3. Code -> notebooks - the code is split into three notebooks
  3.1. Part 1 - data gathering and cleaning
  3.2. Part 2 - clustering
  3.3. Part 3 - Regression
4.Report - a detalied report about the process
