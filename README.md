# 🏗️ Sales Data Warehouse & Analytics Project

![Data Warehouse Architecture](docs/data_architecture.png)

---

## 🧱 Project Architecture

This project is designed using the Medallion Architecture, which separates the pipeline into Bronze, Silver, and Gold layers:

- **Bronze Layer:** Stores raw data as-is (imported from ERP & CRM CSV files).
- **Silver Layer:** Applies data cleaning, standardization, and transformation.
- **Gold Layer:** Business-ready star schema model optimized for analytics and reporting.

---

## 📖 Project Highlights

- **Data Architecture:** Layered data pipeline using Medallion Architecture.
- **ETL Pipelines:** Created robust ETL processes using T-SQL to move data through each layer.
- **Data Modeling:** Designed star schema with fact and dimension tables for optimized querying.
- **Analytics:** Generated insights on sales trends, customer behavior, and product performance.
- **Diagramming:** Designed architecture and ETL flow diagrams using Draw.io.

---

## 🎯 Skills Demonstrated

- SQL Server Development  
- Data Modeling (Star Schema)  
- ETL and Data Cleaning  
- Data Engineering Concepts  
- Business Intelligence Foundations  
- Technical Documentation  

---

## 🛠️ Tools & Technologies Used

- SQL Server Express  
- SQL Server Management Studio (SSMS)  
- T-SQL  
- Draw.io for data architecture & flow diagrams  
- CSV files (ERP and CRM data sources)  
- Git & GitHub  

---

## 🚀 Project Goals

### Data Engineering

- Consolidate data from ERP and CRM systems into a centralized warehouse.  
- Ensure data quality through cleaning and transformation processes.  
- Build a star schema model for structured reporting.

### Analytics

Use SQL to analyze:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These reports are useful for strategic decision-making by business stakeholders.

---

## 📂 Repository Structure

data-warehouse-sales/
│
├── datasets/ → Raw ERP and CRM CSV files
├── docs/ → Project documentation and diagrams
│ ├── architecture.drawio
│ ├── etl_flow.drawio
│ ├── data_model.drawio
│ ├── naming.md
│ ├── catalog.md
│
├── scripts/ → SQL scripts
│ ├── bronze/ → Ingesting raw data
│ ├── silver/ → Cleaning & transforming data
│ ├── gold/ → Creating star schema models
│
├── tests/ → Data validation & quality checks
├── README.md
├── .gitignore
└── requirements.txt


---

## 💡 Future Scope

- Add a dashboarding layer using Power BI or Tableau  
- Automate ETL using Python or SSIS  
- Implement Slowly Changing Dimensions (SCD Type 2)  

---

## 🤝 Let’s Connect

[Connect with me on LinkedIn](https://www.linkedin.com/in/giteshgarg08/)
