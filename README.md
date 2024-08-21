# EDA on Covid 19 data

## Exploratory Data Visualization on COVID-19 data from John Hopkins University.

Data Visualization is the first step towards getting an insight into a large data set in every data science project. Once the data has been acquired and preprocessed (cleaned and de-duplicated) we start with the next step of Data Science's **Exploratory Data Analysis** which kicks off with data visualisation. The aim here is to extract useful insights and patterns from the raw data.

I have used Python and its few powerful libraries to achieve the task such as:
* Pandas
* NumPy
* matplotlib.pyplot
* seaborn
* plotly.express

## Preprocessing the data

For preprocessing it includes:
* Removing superfluous columns like ‘FIPS’, ‘Admin2' and ‘Last_Update’ (since all the data is for single-day — 26th May 2020).
* Removing columns ‘Province_State’ and ‘Combined_Key’ since statewide data is not available for all the countries.
* Grouping data by ‘Country_Region’ and renaming the column to just ‘Country’ by using GroupBy function of the DataFrame(similar to the one used in SQL).

## Plotting various plots

It includes:
* The top 20 countries with the maximum number of confirmed cases
  * Barplot for the highest confirmed cases in the world(top 20).
  * Scatter plots for pairs of numerical columns.
* Plotting Confirmed and Active cases for the top 5 countries with the maximum number of confirmed cases.
* Plotting a Choropleth map on World Map
  * A choropleth map is a type of thematic map in which areas are shaded or patterned proportionately to a statistical variable that represents an aggregate summary of a geographic characteristic within each area, such as population density or per-capita income. It provides an easy way to visualize how the measurement varies across a geographic area or show the level of variability within a region. A choropleth map is a type of thematic map in which areas are shaded or patterned in proportion to a statistical variable that represents an aggregate summary of a geographic characteristic within each area, such as population density or per-capita income. It provides an easy way to visualize how the measurement varies across a geographic area or show the level of variability within a region.



