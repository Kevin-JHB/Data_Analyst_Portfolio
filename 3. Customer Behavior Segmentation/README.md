# Customer Behavior Segmentation

## Objective
Segment customers based on purchase behavior, spending, and preferences to enable targeted marketing strategies and improve retention.

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
| Customer Behavior Segmentation.csv | Cleaned customer dataset from the previous project | 48,750 | 12 | Contains standardized, analysis-ready data |

## Workflow
1. **Data Exploration:**
   - Analyze customer and transaction data to identify relevant features (purchase frequency, amount, categories).  
3. **Feature Engineering:**
   - Create metrics such as total spend, average order value, and purchase frequency per customer.  
5. **Segmentation:**
   - Apply clustering techniques (e.g., K-Means) to group customers with similar behaviors.  
7. **Visualization:**
   - Build dashboards and charts to interpret segments and trends.  
9. **Business Insights:**
    - Identify key customer groups for targeted campaigns.

## Tools

| Tool | Purpose |
|------|---------|
| SQL | Validate customer and transaction data, perform aggregation queries |
| Power BI | Visualize segments and trends for stakeholders |

## Key Insights
- Identified distinct customer segments based on spending, purchase frequency, and product preferences.  
- Recognized high-value customers for VIP campaigns.  
- Detected patterns in purchase behavior and seasonal trends.

## Impact
- Enables personalized marketing campaigns for different customer segments.  
- Helps design strategies to retain high-value and at-risk customers.  
- Provides actionable insights for marketing and sales teams to make data-driven decisions.


