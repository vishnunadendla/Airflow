# Retail Analytics Engineering Pipeline 

A production-style **Modern Data Stack project** demonstrating how to design, orchestrate, and deliver a scalable retail analytics platform with built-in data quality enforcement and executive-ready reporting.

This project simulates a real-world Analytics Engineering workflow — from raw data ingestion to trusted BI dashboards.

---

##  Architecture

**Cloud Platform:** Google Cloud Platform (GCS + BigQuery)  
**Orchestration:** Apache Airflow (Astro CLI, Dockerized)  
**Transformation Layer:** dbt (Dimensional Modeling – Star Schema)  
**Data Quality:** Soda Core (Automated Validation Gates)  
**Visualization:** Power BI (Advanced DAX + KPI Modeling)  
**Metadata & BI Testing:** Metabase  

---

##  End-to-End Data Flow

1. Raw retail CSV data uploaded to **Google Cloud Storage**
2. Airflow DAG orchestrates ingestion into **BigQuery**
3. dbt transforms raw tables into analytics-ready **Fact & Dimension models**
4. Soda enforces automated **data quality checks**
5. Curated datasets power **Power BI executive dashboards**

---

##  Engineering Highlights

- Designed containerized Airflow DAGs for automated ELT workflows
- Built modular dbt transformation models with standardized business KPIs
- Implemented automated data quality gates that halt pipelines on validation failure
- Optimized SQL transformations for performance and scalability
- Delivered executive-level dashboards reducing manual reporting cycles
- Structured project using production-grade development practice

---

##  What This Project Demonstrates

- Modern Data Stack architecture design
- Analytics Engineering best practices
- Data orchestration & workflow automation
- Dimensional modeling for BI scalability
- Data quality governance implementation
- End-to-end ownership from ingestion to insights

---


---

## 📬 Connect

If you’d like to discuss this project or collaboration opportunities, feel free to connect on LinkedIn.
