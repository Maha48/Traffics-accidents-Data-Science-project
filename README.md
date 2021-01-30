# The effect of women driving on accidents in Saudi Arabia
Driving licenses and traffic accidents in Saudi Arabia, we use them to measure the rate of increase in accidents in 2018 and compare it with previous years to note whether Saudi women driving affected the accident rate, as allowing women to drive is a major change in data in Saudi Arabia.


# Files
 - A Jupyter notebook that describes  data with visualizations & statistical analysis.
 - A README markdown file the provides an introduction to and overview of  project.
 - Data for Contains all the data we need for the project.

# Datasets Description

- [Driving Licenses](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets)
 - This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

- [Traffic Accidents and Casualties](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period)
 - This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.

- [Driving Licenses2018-2019](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&refine.time_period=2018&q.timerange.time_period=time_period:%5B2018-01-01+TO+2019-12-31%5D&location=5,24.37495,45.08024&basemap=jawg.streets)
 - This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 2018 - 2019. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

- [Traffic Accidents and Casualties2018-2019](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period&refine.time_period=2018&q.timerange.time_period=time_period:%5B2018-01-01+TO+2019-12-31%5D&refine.region=Total)
 - This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2018. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.
---
# Overview of data
 data dictionary provides a quick overview of features/variables/columns, alongside data types and descriptions.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|licenses_year|int|driving_licenses|The year the licenses were issued|
|licenses_region|object|driving_licenses|The license issuance area|
|driving_llicenses|object|driving_licenses|Number of licenses issued|
|licenses_x_geo_point|float|Driving_Licenses|The x geo point for each Area|
|licenses_y_geo_point|float|Driving_Licenses|The y geo point for each Area|
|traffic_year|int|Traffic_Accidents|The year of calculating these cases |
|traffic_region|object|Traffic_Accidents|The region in which these cases were counted|
|traffic_indicator|object|Traffic_Accidents|Indicator of  Injured, Dead and Accidents|
|traffic_value|int|Traffic_Accidents| Value for each indicator|
|traffic_x_geo_point|float|Traffic_Accidents|The x geo point for each region|
|traffic_y_geo_point|float|Traffic_Accidents|The y geo point for each region|



# Results

Riyadh, Makkah and Eastern are the main cities in Saudi Arabia, and to measure the impact of the Saudi women's driving decision on issuing licenses and accidents in Saudi Arabia, we compare the years 2016-2017 before the implementation of the decision and the year 2018 after implementation. In 2016, Riyadh issued nearly 250,000 licenses per year, and they nearly doubled. In 2017, after the decision to allow women to drive was issued, and they remained at 500,000 in 2018 after the implementation of the decision. As for accidents, Riyadh in 2016 amounted to approximately 140,000 accidents, and in 2017, reduced to 100,000 accidents, and compared to 2018, the number of accidents reached 80,000, which is nearly half the number of accidents before the decision was issued.

In Makkah and Eastern, the licenses in 2016-2017 were approximately 150,000, and in 2018 there was no significant increase. As for the accidents, in the years 2016-2017, there were approximately 140,000 accidents in Makkah and nearly 100,000accidents in Eastern, while in 2018 the percentage decreased dramatically to 100,000 in Makkah and 40,000 in Eastern.

Women driving in Saudi Arabia has greatly reduced accidents, which proves the ability of women and their commitment to traffic and safety regulations.

**Here you can read my article on medium on this project** [The effect of women driving on accidents in Saudi Arabia](https://medium.com/@maha48/the-effect-of-women-driving-on-accidents-in-saudi-arabia-835fe13a434c)
# References
- [stats gov](https://www.stats.gov.sa/ar/news/384)
- [kapsarc](https://datasource.kapsarc.org/)
