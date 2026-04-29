# Retail-Inventory-Fuzzy-Logic-Analysis
A hybrid approach to retail sales prediction using Fuzzy Logic (Python) and Interactive Data Visualization (Power BI)


# 🛒 Retail Inventory & Sales Prediction: A Fuzzy Logic Approach

## 🌟 Project Overview
In retail, demand isn't always "Black or White"—it's fuzzy. This project leverages **Fuzzy Logic Inference** to predict sales volumes based on inventory levels, demand forecasts, and promotional activity. I served as the **Data & Visualization Lead**, bridging the gap between raw data insights and the algorithmic backend.

## 📈 Dashboard Preview
![Dashboard Preview](dashboard_preview.png)
*Interactive Power BI dashboard used to validate business logic and explore 73k+ retail records.*

## 🧠 Core Concepts
### Why Fuzzy Logic?
Traditional models struggle with the "gray areas" of retail. We implemented a **Mamdani Inference System** that categorizes variables into 'Low', 'Medium', and 'High' membership functions. This allows for more nuanced predictions than standard linear models.



### Technical Stack
- **Power BI:** ETL, exploratory data analysis, and trend visualization.
- **Python (Scikit-Fuzzy):** Logic engine and rule-based simulation.
- **Scikit-Learn:** Data normalization and performance metrics.

## 🚀 Key Insights from Analysis
- **Promotion Impact:** Identified a significant sales "lift" during promotional periods, justifying our high-weight fuzzy rules for promotions.
- **Performance Metrics:** - **R² Score:** ~0.91 (Our model explains 91% of sales variance).
  - **MSE:** ~0.03 (Low error rate on normalized data).

## 📂 File Structure
- `sales.ipynb`: The Python notebook containing the Fuzzy Logic model.
- `retail_store_inventory.csv`: Dataset containing 73,100 records.
- `inventory_dashboard.pbix`: The full Power BI source file.
