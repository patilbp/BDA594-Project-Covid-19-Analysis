# BDA594-Project-Covid-19-Analysis
### Project Website: https://sites.google.com/sdsu.edu/covid19/main
### Project Video: https://youtu.be/HYXaKkpt72M

The vaccination dataset is a time series showing the number of vaccines administered, by U.S. County, since January 2021. It provides detailed descriptions of vaccination numbers by age group and frequencies for those partially and fully vaccinated.

The COVID-19 case count and death table shows the number of cases and deaths in all U.S. counties beginning on January 21, 2020; and updating to the current date. The data were published to GitHub by the New York Times.

The demographics table was collected from the five-year American Community Survey published by the Census Bureau from 2014-2019 (their most recent publication). Units of interest are U.S. Counties using variables measuring median age, median household income, educational attainment and racial composition.

These three tables are linked together by a primary key identifying a county’s FIPS code, permitting relationships and analysis to be conducted between tables inside our COVID-19 database. Analysis will be centered on how COVID-19 spread through counties and what characteristics were shared among worst-impacted counties. Furthermore, what characteristics are shared among counties with high- and low-vaccination rates?

The final table contains text scraped from Twitter, hosted on Kaggle, that analyzes people’s views about the vaccines from a global perspective. Capturing the human response to a suddenly changed world, this table provides a unique qualitative perspective in understanding the spread of disinformation, relief and the “return to normalcy”. It contains approximately 300,000 tweets collected over time from August 2020.

Responsibilities performed in this project were:

1. Understand and clean the data tables, understand relationships connecting them to theme of project
2. Analyze demographic characteristics of U.S. counties
3. Measure Covid cases and deaths reported in U.S. counties as a spatial time series (how do cases and deaths change on the map over time?) 
4. Measure Covid vaccine counts by U.S. counties: which counties boast high vaccine-counts relative to population? Low-vaccine counts?
5. Assess whether trends exist between county demographics and confirmed Covid cases/vaccine count
6. Conduct basic text analysis on tweets concerning Covid-19 topics beginning in August 2020
