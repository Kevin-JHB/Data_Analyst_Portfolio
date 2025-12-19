# Regional Sales Optimization
## Objective
Analyze historical sales data to identify performance trends by region and product category, enabling the company to make data-driven decisions to optimize sales strategies and resource allocation.

---

## Dataset
- **Source:** Simulated company sales records

(sample data provided in `https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?select=Sample+-+Superstore.csv`)
  
| File | Description | Records | Columns | Size | Purpose |
|------|-------------|---------|----------|-|-|
| `Superstore Dataset.csv` | Raw data exported | 9,994 | 21 | 2,03 MB | 4 year's base market dataset |

---

## Workflow
 [Check on the analysis](https://github.com/Kevin-JHB/Data_Analyst_Portfolio/blob/main/1.%20Regional%20Sales%20Optimization/notebooks/Regional_Sales_Optimization.ipynb)
1. **Data Cleaning & Preparation**  
   - Removed duplicates and corrected inconsistent naming using SQL.  
   - Ensured consistency and standardized data formats.  
   - Stored clean data in `data/processed/Superstore_Dataset_Cleaned.csv`.

2. **Exploratory Data Analysis (EDA)**  
   - Calculated total and average sales per region and product.
   - Obtained Profit Margin by Product Category  
   - Identified top-performing regions and seasonal trends.  

3. **Dashboard & Visualization**  
   - Designed an interactive Power BI dashboard displaying:  
     - Regional and product-level sales breakdowns
     - Top Product Categories  
     - Monthly trends  
     - Best and worst performing regions  
   - Dashboard screenshots available in `/visuals/`.

---

## Tools
| Tool | Purpose |
|------|----------|
| **SQL (SSMS)** | Data cleaning, aggregation, and trend queries |
| **Power BI** | Dashboard creation and KPI visualization |

---

## Key Insights
- The South Region shows the highest revenue and profit margin.

- Tecnology and Office Supplies categories show the highest performace across regions.

- Seasonal spikes observed in September, November and December.

- Profitability strongly correlates with discount rates.

---

## Business Impact
- Optimize product pricing to improve profit margins.

- Adjust inventory based on seasonal sales patterns.

- Focus training for sales teams in low-performing areas.
