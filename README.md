# python-Life-Expectancy-and-income


## How is life expectancy related to the average income of a country?

Life expectancy at birth shows how long residents of a country potentially can live and  measure the level of the overall population health. Residents of richer countries tend to live longer due to better healthcare facilities , so let see the pattern of association between them.

Richer countries defined as higher growth domestic product (GDP) per capita, so naturally rich countries can afford better healthcare treatment which usually more expensive. 

Cross-country data on life expectancy and GDP per capita is downloaded to uncover the pattern of association between them.
This enables us to identify countries where people live longer than what we would expect based on their average income, or countries where people live shorter lives.

Key takeaway :

1) Average life expectancy across the 181 countries in 2020 is 73 years, with a range of 54 to 85 years old. Thus, there is substantial variation in the average length of life across countries. For a comparison to Malaysia (my country), Malaysia is at the upper half of the range where Malaysian residents expected to live around 76-years-old.

2) Countries with the lowest life expectancy has a range of between 54-55 years-old and are from :
    -CAF Central African Republic
    -TCD Chad
    -LSO Lesotho
    -NGA Nigeria
    -SLE Sierra Leone
    
3) Countries with the highest life expectancy has a range of between 83-85 years-old and are from East Asian countries and South East Asian (Singapore) :
    -CKOR Korea, Rep.
    -SGP Singapore
    -MAC Macao SAR, China
    -JPN Japan
    -HKG Hong Kong SAR, China
    
4) There are 6 countries with extremely high GDP per capita: 
    -Luxembourg
    -Singapore 
    -Ireland
    -Qatar
    -Bermuda 
    -Switzerland
    
5) Average GDP per capita is 21k USD, the median is 13k USD.The standard deviation is 21k USD, suggesting substantial spread. 
   
6) There are two countries with less than 1k USD of GDP per capita (Burundi and the Central African Republic)
    
7) The linear regression with life expectancy as the y variable, and GDP per capita as the x variable shows a positive slope, but the        scatterplot implies that there are strong nonlinearities in the association that the linear regression doesn’t capture. In particular, the  slope appears a lot steeper at lower levels of GDP per capita and a lot flatter at higher levels. 

In contrast with the regression without taking logs, the scatterplot with log GDP per capita suggests a remarkably linear pattern. For most of the range of log GDP per capita, the linear fit appears to be a good approximation of the conditional expectation.

The association between life expectancy and average GDP is best captured with a regression that has log GDP per capita as the x variable. The slope of this regression is 5.29. It shows that countries with a 100% higher GDP per capita have life expectancy higher by 5.29 years.
Standard deviation of log GDP per capita is 1.15 or 115% so that typical cross-country differences are very high.

The countries with the shortest lives given their average income include Equatorial Guinea, Nigeria, and Cote d’Ivoire where the average age at death is 16, 13 and 11 years shorter than what we could expect given their GDP per capita.

The countries with the longest lives given their income include Morocco (7 years), Solomon Islands (8 years), where the average age at death is a little more than what we could expect given their GDP per capita.

7 countries with very high levels of GDP per capita (log gdp more than or equal to 4) have lower life expectancy than predicted by the linear regression. These countries are a mix of Bermuda, US , oil-rich countries (Brunei, United Arab Emirates, Qatar), and well-off small Western European countries (Ireland, Luxembourg).

Other interesting results include that lives are more than 5 years shorter than expected in the USA, 2 years longer than expected in China, and 6 years longer than expected in Japan. Looking at the rich countries, lives are 3 years shorter than expected in Qatar and 3 year shorter than expected in Luxembourg.