# TASK5_EDA
# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview
This repository contains my submission for **Task 5: Exploratory Data Analysis (EDA)** as part of the Data Analyst Internship.

The analysis is performed on a Titanic-like dataset (synthetic fallback created in the absence of internet access, but following the structure and features of the Titanic dataset). The notebook and report demonstrate key EDA steps using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## Contents
- **EDA_Titanic.ipynb**: Jupyter Notebook containing the complete EDA workflow, visualizations, and observations.
- **EDA_Titanic_Report.pdf**: PDF report summarizing the findings with visuals.
- **titanic_used_dataset.csv**: Dataset used for this EDA.
- **Plots**: PNG files of all visualizations created in the notebook.

---

## EDA Steps
1. **Data Overview**: Used `.info()` and `.describe()` to understand data structure and summary statistics.
2. **Missing Values Analysis**: Identified missing data and visualized with bar plots.
3. **Univariate Analysis**:
   - Age distribution (histogram)
   - Fare distribution (boxplot)
   - Passenger counts by embark town
4. **Bivariate & Multivariate Analysis**:
   - Survival counts by passenger class
   - Correlation heatmap for numeric columns
   - Pairplot (sample) for survival, age, fare
   - Age distribution by class
5. **Observations & Insights**: Highlighted patterns, trends, and anomalies.

---

## Key Findings
- Significant missing values in `deck`, and some missing in `age` and `embark_town`.
- Age distribution is slightly right-skewed; fare contains outliers.
- Survival rates vary significantly by passenger class (higher in first class).
- Numeric correlations are generally weak; categorical factors are more influential in survival.

---

## Tools & Libraries
- Python 3
- Pandas
- Matplotlib
- Seaborn

---
## Author
Prepared as part of the Data Analyst Internship tasks.

