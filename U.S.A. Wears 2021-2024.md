# 🛍️ USA Wears Sales Dashboard (2021–2024)

## 📊 Project Overview
This Power BI project analyzes sales performance for **USA Wears**, a fashion and apparel retailer operating across multiple regions and sales channels between **2021 and 2024**.  
The dashboard provides **real-time insights** into sales, profit, customer distribution, and product performance — helping to optimize marketing, pricing, and inventory strategies.

🔗 **Live Dashboard:**  
<iframe title="wears_dashboard" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMWRhMDAwYzMtNGUzNi00M2VlLWEzMDQtMzBkZDA5N2NmZjg5IiwidCI6ImE0NjIyOWM3LTIxZDEtNDE3ZC1hMWNiLTE4NTdhMDdkMjc2NSIsImMiOjh9&pageName=aa222d1e2d133e37710a" frameborder="0" allowFullScreen="true"></iframe>
---

## 🧠 Objective
To visualize **real-time US wears sales and profit performance** and identify key business insights that can **enhance retail and marketing strategy**.

---

## ⚙️ Data Preparation Process
1. **Data Cleaning**
   - Verified and corrected column data types (especially `Order Date`).
   - Removed null or empty rows after every record.
   - Standardized naming conventions for consistency.

2. **Data Modeling**
   - Created a **Calendar table** spanning 2021–today.
   - Established a relationship between the `Calendar[Date]` and `Wears[Order Date]` columns.
   - Developed a **Measures Table** containing KPIs such as Total Revenue, Total Profit, Profit Margin, Total Orders, and YoY calculations.

3. **Tools Used**
   - Power BI Desktop
   - DAX (Data Analysis Expressions)
   - Power Query Editor
   - Excel (for initial cleaning)
   - Power BI Service (for publishing and sharing)

---

## 📈 Dashboard Pages

### 1️⃣ Overview
- Displays **key KPIs**: Total Revenue, Profit, Margin, Quantity, Customers, and Orders.
- Highlights **monthly revenue trend**, **regional profit**, and **sales by channel**.
- Shows **revenue distribution by state** using an interactive map.

### 2️⃣ Product & Category Analysis
- Visualizes **top-selling and most profitable products**.
- Compares **revenue vs. profit by product category**.
- Tracks **monthly revenue trend and average price per product**.

### 3️⃣ Regional Analysis
- Shows **profit margin by channel**, **orders by region**, and **customer distribution**.
- Includes a detailed **Orders vs Quantity vs Profit by State** table.
- Helps identify regional performance and growth opportunities.

---

## 🔍 Key Insights (Year Selected: 2022)
- **Total Revenue:** $231.39K ▲ +15.42% YoY  
- **Total Profit:** $69.36K ▲ +14.68% YoY  
- **Profit Margin:** 29.97% ▼ -0.64%  
- **Total Customers:** 1603 ▲ +37.71%  
- **Top Regions:** South & West drive the highest profits.  
- **Top Products:** Jackets, Sneakers, and Backpacks lead in both sales and profit.  
- **Best Channels:** Marketplaces generate most revenue, while Online Store yields the highest margins.  
- **Peak Months:** March, April, and December show the strongest sales spikes.  

---

## 🧩 Key Learnings
- Cleaning and modeling data efficiently ensures reliable insights.
- Creating calculated measures enhances report flexibility.
- Effective use of visuals (maps, bars, line charts, KPIs) simplifies storytelling.
- Maintaining consistency in DAX and relationships is essential for scalable dashboards.

---

## 🚀 How to Use
1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Explore the dashboard pages via the navigation buttons.
4. Filter by year (2021–2024) or region to view detailed performance.

---

## 🛠️ Tech Stack
- **Power BI**
- **DAX**
- **Power Query**
- **Excel / CSV Data Source**
- **Microsoft Power BI Service**

---

## 👩🏽‍💻 Author
**Linda N’Ciko**  
🎓 Master’s in Data Science and Analytics – *Strathmore University (2025)*  
💼 Experience with ERP systems (Odoo) and Business Intelligence tools (Power BI, Tableau).  
📍 Focus: Data Analysis | Visualization | Business Insights  

---

## 📂 Repository Structure
