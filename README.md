# 🍕 Pizza Sales Analysis Project

This project demonstrates how to analyze sales data using **SQL** for data preparation and **Power BI** for interactive visualization.  
👉 Project is based on the tutorial from **YouTube channel [Data Tutorials]**.

---

## 📂 Project Structure

```
Pizza-Sales-Project/
│
├── data/  
│   └── pizza_sales.csv                # Dataset
│
├── sql/  
│   └── PIZZA SALES SQL QUERIES.docx   # SQL scripts used for analysis
│
├── powerbi/  
│   └── Pizza Sales Dashboard.pbix      # Power BI dashboard
│
└── README.md
```

---

## ⚙️ Data Processing with SQL

All queries are written against the dataset **`pizza_sales.csv`**, which is imported into a database table named **`pizza_sales`**.

### Key Analyses

1. **KPIs**

   * Total Revenue
   * Average Order Value
   * Total Pizzas Sold
   * Total Orders
   * Average Pizzas per Order

2. **Trends**

   * Daily trend of total orders
   * Monthly trend of total orders

3. **Sales Distribution**

   * % of sales by pizza category
   * % of sales by pizza size
   * Total pizzas sold by category

4. **Top/Bottom Performers**

   * Top 5 & Bottom 5 pizzas by revenue
   * Top 5 & Bottom 5 pizzas by quantity
   * Top 5 & Bottom 5 pizzas by total orders

👉 See [PIZZA SALES SQL QUERIES.docx](sql/PIZZA%20SALES%20SQL%20QUERIES.docx) for the full list of queries.

---

## 📊 Power BI Dashboard

The **Pizza Sales Dashboard** provides an interactive view of the above KPIs and trends.
Key features:

* Overview of revenue, order volume, and pizzas sold.
* Dynamic filters by pizza size and category.
* Visuals for top/bottom performing products.

📌 Open `Pizza Sales Dashboard.pbix` in **Power BI Desktop** to explore.

---

## 🚀 How to Use

1. Import `pizza_sales.csv` into your SQL database as table `pizza_sales`.
2. Run the queries in `PIZZA SALES SQL QUERIES.docx` to reproduce the aggregated tables.
3. Open `Pizza Sales Dashboard.pbix` in Power BI Desktop.
4. Connect the dashboard to your dataset (if needed).
