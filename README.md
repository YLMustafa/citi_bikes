# citi_bikes
This project analyses Citi Bike’s inaugural year trip data to uncover early usage patterns in New York City. Using clustering and regression techniques, it explores relationships between rider age, start time, and trip duration to better understand user behaviour and inform future system improvements.

## Citi Bike Data Analysis 
This repository contains Python scripts and Jupyter notebooks used for analysing Citi Bike’s earliest recorded trips. The goal is to reveal insights into how New Yorkers and visitors initially used the bike-sharing system and what early usage patterns might inform ongoing service improvements.

## Project Overview 
Citi Bike launched in New York City in 2013, becoming one of the largest bike-sharing programmes globally. This analysis focuses on data from the system’s first year, providing a snapshot of user behaviour and trip characteristics that have influenced the evolution of urban mobility in NYC.

## Key Questions Addressed
- How does rider age relate to trip start times and durations?
- Can clustering reveal distinct user groups based on age, trip duration, and start hour?
- What are the spatial patterns in trip durations across different neighbourhoods?
- How effective is age as a predictor for trip start times?

## Dataset Information
-Dataset includes:
  - Rider demographics (age)
  - Trip details (start hour, trip duration)
  - Start station geolocation (latitude, longitude)
- Data sourced from Citi Bike’s official 2013 trip logs: https://www.kaggle.com/datasets/ryanmcummings/citi-bike-data/data.
- GEOJSON file sourced from: https://data.cityofnewyork.us/City-Government/2020-Neighborhood-Tabulation-Areas-NTAs-/9nt8-h7nd/about_data
- Data size: approximately 9.71 MB, containing 50000 trip records.

## Tools Used
- Python – for data processing, exploratory data analysis, clustering, and regression modelling
- Pandas, NumPy – data manipulation and numerical operations
- Scikit-learn – clustering (K-Means) and regression models
- Seaborn, Matplotlib – data visualisation
- Jupyter Notebook – combining code, analysis, and narrative
- Tableau – creating interactive dashboards for spatial and cluster analysis

## Project Structure
- Data cleaning and preprocessing scripts
- Exploratory Data Analysis notebooks
- Clustering and regression modeling notebooks
- Tableau dashboards for visualising cluster results and spatial patterns

## Tableau Dashboards
Interactive dashboards showcasing clustering results and spatial trip patterns are available here:
https://public.tableau.com/app/profile/leyla.efe/viz/CitiBikes_17509249164740/Story1?publish=yes 
*This storyboard highlights only the key steps and insights most relevant to the final results. While the full analysis included additional exploration and testing, this dashboard focuses on the findings that had the greatest impact on shaping the conclusions.*

## Final Presentation
Summary of insights and recommendations presented in:
[Insert link or path to PowerPoint or PDF presentation]

*Visualisations and analyses presented here support understanding the earliest Citi Bike usage patterns, informing system development and urban mobility planning.*
