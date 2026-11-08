# Restaurant Order Management Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-Database-blue)
![DAX](https://img.shields.io/badge/DAX-Measures-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An interactive **Power BI + SQL** dashboard that turns raw restaurant data into clear KPIs and visual reports, so managers and business owners can track sales, customer behavior, delivery efficiency, and restaurant performance in one place.

---

## Table of Contents

- [Business Problem](#business-problem)
- [Final Outcome](#final-outcome)
- [Overview](#overview)
- [Purpose](#purpose)
- [Tech Stack](#tech-stack)
- [Data Source](#data-source)
- [Features](#features)
- [Key Business Questions](#key-business-questions)
- [Dashboard Walkthrough](#dashboard-walkthrough)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Author](#author)

---

## Business Problem

Restaurant businesses generate large volumes of data on customers, orders, deliveries, ratings, and revenue. This data is usually stored in raw or unorganized form, which makes it hard for managers and owners to evaluate performance and make informed decisions.

The core problem is the **lack of a centralized analytical system** to monitor key metrics such as total sales, customer behavior, delivery efficiency, restaurant performance, and revenue growth.

## Final Outcome

The project delivers a scalable, user-friendly analytical dashboard that improves operational monitoring, business understanding, customer analysis, and restaurant performance evaluation through data visualization and KPI tracking.

## Overview

The Restaurant Order Management Dashboard is a database-driven project built with **Power BI** and **SQL**. It stores and models customer information, restaurant details, order records, and date-based transactions, then analyzes orders, customer behavior, delivery performance, and revenue trends using visuals and DAX calculations.

It helps businesses:

- Monitor KPIs at a glance
- Identify top-performing restaurants
- Analyze customer retention
- Improve operational efficiency

## Purpose

To simplify decision-making by converting raw database records into meaningful charts, graphs, and performance indicators. Instead of reading tables, users can spot trends, compare restaurants, and understand ordering behavior through visual reports.

## Tech Stack

| Technology | Role |
|------------|------|
| 📊 **Power BI Desktop** | Main platform for report and dashboard creation |
| 🗄️ **SQL** | Database layer for storing and managing customer, restaurant, order, and date data |
| 📂 **Power Query** | Data cleaning and transformation |
| 🧠 **DAX** | Calculated measures, dynamic visuals, and conditional logic |
| 🔗 **Data Modeling** | Table relationships enabling cross-filtering and aggregation |
| 📁 **File Formats** | `.pbix` for development, `.png` for dashboard previews |

## Data Source

- **Platform:** Kaggle
- **Dataset type:** Restaurant and customer data
- **Scale:** 30K+ restaurants worldwide, including location, price, rating, votes, cuisine, and more

> Dataset link: *(add the direct Kaggle dataset URL here)*

## Features

- Business KPI monitoring
- Revenue analysis
- Order tracking and analysis
- Delivery performance monitoring
- Customer behavior analysis
- Restaurant performance evaluation
- Data categorization and filtering
- Time intelligence analysis
- Interactive visualizations (slicers, drill-downs, cross-filtering)

## Key Business Questions

This dashboard answers questions such as:

1. How many total orders were placed?
2. What is the total revenue generated?
3. What is the average order value?
4. Which restaurants perform the best?
5. Which restaurants have the highest ratings?
6. How efficient is the delivery system?
7. What percentage of orders are delayed?
8. What percentage of orders are cancelled?
9. How many customers are repeat customers?

...and more.

## Dashboard Walkthrough

### 1. Executive Overview
High-level KPIs: total orders, total revenue, average order value, and overall trends.

![Executive Overview](Executive%20Overview.png)

### 2. Customer Analysis
Customer behavior, ordering patterns, and repeat-customer insights.

![Customer Analysis](Customers%20Overview.png)

### 3. Delivery and Operations
Delivery efficiency, delayed orders, and cancellation rates.

![Delivery and Operations](Delivery%20and%20operational.png)

### 4. Advanced Insights
Deeper analysis of restaurant performance, ratings, and time-based trends.

![Advanced Insights](Advance%20Insights.png)

## Project Structure

```
Restaurant-Order-Management-Dashboard/
├── Restaurant Order Management.pbix   # Power BI report file
├── Executive Overview.png
├── Customers Overview.png
├── Delivery and operational.png
├── Advance Insights.png
└── README.md
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Restaurant-Order-Management-Dashboard.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
3. Open the `.pbix` file in Power BI Desktop.
4. If prompted, update the data source path or refresh the data.
5. Explore the dashboard pages using the slicers and filters.

## Author

**Your Name**

- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-profile)
