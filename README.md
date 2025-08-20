# 5-Hour SQL Crash Course

**Goal:** Get practical skills fast — enough to analyze real data, join tables, and write useful queries.


## ⏰ Hour 1: SQL Foundations (`SELECT` + `WHERE`)

### 🧠 Learn

- What is SQL? (Quick 5-min read)
- `SELECT`, `FROM`
- `WHERE` clause (filters)
- Comparison operators: `=`, `!=`, `<`, `>`, `LIKE`, `IN`
- `ORDER BY`, `LIMIT`

### 🔨 Practice

- SQL Bolt Lessons 1–3: [https://sqlbolt.com](https://sqlbolt.com)


## ⏰ Hour 2: Aggregations (`GROUP BY`, `COUNT`, `SUM`)

### 🧠 Learn

- `COUNT` – Count the number of rows in a table
- `SUM` – Sum values in a column
- `AVG` – Average value of a column
- `MIN` / `MAX` – Minimum and maximum values
- `DISTINCT` – Remove duplicates
- `GROUP BY` – Group data before aggregating
- `HAVING` – Filter after grouping

### 🔨 Practice

- SQL Bolt Lessons 4–6: [https://sqlbolt.com](https://sqlbolt.com)


## ⏰ Hour 3: Joins (Combining Tables)

### 🧠 Learn

- `INNER JOIN` – Most common join type
- `LEFT JOIN` – Also very useful
- `ON` conditions (`table1.col = table2.col`)
- Table aliasing (`t1`, `t2`) to simplify queries

### 🔨 Practice

- SQL Bolt Lessons 7–9: [https://sqlbolt.com](https://sqlbolt.com)


## ⏰ Hour 4: Data Manipulation (`INSERT`, `UPDATE`, `DELETE`)

### 🧠 Learn

- `INSERT INTO table (col1, col2) VALUES (...)`
- `UPDATE table SET col = value WHERE condition`
- `DELETE FROM table WHERE condition`
- `DROP` and `TRUNCATE`

### 🔨 Practice

- Insert fake data, update a row, delete a row
- Use [https://sqliteonline.com](https://sqliteonline.com) to experiment live


## ⏰ Hour 5: Project + Real-World Practice

### 🧠 What to Do

Use a dataset from [Kaggle](https://www.kaggle.com) or [Mode SQL Tutorial](https://mode.com/sql-tutorial/) and build 5–10 queries:

- Show top customers by revenue
- List products under $20
- Total orders per day
- Users with no orders (`LEFT JOIN` + `NULL`)
- Add or update a product

### 🔨 Tools

- [LeetCode SQL Easy Problems](https://leetcode.com/problemset/database/)
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)


## ✅ Outcome

By the end of this 5-hour course, you will be able to:

- Analyze and filter data using `SELECT` and `WHERE`
- Summarize with `GROUP BY` and aggregation functions
- Join tables using `INNER` and `LEFT JOIN`
- Insert, update, and delete data
- Solve real-world business problems using SQL
