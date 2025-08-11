# Impact of Weather Factors on Traffic Conditions: Pan Island Expressway Analysis

## Overview
This repository contains the Jupyter Notebooks and final report for my Final Year Project (FYP) at Nanyang Technological University (NTU), completed in April 2023. The project examines the relationship between weather factors (rainfall, temperature, wind speed) and vehicle speed bands on Singapore's Pan Island Expressway (PIE) during peak morning hours. Data covers June, July, August, September, and December 2022.

Key objectives:
- Analyze correlations and build predictive models using multiple linear regression.
- Focus on road categories A, B, and F with separate/combined month analyses.

Key Findings: Weak correlations between weather factors and average speeds; R-squared values range from 0.5% to 14.5%, indicating limited explanatory power from weather alone. Other factors (e.g., traffic volume) may dominate.

This project demonstrates skills in data collection via APIs, exploratory data analysis (EDA), statistical modeling, and transportation analytics.

## Technologies Used
- Programming: Python (pandas for data wrangling, NumPy for numerical operations, statsmodels for regression, Matplotlib/Seaborn for visualization)

- Data Sources: LTA DataMall API (traffic data), data.gov.sg API (weather data)

- Tools: Jupyter Notebook for EDA and modeling

## Repository Structure
- FYP Data Processing.ipynb: Notebook for data loading, filtering, processing speed/traffic data, and preparing datasets (e.g., filtering PIE roads, calculating average speeds, assigning nearest rainfall stations).

- FYP Data Analysis.ipynb: Notebook for merging datasets (rainfall, temperature, speed), dropping NaNs, creating interaction terms, and fitting multiple linear regression models using statsmodels.

- Final_Report.pdf: Full project report with literature review, methodology, results, and references.

## Results Summary
- Data Processing: Filtered traffic data to PIE roads (categories A, B, F), calculated average speeds, and assigned nearest rainfall stations using geolocation.

- Data Analysis: Merged cleaned datasets; built multi-linear regression models with interaction terms (e.g., rain_temp_interaction); e.g., rainfall coefficient ~ -2.25 (indicating slight speed reduction).

- Insights: Weather explains only 0.5%-14.5% of speed variance (low R-squared); residuals show non-normality/autocorrelation; recommends further research on additional variables like traffic density.

For detailed results, see the full report.
