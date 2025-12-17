# GlobalRetail

**GlobalRetail** is a complete, practical **end-to-end data engineering project** built on **Databricks**.  
It simulates how modern data teams **design, ingest, process, store, and analyze large-scale retail datasets** using **industry-standard architectures and tools**.

---

## 🛠 Tools Used
- Databricks  
- Delta Lake  
- Databricks SQL  
- Power BI  

---

## 🏗 Architecture Overview

The pipeline follows the **Medallion Architecture (Bronze → Silver → Gold)**:

### 🟤 Bronze Layer
Raw retail data ingested into Databricks with minimal transformation.

### ⚪ Silver Layer
Data cleaned, validated, and standardized using **Delta Lake**.

### 🟡 Gold Layer
Business-ready analytical tables optimized for reporting and dashboards.

### 📊 Analytics & Visualization
Data exposed via **Databricks SQL** and consumed in **Power BI dashboards**.

<img width="1077" height="567" alt="Architecture Diagram" src="https://github.com/user-attachments/assets/433fcc80-40e3-4104-ad70-32d96f5e92e2" />

---

## ✨ Key Features
- End-to-end data pipeline from ingestion to visualization  
- Layered data modeling (Bronze / Silver / Gold)  
- Scalable and maintainable data transformations  
- Analytics-ready datasets for BI consumption  
- Designed to reflect **real-world production data workflows**
