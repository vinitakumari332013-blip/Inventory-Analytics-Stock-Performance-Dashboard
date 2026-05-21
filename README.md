# 📦 Inventory Analytics & Stock Performance Dashboard

## 🔍 Project Overview
This project is an end-to-end **Inventory Analytics Dashboard** built using **Microsoft Power BI**. The dashboard is designed to help supply chain and retail managers track key performance indicators (KPIs), forecast demand, and optimize stock levels using advanced classification techniques like **ABC and XYZ analysis**. 

By transforming raw inventory data into actionable insights, this tool helps prevent stockouts, reduces excess inventory, and highlights SKUs that require immediate attention.

---

## ⚙️ Key Features & Analytical Techniques

✅ **Dynamic KPI Tracking**
* High-level metrics tracking **Annual Sale Quantity (12.85M)**, **Annual Revenue (420.20M)**, **Total SKUs (303)**, and **Value in Warehouse (77.33M)**.
* **Inventory Turnover Ratio (5.43)** calculation to measure how efficiently inventory is being managed.

✅ **ABC & XYZ Inventory Classification**
* **ABC Analysis (Value):** Categorizes inventory into High Value (A), Medium Value (B), and Less Value (C) based on cumulative revenue share.
* **XYZ Analysis (Demand Volatility):** Categorizes inventory based on demand predictability (Uniform, Variable, Uncertain).
* Interactive matrix visuals showing the distribution of Annual Revenue, Current Stock, and Turnover Ratio across these categories.

✅ **Demand & Revenue Forecasting**
* Time-series line charts tracking historical **Demand Flow** and **Revenue Flow**.
* Built-in forecasting models (visualized with confidence intervals) to predict future demand and revenue trends.

✅ **Automated Reorder Monitoring**
* **Stock Status Breakdown:** A donut chart tracking the exact percentage of SKUs that are In Stock, Out of Stock, or Below Reorder point.
* **SKUs to Reorder Gauge:** A quick-glance gauge chart showing the total number of items needing replenishment.
* **"Need Close Monitoring" Table:** A detailed, drill-down view isolating specific SKUs (like AZ category) with their Annual Sales, Safety Stock, and immediate "Need To Order" status.

---

## 📸 Dashboard Previews

### 1. Demand & Revenue Overview
*Focuses on time-series forecasting, stock status distribution, and overall demand flow.*

### 2. Stock Performance Overview
*Focuses on detailed ABC/XYZ classification matrices and actionable SKU-level monitoring.*

---

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI:** For data visualization and interactive dashboard creation.
* **Power Query:** For data cleaning, transformation, and shaping.
* **DAX (Data Analysis Expressions):** Used to calculate complex metrics such as Inventory Turnover Ratio, cumulative totals, and dynamic ABC/XYZ classifications.

---

## 🚀 How to Use This Dashboard
1. Clone this repository to your local machine.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Use the page navigation tabs at the bottom to switch between the **Stock Performance Overview** and **Demand & Revenue Overview**.
4. Interact with the table filters and visuals to drill down into specific SKU behaviors.

---

## 💡 Business Value
This dashboard acts as a comprehensive decision-support tool. By identifying which items bring in the most revenue (Class A) but have the most uncertain demand (Class Z), businesses can adjust their safety stock dynamically, prioritize capital allocation, and significantly improve their supply chain efficiency.
