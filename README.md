![Header](https://img.shields.io/badge/Data%20Engineer-AWS%20%7C%20Databricks%20%7C%20PowerBI-blue?style=for-the-badge)

# aws-databricks-sales-pipeline
End-to-end data pipeline project built with AWS, Databricks, and Power BI
# AWS–Databricks Sales Pipeline

Cloud-based ETL pipeline processing Amazon sales data using **AWS S3**, **Databricks (PySpark)**, and **Power BI**.  
Developed as part of my **Data Engineering portfolio**.

---

## 🚀 Architecture
- **Data Source:** Amazon Sales CSV stored in AWS S3  
- **Processing:** Databricks (PySpark, Delta Lake)  
- **Storage Layers:** Bronze → Silver → Gold  
- **Visualization:** Power BI dashboards  
- **Automation:** AWS Lambda + SNS notifications  

📊 ![Pipeline Diagram](docs/pipeline_diagram.png)

---

## 🧠 Key Learnings
- Designed a **modular Medallion architecture**  
- Implemented **data quality checks** before load stages  
- Integrated **Power BI** directly with Delta Lake tables  
- Automated job triggers via **AWS Lambda**  

---

## 🧰 Tools & Technologies
`AWS S3` • `Databricks` • `PySpark` • `Delta Lake` • `Power BI` • `ETL` • `Lambda` • `SNS`

---

## 📁 Project Structure
