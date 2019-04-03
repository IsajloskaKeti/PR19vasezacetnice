                                     SUICIDES RATES                                                          Keti Isajloska, 70082616

-	Suicide as a global issue, many factors
-	Dataset for suicides overview 1985 to 2016
-	Attributes of dataset: Country, Year, Sex, Age, Suicides_no, Population, Suicides/100k pop, Country-year, HDI for year, GDP_for year($), 
  GDP_per capita($), Generation (based on age grouping average).
  
country,year,sex,age,suicides_no,population,suicides/100k pop,country-year,HDI for year, gdp_for_year ($) ,gdp_per_capita ($),generation
Albania,1987,male,15-24 years,21,312900,6.71,Albania1987,,"2,156,624,900",796,Generation X
Albania,1987,male,35-54 years,16,308000,5.19,Albania1987,,"2,156,624,900",796,Silent
Albania,1987,female,15-24 years,14,289700,4.83,Albania1987,,"2,156,624,900",796,Generation X
Albania,1987,male,75+ years,1,21800,4.59,Albania1987,,"2,156,624,900",796,G.I. Generation
Albania,1987,male,25-34 years,9,274300,3.28,Albania1987,,"2,156,624,900",796,Boomers
Albania,1987,female,75+ years,1,35600,2.81,Albania1987,,"2,156,624,900",796,G.I. Generation
Albania,1987,female,35-54 years,6,278800,2.15,Albania1987,,"2,156,624,900",796,Silent
Albania,1987,female,25-34 years,4,257200,1.56,Albania1987,,"2,156,624,900",796,Boomers
Albania,1987,male,55-74 years,1,137500,0.73,Albania1987,,"2,156,624,900",796,G.I. Generation
Albania,1987,female,5-14 years,0,311000,0,Albania1987,,"2,156,624,900",796,Generation X
Albania,1987,female,55-74 years,0,144600,0,Albania1987,,"2,156,624,900",796,G.I. Generation

-	Obvious: sheer number of suicides corresponds to the size of the population: the bigger the country, the more suicides.
-	Less obvious: crude rates do not allow for a proper comparison between countries. Suicide rates, as we shall see, vary considerably depending on demographic groups, so for a country as a whole one has to take into account its current demographic structure.
-	3 dimensions: Health, Education and Standard of living
-	4 indications: Dimension Indicator Minimum Maximum Health Life expectancy (years) 20 85 Education Expected years of schooling(years) 0 18 Mean years of schooling(years) 0 15 Standard of living Gross national income per capita (2011 PPP $) 100 75.000
-	The HDI (Humann Development Index) is the geometric mean of the three dimensional indices: HDI = (IHealthIEducationIIncome) 1/3

Analysis

Pre-processing the data
Before we make a pre-processing, the set has 27827 samples. But, some countries have data just for one, two, but not for all . 
Because of that, we can not simply look for example total number of suicides by year per each country. And we can not compare each country. 

This dataset includes 101 country. The most suicidle contry is Russia. (1.png). 

Question : Does the socio-economic info have affect of making suicides? Let's go deeper in the problem.

To find a solution we have to make some analyses:
1 Which gender is more suicidle?
2 Which generations are more suicidle?
3 Is there a relation between suicides and GPD per capita?
  (3.png)
- From the results, the males are more suicidal than females (reasons: wars, predisposition to alcohol, drugs etc.) 
- So, low GDP per capita comes with more suicides, if it is increasing, then suicides are decreasing, which indicates that economic conditions has affect on people life. (image.jpg)
- About the generationsBoomers(1946-1964), Silent(1921-1945) and Generation X(1965-1976) are much more suicidal.

So we could say that reasons for making suicides mainly are economical and for older generations the affects of the wars.

