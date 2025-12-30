# Day 37 — 30th Dec 2025

## 🗄️ SQL Progress

### 🔸 Problem Solved  
**Average Time of Process per Machine**

### 🔸 Approach Used
- Grouped records by `machine_id`
- Used **subqueries** to calculate:
  - Average `end` timestamp
  - Average `start` timestamp
- Subtracted the two averages to get processing time
- Used `ROUND()` to format the output

---

### 🔸 Key SQL Concepts Practiced
- Subqueries
- Aggregation with `AVG()`
- `GROUP BY`
- Numeric formatting with `ROUND()`
- Correlated subqueries
---

## 🧩 System Design Concepts

### 🔸 Sharding
- Horizontal partitioning of data across multiple databases
- Each shard contains a subset of rows
- Improves scalability and write performance
- Common sharding keys: user_id, region_id

📌 Used when data volume becomes too large for a single database

---

### 🔸 Vertical Partitioning
- Splitting a table by **columns**, not rows
- Frequently accessed columns stored separately from rarely used ones
- Improves performance and reduces I/O cost
