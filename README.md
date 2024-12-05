# Analyzing Global CO2 Emissions Using Machine Learning Models

## Project Overview
This project analyzes global CO2 emissions using datasets on GDP, population, energy consumption, and CO2 emissions. The objective is to identify the key drivers of emissions and develop predictive models for emissions forecasting, providing actionable recommendations for mitigation efforts.

## Problem Definition
The project addresses the challenge of understanding and forecasting global CO2 emissions, a key driver of climate change.

## Why is this important?
CO2 emissions contribute significantly to global warming, impacting ecosystems, economies, and societies. Accurate modeling and forecasting can guide policymakers and industries toward sustainable practices.

## Datasets
The datasets used in this project include:

Annual CO2 Emissions,Energy Consumption: Country-level historical data from Our World in Data.
GDP, Population: Economic and demographic data from The World Bank.

## Data Cleaning and Refinement
Merged multiple datasets using country and year identifiers.
Handled missing values and standardized formats.
Applied log transformations to normalize data distributions and improve model robustness.

## Methodology
### Exploratory Data Analysis (EDA)
Analyzed global trends in emissions, GDP, population, and energy consumption.
Visualized relationships and computed correlations between variables.
### Machine Learning Models
Linear Regression: Baseline model for understanding relationships.
Random Forest: Feature importance analysis and improved predictive performance.
K-Nearest Neighbors (KNN): Best-performing model for prediction (R² = 0.9883).
Neural Networks: Captured complex relationships for predictive modeling.
ARIMA: Time-series analysis for emissions forecasting.
### Feature Engineering
Log transformations of variables to reduce skewness and enhance interpretability.
Standardized features for models requiring normalized inputs.
### Evaluation Metrics
R² (coefficient of determination) for model accuracy.
Root Mean Squared Error (RMSE) for error analysis.
Validation through comparison of predicted vs. actual emissions.

## Results
### Key Insights:
Strong correlations between emissions, energy consumption (0.98), and GDP (0.92).
Moderate correlation with population (0.75).
### Model Performance:
KNN achieved the highest R² value of 0.9883.
ARIMA models forecast a continued upward trend in emissions.
### Visualization:
Line plots, heatmaps, and scatter plots highlight trends and relationships.

## Reproducibility
Repository Structure
data/: Contains raw and cleanedsed datasets.
code/:  Data cleaning, EDA, and model implementation.
img/: Includes visualizations and model evaluation metrics.

## Future Work
Incorporate sector-specific emissions data.
Explore advanced models (e.g., LSTM) for temporal predictions.
Address data gaps and improve feature diversity.
Acknowledgments

## References
“Our World in Data.” Our World in Data, https://ourworldindata.org/. Accessed 4 Dec. 2024.  
“Glossary | DataBank.” DataBank | The World Bank, https://databank.worldbank.org/metadataglossary/world-development-indicators/series/NY.GDP.MKTP.KD.ZG. Accessed 4 Dec. 2024.

