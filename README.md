# Health-Disease-Analysis(using POWER BI)
# Project Objective
The objective of this project is to develop an interactive and user-friendly Health Disease Dashboard using Power BI to visualize, monitor, and analyze key health and disease-related metrics. The dashboard aims to provide stakeholders—including healthcare professionals, public health authorities, and policy makers—with actionable insights by:
-   Tracking the prevalence and trends of various diseases across regions, age groups, and demographics.
-   Identifying patterns and correlations in disease outbreaks to support early intervention and resource allocation.
-   Monitoring healthcare performance indicators, such as hospitalization rates, recovery rates, and mortality.
-   Improving data-driven decision-making by offering real-time analytics and customizable views.
-   Enhancing public awareness and transparency through clear and accessible health data visualizations.
-   The dashboard will integrate data from multiple sources, ensure data accuracy and privacy, and support timely responses to emerging health concerns.
#  Dataset used
-<a href="https://github.com/vinay9943/Data-Analysis-Dashboard/blob/main/health1.csv"> Heart Disease dataset</a>
# Quections (KPIs)
1.  What percentage of patients meet healthy metrics (cholesterol <200, BP <120/80)?
2.  What is the distribution of triglyceride levels among patients with high LDL cholesterol?
3.  How do stress and sleep levels affect the risk of heart disease?
# Dashboard
<a href="https://github.com/vinay9943/Data-Analysis-Dashboard/blob/main/Screenshot%202025-08-01%20123036.png"> View Dashboard </a>


# Process 
# General Data Analysis
1.	What is the demographic breakdown of the dataset?
•	  Visual: Bar chart for gender distribution and histogram for age groups.
•	  DAX: Create a calculated column for Age Grouping:
2.	What percentage of patients have heart disease?
•	Visual: Donut chart to show heart disease cases vs. non-cases.
•	DAX: Create a calculated measure for Heart Disease Percentage:
3.	What is the average cholesterol level across age groups and genders?
•	Visual: Clustered bar chart with cholesterol averages for each gender and age group.
•	DAX: Measure for Average Cholesterol:
4.	What is the distribution of blood pressure levels?
•	Visual: Histogram for blood pressure levels.
•	DAX: Calculated column for Blood Pressure Category:
5.	How many patients are flagged as high risk?
•	Visual: KPI card with the total count of high-risk individuals.
•	DAX: Calculated column for High Risk Flag:
# Risk Factor Insights
1.	What is the relationship between cholesterol level and triglyceride level?
•	Visual: Scatter plot with cholesterol level on the X-axis and triglycerides on the Y-axis, categorized by heart disease status.
2.	How does BMI correlate with the occurrence of heart disease?
•	Visual: Boxplot for BMI categorized by heart disease status.
3.	What is the impact of family history on heart disease?
•	Visual: Stacked column chart showing heart disease cases by family history.
•	DAX: Measure for Family History Contribution:
4.	What percentage of patients smoke or consume alcohol, and how does it affect heart disease?
•	Visual: Pie charts for smoking and alcohol consumption, segmented by heart disease status.
5.	What is the average sleep duration for different risk categories?
•	Visual: Bar chart for sleep hours across risk groups.
•	DAX: Measure for Average Sleep Hours:
# Temporal Analysis
1.	How does heart disease incidence change across different age ranges?
•	Visual: Line chart showing the percentage of heart disease cases per age group.
2.	What is the trend of blood pressure levels across different genders?
•	Visual: Line chart comparing blood pressure levels over time (if time data exists).
# KPI Tracking and Comparisons
1.	What percentage of patients meet healthy metrics (cholesterol <200, BP <120/80)?
•	Visual: KPI card showing the percentage of patients meeting the healthy criteria.
•	DAX: Measure for Healthy Metric Compliance:
2.	What is the distribution of triglyceride levels among patients with high LDL cholesterol?
•	Visual: Boxplot of triglycerides, filtered by high LDL cholesterol levels.
3.	How do stress and sleep levels affect the risk of heart disease?
•	Visual: Matrix with stress levels as rows, sleep hours as columns, and heart disease percentage as values.
•	DAX: Measure for Stress-Sleep Interaction:

# Next Steps
1.	Data Cleaning: Ensure null values in critical columns are handled.
2.	Dashboard Design: Use slicers for gender, age groups, and risk factors for interactivity.





