# Shopify Sales & Customer Funnel Analytics Dashboard

## 📊 Project Overview
This repository contains a comprehensive **E-commerce Sales and Customer Behavior Analysis** developed using **Power BI**. The project leverages a raw Shopify dataset consisting of over 7,400+ transaction records to uncover actionable business insights into revenue trends, customer purchasing frequencies, geographical demand, and product performance.

The final interactive dashboard serves as a vital tool for stakeholders to analyze transaction efficiency, monitor retention rates, and optimize digital marketing spend.

---

## 📈 Key Dashboard Highlights & KPIs
*   **Transaction Performance:** Tracked total Net Sales ($4.18M), total Order Quantity (7,534 items), and calculated a high-level Net Average Order Value ($562.6).
*   **Customer Purchase Behavior:** Segmented the user base into Total Customers (4,431) to contrast Single Order Customers (2,392) directly against Repeat Customers (2,039).
*   **Retention & Value Metrics:** Outlined critical long-term growth indicators featuring a $943.6 Customer Life Time Value (LTV), an optimal 46.02% Repeat Purchase Rate, and a 1.68 Purchase Frequency.
*   **Payment Gateways:** Visualized financial distributions showing `shopify_payments` dominating over 58.45% of total revenue channels, followed by PayPal and Gift Cards.
*   **Geographical Mapping:** Integrated TopoJSON state-level and interactive dot maps highlighting highest-performing markets across top US provinces (e.g., Texas, Florida) and major cities.

---

## 🛠️ Tech Stack & Skills Demonstrated
*   **Data Source:** Multi-column raw Shopify e-commerce data (`Shopify Sales (1).xlsx`).
*   **Data Cleaning & Transformation:** Handled missing entities, set standardized currencies (USD), parsed comprehensive timestamp variants (`Invoice Date`), and built data mappings using Power Query.
*   **Data Modeling:** Managed relationships between customer demographics, regional billing locations, and transaction IDs.
*   **DAX Formulas:** Developed specialized formulas to dynamically compute LTV, retention distributions, and continuous net sales growth rates over dynamic chronological timelines.
*   **UI/UX Design:** Implemented a modern dark-themed interactive layout optimized with filter panels (by Gateways and Provinces) for scannable user navigation.

---

## 📂 Repository Structure
```text
├── Shopify Sales (1).xlsx       # Raw E-commerce Transaction Dataset
├── Shopify_Analytics_Report.pbix # Interactive Power BI Dashboard File
└── README.md                     # Documentation
