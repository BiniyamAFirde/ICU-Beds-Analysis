# ICU-Beds-Analysis and Ventilator Performance Dashboard

# Project Overview


This project analyzes ICU bed capacity and ventilator preparedness across US counties, focusing on identifying regions with the highest risk of ICU shortages. The analysis leverages hospital bed data from public health sources and combines Python (for data cleaning and feature engineering) with Tableau (for visualization and dashboard creation).

The goal is to guide decision-makers on which areas need urgent ventilator stockpiling and emergency medical support during public health crises like the COVID-19 pandemic.

# Key Features

✅ US Map displaying ICU beds per capita, color-coded by shortage risk (low, moderate, high).
✅ Top 10 High-Risk Counties ranked by ICU shortage risk.
✅ Bar Chart Comparison showing average ICU beds per capita across states.

# Files Included

File Name	Description
Ventilator_Performance_Dashboard.twbx	Tableau workbook containing all visualizations
hospital_beds_data.csv	Raw hospital beds dataset (original)
cleaned_icu_beds_data.csv	Processed dataset (after cleaning & feature engineering in Python)
data_cleaning.ipynb	Python notebook for data preparation

 # Summary Statistics

ICU Beds per Capita
Metric	Value
Count	3142 counties
Mean	0.000921
Standard Deviation	0.002253
Minimum	0.000000
25th Percentile	0.000000
Median (50%)	0.000197
75th Percentile	0.000707
Maximum	0.030201

# Shortage Risk Levels

Risk Level	Number of Counties	Percentage
High Risk	1585	~50.5%
Moderate Risk	653	~20.8%
Low Risk	904	~28.7%


# How to Run the Project

# Step 1: Data Cleaning (Optional)
Open data_cleaning.ipynb using Jupyter or Google Colab.
Run the notebook to generate cleaned_icu_beds_data.csv.

# Step 2: Visualization in Tableau

Open Ventilator_Performance_Dashboard.twbx using Tableau Desktop or Tableau Public.
Confirm data source links to cleaned_icu_beds_data.csv.
Explore the dashboard directly.

# Key Findings

Many rural counties have zero ICU beds, placing them at extreme risk.
Over 50% of US counties are classified as High Risk for ICU shortages.
ICU bed capacity varies significantly across states, highlighting uneven preparedness.
States with larger urban populations tend to have higher ICU bed capacity, while rural areas are more vulnerable.

# Tools & Technologies

Python (Data Cleaning)
Tableau (Visualization & Dashboard)
GitHub (Version Control)
Excel (manual review)

## Interactive Dashboard:
View the interactive version of the dashboard on Tableau Public: https://public.tableau.com/views/ICUBEDPROJECT/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
