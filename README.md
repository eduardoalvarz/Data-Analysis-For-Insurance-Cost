# Data Analysis for Insurance Cost 
---

## Introduction
This GitHub repository hosts a data analysis project focusing on insurance cost analysis using Python and machine learning techniques. The project involves data cleaning, exploratory data analysis (EDA), and the development of predictive models to understand the factors influencing insurance charges.

## Objectives
1. **Load Data:** Import the dataset into a pandas DataFrame.
2. **Clean Data:** Fix or remove incorrect or missing entries.
3. **Exploratory Data Analysis (EDA):** Identify key factors that impact charges.
4. **Model Development:** Create linear regression models to predict charges.
5. **Model Refinement:** Enhance models' accuracy with Ridge regression.

## Setup
The analysis utilizes several Python libraries:
- `pandas` for data management.
- `numpy` for mathematical operations.
- `sklearn` for machine learning and pipeline functions.
- `seaborn` and `matplotlib` for data visualization.

## Dataset Description
The dataset includes parameters such as age, gender, BMI, number of children, smoking status, region, and annual insurance charges in USD.
   ```python
   path = 'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-Coursera/medical_insurance_dataset.csv'
   ```

## Data Wrangling
Handle missing data, replace incorrect entries, and ensure the correct data types.

## Exploratory Data Analysis (EDA)
Visualize key factors impacting insurance charges through regression plots, box plots, and correlation matrices.

## Model Development
Develop linear regression models using 'smoker' attribute and all other attributes. Evaluate model performance using R2 scores.

## Model Refinement
Enhance model accuracy through Ridge regression and polynomial transformation.

## Conclusion
The project provides insights into insurance cost analysis, demonstrating effective data cleaning, exploratory data analysis, and model development. The code is structured in a Jupyter Notebook for easy replication and understanding.

Feel free to explore the code and adapt it to your specific needs. If you have any questions or suggestions, please open an issue or reach out directly.

**Happy Analyzing!**
