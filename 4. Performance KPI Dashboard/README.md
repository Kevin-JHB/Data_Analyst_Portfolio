# Performance KPI Dashboard

## Objective
Create an interactive dashboard to track key performance indicators (KPIs) such as revenue, churn, and sales by product, enabling management to make fast, data-driven decisions.

## Dataset
- **Source:** Simulated company sales records (sample data provided in `data/processed/sample.csv`)

| File | Description | Records | Columns | Notes |
|------|-------------|---------|---------|-------|
| customers_clean.csv | Cleaned customer dataset | 48,750 | 12 | Standardized, analysis-ready customer data |
| transactions.csv | Historical purchase transactions | 120,000 | 8 | Includes purchase date, product, quantity, and amount |
| kpi_targets.csv | KPI targets and benchmarks | 36 | 4 | Reference values for comparison in dashboards |

## Workflow
1. **Data Integration:**
   - Combine customer, transaction, and KPI target data.  
3. **Data Aggregation:**
   - Calculate metrics like total revenue, churn rate, and sales per product.  
5. **Dashboard Design:**
   - Build interactive charts and visualizations in Power BI.  
7. **KPI Tracking:**
   - Implement filters and drill-downs to monitor trends over time.  
9. **Presentation:**
    - Summarize insights for stakeholders through dashboards and reports.

## Tools

| Tool | Purpose |
|------|---------|
| Power BI | Create interactive dashboards with filters, visuals, and KPIs |
| Excel | Perform initial data aggregation, pivot tables, and quick calculations |
| SQL | Validate data, aggregate metrics, and prepare datasets for visualization |

## Key Insights
- Revenue and sales trends were clearly visualized by product and region.  
- Identified areas with high churn and low retention.  
- Highlighted products exceeding or underperforming against KPI targets.

## Impact
- Enables fast, informed decision-making for management.  
- Helps identify critical areas for improvement in sales and customer retention.  
- Provides stakeholders with clear, actionable insights through visual dashboards.

