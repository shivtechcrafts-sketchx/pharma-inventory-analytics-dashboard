# 💊 Pharmaceutical Inventory Analytics Dashboard

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=30&duration=2500&color=1F77B4&center=true&vCenter=true&width=1000&lines=Pharmaceutical+Inventory+Management+Dashboard;Advanced+Plotly+Analytics+Application;Real-World+Healthcare+Data+Insights" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Plotly-Dashboard-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Data-Analytics-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Healthcare-Use--Case-red?style=for-the-badge"/>
</p>

---
View Dashboard : https://94e5bc89-2698-4a37-9d11-c8b3bf0d45e7.plotly.app
------
## 📌 Project Overview

This project is a **fully interactive Pharmaceutical Inventory Management Dashboard** built using **Plotly**.

It simulates a **real-world medical inventory system** used by pharmacies, hospitals, and distributors to:

- Monitor stock levels  
- Track expiry risks  
- Analyze pricing distribution  
- Identify high-value medicines  
- Compare inventory across categories, brands, and suppliers  

> ⚠️ This is **not a toy dashboard** — it reflects how analytics is used in **actual healthcare inventory operations**.

---

## 📸 Dashboard Preview

<p align="center">
  <img src="assets/screenshots/unit_price_distribution.png" width="90%" />
  <img src="assets/screenshots/inventory_summary.png" width="90%" />
  <img src="assets/screenshots/expiry_trend.png" width="90%" />
</p>

---

## 🔍 Key Features

### 📊 Inventory Analytics
- Total inventory value calculation  
- Category-wise & brand-wise breakdown  
- Top medicines by stock value  

### 💰 Pricing Insights
- **Violin plots** for unit price distribution  
- Outlier detection across medication categories  

### ⏳ Expiry Monitoring
- Inventory trends by expiry month  
- Early identification of expiring stock  

### 🔎 Smart Inventory Lookup
- Search medicines by name  
- Filter by category, brand, supplier  
- Sort by price, quantity, expiry date  

### 📈 Pivot & Comparison Analysis
- Dynamic pivot tables  
- Side-by-side category comparison  
- Conditional formatting for quick insights  

---

## 🧪 Dataset Details

- **Total Records:** 500 medicines  
- **Categories:** Tablet, Capsule, Syrup, Injection  
- **Attributes:**  
  - Medicine Name  
  - Category  
  - Brand  
  - Supplier  
  - Unit Price  
  - Quantity  
  - Expiry Date  
  - Batch Number  

> Dataset is designed to mimic **enterprise-level pharmacy inventory data**.

---

## 🛠️ Tech Stack

| Layer | Tools |
|-----|------|
| Visualization | Plotly |
| Analytics | Python |
| Data Modeling | Pandas |
| Dashboard | Plotly Studio |
| Domain | Healthcare / Pharmaceutical Analytics |

---

## 📂 Repository Structure

```bash
pharma-inventory-analytics-dashboard/
│
├── assets/
│   └── screenshots/
│       ├── dashboard_overview.png
│       ├── unit_price_distribution.png
│       ├── expiry_trend.png
│       └── inventory_value.png
│
├── data/
│   └── pharmaceutical_inventory.csv
│
├── README.md
└── LICENSE
