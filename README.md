**🌐 Language:** 🇬🇧 English | [🇵🇹 Português](README.pt-PT.md)
# Pizza Sales & Business Performance Analysis | Power BI

### Business Intelligence · Data Analytics · Data Visualization

## Project Overview

This project was developed as part of the Business Analytics and Data Culture course within the Master's Degree in Data Analysis and Decision Support Systems at ISCAC – Coimbra Business School.

The challenge was to develop a Power BI reporting solution for **Pizzaria Italy**, a fictional business scenario based in New Jersey, using a dataset containing one year of pizza sales transactions.

The goal was to transform raw sales data into useful business information, helping management understand sales performance, customer behavior, product demand and operational capacity.

The final solution consists of **five interactive dashboard pages**, each focused on a specific area of business analysis.

## Business Objectives

The analysis was designed to address several management questions:

- How do revenue and order volumes evolve over time?
- Which days and hours experience the highest demand?
- Which products and categories contribute most to revenue?
- What are the typical customer ordering patterns?
- How does demand compare with the restaurant's available seating capacity?
- Where could management identify opportunities to improve sales and operational efficiency?

## Dashboard Pages

### 1. Sales Overview

Provides an overview of the restaurant's commercial performance.

**Main features:**
- Total revenue, pizzas sold and order volume.
- Average order value.
- Best-selling pizza and units sold.
- Revenue trends over time.
- Interactive filters by date, pizza size and category.

![Sales Overview](screenshots/01-sales-overview.png)

### 2. Peak Demand Analysis

Explores customer demand patterns to identify the restaurant's busiest periods.

**Main features:**
- Distribution of orders by hour.
- Identification of the peak demand period.
- Heatmap showing pizza demand by weekday and hour.
- Interactive filters for dates, categories and sizes.

The dashboard identifies **12:00–13:00 as the peak demand hour** in the full-year view, providing useful information for staffing and operational planning.

![Peak Demand Analysis](screenshots/02-peak-demand.png)

### 3. Product & Menu Performance

Analyzes the contribution of individual products and categories to business revenue.

**Main features:**
- Top 5 and bottom 5 pizzas by revenue.
- Relationship between units sold and revenue.
- Product performance by category and size.
- Interactive Decomposition Tree to investigate revenue drivers.
- Dynamic comparisons through filters.

This page can support menu optimization, promotional decisions and the identification of stronger and weaker-performing products.

![Product Performance](screenshots/03-product-performance.png)

The following example demonstrates how product rankings and the Decomposition Tree respond to applied filters.

![Filtered Product Analysis](screenshots/04-product-filtered.png)

### 4. Customer & Order Behavior

Focuses on understanding purchasing patterns and order composition.

**Main features:**
- Average order revenue.
- Average number of pizzas per order.
- Percentage of orders containing two or more pizzas.
- Distribution of orders by number of pizzas.
- Relationship between order size and average order value.

In the full-year view, the dashboard shows:

- **$38.31** average order revenue.
- **2.32** pizzas per order, on average.
- **62%** of orders containing at least two pizzas.

These indicators help characterize customer purchasing behavior and identify opportunities to increase order value.

![Customer and Order Behavior](screenshots/05-customer-behavior.png)

### 5. Capacity & Operations

Examines the relationship between demand and the restaurant's available seating capacity.

The analysis considers a restaurant with **15 tables and 60 seats**, using an assumed one-hour table turnover.

**Main features:**
- Hourly demand versus theoretical table capacity.
- Identification of potential overcapacity periods.
- Table utilization heatmap by weekday and hour.
- Peak utilization and operational pressure indicators.
- Customized tooltips providing additional information.

This analysis helps identify potential operational bottlenecks and supports capacity planning.

Capacity indicators are based on modeling assumptions and should be interpreted as estimates rather than observed table occupancy.

![Capacity and Operations](screenshots/06-capacity-operations.png)

**Custom Tooltip Example**

![Customized Tooltip](screenshots/07-custom-tooltip.png)

## Tools & Techniques

**Main Tool:** Microsoft Power BI

The project demonstrates practical application of:

- Business Intelligence reporting.
- KPI design and monitoring.
- Data visualization and storytelling.
- Interactive filtering and segmentation.
- Time-based sales analysis.
- Product and customer behavior analysis.
- Decomposition Tree visualizations.
- Customized report tooltips.
- Operational performance analysis.

## Business Value

The dashboard was designed to make business performance easier to understand and explore.

By combining sales, product, customer and operational data into a single reporting solution, it supports decisions related to:

- **Sales optimization:** understanding revenue trends and product performance.
- **Operational planning:** identifying peak demand periods.
- **Menu management:** comparing high-performing and low-performing products.
- **Customer insights:** examining purchasing patterns and order composition.
- **Capacity management:** identifying potential periods of operational pressure.

## Project Context

**Institution:** ISCAC – Coimbra Business School

**Degree:** Master's in Data Analysis and Decision Support Systems

**Course:** Business Analytics and Data Culture

**Tool:** Microsoft Power BI

**Dataset Period:** January–December 2015

**Author:** David Ferreira

---

*Academic Business Intelligence project developed to apply data analysis and visualization techniques to business decision-making.*
