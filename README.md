# 🛒 Enterprise Sales Data Warehouse & BI Dashboard

### *Architecting a Scalable Star Schema for Global Retail Analytics*

## 🌟 Project Overview

This project demonstrates the end-to-end development of a **Data Warehouse** utilizing the Northwind Sales dataset. The objective was to transform a transactional database into a high-performance analytical environment, enabling stakeholders to track revenue drivers and seasonal demand shifts through **Power BI**.

## 🚀 Key Results & Outcomes

* **Seasonal Revenue Optimization:** Identified a critical revenue peak in April (exceeding **$190,000**) and established June as a consistent off-peak period, providing a baseline for inventory forecasting.


* **High-Value Product Analysis:** Isolated "Côte de Blaye" as the top-performing product, contributing over **$149,000** to total revenue.


* **Data Integrity & Outlier Detection:** Conducted rigorous data profiling to detect and resolve order anomalies, such as individual transactions exceeding **$17,000**, ensuring high forecast accuracy.


* **Historical Performance Tracking:** Successfully modeled and visualized over **51,000 units sold** across a three-year period (1996–1998).



## 🛠️ Technical Implementation

### **1. Data Architecture (Star Schema)**

* Designed and deployed a robust **Star Schema** to optimize query performance.


* **Fact Table:** `FactSales` containing metrics like Quantity, Unit Price, and Discount.


* **Dimension Tables:** `DimCustomers`, `DimProducts`, `DimDate`, and `DimSuppliers` for multi-dimensional analysis.



### **2. ETL & Data Profiling**

* **Profiling:** Used SQL and Excel to assess data completeness and uniqueness across the dataset.


* **Cleansing:** Standardized inconsistent records and handled 64 missing values using mean imputation to ensure 100% data integrity.



### **3. Business Intelligence Dashboard**

* Developed an interactive **Power BI Dashboard** with dynamic filters for Year, Month, and Product Category.


* Implemented **Heatmaps** and **Time-Series Charts** to provide a real-time view of shifting top-10 product performances annually.



## 📂 Repository Structure

```text
├── documentation/      # Star Schema design documents and Data Profiling reports
├── images/             # Power BI dashboard screenshots and Schema diagrams
├── README.md           # Project documentation
└── Northwind_BI.pbix   # Power BI project file

```

## 📥 Getting Started

1. **Database:** Execute the SQL scripts in the `/data` folder to view the Star Schema structure.
2. **Dashboard:** Open `Northwind_BI.pbix` in Power BI Desktop to interact with the sales analytics.

---
