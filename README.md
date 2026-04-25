# Well-Life-Patient-Admissions-and-Diagnosis-Trends Analysis

### Table Of Content
[Background](#background)

[Problem Statement](#problem-statement)

[Analysis Objectives](#analysis-objectives)

[Dataset Description](#dataset-description)

[Tools Used](#tools-used)

[Data Cleaning Process](#data-cleaning)

[Data Analysis](#data-analysis)

[Key Insights](#key-insights)

[Business Recommendation](#business-recommendation)

### Background
WellLife General Hospital has collected data spanning from 2021 to 2024 to assist with 
hospital planning and resource allocation. The dataset contains key patient information 
such as 
- Patient_ID
- Age, Diagnosis
- Gender
- Admission_Date
- Diagnoses{ these are grouped into two categories: Patient Cases and Chronic Cases.
Management requires a comprehensive overview of patient distribution, diagnosis trends, and demographic factors 
to improve resource allocation for the upcoming years. 

### Problem Statement
Management currently lacks a consolidated, summarized view of patient admissions,diagnosis trends, and demographic data for 2021-2024. 
Specifically: 
- There is no clear understanding of patient distribution by age, gender, or diagnosis group.
- Clinical trends in patient admissions over time are not readily visible.
- Diagnosis types (chronic vs. patient cases) need further clarification.
- Distribution of Diagnosis across Age groups
Without this information, management is unable to effectively plan for the 
allocation of hospital resources or assess trends across different patient groups.

### Analysis Objectives
The objective of this analysis is to describe and summarize the distribution of patients from 
2021 to 2024. This analysis will: 
- Present the total number of patients recorded from 2021 to 2024.
- Show the distribution of patients by age and gender.
- Summarize patient distribution by diagnosis group (Chronic Cases, Patient Cases).
- Highlight trends in patient admissions by year.

### Dataset Description
The dataset contains patient admission spanning the period of 2021 - 2024. It dontains 5 columns and 10002 rows of data. The columns present in this dataset includes
- Patient ID
- Age: Age of patient
- Diagnosis: disease disgnosis type
- Gender: Male or felame
- Admission Date: Date the patient was admitted
Aditionally we were provided with a file, classifying diagnosis by groups
- Infectious
- Chronic

### Tools Used
- Power BI
- Power Query
- DAX

### Data Cleaning
To clean this data, i imported this data into power query and carried out the following processes
- Ensured appropriate data type for each column
- Removed duplicates from the patient ID column
- Trimmed the name fields
- Standardized the Gender
- Standardized the date column

### Data Analysis
I loaded this clean data into Excel, and used Pivot table to summerize this data. This data summerization provided me with insight into the objective of this analysis. Using the pivot table, i carried out an exploratory data analysis to extract the following information

Total Patients: 
- What is the total number of patients admitted from 2021 to 2024?
Age Distribution:
- What is the average age of patients admitted during the period
- How are patients distributed across various age?
Gender:
- What is the gender distribution of patients?
Diagnosis Group:
- How are patients distributed across the diagnosis groups
Admission Trends
- How do patient admissions vary across different years (2021-2024)? 
- What is the year-on-year growth rate of patient admissions? 
- Are there any notable seasonal or annual trends in admissions? 
- How many patients do we expect to be admitted during the first three months of 2025?

### Key Insights
- Total Patients Admitted were 10000
- Average age of Patients admitted is 44 years
- The facility recorede 7 unique diagnosis with typhiod leading in count of cases recorded
- The facility had higher cases of Chronic diseases than Infectious diseases
- Chronic disease were more prevalent in older adults above 40 years of age
- Men admitted showed higher cases of chronic diseases
- Infectious disease were more prevalent in persons below 40 years of age
### Top Key insight
Patient Growth rate: The facilityshowed an increased no of patient inflow over time by records, this would mean increased services and ultimately increased revenue. How ever when we too a deeper look into the growth rate of the facility we saw a sharp decline in Patient growth rate over time spanning from 2022 - 2024. This was not noticeable on the surface, but with a deeper look using time intelligence analysis, this became obvious

### Business Recommendation
- Noting the prevalence of infectious diseases among the younger generation, a public health measure should be taken to curb the spread of diseases. More public health awarenesson on hygenic measures in public spaces should be encouraged
- Older adults should be asked to follow healthier lifestyles to reduce the impact or hasten the health recovery from chronic diseases
- With the decline in patient inflow, the facility will loose its market share shortly, hence they should look into providing better services for patients within the middle and older age seeing most of their patients fall within this age brackets, primirily solving chronic health cases

