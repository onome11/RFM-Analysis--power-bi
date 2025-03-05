# 📊 RFM Analysis Project - Power BI

## 📝 Overview
This project demonstrates a full **RFM (Recency, Frequency, Monetary)** analysis conducted with **Power BI** to segment customers based on their purchasing behavior. By calculating **RFM scores** and grouping customers into meaningful segments, this analysis helps businesses identify their most valuable customers and create targeted marketing strategies.

RFM Analysis answers:
- **Recency** – How recently did the customer purchase?
- **Frequency** – How often do they purchase?
- **Monetary** – How much do they spend?

The result is an actionable customer segmentation, such as:
✅ Best Customers  
✅ Loyal Customers  
✅ At-Risk Customers  
✅ Lost Customers  

---

## 🚀 Key Features
- Dynamic **RFM Scoring** using **percentile-based ranking**.
- Customer segmentation with **DAX calculations**.
- Interactive Power BI dashboards.
- Visual insights for better decision-making.
- Scalable model for ongoing customer analytics.

---

## 📊 RFM Process Flow

```mermaid
graph TD
A[Import Sales Data] --> B[Calculate Recency, Frequency, Monetary]
B --> C[Assign RFM Scores (1-5)]
C --> D[Combine into RFM Score]
D --> E[Customer Segmentation]
E --> F[Power BI Dashboard Visualization]
