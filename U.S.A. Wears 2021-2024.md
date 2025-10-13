# 🧥 USA Wears Sales Power BI Dashboard (2021–2024)

<iframe title="wears_dashboard" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMWRhMDAwYzMtNGUzNi00M2VlLWEzMDQtMzBkZDA5N2NmZjg5IiwidCI6ImE0NjIyOWM3LTIxZDEtNDE3ZC1hMWNiLTE4NTdhMDdkMjc2NSIsImMiOjh9&pageName=aa222d1e2d133e37710a" frameborder="0" allowFullScreen="true"></iframe>

<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiMWRhMDAwYzMtNGUzNi00M2VlLWEzMDQtMzBkZDA5N2NmZjg5IiwidCI6ImE0NjIyOWM3LTIxZDEtNDE3ZC1hMWNiLTE4NTdhMDdkMjc2NSIsImMiOjh9&pageName=aa222d1e2d133e37710a" target="_blank">
    <img src="https://img.shields.io/badge/🔍 Explore%20Dashboard%20Live-blue?style=for-the-badge" alt="Explore Dashboard Live">
  </a>
</p>


---

## 📘 Project Overview
This Power BI dashboard visualizes **US Wears Sales Performance (2021–2024)**, focusing on **2022** for detailed analysis.  
It provides insights into sales, profit, quantity, and customer distribution across regions, products, and sales channels.  
The main goal is to **analyze sales growth trends** and **enhance data-driven retail strategy decisions**.

---

## ⚙️ Data Preparation & Modeling

**Data Source:**  
The dataset consists of transactional wear sales records from multiple US regions, including fields like:
`Order ID, Order Date, Customer ID, Product, Sales Channel, Quantity, Price, Profit, Revenue, Region, and State`.

**Data Cleaning Process:**
1. Imported dataset into Power BI.
2. **Checked and corrected data types** (especially `Order Date` to *Date* format).
3. Removed **null rows** (there was one empty line after each record).
4. Created a **Calendar Table** (from 2021 to Today) and linked it to the `Order Date` column.
5. Built a **Measures Table** containing key DAX measures such as:
   - Total Revenue  
   - Total Profit  
   - Profit Margin  
   - Total Quantity  
   - Total Orders  
   - Total Customers  
   - Year-over-Year (YoY) Growth %

---

## 🧭 Dashboard Structure

The dashboard is divided into **three main report pages (sheets):**

---

### **1️⃣ Overview Sheet**
**Purpose:** High-level performance summary for 2022.

#### 📊 Key Performance Indicators
| Metric | Value (2022) | YoY Change | Observation |
|--------|---------------|------------|--------------|
| **Total Revenue** | $231.39K | ▲ 15.42% | Strong revenue growth year-over-year. |
| **Total Profit** | $69.36K | ▲ 14.68% | Profitable year with stable margins. |
| **Profit Margin** | 29.97% | ▼ 0.64% | Slight drop due to cost or discount factors. |
| **Total Quantity Sold** | 4732 | ▲ 16.55% | Demand increased. |
| **Total Customers** | 1603 | ▲ 37.71% | Strongest YoY growth; expanded customer base. |
| **Total Orders** | 1603 | ▲ 20.98% | One order per customer on average. |

#### 📈 Monthly Revenue Trend
- Peaks: **March ($22.6K)**, **April ($22.6K)**, and **December ($22.9K)**.  
- Dips: **February ($16.7K)** and **September ($15.6K)**.  
➡️ Indicates **seasonal demand**, with boosts during spring and holiday seasons.

#### 🌎 Profit by Region
| Region | Profit | Observation |
|--------|---------|-------------|
| **South** | $20.0K | Top-performing region |
| **West** | $18.6K | Strong secondary region |
| **Midwest** | $17.5K | Moderate |
| **Northeast** | $13.3K | Needs strategic focus |

#### 🛒 Sales by Channel
| Channel | Revenue | Insight |
|----------|----------|---------|
| **Marketplaces** | $65K | Leading revenue source |
| **Pop-ups & Events** | $63K | Close second |
| **Online Store** | $54K | Needs optimization |
| **Retail Stores** | $49K | Lowest performance |

#### 🗺️ Revenue by State
- Nationwide coverage, strongest contributions from **California, Texas, and Florida**.

---

