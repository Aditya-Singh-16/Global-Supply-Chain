# Global Supply Chain & Business Intelligence Dashboard

An enterprise-style Power BI project: 8 star-schema CSV table,
a measure DAX library, a custom dark-blue executive theme.

## Overview

A full-stack Power BI analytics project simulating an enterprise supply chain BI
solution, covering sales, inventory, logistics, suppliers, customers, and finance
across a 5-year (2022–2026) global operation.

This project models a mid-size global distribution company operating across 25
countries, 12 warehouses, 120 suppliers, and 800 SKUs. It's built entirely on a star-
schema data model — 8 connected CSV tables totaling ~35,800 rows — with a 60+ measure
DAX library powering time intelligence (YTD/MTD/QTD, YoY growth), customer analytics
(CLV, repeat rate), inventory health (turnover, stock coverage), and logistics
performance (on-time delivery %, average transit days).

The dashboard is organized into 8 interconnected pages — Executive, Sales, Customer,
Inventory, Logistics, Supplier, Financial, and Forecast — styled with a custom dark-
navy executive theme, color-coded KPI cards, filled maps, decomposition trees, and
Power BI's native forecasting and Key Influencers AI visuals.

---

## Demo
 
  ### Dashboard
  
  <img width="717" height="430" alt="Screenshot_1" src="https://github.com/user-attachments/assets/75753b1f-6cb6-4668-a83c-bc189eda8180" />
  <img width="717" height="385" alt="Screenshot_2" src="https://github.com/user-attachments/assets/33d9e5f0-d0ef-4466-942f-e6602db12590" />
  <img width="720" height="364" alt="Screenshot_3" src="https://github.com/user-attachments/assets/c54c7cbd-c4c6-4790-b62b-1de94d19af5f" />
  <img width="722" height="371" alt="Screenshot_4" src="https://github.com/user-attachments/assets/846f4e7f-ba4a-4757-ac7d-cfd864227e95" />
  <img width="715" height="376" alt="Screenshot_5" src="https://github.com/user-attachments/assets/3216925a-b54b-47dc-a953-7cdd26efa807" />
  <img width="717" height="389" alt="Screenshot_6" src="https://github.com/user-attachments/assets/3985ea46-41b7-4de7-a8a3-c6b0b50529bb" />
  <img width="718" height="414" alt="Screenshot_7" src="https://github.com/user-attachments/assets/02144167-9aaf-4bce-991b-e5be7a5f2328" />

---

## What it demonstrates :

- **Data modeling**: star schema design, relationship cardinality, role-playing date dimensions
- **DAX**: time intelligence, ranking, running totals, dynamic titles, RANKX/TOPN patterns
- **Data storytelling**: KPI hierarchy, drill-through/drill-down, custom tooltips, bookmarked navigation
- **Design systems**: a reusable Power BI theme file, consistent typography and color logic across 8 pages
- **AI-assisted BI**: forecasting, Key Influencers, and natural-language Q&A visuals

**Tech stack**: Power BI Desktop · Power Query (M) · DAX · CSV-based star schema · custom JSON theming

**Use case framing**: Designed to resemble the kind of internal BI tool used by global
logistics/retail operators (in the spirit of Amazon, Walmart, DHL, or Maersk supply
chain reporting) — suitable as a portfolio piece for data analyst, BI developer, or
supply chain analytics roles.

## 1. Folder Contents

```
data/
  Calendar.csv 
  Warehouses.csv 
  Suppliers.csv 
  Products.csv 
  Customers.csv 
  Sales.csv
  Shipments.csv
  Inventory.csv
dax/
  DAX_Measures.txt
theme/
  ExecutiveDarkBlue_Theme.json                  (light-card, dark-blue-on-white variant)
  ExecutiveDarkNavy_ReferenceMatch_Theme.json    (dark-navy canvas — matches the reference image, use this one)
```

