# Coffee-Sales

# ☕ Coffee Sales Analysis Dashboard

### 📊 Project Overview

This project presents a **comprehensive analysis of coffee vending machine sales data** to uncover customer purchasing behavior, sales trends, and actionable insights for business decision-making. The analysis was performed using data from **March 2024 to July 2024**, focusing on optimizing product inventory, restocking schedules, and promotional strategies.

---

### 🧠 Executive Summary

The analysis revealed that **Americano with Milk** and **Latte** are the most popular beverages, with **Latte generating the highest revenue**. Peak sales were observed at **10:00 AM and 7:00 PM**, and **Tuesdays recorded the highest sales volume**.

Key findings were visualized through interactive dashboards displaying total sales, payment type distribution, and sales trends over time. Strategic recommendations include optimizing product stocking, focusing promotions on mid-week days, and ensuring reliable card payment systems.

---

### 🗂️ Data Overview

* **Data Period:** March 2024 – July 2024
* **Total Transactions:** 1,133
* **Columns Included:**

  * `date`, `datetime`, `cash_type`, `card`, `money`, `coffee_name`
  * Engineered features: `month`, `day`, `hour`

**Data Preparation Steps:**

* Converted `date` and `datetime` columns into proper datetime format for time-series analysis.
* Replaced missing card values (≈89) based on corresponding cash transactions.
* Verified no duplicate entries.

---

### 📈 Key Visualizations

The Tableau dashboard includes the following visuals:

1. **Revenue by Product** – Latte generates the highest revenue.
2. **Monthly Sales Trend** – Upward trends in Latte and Americano with Milk.
3. **Sales by Day of the Week** – Tuesday leads in total sales.
4. **Sales by Hour of the Day** – Peaks at 10:00 AM and 7:00 PM.
5. **Payment Type Analysis** – 92% of transactions are card payments.

---

### 🔍 Analytical Findings

* **Top Sellers (by Count):**

  * Americano with Milk – 23.65%
  * Latte – 21.45%
* **Highest Revenue Product:** Latte
* **Least Popular:** Cocoa (3.09%) and Espresso (4.32%)
* **Payment Distribution:** 92% Card | 8% Cash
* **Peak Hours:** 10:00 AM and 7:00 PM

---

### 💡 Strategic Recommendations

1. **Inventory & Stocking Optimization**

   * Keep Latte and Americano with Milk well-stocked before peak hours.
   * Reduce low-demand items (Cocoa and Espresso).

2. **Marketing & Promotions**

   * Offer **Tuesday promotions** or discounts to leverage peak demand.
   * Introduce **“Evening Treat” offers** for Cappuccino and Hot Chocolate.

3. **Operational Improvements**

   * Maintain card reader functionality due to dominant card usage.
   * Align restocking schedules before 10:00 AM and 6:00 PM.

---

### 🧮 Tools & Technologies

* **Data Analysis:** Python / Excel / Tableau
* **Visualization:** Tableau Dashboard
* **Techniques Used:** EDA, Time-Series Analysis, Sales Trend Analysis

---

### 📘 Conclusion

The project successfully identified high-performing products, customer buying trends, and optimal restocking times. The insights are crucial for improving vending machine efficiency and guiding data-driven marketing strategies.
![Image](https://github.com/ramyaa0805/Coffee-Sales/blob/2315369f8a1dd05ce4fe9bb7c3a1658ceeb5f8b9/WhatsApp%20Image%202025-10-05%20at%2011.57.19_f8c5f0b1.jpg)
