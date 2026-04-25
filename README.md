# 🚀 ELEVATE: Enterprise E-Commerce Analytics Dashboard

<div align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/DAX-00599C?style=for-the-badge&logo=dax&logoColor=white" alt="DAX" />
  <img src="https://img.shields.io/badge/Data_Modeling-000000?style=for-the-badge&logo=database&logoColor=white" alt="Data Modeling" />
  <img src="https://img.shields.io/badge/UI%2FUX_Design-FF6F61?style=for-the-badge" alt="UI/UX" />
</div>

## 🎯 Executive Summary
**ELEVATE** is a comprehensive, end-to-end Business Intelligence solution developed to monitor, analyze, and optimize the performance of a large-scale e-commerce business. This project demonstrates advanced capabilities in Data Modeling, complex DAX engineering, and highly intuitive UI/UX design using Power BI.

The dashboard transforms raw transactional data into a 5-pillar analytical narrative: **Executive Overview, Product Analysis, Customer Analysis, Operations, and Returns Analysis.**

## 📊 High-Level Business KPIs
- **Total Revenue:** $6.4M 💰
- **Total Orders:** 10K 📦
- **Total Products Sold:** 28K 🛒
- **Average Order Value (AOV):** $639.24 📈
- **Overall Return Rate:** 0.33% 🔄

---

## 📸 Interactive Dashboard Modules

### 1️⃣ Executive Overview
*A high-level pulse check of the business, featuring monthly revenue trends and top-performing products (MacBook Air M2 & iPhone 15 Pro).*
<img width="1282" height="696" alt="Screenshot 1" src="https://github.com/user-attachments/assets/6440cd1b-5825-4e44-ba78-1ba78e021456" />

### 2️⃣ Product & Supplier Analysis
*Deep dive into category performance. Uncovered that 'Tech Giant' is the dominant supplier generating $4.3M, while mapping product revenue against return rates in a scatter matrix.*
<img width="1274" height="692" alt="Screenshot 2" src="https://github.com/user-attachments/assets/1608894c-a7a8-400d-aed6-df440e9423c2" />

### 3️⃣ Customer Demographics & Value Matrix
*Geographical and behavioral analysis. New York leads with $2.6M in revenue, and average revenue per customer stands at a healthy $12.8K.*
<img width="1275" height="690" alt="Screenshot 3" src="https://github.com/user-attachments/assets/2badea87-b965-4530-8b13-21269a2372d8" />

### 4️⃣ Operations & Fulfillment tracking
*Tracking logistics efficiency. Monitored an 81.0% fulfillment rate, analyzed payment methods (Cash dominates at 65.1%), and evaluated carrier performance (FedEx & UPS average 1 day, while USPS averages 4 days).*
<img width="1273" height="689" alt="Screenshot 4" src="https://github.com/user-attachments/assets/528a8e4f-07e7-43a4-96ac-81d96b29df3c" />

### 5️⃣ Returns & Refund Diagnostics
*Crucial analysis for loss prevention. Discovered that the 'Beauty' category faces the most returns, primarily driven by the "Changed My Mind" reason, resulting in an 81.8% return rejection rate.*
<img width="1278" height="693" alt="Screenshot 5" src="https://github.com/user-attachments/assets/9751094a-cd9a-49e0-ba4e-b25a75fe285e" />

---

## ⚙️ The Engine: Technical Architecture

### 🔗 Robust Data Modeling
- Designed an optimized **Star Schema** to connect multiple fact tables (Sales, Returns, Operations) with unified dimension tables (Date, Products, Customers, Geography).
- Ensured seamless cross-filtering and high-performance querying across millions of simulated rows.

### 💻 Advanced DAX Engineering
Developed sophisticated DAX measures to calculate dynamic KPIs, including:
- **AOV (Average Order Value):** `DIVIDE([Total Revenue], [Total Orders], 0)`
- **Fulfillment & Rejection Rates:** Context-aware percentage calculations.
- **Dynamic Formatting:** Custom formatting for tooltips and KPI cards.

### 🎨 UI/UX & Interactivity
- **App-Like Navigation:** Built a custom sidebar utilizing Power BI *Buttons* and *Page Navigation* actions.
- **Dark Mode Aesthetic:** Custom color palette designed for reduced eye strain and professional corporate presentation.
- **Interactive Visuals:** Employed scatter plots, treemaps, and synchronized slicers for deep drill-down capabilities.

---

## 💡 Key Strategic Recommendations
1. **Logistics Optimization:** Re-evaluate the USPS contract, as their 4-day average delivery time significantly lags behind FedEx and UPS (1 day), potentially impacting customer satisfaction.
2. **Payment Digitization:** With 65.1% of transactions paid in Cash, the company should incentivize digital payments (Credit Card/PayPal) to reduce handling costs and cash flow risks.
3. **Return Policy Review:** The 'Beauty' category suffers from high returns due to "Changed My Mind". Implementing stricter return policies or better product sampling for this category could save significant operational costs.

<br>
<p align="center"><i>Data Architecture & Analytics by Ibrahim Atya</i></p>
