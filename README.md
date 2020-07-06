## COVID-19 data
The data is in the repository COVID-19 forked from JHU repo: https://github.com/CSSEGISandData/COVID-19.

To keep the databse automatically updated, I installed this [great app](https://github.com/wei/pull) that automatically pull newest version from the master repo.

## Analysis of global cases (*EDA_global.ipynb*)
For the global cases, I also incorporate external dataset about country's attributes to gain more insight because the original dataset only contains geographical information of countries (latitude/longitude).

* First, I got GDP and population data from World Bank database: https://data.worldbank.org/
* Second, I got health care spending data from WHO: https://apps.who.int/nha/database/Select/Indicators/en

These data are in 'data' folder.

## Analysis of US cases (*EDA_US.ipynb*)
For US I also used other sources of data such as population, GDP and income
