# sql-analytics-cheat-sheet
sql · data-analytics · business-intelligence · data-science · cheat-sheet · data-warehouse · analytics

# 📊 SQL Analytics Cheat Sheet Hub

Welcome to my personal SQL repository! This project serves as a structured, production-ready resource hub containing optimized SQL queries for business intelligence, product analytics, and data warehouse workflows.

## 📌 Repository Purpose
As a Data Analyst, I built this repository to document advanced SQL query patterns that solve real-world business problems. Instead of rewriting complex logic from scratch, this hub organizes reusable templates by specific analytical domains.

---

## 🗺️ Index of SQL Analytics Topics

Click on any topic below to view the dedicated SQL code script and implementation details:

*   **[01. Conditional Aggregations](sql-topics/01_aggregations.sql)**
    *   *What's inside:* Pivoting metrics dynamically, grouping data by custom ranges, and calculating segmented Customer Lifetime Value (LTV).
*   **[02. Advanced Window Functions](sql-topics/02_window_functions.sql)**
    *   *What's inside:* Running totals, Month-over-Month (MoM) growth metrics, and tracking rolling data windows.
*   **[03. Cohort & Retention Analysis](sql-topics/03_cohort_analysis.sql)**
    *   *What's inside:* User signup cohorts, tracking retention over time, and active user login trends.

---

## 🛠️ Tech Stack & Database Compatibility
The query patterns documented here are written using standard ANSI SQL and are optimized for major cloud data warehouses and relational databases:
*   **Google BigQuery**
*   **Snowflake**
*   **PostgreSQL**

---

## 🚀 Optimization & Performance Best Practices
Every script in this repository follows strict analytical query standards:
1.  **Filter Early:** Using `WHERE` clauses before execution to scan fewer rows.
2.  **Explicit Columns:** Avoiding `SELECT *` to maintain low database execution costs.
3.  **Readability:** Leveraging Common Table Expressions (CTEs / `WITH` clauses) instead of deeply nested subqueries.

---
💡 *Feel free to fork this hub, explore the scripts in the `/sql-topics` folder, and star the repository if you find these shortcuts helpful!*

