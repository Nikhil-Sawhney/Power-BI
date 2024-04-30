# Introduction: 
The Healthcare Data Analysis Dashboard on Power BI offers an in-depth examination of patient health data spanning from 2019 to 2023. Divided into two main sections — “Patient Demographics” and “Clinical Insights” — this report utilizes visualizations and DAX calculations to unveil critical trends and key performance indicators (KPIs), enabling healthcare providers to make informed decisions and optimize patient care strategies.

# Data Collection: 
The dataset comprises various attributes including patient demographics, medical conditions, admission details, and more. It's a synthetic dataset designed for educational and non-commercial use, ensuring privacy and compliance. The data cleaning is done using Microsoft Excel, removing incomplete records and irrelevant columns to enhance analysis accuracy.


# Data Preparation for Analysis using Power BI:
* Creating Separate Tables: A Date table is established to facilitate temporal analysis, linked with the main dataset. Additionally, a “Calculations” table is created for KPI measures.
* Creating Calculated Columns: New calculated columns such as Age Buckets, Readmission Indicator, and Total Stay Duration are generated to facilitate analysis and visualization.
*Creating Measurements for KPIs: Various KPIs are calculated using DAX expressions, including Readmission Count, Readmission Rate, and other pertinent metrics.

# Analysis and Visualizations for the Report: 
The report is structured into two sections for clarity:

1. Patients Demographics:

Reveals insights into the patient population demographics, including age distribution, gender distribution, and prevalent medical conditions.
Provides actionable insights for tailoring care approaches to specific patient groups, optimizing resource allocation, and improving overall patient satisfaction.

![Patient Demographics](https://github.com/Nikhil-Sawhney/Power-BI/assets/134135837/c6671fb9-e0ef-472d-b2ff-39aefc97ef2e)

2. Clinical Insights:

Unveils critical medical trends and insights, including common admission types, prevalent health concerns, treatment efficacy, and cost management insights.
Empowers healthcare providers to identify areas for improvement, target interventions, and enhance treatment efficacy while managing costs effectively.

![Clinical Insights](https://github.com/Nikhil-Sawhney/Power-BI/assets/134135837/9ca395e8-f7cf-4fc3-a124-40112512a347)

# Core Questions Answered in the Healthcare Analytics Report:
This Power BI report provides a comprehensive analysis of patient health data, empowering healthcare providers with data-driven insights to optimize patient care. By leveraging DAX calculations and data visualizations, the report tackles critical questions regarding the patient population and recent medical trends within the specified timeframe (October 2018 — December 2023).

- Who are our patients? 

The report delves into the demographics of admitted patients, uncovering insights into age distribution, blood group distribution (by gender), and the total number of patients treated. Most of the patient that were admitted were “Adults” and “Elderly” i.e. >35 with having greater Female count among patients by some percentage (55% Female and 45% Male). This information helps tailor care approaches to specific patient populations.

- What are the most common admission types?

Analyzing the distribution of admissions by type (emergency, urgent, elective) reveals trends in patient acuity and resource utilization. Major portion of Admission type is “Emergency” type (around 40%). This knowledge allows for informed decisions regarding resource allocation to best serve incoming patients.

- What are the top health concerns affecting our patients?

Among patients, the most common health concerns are Jaundice, Diarrhea, and Tuberculosis. Diarrhea is most common among young adults (18–35), arthritis is most common among adults (>35–65), and most cases of cancer occur in the elderly (>65). By identifying the most prevalent medical conditions during this period, the report empowers healthcare providers to target interventions and preventative measures for those specific conditions.

- How effective are our current treatment plans?

Average Readmission rate is 11% with highest admission-readmission ratio in the month of June, November and December. Patients suffering from Tuberculosis has the highest readmission rate. By analyzing readmission rates by condition or month, areas needing improvement can be pinpointed to enhance treatment efficacy and potentially reduce readmissions.

- How satisfied are our patients?

The report calculates average patient satisfaction, offering valuable feedback on the patient experience. The Average rating is 3.1/5 remains constant in every year from 2019–23. Highest average Rating comes from “Jaundice” Patients and lowest from “Arthritis”. Tracking changes in satisfaction over time allows for targeted initiatives to improve the overall patient experience.

- What is the average billing cost per patient?

Average billing cost per patient is around $25k with Cancer being the highest of $31k and Asthma being the lowest $23k. This KPI provides insights into the average cost of treatment, which can inform resource allocation decisions and potential cost-saving strategies.

# Additional Considerations:

The report also highlights top doctors based on patient ratings, fostering recognition for high performers and potentially boosting patient morale. Furthermore, it identifies medical conditions with the highest readmission rates, prompting a deeper analysis of factors contributing to these occurrences and the development of strategies for reduction.

# Conclusion: 

In conclusion, this Healthcare Data Analysis Dashboard on Power BI provides comprehensive insights into patient health data, empowering healthcare providers to optimize resource allocation, enhance treatment efficacy, improve patient experience, and manage costs effectively. By addressing core questions and leveraging data-driven insights, this report facilitates informed decision-making and enhances overall healthcare delivery