### **2️⃣ Product & Category Analysis**

#### 🥇 Top Selling Products
| Product | Revenue | Profit |
|----------|----------|--------|
| **Jackets** | $59K | $17.4K |
| **Sneakers** | $49K | $14.7K |
| **Backpacks** | $36K | $10.8K |
| **Yoga Mats** | $23K | $6.9K |
| **Socks** | $5K | $1.6K |

➡️ Outerwear (Jackets, Sneakers) are the **key revenue and profit drivers**.

#### 📅 Monthly Revenue Trend
- Consistent pricing (average $45–53 per product).  
- Revenue spikes in **March, April, and December** match the overall sales pattern.

#### 💰 Revenue vs Profit by Product
- Jackets, sneakers, and backpacks show healthy margins.  
- Shirts and socks underperform — possibly due to low pricing or heavy discounting.

---

### **3️⃣ Regional & Channel Analysis**

#### 💹 Profit Margin by Sales Channel
| Channel | Margin | Insight |
|----------|---------|----------|
| **Online Store** | 30.48% | Highest margin |
| **Retail Stores** | 30.42% | Stable profitability |
| **Marketplaces** | 29.81% | Slightly reduced due to fees |
| **Pop-ups & Events** | 29.36% | Higher event costs impact margin |

Margins across all channels are **well-balanced around 30%**.

#### 🏬 Orders by Region
| Region | Orders | Observation |
|---------|---------|-------------|
| **South** | 480 | Highest order volume |
| **West** | 432 | Second strongest |
| **Midwest** | 401 | Moderate |
| **Northeast** | 290 | Lowest |

#### 🥧 Customer Distribution by Channel
| Channel | % of Customers |
|----------|----------------|
| Marketplaces | 27.01% |
| Pop-ups & Events | 26.64% |
| Online Store | 25.2% |
| Retail Stores | 21.15% |

➡️ Customer base is **evenly distributed**, showing **multi-channel strength**.

#### 🗃️ Orders vs Quantity vs Profit by State
- Highest profits: **Missouri, Rhode Island, and Washington**.  
- Smaller states still deliver strong profit margins.  
- Totals align with overall KPIs, ensuring data consistency.

---

## 📊 Summary Insights

| Category | Key Takeaway |
|-----------|---------------|
| **Performance** | 2022 achieved **double-digit growth** in both sales and profit. |
| **Customer Base** | Expanded rapidly (+37.7%), but most customers made only one order. |
| **Regional** | South and West regions dominate; Northeast underperforms. |
| **Channel** | Marketplaces lead in revenue; online store delivers top margins. |
| **Product** | Jackets, sneakers, and backpacks are the best sellers. |
| **Seasonality** | Sales peak during spring and holiday months. |
| **Profitability** | Stable 30% margin across all sales channels. |

---

## 🧠 Recommendations
1. **Boost off-peak sales (Feb–Sep)** using targeted discounts or campaigns.  
2. **Expand top products (jackets, sneakers)** with new styles or bundles.  
3. **Enhance online store marketing** to match marketplace reach.  
4. **Invest in Northeast region growth** through promotions or localized ads.  
5. **Introduce loyalty programs** — since most customers purchase only once.  
6. **Optimize logistics and event costs** to maintain >30% margin.

---

## 🧰 Tools & Technologies
- **Power BI** (data cleaning, modeling, and visualization)
- **DAX Measures** (custom KPIs and YoY analysis)
- **Data Modeling** (Calendar relationship with Order Date)
- **Map Visualization** (Revenue by State)
- **Bar & Line Charts** (Trends and comparisons)

---

## 👩🏽‍💻 Author
**Linda Nciko**  
📊 Data Science & Analytics Graduate (Strathmore University, 2025)  
💼 Experienced in Power BI and Data-Driven Decision Making.  

---

## 📎 Dashboard Access
You can explore the interactive dashboard here:  
🔗 **[Open in Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiMWRhMDAwYzMtNGUzNi00M2VlLWEzMDQtMzBkZDA5N2NmZjg5IiwidCI6ImE0NjIyOWM3LTIxZDEtNDE3ZC1hMWNiLTE4NTdhMDdkMjc2NSIsImMiOjh9&pageName=aa222d1e2d133e37710a)**

---

⭐ *If you found this project insightful, feel free to star the repo and connect!*
