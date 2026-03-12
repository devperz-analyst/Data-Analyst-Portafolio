# Project 2: Customer Segmentation (RFM Analysis)

## Objective
To classify customers into meaningful segments based on their purchase behavior, enabling personalized marketing strategies and improved customer retention.

## Tools Used
- **SQL:** Data extraction and aggregation from a simulated relational database.
- **Excel:** RFM analysis, pivot tables, and dashboard visualization.

## Process
1. **Data Extraction (SQL):**
   - Wrote SQL queries with joins and aggregations to extract customer purchase history (order dates, amounts, frequencies) from a simulated database.
   - Calculated key metrics: Recency (days since last purchase), Frequency (total orders), and Monetary (total spend).

2. **RFM Analysis (Excel):**
   - Imported SQL results into Excel and used formulas to assign RFM scores (1-5) to each customer.
   - Created a composite RFM score to segment customers into groups:
     - **VIP:** High recency, frequency, and monetary value.
     - **Loyal:** Frequent buyers but lower monetary value.
     - **Occasional:** Infrequent buyers with potential.
     - **Lost:** No purchases in a long time.

3. **Visualization:**
   - Built an Excel dashboard with pivot tables and charts to visualize the distribution of customer segments.
   - Added conditional formatting to highlight high-value segments.

## Key Insights (Ejemplo)
- 15% of customers (VIP segment) contribute 45% of total revenue.
- 30% of customers are "Lost" and could be targeted with reactivation campaigns.
- Occasional buyers show potential for upselling if offered loyalty discounts.

## Files
- `sql_queries.sql`: SQL scripts used for data extraction.
- `rfm_analysis.xlsx`: Excel file with RFM calculations and dashboard.
- `README.md`: This file.

## Preview
*(Here you can add a screenshot of your Excel dashboard)*
