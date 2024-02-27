# Time Series Analysis of Air Pollution Data in the United States

## Introduction:
This repository contains the project proposal and code for conducting a comprehensive time series analysis of air pollution data in the United States. The project is undertaken by Group 6 of BUAN 6312.

## Project Overview:
The aim of this project is to analyze air pollution data collected by the U.S. EPA from 2000 to 2016. The dataset, available at [data.world](https://data.world/data-society/us-air-pollution-data), includes information on various air pollutants measured at different locations over time. Our objective is to uncover patterns, trends, and potential correlations within the air pollution data.

## Dataset Description:
The dataset comprises the following variables:
- State code
- County code
- Site number
- Address
- State
- County
- City
- Date (local)
- NO2 units
- O3 units
- SO2 units
- CO units

## Objectives:
1. Analyze the time series patterns of various air pollutants such as Nitrogen Dioxide, Ozone, Sulfur Dioxide, and Carbon Monoxide across different geographical locations.
2. Assess and analyze each state's contribution to air pollution, understanding the variations and trends in pollutant levels over time.

## Methodology:
To achieve our objectives, we will follow these steps:

1. **Data Preprocessing:**
   - Identify and handle missing values, outliers, and other data quality issues.
   - Perform mean imputation for missing values.
   - Encode categorical variables and perform feature scaling.

2. **Exploratory Data Analysis (EDA):**
   - Analyze relationships between variables and identify trends using visualizations and statistical analysis.
   - Study correlations between target and explanatory variables.

3. **Feature Selection:**
   - Employ feature selection techniques such as correlation analysis, mutual information, and recursive feature elimination to identify critical variables contributing to pollution.
   - Select a subset of the most important variables for further analysis.

4. **Model Selection:**
   - Utilize pooled OLS, random effect, and fixed effects models to test the project objectives.

5. **Model Evaluation:**
   - Perform hypothesis testing to study joint significance between variables.
   - Evaluate models using metrics such as R-squared, Adjusted R-squared, and Mean Squared Error (MSE) to gain insights into air pollution in the United States.

## Contributors:
- Sofia Rajan
- Prriyamvradha Parthasarathi
- Premi Jawahar Vasagam
- Mira Radhakrishnan
- Martin Navarro
- Manoj Mareedu
- Vyshnavi Gangineni
- Siva Renuka Chowdary Nandigam

For further details, refer to the project documentation and code available in this repository.
