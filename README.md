# E-Commerce Sales & Customer Analytics

**NeST Digital Academy — Real-World Business Analytics Project**

An end-to-end e-commerce analytics project using **Excel, Power Query, MySQL, Python, and Power BI** to transform raw transaction data into actionable business insights. The analysis explores sales performance, customer segments, product demand, discount patterns, city-level performance, and order cancellations and returns.

---

## Project Showcase

<p align="center">
  <img src="https://raw.githubusercontent.com/bibythayyil/bibythayyil/main/assets/E-Commerce_Sales_Dashboard.png" width="100%" alt="E-Commerce Sales and Customer Analytics Power BI Dashboard">
</p>

---

## Business Objective

E-commerce businesses generate large amounts of transaction data, but raw records alone do not provide a clear picture of business performance.

The objective of this project is to analyse e-commerce sales and customer data, identify important performance patterns, and develop interactive dashboards and practical recommendations to support business decision-making.

### Key Business Questions

- How are sales and order volumes distributed across months, product categories, and cities?
- Which products and customer segments contribute most to sales?
- How do different discount levels relate to average order value?
- What proportion of orders are cancelled or returned?
- Which categories require further investigation based on their cancellation and return rates?
- What actions could improve sales analysis, customer retention, and operational performance?

---

## Dataset Overview

The analysis covers e-commerce transactions from 2025.

| Dataset Metric | Value |
|---|---:|
| Unique customers after cleaning | 4,000 |
| Orders after cleaning | 18,000 |
| Products | 30 |
| Cities | 8 |
| Analysis period | January–December 2025 |

The data supports analysis of customer information, order transactions, product categories, sales amounts, discounts, locations, and order status.

---

## Tools & Technologies

| Tool | Application |
|---|---|
| Microsoft Excel | Data inspection, validation, and business analysis |
| Power Query | Data cleaning and transformation |
| MySQL | SQL-based querying and business analysis |
| Python | Exploratory data analysis and visualisation |
| Power BI | Interactive dashboards, DAX measures, and reporting |

---

## Project Workflow

### 1. Data Cleaning & Preparation

Used Excel and Power Query to prepare the data for analysis.

Key activities included:

- Identifying and removing duplicate customer and order records.
- Standardising inconsistent text values in customer segments and order statuses.
- Converting date fields into appropriate date formats.
- Calculating missing net sales values using available transaction fields.
- Reviewing invalid product unit prices and resolving five records using transaction-derived prices.
- Flagging potential outliers and inconsistent signup/order dates for further review.
- Validating customer, product, and location references.

Potential outliers and date inconsistencies were flagged for review rather than automatically removed.

### 2. SQL Analysis — MySQL

Used SQL to explore the cleaned data and answer business questions through queries involving:

- Sales and order aggregations.
- Product and category performance.
- Customer segment analysis.
- City-level sales comparisons.
- Discount patterns.
- Order status and cancellation/return analysis.

### 3. Exploratory Data Analysis — Python

Used Python for data exploration and analytical checks to understand distributions, compare business metrics, and identify patterns that could support further investigation.

### 4. Interactive Dashboard — Power BI

Developed dashboard views to communicate key business metrics and support analysis of:

- Executive sales performance.
- Monthly sales trends.
- Product and category performance.
- Customer segments.
- City-level sales.
- Discount levels and average order value.
- Order completion, cancellation, and return patterns.

DAX measures were used to calculate key metrics and support interactive analysis.

### 5. Business Reporting & Presentation

Consolidated the analysis into a business report and presentation covering the methodology, findings, limitations, and recommendations.

---

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | ₹10.05 crore |
| Total Orders | 18,000 |
| Average Order Value | ₹5,580.63 |
| Completed Orders | 15,797 |
| Completed Order Rate | 87.76% |
| Cancelled Orders | 1,104 |
| Returned Orders | 1,099 |
| Combined Cancellation/Return Rate | 12.24% |

*Sales and order metrics are based on the cleaned 2025 dataset.*

---

## Key Findings

### 1. Sales & Category Performance

