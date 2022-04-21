# UGDissertation
Files used for my dissertation project.
These are the CSV files used for the data analysis section of my Undergraduate Dissertation.

The main data used for analysis is labelled "Analysis Data.csv" above, used to create the regression models and the main findings of my dissertation. It is collected from US Census Bureau's Household Pulse Survey Public Use Files, which can be found at: https://www.census.gov/programs-surveys/household-pulse-survey/datasets.html. The surveys used for this dissertation is week 18 to week 24, from 28th Oct 2020 to 15th Feb 2021. 

"policy.csv" contains the lockdown policy's stringency levels, collected from Oxford University's published data source: https://github.com/OxCGRT/USA-covid-policy. It recorded the policy variations for each US state (plus Washington DC) during the seven survey periods. It also has a column indicating new Covid-19 cases and deaths for each survey period. 

"us.csv" contains the cumulative Covid-19 cases and deaths for the entire US since 21st Jan, 2020, until 10th April, 2022. A column of daily new Covid-19 cases is also included. The source of the data is from New York Time's published repository: https://github.com/nytimes/covid-19-data.

The results of my dissertation can be replicated using the R Markdown file provided in this repository. "Analysis Code.Rmd" uses the three data stored in this repository. If one wishes to see how "Analysis Data.csv" is created, a separate R Markdown file is also availabe, which illustrated how I cleaned up the data from different sources, and created the data files "Analysis Data.csv" and "policy.csv". 
