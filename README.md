# unemployment_and_crime
Crime and Unemployment Statistical Analysis

This project explores the relationship between crime rates and unemployment across different countries and regions from 1998 to 2022. The focus is on cleaning and preparing the data, applying custom-built statistical methods, and creating visualizations to show trends and correlations over time.

## What the project does
* Loads and cleans combined datasets with unemployment and crime indicators
* Transforms data into long format for easier analysis
* Maps countries to regions (Africa, Europe, Asia, South America, Oceania)
* Removes invalid or missing values and handles outliers
* Computes descriptive statistics (mean, median, variance, standard deviation, min, max)
* Detects and replaces outliers using the IQR method
* Tests data distribution for normality (skewness, kurtosis)
* Calculates Spearman correlation with p-values to measure the strength of the relationship
* Runs simple linear regression (slope, intercept, R²)
* Produces regional and yearly analyses
* Generates visualizations: histograms, scatter plots with regression lines, Q-Q plots, heatmaps, and time series

## Methods used
* Data wrangling and cleaning with **pandas** and **numpy**
* Manual implementation of statistical functions instead of relying on sklearn or statsmodels
* Outlier detection and treatment for more robust analysis
* Correlation analysis using **Spearman’s rank correlation**
* Linear regression coded from scratch to better understand the process
* Regional trend analysis across multiple years
* Data visualization with **matplotlib** and **seaborn**

## Example outputs
* Histograms showing unemployment and crime index distributions
* Heatmaps of Spearman correlations by region and year
* Line plots showing changes in correlation over time
* Scatter plots with regression lines for the most recent year in each region
"# unemployment_and_crime" 
