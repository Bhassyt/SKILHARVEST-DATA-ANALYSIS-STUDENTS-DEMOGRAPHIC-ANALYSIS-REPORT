# SKILHARVEST-DATA-ANALYSIS-STUDENTS-DEMOGRAPHIC-ANALYSIS-REPORT
---

**Documentation Outlines**

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Conclusions and Recommendations](#conclusions-and-recommendations)

## Project Overview
---
This project explores the diverse backgrounds of students enrolled in the Data Analysis course at SkilHarvest Academy. Surveys were conducted to gather information on age, gender, education, marital status, occupation and location. The analysis of this data unveils diversity in age groups, geographic locations, prior education levels, and more. The goal is to identify any underrepresented groups and understand how student backgrounds influence their learning needs. The report presents key findings using visual charts and graphs. These insights will inform enhancements to the course, such as updating teaching approaches and providing tailored support resources, to ensure an enriching experience for all students, regardless of their demographic profile. Ultimately, this study aims to deeply understand student demographics to optimize the effectiveness of the Data Analysis course at SkilHarvest Academy.

## Data Sources
---
The primary dataset utilized for this analysis is the "skilharvest_class_data.xlsx" file containing detailed information about each students enrolled in SkilHarvest Academy's Data Analysis course. It encompasses essential demographic variables such as age, gender, education, marital status, occupation, and location.

## Tools Used
---
- Google Forms and Google Sheets (For Data Collection and Organization)
- Microsoft Excel (For Data Cleaning)
- Microsoft Power BI (For Reporting and Dashboarding)

## Data Cleaning and Preparation
---
In the initial data preparation phase, the following tasks were performed:
1. Data Loading and inspection.
2. Handling missing values.
3. Data Cleaning and formatting.

**Exploratory Data Analysis**

EDA entails delving into the data to address various questions regarding its characteristics, which includes:
- What is the distribution of students across different age groups?
- How does the distribution of students vary between male and female genders in terms of total numbers?
- How does the total number of students differ between individuals who are single and those who are married?
- How does the total number of students vary across different educational qualifications?
- What is the distribution of students among different countries?
- How does the distribution of students between single and married individuals vary across different levels of education?
- How does the distribution of students between male and female individuals vary across different marital statuses?
- How does the distribution of students between male and female individuals vary across different age groups?

## Data Analysis
---
Here is where I incorporated certain Data Analysis Expressions (DAX) utilized during my analysis.
```
Number of Countries = DISTINCTCOUNT('Form Responses 1'[Country of Residence])
```
```
Number of Females = CALCULATE(COUNTROWS('Form Responses 1'), 'Form Responses 1'[Gender] = "Female")
```
```
Number of Males = CALCULATE(COUNTROWS('Form Responses 1'), 'Form Responses 1'[Gender]= "Male")
```
```
Total Number of Students = COUNT('Form Responses 1'[Names])
```

## Results and Findings
---
This is where the insights obtained from the analysis are presented. "Access my insights here:[[Dashboard Report Link](https://app.powerbi.com/view?r=eyJrIjoiOTVkY2U4YWUtYWQ1NS00M2U3LTlmODItYmM1NjAyYjRhOTkxIiwidCI6IjBlZjcwYWU3LWI3NmUtNGI4ZC04NWEzLWZlZmFmNjg4MDAxZCJ9)]"



