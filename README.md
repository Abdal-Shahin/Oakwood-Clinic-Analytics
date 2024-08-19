# THE OAKWOOD CLINIC ANALYTICS

Live Interactive Dashboard: https://shorturl.at/x9wLC

## PROBLEM STATEMENT:

The Oakwood Clinic in Edinburgh is dedicated to advancing its healthcare services, optimizing patient outcomes, and driving revenue growth. With a diverse patient population and an extensive range of services, a comprehensive analysis is necessary to identify key trends. The clinic seeks to leverage data-driven insights to make informed decisions that will enhance operational efficiency and patient care.

## PROJECT OBJECTIVES:
Conduct a detailed analysis of patient demographics, healthcare utilization patterns, and financial performance.
Identify opportunities for operational efficiency and resource optimization.
Develop forward-looking recommendations to drive growth, expand service offerings, and foster innovation.

## TRANSFORMATIONS PERFORMED

In this project, I worked with eight tables in Power BI: Cities, Departments, Diagnosis, Insurance, Patients, Procedures, Providers, and Visits. The Visits table served as the fact table, while the others were dimension tables. Key transformations included:

- **Fixed Data Types:** Ensured that all data types were appropriately set for accurate analysis.
- **Created Date Table:** Added a Date table for in-depth time-based analysis, including columns like Date, Year, Month, and Quarter.
- **Age Grouping:** Divided patients into different age groups based on their age.
- **Length of Stay Calculation:** Calculated the length of stay by subtracting the discharge date from the admission date.
- **Adjusted Visit Type:** Created a new column called Adjusted Visit Type to classify patients with missing admission and discharge dates as outpatients.

## METRICS

Several metrics were developed to assess the clinic's performance:

- **Average Patient Age**
- **Total Patients**
- **Total Visits**
- **Average Length of Stay**
- **Average Billing Amount**
- **Medication Cost**
- **Total Room Charges**
- **Total Treatment Cost**
- **Out-of-Pocket Expenses**

In total, over 20 measures were created for detailed analysis.

## VISUALIZATIONS
<p align="center">
  <img src="https://github.com/user-attachments/assets/18f8abb1-0bf2-40a1-b0b3-d15639188bd2" alt="1">
</p>


### Tables
- **Patient Density Map:** Visualized patient density across locations, highlighting Edinburgh as the highest density area.

### KPI Cards
- **Demographics KPIs:** Average patients per day, total patients, average patient age, total visits.
- **Financial KPIs:** Total billing, average billing, medication cost, treatment cost, total insurance, room charges etc.

### Charts
- **Stacked Bar Charts:** Insurance Coverage by Demographics.
- **Bar Charts:** Patient Distribution by Age, Gender, Race.
- **Clustered Bar Charts:** Visit Type by Department.
- **Matrix:** Diagnosis & Procedure Correlation.
- **Line Charts:** Peak Service by Months, Quarters, Weekdays, Year.
- **Waterfall Charts:** Cost Breakdown by Department.
- **Scatter Plot:** Cost Distribution by Service.
- **Pie Chart:** Room Charges by Type.

## INSIGHTS

### Demographics Trends
- **Key Insights:** The clinic serves an aging population, with the majority aged 65 and above. Black patients have the highest insurance coverage.
- **Action Plan:** Expand geriatric services and establish a Geriatric Care Unit to cater to the senior population.
<p align="center">
  <img src="https://github.com/user-attachments/assets/f22bb54a-9b8d-4485-826e-31b3c8431733" alt="2">
</p>


### Healthcare Utilization & Patterns
- **Key Insights:** Predominantly outpatient base, with Cardiology leading outpatient visits and Orthopedics in inpatient and emergency services.
- **Action Plan:** Introduce telemedicine options and launch educational initiatives to enhance patient information and accessibility.
<p align="center">
  <img src="https://github.com/user-attachments/assets/94d75816-d838-4466-94cc-152064b97a35" alt="3">
</p>


### Financial Insights
- **Key Insights:** Revenue is substantial with high billing from X-rays and Cardiology. Outpatients contribute significantly to medication and treatment costs.
- **Action Plan:** Implement seasonal promotions, diversify revenue streams with advanced diagnostic services, and launch a Hypertension Management Program.
<p align="center">
  <img src="https://github.com/user-attachments/assets/b90250b2-a454-4c6e-9cf6-e89a7c7ad758" alt="4">
</p>


## CONCLUSION

The analysis reveals crucial insights into patient demographics, healthcare utilization patterns, and financial performance. The clinic should focus on expanding services in Cardiology, Orthopedics, and Geriatrics, while optimizing cost management, particularly in outpatient services, to enhance overall financial performance.
