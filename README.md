# Employee Attrition Analysis

This repository contains code for analyzing employee attrition using the HR Employee Attrition dataset. The analysis includes exploratory data analysis (EDA), hypothesis testing, and predictive modeling to understand factors contributing to employee attrition and predict attrition rates based on various features.

## Dataset

The dataset used in this analysis is the HR Employee Attrition dataset, which includes information about employees such as age, gender, job role, department, education level, salary, job satisfaction, work-life balance, and attrition status (whether an employee left the company or not). The dataset is available in CSV format and can be found in the `/data` directory.

## Contents

- **attrition_analysis.ipynb**: Jupyter Notebook containing Python code for data exploration, preprocessing, hypothesis testing, and predictive modeling.
  
- **README.md**: Comprehensive documentation providing an overview of the project, instructions, and explanations of the code and analysis.

- **Tableau Dashboard**: A Tableau dashboard for visualizing key insights and trends in the employee attrition data. The dashboard includes interactive visualizations to explore attrition rates, demographic distributions, and relationships between variables.

## Analysis Highlights

1. **Exploratory Data Analysis (EDA)**: The analysis begins with EDA to understand the distribution of variables, identify missing values, and explore relationships between features and attrition.

2. **Hypothesis Testing**: Hypothesis tests are conducted to validate assumptions about the relationship between different variables and attrition. Tests include t-tests and ANOVA to assess significance levels.

3. **Predictive Modeling**: Linear Discriminant Analysis (LDA) is used to predict employee attrition based on various features. The dataset is split into training and testing sets, and the LDA model is trained and evaluated for accuracy.

## Tableau Dashboard

The Tableau dashboard provides a user-friendly interface for exploring the employee attrition data visually. Key features of the dashboard include:

- Overview of attrition rates by gender, department, job role, and other factors.
  
- Distribution of demographic variables such as age, education level, and salary.
  
- Interactive filters and drill-down options to analyze specific subsets of the data.

## How to Use
1. **Explore the Notebook**: Open and run the `attrition_analysis.ipynb` notebook in Jupyter or any compatible environment to execute the analysis.

2. **Access the Tableau Dashboard**: Open the Tableau dashboard file (`attrition_dashboard.twbx`) using Tableau Desktop or Tableau Public to interactively explore the visualizations.
