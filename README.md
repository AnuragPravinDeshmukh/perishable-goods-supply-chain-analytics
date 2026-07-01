# Perishable Goods Sales & Waste Analysis Dashboard

📊 **An Interactive Excel Analytics Solution to Optimize Supply Chain Efficiency and Protect Retail Margins.**

---

## 📌 Project Overview
This repository features an end-to-end data analysis project focused on resolving inventory inefficiencies within a perishable goods retail network. By leveraging advanced Excel functions, data modeling, and dynamic visualizations, this project takes raw transactional data and converts it into strategic business intelligence.

The primary objective is to address a critical profitability threat: **a 20.4% inventory wastage rate** that severely compresses the company's average profit margins[cite: 1].

---

## 💼 Business Problem Statement
The organization generates a robust top-line gross revenue of **₹59.11 Crores**, yet the overall Average Profit Margin is heavily compressed at just **₹13.39**[cite: 1]. 

### Key Operational Challenges Addressed:
1. **The Spoilage Leak:** Total Unit Waste has reached **5,201,615 units** against **20,283,565 Total Units Sold**[cite: 1]. Roughly 1 in 5 items stocked results in unrecovered capital[cite: 1].
2. **Revenue Over-Reliance:** Over **68% of total revenue (₹40.78 Crore)** is generated solely by the *Pharmaceuticals* category, creating a risky single-point-of-failure dependency[cite: 1].
3. **Store Performance Disparity:** While `STORE_040` has optimized its local supply chain to achieve peak profits (**₹27.40 Lakhs**), all other stores are underperforming and stagnant (~₹22 Lakhs)[cite: 1].
4. **Product-Specific Spoilage:** Volume-heavy categories like *Frozen Dinners* and *Frozen Desserts* suffer from the highest unit spoilage rates due to a failure in local demand forecasting or cold-chain management[cite: 1].

---

## 🛠️ Repository Structure
The project is organized as follows to match professional consulting and data delivery standards:

*   📂 **`PROBLEM_STATEMENT.md`** - Comprehensive breakdown of the retail and supply chain conflicts[cite: 1].
*   📂 **`dataset/`** - Contains the raw and cleaned `.csv` / `.xlsx` data files used for modeling.
*   📂 **`dashboard/`** - Holds the final interactive Excel workbook showcasing the interactive visuals.
*   📂 **`REPORT.md`** - A deep-dive executive performance report containing structured data findings and strategic operational recommendations[cite: 1].

---

## 📊 Dashboard Features & Architecture
*(As documented in `"C:\Users\Victus\OneDrive\Pictures\Screenshots\Perishable Goods Sales & Waste Analysis Dashboard.png"`)*

The final dashboard was built entirely within **Microsoft Excel** using advanced analytics features:
*   **Executive KPI Cards:** Top-level view of Total Revenue, Total Profit, Average Profit Margin, Total Units Sold, and an orange-highlighted **Total Unit Waste** card to prioritize cost control.
*   **Multi-Layered Slicers:** Interactive filtering by **Category**, **Store ID**, and **Region** to allow stakeholders to run localized root-cause analyses seamlessly.
*   **Cross-Sectional Analytics:** 
    *   *Store VS Profit* & *Profit VS Waste By Store* (Bar/Column charts tracking store efficiencies).
    *   *Category VS Revenue* (Visualizing the massive pharmaceutical dependency).
    *   *Product VS Unit Wasted* (Isolating specific product items driving stock loss).
    *   *Monthly Demand Trend* (Line chart detailing a distinct cyclical dip in October and peak in December).

---

## 📈 Key Data Insights & Recommendations
*   **Implement FEFO (First-Expired, First-Out):** Tailor warehouse dispatch schedules specifically for *Frozen Dinners* and *Frozen Desserts* to clear out older stock before they hit their expiration thresholds[cite: 1].
*   **Clone the `STORE_040` Blueprint:** Audit and replicate the supply chain, inventory handling, and localized discounting practices of the top-performing store across all underperforming branches[cite: 1].
*   **Dynamic Q4 Inventory Planning:** Scale back procurement volumes by **~15-18% heading into the October demand valley**, then ramp up supply aggressively through November to securely fulfill the **December demand peak** without inflating waste counts[cite: 1].

---

## 🚀 How to Interact with the Dashboard
1. Clone this repository to your local machine.
2. Navigate to the `dashboard/` folder and download the Excel file.
3. Open the file in Microsoft Excel and ensure macros/connections are enabled if prompted.
4. Click through the **Slicers (Left panel)** to filter the data by Region, Store, or Product Category to view dynamic updates across all charts.

---
*Developed as part of a professional Data Analysis portfolio to showcase Excel modeling, supply chain optimization, and executive business reporting capabilities.*