- Total sales reached approximately **₹10.05 crore** across 18,000 orders.
- Beauty recorded the highest category sales at approximately ₹2.34 crore.
- Fashion followed with approximately ₹2.30 crore.
- Sports recorded the lowest category sales at approximately ₹1.59 crore.

### 2. Monthly Sales Trends

- January recorded the highest monthly sales at approximately ₹88.15 lakh.
- February recorded the lowest monthly sales at approximately ₹74.35 lakh.
- Sales varied across months without a sustained upward or downward trend.

### 3. Customer Segments

Regular customers accounted for the largest share of order volume, with 9,013 orders, followed by New customers with 6,424 and Premium customers with 2,563.

This highlights the importance of understanding repeat purchasing behaviour alongside customer acquisition and retention.

### 4. Product & City Performance

- Moisturizer recorded the highest sales among individual products, at approximately ₹49.78 lakh.
- Mumbai recorded the highest sales among the eight cities, at approximately ₹1.36 crore.
- Product and city comparisons can help identify areas for further investigation, but sales alone do not establish profitability or future growth potential.

### 5. Discount Patterns

Average order value decreased across the observed discount levels:

- No discount: ₹5,971.73
- 10% discount: ₹5,472.98
- 20% discount: ₹4,968.05
- 30% discount: ₹4,462.33

Higher discount levels were associated with lower average order values in this dataset. This is an observed association and does not establish that discounts caused the decrease.

### 6. Cancellations & Returns

- The combined cancellation and return rate was **12.24%**.
- Sports had the highest combined cancellation/return rate among the five product categories, at approximately 13.69%.
- Beauty had the lowest combined rate, at approximately 11.07%.

Further analysis of return reasons, product quality, fulfilment, and customer feedback would help explain these differences.

---

## Business Recommendations

Based on the observed patterns, the following actions could be investigated:

1. **Review cancellation and return drivers:** Investigate the higher combined rate in Sports and identify whether particular products or operational issues contribute to it.
2. **Evaluate discount effectiveness:** Test targeted discount strategies and assess their impact on order value, sales, and profitability before expanding them.
3. **Improve customer retention analysis:** Examine repeat purchases and customer-level behaviour to develop more meaningful retention strategies.
4. **Investigate product performance:** Evaluate sales alongside margins, inventory levels, and return rates before deciding which products to promote or discontinue.
5. **Compare city performance in context:** Combine sales data with market size, acquisition costs, and customer growth before making expansion decisions.
6. **Strengthen performance monitoring:** Use interactive dashboards to track sales, average order value, customer segments, and order outcomes over time.

---

## Deliverables

The GitHub repository contains the project's main analytical deliverables:

- **Dataset:** Source and/or prepared data files.
- **Excel workbook:** Data cleaning and initial business analysis.
- **SQL file:** MySQL queries for business analysis.
- **Python file:** Exploratory data analysis.
- **Power BI file(s):** Dashboard and analytical reporting.
- **Business report:** Detailed findings, limitations, and recommendations.
- **Presentation:** Summary of the project and its business implications.

Refer to the files in the repository for the complete implementation and supporting analysis.

---

## Skills Demonstrated

- Data cleaning and transformation
- Excel and Power Query
- MySQL and SQL querying
- Python-based exploratory data analysis
- Power BI dashboard development
- DAX measures and KPI calculation
- Data visualisation and business reporting
- Analytical reasoning and interpretation
- Translating data findings into business recommendations

---

## Limitations

- The analysis describes the supplied 2025 dataset and does not independently establish future business performance.
- Observed relationships are associations, not proof of causation.
- Sales figures alone do not measure profitability because product costs and margins are not included in the reported findings.
- Some data-quality issues were flagged for review rather than automatically corrected or removed.
- Recommendations require additional business context and validation before implementation.

---

## About the Project

**Programme:** NeST Digital Academy  
**Project Type:** Real-World E-Commerce Business Analytics  
**Author:** Bibin T S

- GitHub: [@bibythayyil](https://github.com/bibythayyil)
- LinkedIn: [Bibin T S](https://linkedin.com/in/bibints)

---

*This project demonstrates an end-to-end analytics workflow, from data preparation and exploratory analysis to interactive dashboards and business recommendations.*
