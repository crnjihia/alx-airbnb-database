### 📘 README.md (for `database-adv-script` folder)

````markdown
# Advanced SQL and Database Optimization — Airbnb Clone (ALX)

This directory contains advanced database scripting and performance optimization tasks for the **ALX Airbnb Database Module**. It focuses on simulating real-world scenarios involving large datasets, complex queries, indexing, and partitioning, designed to build practical DBA-level SQL skills.

## 📌 Objectives

- Master complex SQL queries (joins, subqueries, aggregations, window functions).
- Implement indexing and partitioning to enhance query performance.
- Use EXPLAIN, ANALYZE, and SHOW PROFILE to monitor and optimize performance.
- Apply real-world optimization strategies for large-scale applications.

---

## 🗂️ Files

| File | Description |
|------|-------------|
| `joins_queries.sql` | SQL scripts demonstrating INNER, LEFT, and FULL OUTER JOIN operations. |
| `subqueries.sql` | Contains both correlated and non-correlated subqueries. |
| `aggregations_and_window_functions.sql` | SQL using COUNT, GROUP BY, and window functions like RANK, ROW_NUMBER. |
| `database_index.sql` | Commands to create indexes on high-usage columns. |
| `index_performance.md` | Performance analysis before and after indexing. |
| `perfomance.sql` | Original and optimized complex query joining multiple tables. |
| `optimization_report.md` | Summary of performance issues and optimization steps taken. |
| `partitioning.sql` | SQL commands to partition the Booking table by `start_date`. |
| `partition_performance.md` | Observations on query performance with and without partitioning. |
| `performance_monitoring.md` | Logs and insights from using EXPLAIN and SHOW PROFILE to monitor and improve database health. |

---

## 🚀 Key Concepts Covered

1. **Entity-Relationship Modeling**: Define relationships between core Airbnb entities.
2. **Complex Joins**: Use INNER, LEFT, and FULL OUTER JOINs to extract insights.
3. **Subqueries**: Nest SELECTs for analytical tasks and filtering.
4. **Aggregations & Windows**: COUNT, SUM, RANK, ROW_NUMBER for deep analysis.
5. **Indexing**: Improve performance with strategic indexing.
6. **Query Optimization**: Analyze and refactor inefficient queries.
7. **Partitioning**: Break large tables into manageable partitions.
8. **Performance Monitoring**: Use SQL profiling tools to fine-tune queries.

---

## ✅ Requirements

- SQL fundamentals: SELECT, WHERE, GROUP BY.
- Understanding of relational database concepts.
- Familiarity with MySQL performance tools (EXPLAIN, SHOW PROFILE).
- GitHub workflow for versioning and submission.

---

## 🧠 Learning Outcome

By completing this module, you will:
- Write production-level SQL for high-volume environments.
- Identify and solve performance issues using real profiling tools.
- Think like a Database Administrator (DBA) when structuring schemas and queries.

---

## 📁 Repo Structure

```bash
alx-airbnb-database/
└── database-adv-script/
    ├── joins_queries.sql
    ├── subqueries.sql
    ├── aggregations_and_window_functions.sql
    ├── database_index.sql
    ├── index_performance.md
    ├── perfomance.sql
    ├── optimization_report.md
    ├── partitioning.sql
    ├── partition_performance.md
    └── performance_monitoring.md
````

---
