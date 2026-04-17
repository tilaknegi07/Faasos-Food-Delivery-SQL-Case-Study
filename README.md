# 🍽️ Faasos Food Delivery SQL Case Study

## 📌 Project Overview

This project is a **SQL case study based on Faasos (Rebel Foods)** food delivery data. It focuses on analyzing customer orders, driver performance, and delivery efficiency using structured SQL queries.

The goal is to simulate real-world business problems and extract meaningful insights from raw data.

---

## 🏢 About Faasos

Faasos is a popular Indian food delivery brand known for its wraps and rolls. This dataset mimics its order and delivery system, helping practice real-world data analysis scenarios.

---

## 🗂️ Database Structure

The database consists of 6 core tables:

### 🔹 `driver`

Stores driver registration details.

### 🔹 `ingredients`

Contains all ingredients used in rolls.

### 🔹 `rolls`

Defines types of rolls (Veg / Non-Veg).

### 🔹 `rolls_recipes`

Maps rolls to their ingredients.

### 🔹 `customer_orders`

Captures customer order details including customizations.

### 🔹 `driver_order`

Tracks delivery status, distance, duration, and cancellations.

---

## ⚙️ Key Concepts Used

* Data Cleaning & Transformation
* Handling NULL and inconsistent values (`NaN`, blanks)
* String manipulation (`REPLACE`, `TRIM`, `LOWER`)
* Type casting (`CAST`)
* Window functions (`ROW_NUMBER`)
* Common Table Expressions (CTEs)
* Aggregations & Grouping

---

## 📊 Business Problems Solved

### 🔹 A. Order & Sales Metrics

* Total number of rolls ordered
* Unique customers count
* Successful deliveries by each driver
* Most ordered roll types
* Orders with vs without customization
* Hourly order distribution
* Daily order trends

---

### 🔹 B. Driver & Delivery Insights

* Average pickup time per driver
* Relationship between order size and preparation time
* Average distance traveled per customer
* Delivery time variability (longest vs shortest)
* Average delivery speed per driver
* Driver success rate (delivery completion %)

---

## 🧹 Data Cleaning Highlights

* Standardized `distance` (e.g., '20km', '23.4 km' → numeric)
* Converted `duration` into minutes
* Handled `NULL`, empty strings, and `'NaN'` values
* Cleaned inconsistent cancellation labels

---

## 📈 Key Insights

* Peak ordering hours and busiest days
* Driver efficiency and performance differences
* Impact of order customization on preparation time
* Delivery delays and operational bottlenecks

---

## 🚀 How to Use

1. Run the SQL script to create tables and insert data
2. Execute analytical queries step-by-step
3. Modify queries to explore additional insights

---

## 🛠️ Tech Stack

* SQL (PostgreSQL / MySQL)
* Data Analysis Techniques

---

## 💡 Future Enhancements

* Build interactive dashboards using **Power BI / Tableau**
* Perform advanced analysis using **Python (Pandas)**
* Add indexing and query optimization
* Convert into end-to-end data pipeline project

---

## 👤 Author

**Tilak Negi**
Aspiring Data Analyst
Skills: SQL | Python | Power BI | Excel

---

