# 🧸 Maven Toy Sales Analysis Dashboard

An interactive **Power BI** dashboard analyzing sales, profit, product, and store performance for **Maven Toys**, a toy retail chain with 50 stores across Mexico. The report covers January 2022 – September 2023 and helps answer where revenue comes from, which products and categories drive profit, and how store locations perform.

---

## 📸 Dashboard Preview

### Page 1 – Home (Sales Overview)
<img width="1898" height="822" alt="image" src="https://github.com/user-attachments/assets/17fb2a75-27a1-4e53-9b52-54d46cd3f093" />


### Page 2 – Category & Store Sales
<img width="1898" height="815" alt="image" src="https://github.com/user-attachments/assets/9e97b32a-c049-41df-84bd-8c37260469c2" />


> Save your two screenshots in an `images/` folder using the file names above (or update the paths).

---

## 🎯 Objectives

- Track overall business performance (revenue, profit, units, orders, margin)
- Identify top-performing product categories and individual products
- Compare revenue across store locations (Downtown, Commercial, Residential, Airport)
- Analyze monthly, quarterly, and yearly sales trends
- Evaluate store-level performance and inventory metrics

---

## 📊 Key Metrics (Overall)

| Metric | Value |
|---|---|
| Total Revenue | **$14.44M** |
| Total Profit | **$4.01M** |
| Total Units Sold | **1,091K** |
| Profit Margin | **~28%** |
| Total Orders | **829K** |

---

## 🗂️ Dashboard Pages

### 1. Home – Sales Overview
- **KPI cards:** Total Revenue, Total Profit, Total Units, Profit Margin %, Total Orders
- **Line chart:** Total Revenue by Year, Quarter and Month
- **Donut chart:** Total Revenue by Store Location
- **Bar chart:** Total Revenue by Product Category
- **Map:** Total Revenue by Store City across Mexico
- **Slicers:** Store Location, Year

### 2. Category & Store Sales
- **Slicers:** Product Category, Store Location, Year
- **KPI cards:** Total Product Count, Highest Revenue Product, Total Store Count, Sales per Store, Inventory Turnover Rate, Average Inventory
- **Line charts:** Revenue trend by product category and by store location
- **Tables:** Product-level (revenue, profit, profit margin %, order count, cost) and store-level (order count, units sold, average order value, location)

---

## 🔍 Key Insights

- **Downtown stores dominate** with about **$8.22M (56.9%)** of total revenue, followed by Commercial ($3.28M), Residential ($1.66M) and Airport ($1.29M).
- **Toys is the top category** at **$5.09M**, followed by Art & Crafts ($2.71M), Electronics ($2.25M), Games ($2.23M) and Sports & Outdoors ($2.17M).
- **Revenue trend:** monthly revenue dipped to its lowest point (~$489K) around mid-2022 and peaked at roughly $0.88M–$0.89M in early 2023.
- **Games category:** Rubik's Cube brings the highest revenue (~$913K) but a low margin (~10%), while products like Jenga (~70%) and Uno Card Game (~50%) have much higher margins.
- **Games category overall:** ~$2.23M revenue with a ~30% profit margin across 8 products and 157K orders.

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** – dashboard design and visualization
- **DAX** – calculated measures (Profit Margin %, Sales per Store, Inventory Turnover Rate, Average Inventory, Highest Revenue Product)
- **Power Query** – data cleaning and transformation
- **Data modeling** – relational model across `sales`, `products`, `stores`, and `inventory` tables
- **Design** – custom color theme, slicer buttons, drill-down by Year → Quarter → Month

---

## 🗃️ Data Model

| Table | Description |
|---|---|
| `sales` | Transaction-level sales records (date, store, product, units) |
| `products` | Product name, category, cost and price |
| `stores` | Store name, city, and location type |
| `inventory` | Stock on hand per store and product |
| `Measure` | Table holding all DAX measures |

**Dataset source:** [Maven Analytics – Toy Sales Data](https://mavenanalytics.io/data-playground) (Maven Toys, Mexico)

---

## 📁 Repository Structure

```
Maven-Toy-Sales-Dashboard/
│
├── Maven_Toy_Sales.pbix        # Power BI report file
├── data/                       # Source CSV files (sales, products, stores, inventory)
├── images/                     # Dashboard screenshots
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Maven_Toy_Sales.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to the `data/` folder and click **Refresh**.
4. Use the slicers (Product Category, Store Location, Year) to explore the report.

---

## 💡 Business Recommendations

- Invest more in **Downtown** locations and consider replicating their success factors in Residential and Airport stores.
- Promote **high-margin products** (e.g., Jenga, Uno) over high-revenue, low-margin items like Rubik's Cube.
- Plan inventory and marketing around the **early-year demand peak** and the mid-year slowdown.

---

## 👤 Author

**Chaitanya Darekar**
Data Analyst | SQL • Python • Power BI • Excel • Tableau

- 🔗 LinkedIn: [chaitanyadarekar](https://www.linkedin.com/in/chaitanyadarekar02)
- 💻 GitHub: [ChaitanyaDarekar2002](https://github.com/ChaitanyaDarekar2002)
- 🌐 Portfolio: [chaitanyadarekar2002.github.io](https://chaitanyadarekar2002.github.io)
- 📧 Email: chaitanyadarekar2002@gmail.com

---

⭐ If you found this project useful, consider giving it a star!
