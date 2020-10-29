All the covid data comes from the [Jonh Hopikins Resourse Center](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data)

Name|Data Type|Description
---|---|---
fibs|float|federal information processing standards code for county indentification
county|string|county name
province_state|string|state name
covid_last_update|string|data of last update for covid data in UTC
county_latitude|float|county latitude information
county_longitude|float|county longitude information
covid_confirmed|integer|number of confirmed COVID-19 cases (includes probable)
covid_death|integer|number of death due to COVID-19 (includes probable)
covid_recovered|integer|number of recovered COVID-19 cases (these are estimates and may be inaccurate)
covid_active|integer|number of active COVID-19 cases calculated from total cases - total recovered - total deaths
covid_incidence_rate|float|incidence rate of COVID-19 cases; cases per 100,000 persons.
covid_case_fatality_ratio|float|case-fatality ratio; number of deaths/number of cases
county_population|integer|population of the county
covid_death_per_capita|float|number of death per capita due to COVID-19 (deaths/county population)
covid_confirmed_per_capita|float|number of confirmed COVID-19 cases per capita (confirmed cases/county population)
covid_active_cases_per_capita|float|number of active COVID-19 cases per capita (active cases/county population)
fire_per_county_in_2020|integer|number of fires in 2020 per county (includes both inactive and active fires)
active_fires_per_county|integer|number of active fires per county
fire_score|integer|a score represeneting fire danger in each county: this is the sum of weighted events. The weight is determined based on the extent of fire and whether it is an active fire or not.
earthquakes_per_county_in_2020|integer|number of earthquakes in 2020 per county
earthquakes_score|integer|a score representing earthquake danger in each couny: this is the sum of weighted events. The weights are determined based on the magnitude of the earthquake.

