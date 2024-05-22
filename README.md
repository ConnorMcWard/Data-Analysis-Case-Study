# Utility Data Case Study

## Table of Contents
- [Case Study Overview](#case-study-overview)
- [Results](#results)
  - [Introduction](#Introduction)
  - [Methodology](#Methodology)
  - [Observations](#Observations)
  - [Issues Identified](#Issues-Identified)
  - [Recommendations](#Recommendations)
  - [Conclusion](#Conclusion)

- [Tasks](#Tasks)
- [Evaluation Rubric](#evaluation-rubric)

## Case Study Overview
### Background
The goal of this case study is to utilize artificial intelligence to retrofit buildings, helping real estate customers achieve their net-zero goals. This relies on consistent and accurate utility data from customers.

### Instructions
You have been provided with a dataset consisting of utility data, including natural gas and electricity consumption over the past year. Your tasks are to clean the dataset, implement checks to identify inaccuracies or data gaps, and make sense of the data.

### Detailed Overview of Tasks
1. **Data Cleaning:**
    - Prepare the dataset for analysis by addressing any data irregularities and ensuring data readiness.
    - Explain how inaccuracies, inconsistencies, or gaps were handled.
    - Get the data into a usable format for visualization and platform ingestion.
2. **Data Validation:**
    - Evaluate the quality and reliability of the utility data.
    - Identify any anomalies or outliers and attempt normalization if possible.
3. **Carbon Emissions Analytics:**
    - Convert the energy usage to carbon emissions (in metric tons) using EnergyStar’s reference guide.
4. **Data Visualization and Analysis:**
    - Create visualizations to represent key trends and insights.
    - Use appropriate tools to enhance data understanding.
    - Summarize findings and insights in a final report.
5. **Communication:**
    - Summarize findings and insights, highlighting any issues and recommendations for further action.

## Results

### Introduction
This report summarizes the analysis conducted on energy consumption data from seven units across two properties. The focus was on identifying any patterns or trends that could inform energy efficiency strategies.

### Methodology
My analysis followed these steps:
1. **Data Cleaning and Validation:** Energy consumption data was gathered for each unit, ensuring accuracy and consistency.
2. **Data Normalization:** Normalized energy consumption values.
3. **Energy Conversion:** Energy consumption was converted into CO2 emissions per metric ton.
4. **Calculation of Average Emissions by Unit and Property:** Analysis was done to highlight companies and buildings which had higher than average CO2 emissions per square foot.
5. **Data Visualizations/ Trend and Seasonality Analysis:** The data was examined for linear trends, indicative of long-term changes in energy usage. An Autocorrelation Function (ACF) was utilized to evaluate the seasonality in energy consumption, particularly for gas usage.

### Observations
1. **Consistency in Energy Usage:** The data analysis didn’t point to any significant linear or seasonal trends in energy consumption across the units. Specifically, the ACF analysis for gas usage didn’t show any strong correlations indicative of seasonality, suggesting that other external factors might be mitigating potential seasonal influences.
2. **Comparison of Emission Efficiency:** An interesting finding was that the Empire State Building, even post its 2010 retrofit, registered higher average emissions per square foot in comparison to the more modern World Trade Center. This discrepancy highlights the potential for more advanced retrofitting initiatives.

### Issues Identified
1. **Incomplete Data:** There were gaps in the data collection, which could impact the accuracy and comprehensiveness of the analysis.
2. **Inconsistent Data Reporting:** Some conflicting values were noted in data reporting, from sources like LinkedIn and Condé Nast.

### Recommendations
1. **Targeted Retrofitting for Enhanced Efficiency:** Considering the higher emission rates of the Empire State Building, it’s advisable to plan for additional retrofitting, focusing on incorporating cutting-edge sustainability features to boost energy efficiency.
2. **Refinement of Data Collection Methods:** We need to bolster our data collection methods to fill in any gaps and ensure uniformity in data reporting. This would involve, for instance, ensuring that sources like LinkedIn and Condé Nast deliver one consistent utility data point every 28 days.

### Conclusion
My analysis indicates consistent energy consumption patterns across the evaluated units, with a notable disparity in emission efficiency between older and newer buildings. Addressing the identified data issues and implementing the recommended strategies can significantly enhance energy efficiency and sustainability, aligning with environmental standards and reducing operational costs. The Company customer success team should prioritize these actions to optimize energy management in their properties.

## Tasks

### Data Cleaning
Details of the data cleaning process, including:
- Handling missing values
- Removing duplicates
- Correcting data types
- Normalizing data

### Data Validation
Methods used to evaluate data quality, including:
- Identifying outliers
- Ensuring data consistency
- Implementing validation checks

### Carbon Emissions Analytics
Steps to convert energy usage to carbon emissions:
- Using conversion factors from EnergyStar’s reference guide

### Data Visualization and Analysis
Creating visualizations to represent key trends and insights:
- Line charts for usage trends
- Bar charts for emissions comparison
- Heatmaps for correlation analysis

## Evaluation Rubric
- **Data Integrity:** Ability to identify and rectify inaccuracies and inconsistencies.
- **Data Validation Techniques:** Knowledge of data validation methods to ensure accuracy.
- **Domain Knowledge:** Understanding of utility data and industry terminology.
- **Attention to Detail:** Thoroughness in identifying and correcting errors.
- **Communication of Findings:** Ability to communicate complex data issues and insights clearly.
- **Technical Proficiency:** Proficiency in relevant tools and programming languages.
- **Data Visualization and Analysis:** Ability to visually represent data and draw meaningful insights.
