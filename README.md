# Superstore Dashboard — Excel

## Business Problem

The main goal of this project was to answer a few practical business questions:

- How is the business performing overall?
- Which categories generate the most sales?
- Which regions are the most profitable?
- How do sales change over time?
- Which products generate the most profit?
- How do different discount levels relate to profit?

The final dashboard brings these analyses together in one interactive view.

---

## Dataset

I used a Superstore sales dataset containing **10,192 orders** across multiple years.

Some of the main columns include:

- Order Date
- Ship Date
- Ship Mode
- Customer Name
- Segment
- Country/Region
- City
- State
- Postal Code
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

## Data Cleaning

Before starting the analysis, I reviewed the dataset column by column and checked the data carefully.

The cleaning and validation process included:

- Checked for duplicate records.
- Checked for blank values.
- Checked categorical values for spelling and consistency.
- Checked numeric columns for invalid values.
- Checked the dates and their logic.
- Removed an unnecessary row-number column.
- Changed Postal Code to the appropriate text format.
- Standardized Order Date and Ship Date to `dd/mm/yyyy`.
- Standardized the Discount field as a percentage.
- Rechecked the dataset after cleaning to make sure everything was consistent.

---

## Dashboard

The final dashboard includes:

- KPI cards
- Sales by Category
- Profit by Region
- Monthly Sales Over Time
- Top 10 Products by Profit
- Profit by Discount Level
- Interactive slicers
- Order Date timeline

The dashboard can be filtered by:

- Segment
- Country/Region
- Ship Mode
- Region
- Order Date

---

## KPIs

The dashboard includes five main KPIs:

| KPI | Value |
|---|---:|
| Total Sales | $2.33M |
| Total Profit | $292.3K |
| Total Orders | 10,192 |
| Profit Margin | 12.56% |
| Average Order Value | $228.2 |

---

## Analysis & Business Questions

### 1. Sales by Category

**Question:** Which product category generates the most sales?

Technology generated the highest total sales among the three main categories.

### 2. Profit by Region

**Question:** Which region generates the most profit?

The West region generated the highest total profit.

### 3. Monthly Sales Over Time

**Question:** How do sales change over time?

Sales increased significantly across the years, with 2026 generating the highest total sales in the dataset. November 2026 was the strongest individual month by sales.

### 4. Top 10 Products by Profit

**Question:** Which products generate the most profit?

A small number of products generated significantly more profit than the other products in the Top 10. The Canon imageCLASS 2200 Advanced Copier was the strongest individual product by profit.

### 5. Profit by Discount Level

**Question:** How do different discount levels relate to profit?

Orders with 0% discount generated the largest total profit. Higher discount levels, particularly 30% and above, were generally associated with negative total profit.

---

## Key Insights

A few things stood out from the analysis:

- **Technology** generated the highest sales among the three main categories.
- **West** was the most profitable region.
- **Consumer** generated the highest total sales among the three customer segments.
- **2026** generated the highest total sales among the years analyzed.
- **November 2026** recorded the highest monthly sales in the dataset.
- The **Canon imageCLASS 2200 Advanced Copier** generated significantly more profit than the other products in the Top 10.
- Orders with **0% discount generated the largest total profit**.
- Higher discount levels, especially **30% and above, were generally associated with negative total profit**.

---

## Business Recommendations

Based on the analysis, I would recommend:

1. **Focus on high-performing categories**
   - Continue monitoring Technology and identify the products driving its strong sales performance.

2. **Investigate regional performance**
   - Look into why the West region generates higher profit and whether successful patterns can be applied to other regions.

3. **Review discount strategies**
   - Reevaluate high discount levels, especially 30% and above, because they are associated with negative total profit.

4. **Monitor high-profit products**
   - Identify what makes the most profitable products successful and consider whether similar products could be prioritized.

5. **Use sales trends for planning**
   - Use historical monthly sales patterns to support future inventory, marketing, and sales planning.

These recommendations are based on the patterns found in the dataset. Further analysis would be needed before making major business decisions because the analysis shows relationships in the data but does not prove causation.

---

## Tools & Skills Used

- Microsoft Excel
- Excel Tables
- Excel Formulas
- PivotTables
- PivotCharts
- Slicers
- Timeline
- KPI Calculations
- Data Cleaning
- Exploratory Data Analysis
- Dashboard Design
- Business Insights

---

## What I Learned

This project helped me practice the complete process of working with data in Excel:

**Raw Data → Cleaning → Analysis → Visualization → Business Insights**

More importantly, I learned that building a dashboard is not just about making charts look good. The important part is starting with a business question, choosing the right analysis, and then using the appropriate visualization to communicate the result.

This project also helped me become more comfortable with PivotTables, PivotCharts, slicers, KPI calculations, and turning analysis into a clear dashboard.
