# 🏢 Vendor Performance Dashboard  

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=power-bi&logoColor=black)
![Python](https://img.shields.io/badge/Python-Data%20Processing-3776AB?logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## **📘 Project Title / Headline**  
### **Procurelytics: Vendor Performance & Profitability Dashboard**

An interactive **Power BI Dashboard** that delivers in-depth analysis of **vendor performance, purchase efficiency, and profitability**.  
It consolidates multi-source data (purchases, sales, invoices) to empower **data-driven procurement and pricing strategies**.

---

## **🎯 Short Description / Purpose**

The **Vendor Performance Dashboard** evaluates how effectively vendors contribute to revenue, profit, and inventory movement.  
It helps decision-makers and analysts optimize vendor relationships, manage stock levels, and improve overall business efficiency.

### 💡 **Key Insights Provided**
- 💰 Identify **most and least profitable vendors**
- 📦 Track **stock turnover and excess inventory**
- 📊 Measure **sales vs purchase contribution**
- 📈 Monitor **profit margins, logistics, and freight costs**
- ⚖️ Evaluate **procurement dependency** on top vendors

---

## **🧠 Tech Stack**

| Tool / Technology | Purpose |
|-------------------|----------|
| 📊 **Power BI Desktop** | Data visualization & dashboard creation |
| 🔄 **Power Query (ETL)** | Data extraction, transformation & loading |
| 🧮 **DAX (Data Analysis Expressions)** | KPI calculations & dynamic measures |
| 🗄️ **SQLite Database** | Centralized structured data |
| 🐍 **Python (Pandas, SQLAlchemy)** | Data ingestion, cleaning & summary table creation |
| 📂 **CSV / Excel Files** | Raw input data for purchases, sales & invoices |

---

## **🚀 Features**

✅ **Vendor & Brand Performance:** Sales, purchases, profit & margin tracking  
📈 **Profitability KPIs:** Gross Profit, Profit Margin, Sales-to-Purchase Ratio  
📦 **Stock Turnover:** Detect fast vs slow-moving inventory  
🚚 **Freight & Logistics Costs:** Identify high shipping expenses  
📊 **Pareto (80/20) Analysis:** Measure contribution of top vendors  
🧮 **Statistical Insights:** Correlation, Confidence Intervals, and T-Tests  
🎨 **Interactive Filters:** Analyze by vendor, brand, and category dynamically  

---

## **🖼️ Dashboard Preview**

Here’s a preview of the **Vendor Performance Dashboard** 👇  

![Vendor Performance Dashboard Preview](Screenshot%202025-11-12%20192936.png)

> The dashboard displays **Total Sales**, **Total Purchases**, **Gross Profit**, **Profit Margin**, and **Unsold Capital**,  
> along with key visuals like Purchase Contribution %, Top Vendors/Brands by Sales, and Low-Performing Vendors & Brands.

---

## **🗂️ Dataset & Source References**

📂 **Datasets:**  
- `purchases.csv` – Purchase transactions per vendor  
- `sales.csv` – Sales and revenue records  
- `vendor_invoice.csv` – Freight and invoice data  

🗄️ **Database:** `inventory.db` generated from Python ETL scripts  
📘 **ETL Script:** `ingestion_db.py` – Automates ingestion of CSVs into SQLite  
📊 **Transformation Script:** `vendor_summary.py` – Cleans, merges & creates summary KPIs  

---

## **📊 Key Analytical Insights**

🔹 **Top Vendors by Sales & Profit** – Identify who drives your revenue  
🔹 **Low Inventory Turnover** – Highlight vendors with stagnant stock  
🔹 **Gross Profit vs Sales** – Understand margin patterns  
🔹 **Procurement Dependency** – Track % of total spend by top 10 vendors  
🔹 **Hypothesis Testing (T-Test)** – Compare profit margins across vendor groups  

---

## **⚙️ How It Works**

1. **Data Ingestion:**  
   CSVs from `data/` folder are loaded into SQLite via Python.  
2. **Data Cleaning & Transformation:**  
   Pandas performs aggregation, feature creation, and KPI derivation.  
3. **Database Storage:**  
   Cleaned data stored in `inventory.db` for Power BI connection.  
4. **Power BI Modeling:**  
   Data modeled & related to create visual insights.  
5. **Visualization Layer:**  
   Dashboards built with DAX calculations, slicers, and custom charts.

---

## **📈 Example KPIs in Dashboard**

| Metric | Description |
|--------|--------------|
| **Gross Profit** | TotalSalesDollars – TotalPurchaseDollars |
| **Profit Margin (%)** | (GrossProfit / TotalSalesDollars) × 100 |
| **Stock Turnover** | TotalSalesQuantity / TotalPurchaseQuantity |
| **Sales-to-Purchase Ratio** | TotalSalesDollars / TotalPurchaseDollars |
| **Freight Cost Impact** | FreightCost / TotalPurchaseDollars |

---

## **📎 Statistical Analysis Section**

- 📉 **Correlation Analysis:** Explore relationships between sales, profit & margin  
- 📊 **Confidence Intervals:** Determine precision of profit margin estimates  
- 🧪 **T-Test:** Test significance between top & low performing vendors  

---

## **📚 Summary**

The **Vendor Performance Dashboard** is a **data-driven procurement intelligence tool** that helps organizations:  
✅ Track vendor efficiency and contribution  
✅ Optimize profit margins  
✅ Minimize excess inventory  
✅ Drive smarter purchase and pricing decisions  

---

## **🔗 View Project on GitHub**

👉 [**Click here to view the project**](https://github.com/YourUsername/Vendor-Performance-Dashboard)


