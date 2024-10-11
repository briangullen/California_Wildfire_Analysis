# California_Wildfire_Analysis

## Overview
This analysis of California fires from 1992 to 2020 was completed as part of a final project for a Grand Circus Data Python course. It used detailed specifics of fire incidents, including location, size, cause, etc. combined with historical weather data to help identify key trends in the frequency or occurence of fires.

## Goal
To determine which key indicators exist and if they can be used to help predict aspects of fires in California such as cause, time of year, weather conditions or various other factors. Providing insight or predictive analyitics can help fire agencies and responders better prepare or prevent fires in the future.

## Data Sources
USDA Research Data Archive
- Short, Karen C. 2022. Spatial wildfire occurrence data for the United States, 1992-2020 [FPA_FOD_20221014]. 6th Edition. Fort Collins, CO: Forest Service Research Data Archive. https://doi.org/10.2737/RDS-2013-0009.6

*Open-Meteo* "Historical Weather API".
- See [Information & Documentation](https://open-meteo.com/en/docs) regarding API usage and available data.

## Technologies Used
The data acquisition and analysis was performed in Jupyter Notebooks with Pandas. Cleaned and organized data was loaded into a Postgres SQL database in Supabase for later retrieval and analysis. Visual reports with slicers for analysis was created via Power BI. Predictive analytics performed via Sklearn

*Python Libraries & Modules*
- Pandas
- Matplotlib
- Seaborn
- Sqlalchemy
- Sklearn
