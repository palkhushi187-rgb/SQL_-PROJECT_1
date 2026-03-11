# 🍕 Pizza Sales Analysis (SQL Project)

## 📌 Project Overview
Is project mein maine **Pizza Hut** ke dataset ka use karke sales performance ko analyze kiya hai. SQL queries ke zariye business metrics jaise total revenue, pizza distribution, aur customer ordering patterns (hourly/daily) ka pata lagaya gaya hai.


## 🛠️ Database Schema & Tools
- **Database:** `pizzahut`
- **Key Tables:** `orders`, `order_details`, `pizzas`, `pizza_types`
- **SQL Skills:** Joins, Window Functions (RANK, SUM OVER), CTEs/Subqueries, Aggregations, Date/Time Functions.

---

## 📊 Key Insights & Queries

### 1. Basic Analysis
* **Total Orders:** Orders ki total counting.
* **Total Revenue:** Har pizza ki price aur quantity ko multiply karke total sales nikali gayi.
* **Highest-Priced Pizza:** Sabse mehenga pizza dhoonda gaya.

### 2. Intermediate Insights
* **Hourly Distribution:** Pata lagaya gaya ki din ke kis ghante mein sabse zyada orders aate hain.
* **Average Daily Orders:** Rozana average kitne pizzas order ho rahe hain.
* **Top 5 Best Sellers:** Quantity ke hisaab se top 5 pizza types.

### 3. Advanced Business Metrics
* **Revenue Contribution:** Har category (Veg, Non-Veg, etc.) ka total revenue mein kitna percentage share hai.
* **Cumulative Revenue:** Time ke sath revenue kaise grow kar raha hai (Running Total).
* **Top 3 by Category:** Har category ke andar top 3 performing pizzas (using Window Functions).

---

## 🚀 How to Run the Queries
1. MySQL Workbench ya koi bhi SQL editor open karein.
2. Dataset tables (`pizzas`, `orders`, etc.) ko import karein.
3. `SQL_PROJECT 1.sql` file ko load karein aur queries execute karein.

---

## 📂 Project Structure
* `SQL_PROJECT 1.sql`: Saari queries ka main script.
* `README.md`: Project ki details aur documentation.

---
