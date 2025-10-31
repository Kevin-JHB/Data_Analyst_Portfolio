# Monthly Sales Forecasting

## Objective
Analyze historical sales data to generate monthly sales forecasts per product, enabling proactive inventory planning and sales target setting.

## Dataset

| File | Description | Records | Columns | Notes |
|------|-------------|---------|---------|-------|
| transactions.csv | Historical purchase transactions | 120,000 | 8 | Includes purchase date, product, quantity, and amount |
| customers_clean.csv | Cleaned customer dataset | 48,750 | 12 | Standardized, analysis-ready customer data |
| product_list.csv | Product details and categories | 50 | 5 | Reference for sales aggregation by product |

## Workflow
1. **Data Cleaning & Aggregation:**
   - Prepare sales data by product and month.  
3. **Exploratory Analysis:**
   - Identify seasonal trends, peaks, and troughs in sales.  
5. **Forecasting Models:**
   - Apply simple moving averages and basic linear regression to project future sales.  
7. **Visualization:**
   - Present forecasts in charts and dashboards for easy interpretation.  
9. **Validation:**
    - Compare forecasted vs actual sales for accuracy and adjustments.

## Tools

| Tool | Purpose |
|------|---------|
| Excel | Aggregate historical sales, calculate moving averages, and build initial charts |
| Python (pandas, numpy, matplotlib) | Prepare data, perform linear regression, and generate visualizations |
| Power BI | Create interactive dashboards to display monthly sales projections |

## Key Insights
- Identified seasonal trends and high-sales periods for each product.  
- Detected products with consistent growth or decline over time.  
- Forecasting models provide a reliable baseline for monthly planning.

## Impact
- Enables proactive inventory management and sales target setting.  
- Helps stakeholders plan marketing campaigns around high-demand periods.  
- Provides actionable insights for strategic decision-making based on historical trends.

