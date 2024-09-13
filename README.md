# KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-/-preparation)
- [Key Questions](#key-questions)
- [Results/Findings](#results-/-findings)
- [Recommendations](#recommendations)

### Project Overview
The primary objective of this project is to develop a comprehensive KPI Dashboard that provides an in-depth overview of patient data from the cardiology unit at Hero Dayanand Medical College Heart Institute. The dashboard aims to deliver actionable insights by visualizing key performance indicators (KPIs) and metrics related to patients' admissions and discharges over a two-year period. 

### Data Source
https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data?select=HDHI+Admission+data.csv

### Tools
Microsoft Excel:
- Power Query - Data Cleaning/Preparation
- Pivot Table - Data Analysis and Summarization
- Charts - Data Visualization and Storytelling

### Data Cleaning/Preparation
- Data loading and inspection
- Handling missing values and removing blank rows
- Removing duplicates and clear formatting
- Removing unnecessary columns
- Renaming some values for a clearer understanding of certain terms
- Added a new columns for Date of Admission and Date of Discharge to correct formatting issues
- Removed D.O.A and D.O.D columns 
- Changed the correct data type of all the columns

### Key Questions
To ensure that the KPI Dashboard provides valuable insights and meets the needs of stakeholders, the following key questions were addressed:
- What is the total number of patients admitted over the two-year period?
- Are there any significant variations in patient admission numbers over time?
- Are there peak periods or trends in patient admissions?
- What is the average duration of stay for patients?
- What are the age demographics of patients admitted? Are there specific age groups that are more frequently admitted?
- How are patient admissions distributed across different types? 
- What are the annual outcome status of patients?
- How do outcomes vary year-over-year, and are there any noticeable trends or patterns?
- How do different types of admissions vary by gender?
- What is the geographical distribution of patients admitted? Are there specific regions or localities that contribute more significantly to patient admissions?
- What is the gender distribution of patients admitted?

### Results/Findings
<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/image1.png" alt="First Image" width="200"/>
<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/patientsbyadmissiondate.png" alt="Second Image" width="500" height="300"/>

- There are a total of 15757 admitted patients over the two-year period.
- The total number of admissions increased from 2017 to 2018, peaking in 2018, especially in March. However, this upward trend was followed by a decline in admissions throughout 2019.
- The average duration of stay of the patients is 6.4 days and for the average duration of intensive stay is 3.8 days.

<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/agedistribution.png" alt="First Image" width="500" height="300"/>

- Over the two-year period, the distribution of patients by age group was as follows: approximately 60.29% were aged 60 and above, 33.78% were between 40 and 59 years old, 5.39% were aged 20 to 39 years, 0.36% were between 13 and 19 years old, 0.12% were aged 5 to 12 years, and only 0.05% were between 2 and 4 years old. Hence, the data suggests that patients aged 60 and older are significantly more frequently admitted compared to other age groups.

<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/patientadmissiontype.png" alt="First Image" width="500" height="300"/>

- Out of the 15,757 patients, 4,833 were classified as outpatients, while 10,924 were admitted through emergency services.

<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/patientoutcome.png" alt="First Image" width="500" height="300"/>

- In 2017, out of 5,571 admitted patients, 4,904 were discharged, 273 were discharged against medical advice, and 394 patients expired. In 2018, out of 7,789 admitted patients, 6,795 were discharged, 440 were discharged against medical advice, and 554 patients expired. In 2019, out of 2,397 admitted patients, 2,057 were discharged, 183 were discharged against medical advice, and 157 patients expired.
- The percentage of patients discharged has remained relatively stable across the years, hovering around 87%. However, there is a slight decrease in 2019, which corresponds with the reduction in total admissions. On the other hand, The percentage of patients discharged against medical advice increased in 2018 compared to 2017 but decreased in 2019. Despite the decrease, the percentage in 2019 is higher than in 2017. Meanwhile the percentage of expired patients has remained consistent over the years, though the number of expired patients decreased significantly in 2019. This suggests a reduction in overall mortality in 2019 relative to the number of admissions.

<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/locality.png" alt="First Image" width="500" height="300"/>

- The majority of admitted patients are from urban areas, which make up approximately 77% of the total admissions, while rural areas contribute only 23%.

<img src="https://github.com/angelicamerced/KPI-Dashboard-Patient-Overview-at-Hero-Dayanand-Medical-College-Heart-Institute/blob/main/gender.png" alt="First Image" width="500" height="300"/>

- This distribution shows a higher proportion of male patients compared to female patients, with males making up 63% of admissions and females 37%.

### Recommendations
- Given the average duration of stay and intensive care duration, assess the efficiency of current treatment protocols and patient management strategies to ensure optimal use of hospital resources and timely patient recovery.
- With a significant portion of patients being aged 60 and above, develop specialized care programs and resources suitable to the needs of elderly patients. 
- Given the high percentage of emergency admissions, ensure that emergency services are well-equipped and staffed to handle peak periods effectively. 
- Investigate the reasons for patients being discharged against medical advice and implement strategies to address any underlying issues, such as patient education or improving discharge planning.
- Explore ways to increase outreach and accessibility to rural areas to balance the admission distribution and address any disparities in healthcare access between urban and rural populations.
- While the gender distribution shows a higher proportion of male patients, ensure that healthcare services are equitably designed and address any gender-specific health needs.

By implementing these recommendations, the hospital can enhance patient care, optimize resource utilization, and address any disparities in service delivery.









