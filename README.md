
# Chicago Crime Data Analysis (2001-Present) and Safety Index

## Project Overview

This project analyzes crime data in Chicago from 2001 to the present to uncover crime patterns and develop a **Safety Index** that can help individuals and authorities assess the relative safety of different neighborhoods. The dataset, publicly available through the **Chicago Data Portal**, includes detailed information on reported crimes, such as the type of crime, date, location, arrest status, and the involvement of domestic issues.

## Dataset Description

The dataset spans crimes reported between **2001 and the present** and includes the following fields:

- **ID**: Unique identifier for each reported crime.
- **Case Number**: Official case number for the reported crime.
- **Date**: Date and time when the crime occurred.
- **Block**: Address block where the crime was reported.
- **IUCR**: Illinois Uniform Crime Reporting (IUCR) code for the type of crime.
- **Primary Type**: General category of the crime (e.g., Assault, Theft, Robbery).
- **Description**: A more detailed description of the crime type.
- **Location Description**: Specific location of the crime (e.g., Street, Apartment).
- **Arrest**: Indicates whether an arrest was made (True/False).
- **Domestic**: Indicates whether the crime was domestic in nature (True/False).
- **Beat**: The police beat where the crime was reported.
- **District**: The police district where the crime was reported.
- **Ward**: The city ward where the crime was reported.
- **Community Area**: The community area number where the crime occurred.
- **FBI Code**: FBI code for the type of crime.
- **X Coordinate & Y Coordinate**: Coordinates of the crime location.
- **Year**: The year the crime was reported.
- **Updated On**: The date when the crime entry was last updated.

## Objectives

1. **Exploratory Data Analysis (EDA)**: 
   - Analyze crime trends over the years.
   - Understand the distribution of different types of crimes across various **community areas**, **districts**, and **wards**.
   - Evaluate **arrest rates** and determine trends related to domestic crimes.
   - Analyze crime occurrences at different times of the day and week.

2. **Safety Index Development**: 
   - Use statistical models and machine learning techniques to develop a **Safety Index** for each community area in Chicago based on crime rates, crime types, arrest rates, and other factors.
   - Provide insights into the **safest** and **most dangerous** neighborhoods.

3. **Visualization**: 
   - Create interactive maps to visualize crime hotspots and the **Safety Index** for each neighborhood.
   - Generate charts to illustrate trends in crime over time and by location.

## Project Workflow

1. **Data Preprocessing**:
   - Handle missing values, duplicates, and outliers.
   - Standardize date-time formats.
   - Perform feature engineering to create new variables such as **crime frequency per capita** for each community area.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze trends by year, month, day, and hour.
   - Explore crime distribution by type, location, and whether an arrest was made.
   - Examine correlations between different crime types and socio-economic factors in community areas.

3. **Safety Index Calculation**:
   - Normalize crime data by community area population.
   - Use weighted averages of crime severity (violent vs. non-violent) to calculate a **Safety Index**.
   - Rank community areas based on crime rates and types.

4. **Data Visualization**:
   - Use libraries like **matplotlib**, **seaborn**, and **folium** to create static and interactive maps.
   - Build dashboards to visualize key crime statistics and trends.

## Tools and Technologies

- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation and preprocessing.
- **Matplotlib/Seaborn**: Data visualization.
- **Folium/Plotly**: Mapping and interactive visualizations.
- **Scikit-learn**: Machine learning models for clustering and predictions.
- **Geopandas**: Spatial data analysis and mapping.
- **Jupyter Notebook**: For interactive data exploration and code development.

