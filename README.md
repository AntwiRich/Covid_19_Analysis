# Covid_19_Analysis
COVID-19 is an infectious disease caused by a variant of the coronavirus family. The disease is associated with respiratory illnesses. 
Response Variables:
1. t1: The number of days it takes for a country to report a confirmed infec- tion following the earliest report date in china. 
2. t2: The number of days it takes for a country to report it’s first known death as a result of the virus following it’s first confirmed infection. 
The earliest confirmed case of COVID-19 is unofficially reported to be 17 November 2019 
Demographic Variables:
The following demographic variables are used to fit the model:
1. Population: country population
2. Annual Change: annual change of population in proportions
3. Annual Change Absolute: annual change of population in absolute terms 4. Density: P/km2
5. Land Area: km2
6. Migrants: Net migration in the country
7. Fertility Rate
8. Median Age
9. Urban Population: Proportion of population living in urban areas 
10. World Share
11. Migration index = sgn(Migrants)×ln(abs(Migrants)) 
12. lnPopulation = ln(Population) 
The demographic data is with respect to the year 2020, as reported by worldometer 

Additional Variables

An additional predictor was retrieved from wikipedia [2] due to the association of the virus with travelling: 
1. Passengers: Annual number of airline passengers per country 2. lnPassengers = ln(Passengers) 
The data has been processed and stored in the repository. 


Summary Statistics Overview 

Data from approximately 169 countries was used to fit the linear model. Atleast 54 of these countries have not recorded a death as a result of COVID-19. Also, atleast 11 countries have missing demographic data, especially countries with very small population sizes such the Holy See. 
