# 🍕 Pizza Sales Data Analysis – MySQL & Excel Project  
<img src="sql_logo.png" alt="SQL" width="50"/> <img src="excel_logo.png" alt="Excel" width="50"/>  

## 📌 Overview
This project presents an **end-to-end sales analysis** for a pizza delivery business, using **SQL** for data extraction and transformation, and **Excel** for visualization, dashboards, and reporting.

The goal was to uncover **sales patterns, customer trends, and product performance** metrics to guide business decisions.  
All insights are generated **only** using SQL queries and Excel workbooks.

---

## 🗄️ Data Source & Structure

**Database Schema:** `pizzahut`  
**Main Table:** `Pizza_Sales`

**Key Columns:**
- `order_id` – Unique ID of each order  
- `order_date` – Date of the order (**stored as text** in `DD-MM-YYYY` format)  
- `order_time` – Time of the order  
- `pizza_name` – Full pizza name  
- `pizza_category` – Category (e.g., Classic, Veggie, Chicken, Supreme)  
- `pizza_size` – Size codes (S, M, L, XL, XXL)  
- `quantity` – Number of pizzas sold in the line item  
- `total_price` – Price × Quantity  

---

## ⚙️ Tools & Technologies
- <img src="sql_logo.png" alt="SQL" width="24"/> **MySQL** – For all querying, data transformation, filtering, and aggregations  
- <img src="excel_logo.png" alt="Excel" width="24"/> **Excel** – For dashboard creation, charts, trend analysis, and final reporting  

---

## 📊 Analyses Performed
1. **Total Revenue** – Overall revenue from sales  
2. **Average Order Value (AOV)** – Revenue per order  
3. **Total Pizzas Sold** – Total quantity sold across all orders  
4. **Total Orders** – Number of unique orders  
5. **Average Pizzas per Order** – Quantity ratio per order  
6. **Daily Trend for Orders** – Order distribution over weekdays  
7. **Hourly Trend for Orders** – Order distribution by hours of the day  
8. **% of Sales by Pizza Category** – Revenue share by category  
9. **% of Sales by Pizza Size** – Revenue share by pizza size  
10. **Pizzas Sold by Category (February)** – Monthly category-wise breakdown  
11. **Top 5 Best Sellers** – Best-selling pizzas by quantity  
12. **Bottom 5 Worst Sellers** – Least-selling pizzas by quantity  

---

## 📂 Suggested CSV Export File Names
When exporting results from SQL to CSV to use in Excel, use descriptive names:

| Analysis                                   | File Name                                 |
|--------------------------------------------|-------------------------------------------|
| Daily Trend for Total Orders               | `daily_order_trends.csv`                  |
| Hourly Trend for Orders                    | `hourly_order_trends.csv`                 |
| % of Sales by Pizza Category               | `pizza_category_sales_percentage.csv`     |
| % of Sales by Pizza Size                   | `pizza_size_sales_percentage.csv`         |
| Total Pizzas Sold by Category (Feb)        | `pizza_category_total_pizzas_sold.csv`    |
| Top 5 Best Sellers                         | `top5_best_selling_pizzas.csv`            |
| Bottom 5 Worst Sellers                     | `bottom5_worst_selling_pizzas.csv`        |

---

## 📤 Process Workflow
1. **Data Cleaning in SQL**  
   - Converted `order_date` (text) to valid date format using `STR_TO_DATE()`  
   - Removed NULL and empty date rows  

2. **Data Aggregation in SQL**  
   - Summarized totals, averages, category & size breakdowns  
   - Ranked best & worst sellers  

3. **Data Export**  
   - Exported query results to CSV files with meaningful names  

4. **Excel Analysis & Dashboards**  
   - Imported CSV into Excel  
   - Created interactive charts (bar charts, pie charts, funnel charts)  
   - Built KPI summary dashboard  

---

## 📌 Insights Gained
- Identified **busiest days** and **peak order times**  
- Discovered that certain pizza sizes or categories contribute more to revenue  
- Pinpointed best & worst-performing pizzas  
- Created **February-specific performance reports** for seasonal trend analysis  

---

## ✅ Conclusion
This project demonstrates how **SQL + Excel** can be combined to perform comprehensive sales analytics without using additional BI tools.  
The results can be easily reused for **dashboards, business reports, and decision-making**.

---

