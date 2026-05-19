# CHIP Python Analysis Project

## Overview

This project analyzes active commuting trends across U.S. states using CDC public health data. Active commuting refers to walking or biking to work and is commonly used as an indicator of physical activity and population health.

The analysis focuses on identifying geographic differences and temporal trends in commuting behavior using Python-based data analysis techniques.

## Research Question

How do active commuting rates vary across U.S. states, and what trends can be observed over time?

## Data Source

Dataset: Nutrition, Physical Activity, and Obesity – American Community Survey
Source: CDC Data Portal (data.cdc.gov)

The dataset contains public health indicators related to physical activity and commuting behavior across multiple U.S. states and years.

## Variables Used

Variable	Description
LocationDesc	U.S. state
YearStart	Reporting year
Data_Value	Active commuting rate (%)

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analytical Workflow

1. Data Preparation

The dataset was imported into Python using Pandas. Relevant variables related to state, year, and active commuting percentage were selected for analysis.

Missing values and non-numeric entries were removed to improve data quality and ensure accurate calculations.

2. Data Cleaning & Transformation

The year and commuting rate variables were converted into numeric formats to support aggregation and visualization.

This step ensured consistency across observations before performing trend analysis.

3. Exploratory Data Analysis

Average active commuting rates were calculated:

Across years to identify temporal trends
Across states to compare geographic variation

This analysis helped identify states with consistently high or low active commuting rates.

4. Data Visualization

Visualizations were created to communicate patterns in the dataset, including:

Line chart showing active commuting trends over time
<img width="731" height="468" alt="trend_graph" src="https://github.com/user-attachments/assets/4d64ea66-dd35-42f5-b0be-15a0fc8c0114" />

Bar chart of top 5 states with highest commuting rates
<img width="708" height="473" alt="top5 trend graph" src="https://github.com/user-attachments/assets/574fdcb9-911c-4895-8009-94ffa89363e9" />

Bar chart of bottom 5 states with lowest commuting rates
<img width="722" height="484" alt="bottom5 trend graph" src="https://github.com/user-attachments/assets/ee6bc3a5-e4b4-45aa-992f-9551879ce89c" />

The visualizations provide a clearer understanding of public health and transportation behavior differences across states.

## Key Findings

The analysis showed substantial variation in active commuting rates across U.S. states.

The District of Columbia, Alaska, and New York demonstrated higher average active commuting rates.
Alabama, Tennessee, and Mississippi showed comparatively lower rates.
A decline in active commuting was observed around 2020–2021, followed by a modest recovery in recent years.

These findings suggest that regional infrastructure, urbanization, and lifestyle patterns may influence active commuting behavior.

## Repository Contents

File	Description
- analysis_new.ipynb	Jupyter Notebook containing data cleaning, analysis, and visualizations
- Nutrition,_Physical_Activity,_and_Obesity_-_American_Community_Survey_20260430.csv	CDC dataset used for analysis
- README.md	Project documentation

## Conclusion

This project demonstrates how Python can be used to clean, analyze, and visualize real-world public health data.

The workflow highlights practical skills in:

Data cleaning
Exploratory data analysis
Public health analytics
Data visualization
Python programming

This project also demonstrates the application of data analytics techniques within a healthcare and biomedical informatics context.
