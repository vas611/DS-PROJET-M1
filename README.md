# DS-PROJET-M1
PROJET 1 
# COVID-19 Country-wise Latest Data Analysis

## Overview
This project analyzes country-level COVID-19 data using the "country_wise_latest.csv" dataset. The analysis aims to explore global trends in confirmed cases, deaths, recoveries, and active cases across different countries. The findings will provide insights into how the pandemic has affected various regions and countries.

## Data Source
- **Dataset**: "country_wise_latest.csv"
- **Source**: [Kaggle](https://www.kaggle.com/datasets)
- **Description**: The dataset contains information on:
  - Confirmed cases
  - Deaths
  - Recoveries
  - Active cases
  - New cases
  - Death rates per 100 cases
  - WHO region

## Objectives
The primary questions addressed in this analysis are:
- What are the trends in confirmed cases and deaths across different countries?
- How do recovery rates vary by region?
- Which countries are experiencing the highest increase in cases?

## Data Analysis Process
1. **Data Loading**: The dataset is loaded using the `pandas` library in Python.
2. **Data Cleaning**: 
   - Handled missing values by filling them with 0.
   - Renamed columns for clarity and ease of use.
3. **Exploratory Data Analysis (EDA)**:
   - Visualizations created to analyze the distribution of confirmed cases, the relationship between active cases and deaths, and confirmed cases by WHO region.

## Key Findings
- The average number of deaths per country is approximately [insert average number].
- The top countries experiencing significant increases in confirmed cases include [List top countries].
- There is a strong positive correlation between confirmed cases and deaths.

## Visualizations
The analysis includes the following key visualizations:
- Distribution of confirmed cases.
- Top 10 countries by confirmed cases.
- Scatter plot of active cases vs. deaths.
- Bar chart of confirmed cases by WHO region.

## Conclusion
This analysis highlights the importance of monitoring COVID-19 trends to inform public health decisions. Future work could involve further analysis of recovery rates and long-term trends.

## Getting Started
To run the analysis:
1. Clone this repository.
2. Ensure you have the necessary libraries installed (e.g., `pandas`, `matplotlib`, `seaborn`).
3. Run the Jupyter Notebook (`.ipynb`) to reproduce the analysis.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating static, animated, and interactive visualizations in Python.
- `seaborn`: For making statistical graphics in Python.

## Acknowledgments
- Thanks to Kaggle for providing the dataset.
- Special thanks to the open-source community for their valuable resources.
