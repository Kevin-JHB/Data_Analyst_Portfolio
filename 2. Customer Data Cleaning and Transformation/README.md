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
  `region` | geographic sales area  
  `product` | product category or SKU  
  `sales_amount` | total sales (USD)  
  `date` | transaction date  

| File | Description | Records | Columns | Notes |
|------|-------------|---------|---------|-------|
| customers_raw.csv | Original messy customer data | 50,000 | 12 | Contains duplicates and missing values |
| customers_clean.csv | Cleaned dataset | 48,750 | 12 | Ready for analysis, sample included for repo |


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
| SQL | Validate data integrity, check duplicates, and perform simple queries for data verification. |
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

