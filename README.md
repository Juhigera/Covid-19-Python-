COVID-19 Global Data Analysis — Python & Pandas Project
📌 Project Overview

The COVID-19 pandemic, caused by the SARS-CoV-2 virus, emerged in late 2019 and rapidly spread across the world, creating unprecedented health, economic, and social challenges. This project uses Python to analyze global COVID-19 datasets and draw meaningful insights from confirmed cases, deaths, and recoveries across 276+ regions.
By applying data cleaning, feature engineering, transformation, and time-series visualization techniques, this project demonstrates how data analytics can support informed decision-making during global health crises.

📂 Datasets Used

The analysis uses three key datasets (Jan 2, 2020 – Dec 5, 2021):

1. Confirmed Cases Dataset

Cumulative confirmed COVID-19 cases

Daily updates for each country and province/state

276+ geographic entries

2. Deaths Dataset

Cumulative reported deaths

Helps determine lethality and outbreak severity

3. Recovered Cases Dataset

Cumulative recoveries

Indicates disease progression and management effectiveness

Each dataset contains:

Province/State

Country/Region

Latitude, Longitude

Daily cumulative counts

🎯 Objectives of the Case Study

Strengthen practical Python skills using Pandas, NumPy, and Matplotlib

Clean, transform, visualize, and merge real-world time-series datasets

Analyze COVID-19 spread, recovery trends, and mortality patterns

Perform multi-country comparisons and derive actionable insights

🛠 Key Analysis Performed
1. Data Loading & Exploration

Load all datasets using Pandas

Inspect rows, columns, and datatypes

Plot confirmed cases for:

Top affected countries

China

2. Handling Missing Data

Identify NULLs

Impute missing values using forward fill

Replace blank province entries with "All Provinces"

3. Independent Analysis

Peak daily new cases for Germany, France, Italy

Compare recovery rates for Canada vs. Australia

Death rate distribution across Canada’s provinces

4. Data Transformation

Convert wide-format dataset → long format

Convert date columns into datetime

Calculate:

Total deaths per country

Top 5 countries with highest avg daily deaths

U.S. death trends over time

5. Data Merging

Merge transformed confirmed, deaths, and recovered datasets

Analyze monthly totals for each country

6. Combined Dataset Analysis

Identify 3 countries with highest average death rates in 2020

Compare total recoveries vs. deaths in South Africa

Monthly recovery ratio for U.S. from Mar 2020 to May 2021

📊 Tools & Libraries

Python 3

Pandas

NumPy

Matplotlib

Jupyter Notebook

📘 Conclusion

This project demonstrates how Python can be used to analyze complex real-world time-series health datasets. It highlights important epidemiological insights such as peak infection periods, country-wise mortality trends, and recovery performance.
It also showcases essential data analytics skills: wrangling, merging multi-structured datasets, applying transformations, and visualizing pandemic progression.
