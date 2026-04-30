# CHIP Python Analysis Project

## Overview
This project analyzes active commuting rates, defined as walking or biking to work, across U.S. states using CDC data.

## Research Question
How do active commuting rates vary across U.S. states, and what trends can be observed over time?

## Data Source
Dataset: Nutrition, Physical Activity, and Obesity – American Community Survey  
Source: CDC data portal / data.cdc.gov

## Variables Used
- LocationDesc: U.S. state
- YearStart: Year
- Data_Value: Active commuting rate percentage

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Steps
1. Loaded the CDC dataset into Python.
2. Selected the state, year, and data value columns.
3. Cleaned the data by removing missing values.
4. Converted year and value columns into usable numeric formats.
5. Calculated average active commuting rates by year.
6. Calculated average active commuting rates by state.
7. Created visualizations to show trends and state comparisons.

## Visualizations
The notebook includes:
- A line chart showing active commuting trends over time.
- A bar chart showing the top 5 states by active commuting rate.
- A bar chart showing the bottom 5 states by active commuting rate.

## Key Findings
Active commuting rates vary across U.S. states. The District of Columbia, Alaska, and New York showed higher average active commuting rates, while Alabama, Tennessee, and Mississippi showed lower average rates. The trend over time shows a decline around 2020-2021, followed by a slight recovery in recent years.

## Files in This Repository
- `analysis_new.ipynb` — Jupyter Notebook with Python code, analysis, tables, and visualizations.
- `Nutrition,_Physical_Activity,_and_Obesity_-_American_Community_Survey_20260430.csv` — CDC dataset used for the analysis.
- `README.md` — Explanation of the project.

## Conclusion
This project demonstrates how Python, Pandas, and Matplotlib can be used to clean, analyze, and visualize real-world public health data.
