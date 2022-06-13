# python-Life-Expectancy-and-income


## How is life expectancy related to the average income of a country?

Life expectancy at birth shows how long residents of a country potentially can live and  measure the level of the overall population health. Residents of richer countries tend to live longer due to better healthcare facilities , so let see the pattern of association between them.

Richer countries defined as higher growth domestic product (GDP) per capita, so naturally rich countries can afford better healthcare treatment which usually more expensive. 

Cross-country data on life expectancy and GDP per capita is downloaded to uncover the pattern of association between them.

Key takeaway :

1) Countries with the lowest life expectancy has a range of between 54-55 years-old and are from :
    -CAF Central African Republic
    -TCD Chad
    -LSO Lesotho
    -NGA Nigeria
    -SLE Sierra Leone
    
2) Countries with the highest life expectancy has a range of between 84-86 years-old and are from East Asian countries and South East Asian (Singapore) :
    -CKOR Korea, Rep.
    -SGP Singapore
    -MAC Macao SAR, China
    -JPN Japan
    -HKG Hong Kong SAR, China
    
3) There are 6 countries with extremely high GDP per capita: 
    -Luxembourg
    -Singapore 
    -Ireland
    -Qatar
    -Bermuda 
    -Switzerland
    
4) Average GDP per capita is 21k USD, the median is 13k USD.The standard deviation is 21k USD, suggesting substantial spread. 
   
5) There are two countries with less than 1k USD of GDP per capita (Burundi and the Central African Republic)
    
6) The linear regression with life expectancy as the y variable, and GDP per capita as the x variable shows a positive slope, but the        scatterplot implies that there are strong nonlinearities in the association that the linear regression doesn’t capture. In particular, the  slope appears a lot steeper at lower levels of GDP per capita and a lot flatter at higher levels. 

In contrast with the regression without taking logs, the scatterplot with log GDP per capita suggests a remarkably linear pattern. For most of the range of log GDP per capita, the linear fit appears to be a good approximation of the conditional expectation.

