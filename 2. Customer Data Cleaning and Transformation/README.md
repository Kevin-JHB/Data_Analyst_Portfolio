# Customer Data Cleaning and Transformation

## Objective
Standardize and clean a messy customer dataset to ensure reliability for analysis, reporting, and actionable insights.

---

## Dataset
- **Source:** Public dataset or internal CRM export.  
- **Note:** Only a sample dataset included for demonstration.
- **Columns:**
  |Main columns | Description|
  |-|-|
  `PatientId` | Identification of a patient  
  `AppointmentID` | Identification of each appointment  
  `ScheduledDay` | day of the actuall appointment  
  `AppointmentDay` | day someone called or registered the appointment  

| File | Description | Records | Columns | Notes |
|------|-------------|---------|---------|-------|
| Customer_Data_Cleaning_and_Transformation.csv | Original messy customer data | 110.527 | 14 | Contains duplicates and missing values, requires deep cleanning |

https://www.kaggle.com/datasets/joniarroba/noshowappointments


---

## Workflow
1. **Data Import & Inspection** using Python (`pandas`).  
2. **Data Cleaning:** remove duplicates, handle missing values, standardize formats.  
3. **Validation:** SQL queries to verify data quality and integrity.  
4. **Preparation for Analysis:** clean data ready for dashboards, visualizations, and reporting.

---

## Tools

| Tool | Purpose |
|------|---------|
| Python (pandas, numpy) | Data cleaning, transformation, handling missing values, and preparing datasets for analysis. |
| Power BI | Create dashboards and visualizations using the cleaned dataset for reporting and insights. |

---

## Key Insights
- Identified and resolved duplicates, missing fields, and inconsistent formats.  
- Standardized data for accurate analysis and visualization.  

---

## Impact
- Enables reliable reporting and data-driven decision-making.  
- Reduces errors in analytics pipelines.  
- Demonstrates practical skills in SQL, Python, data cleaning, and preparing dashboards.

