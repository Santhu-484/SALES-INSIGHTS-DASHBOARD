# 📊 Sales Insights Dashboard – Power BI + MySQL + ETL

This project demonstrates a complete **ETL (Extract, Transform, Load)** and **Business Intelligence** workflow. It uses dummy sales data to build a rich, interactive **Sales Dashboard** in Power BI, supported by a **MySQL database** backend.

---

## 🔍 Project Objective

To extract, transform, store, and visualize sales data for business decision-making using:

- ETL Pipeline
- MySQL as the database
- Power BI for analysis and visualization

---

## 📁 Project Workflow

### ✅ Step 1: Data Generation
- Dummy data generated using [Mockaroo](https://mockaroo.com/)
- Columns include:
  - Order ID
  - Timestamp
  - Product
  - Quantity
  - Price
  - Customer Region
  - Payment Method

### ✅ Step 2: Database Setup (MySQL)

```sql
CREATE DATABASE IF NOT EXISTS sales_db;
USE sales_db;

CREATE TABLE IF NOT EXISTS sales (
    order_id INT PRIMARY KEY,
    timestamp DATETIME,
    product VARCHAR(100),
    quantity INT,
    price DECIMAL(10, 2),
    customer_region VARCHAR(50),
    payment_method VARCHAR(50)
);  
```
## ✅ Step 3: Power BI Integration

- Connected **Power BI** directly to the **MySQL** database  
- Performed data cleaning and modeling within Power BI  
- Created dynamic visuals and interactive KPIs for effective data storytelling

---
## 📉 Sales Insight Dashboard

![Screenshot 2025-05-22 193042](https://github.com/user-attachments/assets/502960d6-f1f4-4f36-a779-1b375f4c8b73)



Interactive Power BI dashboard with filters, KPIs, and dynamic visuals

## 📊 Key KPIs and Visuals

| KPI                    | Description                                |
|------------------------|--------------------------------------------|
| 💰 Total Sales         | SUM of all order values                    |
| 📦 Total Orders        | Count of orders                           |
| 📈 Total Quantity      | SUM of quantities sold                    |
| 🌍 Sales by Region     | Performance by customer region            |
| 🛒 Sales by Product    | Top-selling products                      |
| 💳 Payment Methods     | Preferred payment methods                 |
| 🕒 Sales Trend         | Sales over time (Year/Quarter)            |

---

## 🛠️ Tools & Technologies Used

- MySQL – Relational database management  
- Power BI – Data visualization & dashboarding  
- SQL – Data manipulation and querying  
- DAX – KPIs and calculated measures  
- Mockaro – Data generation  
- ETL Concepts – Manual transformation and loading  


## 💡 Insights Gained

- Highest Sales: Q1 2025 with over ₹37,000+  
- Top Product: Shoes
- Top Region: Northeast  
- Popular Payment Methods: Bitcoin and Venmo

---

## 📚 What I Learned

- Building an end-to-end BI pipeline  
- Hands-on experience in ETL workflows  
- Integrating MySQL with Power BI  
- Designing interactive dashboards  
- Writing DAX formulas for dynamic KPIs  

---

## 📎 Future Improvements

- Automate ETL using Python scripts or SSIS  
- Add user segmentation and customer profiling  
- Deploy dashboard via Power BI Service for real-time collaboration
---

## 🏷️ Tags

`#PowerBI` `#SalesDashboard` `#DataVisualization` `#ProductAnalytics` `#SanthoshVoorugonda` `#InteractiveDashboard` `#BusinessIntelligence`

