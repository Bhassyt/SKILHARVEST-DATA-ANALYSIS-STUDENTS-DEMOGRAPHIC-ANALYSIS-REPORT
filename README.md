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
- Data Loading and Inspection.
- Handling Duplicate Data.
- Handling Missing Data.
- Data Formatting.
- Feature Selection/Engineering.

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
- Among the age groups analyzed, the 25 to 29 age group exhibited the highest total number of students, with a count of 18, which was 500% higher than that of the 35 to 39 age group, which had a count of 3.
- There is a variation in the distribution of students between male and female genders in terms of total numbers. Specifically, the total number of male students (22) was higher than that of female students (21), indicating a difference in distribution between the two genders.
- The distribution of students varies depending on marital status. Notably, the total number of single students (32) surpassed that of married students (11), illustrating a distinction in student counts between the two marital categories.
- The distribution of students differs across various educational qualifications. Notably, HND/BSc/B.Tech recorded the highest total number of students at 34, followed by MSc/MTech with a count of 7.
- Across various countries, Nigeria had the highest total number of students at 40, while Ghana, Zambia, and Zimbabwe each had one student, indicating a diverse distribution among the countries analyzed.
- The distribution of students between single and married individuals fluctuates across various levels of education. Notably, the greatest disparity between single and married individuals was observed when the highest level of education attained was HND/BSc/B.Tech, with single individuals exceeding married individuals by 20 students.
- The distribution of students between male and female individuals varies depending on marital status. Notably, the most significant difference between male and female students was observed when the marital status was married, with males exceeding females by 3 students.
- The distribution of students between male and female individuals exhibits variance across various age groups. Notably, the most significant difference between male and female students was observed in the age groups of 30-34 and 20-24. In the age group of 30-34, males exceeded females by 5 students, whereas in the age group of 20-24, females outnumbered males by 5 students.

## Conclusions and Recommendations
---

**Conclusions**
- **Age Group Analysis:** The 25 to 29 age group has the highest number of students, showing a significant difference compared to the 35 to 39 age group.
- **Gender Distribution:** There's a variation in the number of male and female students, with slightly more males than females.
- **Marital Status:** Single individuals comprise a larger portion of students compared to married individuals.
- **Educational Qualifications:** Students with HND/BSc/B.Tech qualifications constitute the majority, followed by those with MSc/MTech degrees.
- **Country Distribution:** Nigeria has the highest number of students, showcasing diversity across countries.
- **Intersection of Marital Status and Education:** The disparity between single and married individuals is most prominent among those with HND/BSc/B.Tech qualifications.
- **Intersection of Gender and Marital Status:** Males outnumber females, particularly among married students.
- **Intersection of Gender and Age:** Variances in male-female ratios are observed across different age groups.

**Recommendations**

Based on the analysis, i recommend the following actions:
- **Targeted Programs:** Design programs tailored to the needs and preferences of the 25 to 29 age group, considering their significant representation.
- **Gender-Inclusive Initiatives:** Implement initiatives to encourage gender diversity, ensuring equal opportunities for both male and female students.
- **Support for Married Students:** Provide support services tailored to the unique challenges faced by married students to ensure their success.
- **Education Accessibility:** Expand educational opportunities for individuals with diverse qualifications, considering the prevalence of HND/BSc/B.Tech and MSc/MTech students.
- **International Collaboration:** Foster collaborations and partnerships with institutions in countries like Nigeria, Ghana, Zambia, and Zimbabwe to promote cultural exchange and global learning experiences.
- **Marriage and Education Support:** Offer resources and support systems catering to the needs of both single and married students, recognizing the different life stages they may be in.
- **Gender Equity Initiatives:** Implement strategies to address gender imbalances, especially among married students, promoting equal representation and inclusivity.
- **Age-Specific Programs:** Develop initiatives tailored to the specific needs and interests of different age groups to ensure targeted support and engagement.
