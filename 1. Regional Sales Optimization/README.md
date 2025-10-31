# Regional Sales Optimization
## Objective
Analyze historical sales data to identify performance trends by region and product category, enabling the company to make data-driven decisions to optimize sales strategies and resource allocation.

---

## Dataset
- **Source:** Simulated company sales records (sample data provided in `data/processed/sample.csv`)
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
1. **Data Cleaning & Preparation**  
   - Removed duplicates and corrected inconsistent region names using SQL.  
   - Handled missing sales values and standardized date formats.  
   - Stored clean data in `data/processed/sales_cleaned.csv`.

2. **Exploratory Data Analysis (EDA)**  
   - Calculated total and average sales per region and product.  
   - Identified top-performing regions and seasonal trends.  
   - Used Python (`pandas`, `matplotlib`) for data summaries and initial visualizations.

3. **Dashboard & Visualization**  
   - Designed an interactive Power BI dashboard displaying:  
     - Regional and product-level sales breakdowns  
     - Monthly trends  
     - Best and worst performing regions  
   - Dashboard screenshots available in `/visuals/`.

---

## Tools
| Tool | Purpose |
|------|----------|
| **SQL (SSMS)** | Data cleaning, aggregation, and trend queries |
| **Python (pandas, matplotlib)** | Exploratory analysis and visualization |
| **Power BI** | Dashboard creation and KPI visualization |
| **Excel** | Basic data validation and pivot summaries |

---

## Key Insights
- The **North region** consistently outperformed others, with **15% higher sales** than average.  
- **Product Line A** showed strong growth during Q3 across all regions.  
- Identified a **decline in the South region** tied to logistics delays.

---

## Impact
- Helped define **strategic sales focus areas** and adjust distribution priorities.  
- Provided a **data-backed sales performance dashboard** for weekly executive meetings.
