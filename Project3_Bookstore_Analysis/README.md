# Project 3: Bookstore Sales Analysis

## Objective
To analyze sales data for a fictional bookstore, identifying top-performing authors, best-selling genres, and seasonal sales trends to support inventory and marketing decisions.

## Tools Used
- **SQL:** Database design, data insertion, and complex queries.
- **Power BI:** Data modeling, DAX calculations, and interactive dashboard creation.

## Process
1. **Database Setup (SQL):**
   - Designed a relational database with tables for: `books`, `authors`, `customers`, and `orders`.
   - Populated the database with simulated data (500+ books, 1000+ customers, 5000+ orders) using INSERT statements.
   - Wrote complex SQL queries with JOINs, GROUP BY, and window functions to calculate:
     - Monthly revenue trends.
     - Top 10 best-selling books and authors.
     - Sales distribution by genre and quarter.

2. **Data Modeling (Power BI):**
   - Connected Power BI directly to the SQL database.
   - Built a star schema data model with relationships between tables.
   - Created calculated columns and measures using DAX (e.g., Total Revenue, Revenue by Author, Running Total).

3. **Dashboard Design:**
   - Designed an interactive dashboard with:
     - KPI cards: Total revenue, total orders, average order value.
     - Bar chart: Top 10 authors by revenue.
     - Line chart: Monthly sales trend.
     - Slicers: Genre, year, and quarter filters.

## Key Insights (Ejemplo)
- Fiction and Mystery genres account for 60% of total sales.
- Sales peak in December (holiday season) and dip in January.
- The top 3 authors generate 25% of all revenue.

## Files
- `sql_queries.sql`: SQL scripts for database creation, data insertion, and analysis queries.
- `bookstore_dashboard.pbix`: Power BI dashboard file.
- `README.md`: This file.

## Preview
*(Here you can add a screenshot of your Power BI dashboard)*
