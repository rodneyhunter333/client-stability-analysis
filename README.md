# Client Stability Analysis: Modeling Housing Outcomes with ACEs, Victimization, and Demographic Data

## Overview
This project analyzes how adverse childhood experiences (ACEs), victimization history, demographic factors, and income relate to housing stability outcomes. Using Python, I cleaned and merged multiple client-level datasets, performed exploratory data analysis, and built predictive models to better understand the factors associated with stay length.

The project was designed to support data-informed intervention strategies by identifying patterns across client risk factors and stability outcomes.
## Business Problem
Housing stability is shaped by a combination of economic, demographic, and trauma-related factors. Organizations serving vulnerable populations often need better ways to identify which clients may require additional support.

This project explores the following questions:
- How do ACEs, victimization history, and demographic characteristics relate to housing stability?
- Which client-level factors appear most associated with stay length?
- Can predictive modeling help explain or estimate housing stability outcomes?
## Data
This analysis uses merged client-level data from multiple Excel sources, including:
- Client housing and demographic records
- ACEs survey responses
- Victimization survey responses

After merging and preprocessing, the dataset included variables related to:
- Stay length
- Age
- Entry and latest income
- Education
- Race and sex
- Disability and veteran status
- Domestic violence indicators
- ACEs total score
- Victimization history
## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Excel
- Tableau

## Data Cleaning & Preparation
To prepare the data for analysis, I:
- Loaded and reviewed multiple Excel sheets containing client, ACEs, and victimization data
- Standardized column names across datasets
- Merged the files using a shared client ID
- Converted numeric fields such as stay length, age, and income into usable formats
- Replaced invalid negative values in stay length
- Created new variables such as income change, education group, race group, age group, ACE risk category, and income level
- Addressed missing values through imputation during model building
## Exploratory Data Analysis
I used exploratory analysis and visualizations to examine:
- The distribution of stay length
- The relationship between ACEs total score and stay length
- Differences in stay length across education groups
- Correlations among stay length, age, income, and ACEs
- Risk patterns across income and demographic variables

These analyses helped identify broad patterns in the data and informed the feature selection process for modeling.
