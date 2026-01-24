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
1.	What is the demographic breakdown of the dataset? <br>
•	  Visual: Bar chart for gender distribution and histogram for age groups.<br>
•	  DAX: Create a calculated column for Age Grouping <br>
2.	What percentage of patients have heart disease?<br>
•	Visual: Donut chart to show heart disease cases vs. non-cases.<br>
•	DAX: Create a calculated measure for Heart Disease Percentage:<br>
3.	What is the average cholesterol level across age groups and genders?<br>
•	Visual: Clustered bar chart with cholesterol averages for each gender and age group.<br>
•	DAX: Measure for Average Cholesterol<br>
4.	What is the distribution of blood pressure levels?<br>
•	Visual: Histogram for blood pressure levels.<br>
•	DAX: Calculated column for Blood Pressure Category:<br>
5.	How many patients are flagged as high risk?<br>
•	Visual: KPI card with the total count of high-risk individuals.<br>
•	DAX: Calculated column for High Risk Flag<br>
# Risk Factor Insights<br>
1.	What is the relationship between cholesterol level and triglyceride level?<br>
•	Visual: Scatter plot with cholesterol level on the X-axis and triglycerides on the Y-axis, categorized by heart disease status.<br>
2.	How does BMI correlate with the occurrence of heart disease?<br>
•	Visual: Boxplot for BMI categorized by heart disease status.<br>
3.	What is the impact of family history on heart disease?<br>
•	Visual: Stacked column chart showing heart disease cases by family history.<br>
•	DAX: Measure for Family History Contribution:<br>
4.	What percentage of patients smoke or consume alcohol, and how does it affect heart disease?<br>
•	Visual: Pie charts for smoking and alcohol consumption, segmented by heart disease status.<br>
5.	What is the average sleep duration for different risk categories?<br>
•	Visual: Bar chart for sleep hours across risk groups.<br>
•	DAX: Measure for Average Sleep Hours:<br>
# Temporal Analysis
1.	How does heart disease incidence change across different age ranges?<br>
•	Visual: Line chart showing the percentage of heart disease cases per age group.<br>
2.	What is the trend of blood pressure levels across different genders?<br>
•	Visual: Line chart comparing blood pressure levels over time (if time data exists).<br>
# KPI Tracking and Comparisons
1.	What percentage of patients meet healthy metrics (cholesterol <200, BP <120/80)?<br>
•	Visual: KPI card showing the percentage of patients meeting the healthy criteria.<br>
•	DAX: Measure for Healthy Metric Compliance:<br>
2.	What is the distribution of triglyceride levels among patients with high LDL cholesterol?<br>
•	Visual: Boxplot of triglycerides, filtered by high LDL cholesterol levels.<br>
3.	How do stress and sleep levels affect the risk of heart disease?<br>
•	Visual: Matrix with stress levels as rows, sleep hours as columns, and heart disease percentage as values.<br>
•	DAX: Measure for Stress-Sleep Interaction:<br>

# Next Steps
1.	Data Cleaning: Ensure null values in critical columns are handled.<br>
2.	Dashboard Design: Use slicers for gender, age groups, and risk factors for interactivity.<br>





