# Pipeline Flow & Inventory Monitoring System

## Project Status

 **Project in Progress**

This project is being developed as part of my **Energy, Supply Chain & Operations Analytics Portfolio**.

The objective is to explore how data analytics can be used to monitor pipeline movements, identify flow imbalances, and provide operational visibility into inventory conditions.

> **Important:** This is an independent portfolio project designed to demonstrate analytical and technical skills. It does not use confidential Enbridge operational data or represent an official Enbridge system.

---

##  Company Context

**Enbridge** is an energy infrastructure company with major operations across North America, including pipelines and energy transportation infrastructure.

For this portfolio project, I am exploring a simplified operational analytics problem around:

* Pipeline inflow
* Pipeline outflow
* Inventory/storage
* Flow imbalance
* Operational exceptions

---

##  Problem Statement

Pipeline systems need to maintain a reasonable balance between incoming volumes, outgoing volumes, and available inventory.

Significant differences between these measurements may indicate situations requiring operational attention.

The analytical question for this project is:

> **Can operational data be used to monitor pipeline flow and inventory conditions and identify periods of potential imbalance?**

---

##  Proposed Solution

I plan to build a:

### **Pipeline Flow & Inventory Monitoring System**

The system will combine data analysis and visualization to monitor:

* Incoming pipeline volumes
* Outgoing pipeline volumes
* Inventory/storage levels
* Daily/weekly flow changes
* Flow imbalance
* Operational exceptions

---

##  Key Analytical Questions

The analysis will investigate questions such as:

1. What are the incoming and outgoing volume patterns?
2. How does inventory change over time?
3. When does inflow significantly differ from outflow?
4. Which periods experience the largest imbalance?
5. Are there recurring patterns in the imbalance?
6. How does inventory respond to sustained flow differences?
7. Which operational periods require further investigation?

---

##  Technologies

* Python
* Pandas
* NumPy
* SQL
* MySQL
* Power BI
* Data Visualization
* Data Quality Assessment
* Data Cleaning

---

##  Planned Workflow

```text
Data Source
     ↓
Data Collection
     ↓
Data Exploration
     ↓
Data Quality Assessment
     ↓
Data Cleaning
     ↓
SQL Data Analysis
     ↓
Operational KPI Development
     ↓
Python Analysis
     ↓
Power BI Dashboard
     ↓
Operational Insights
```

---

##  Planned KPIs

Potential KPIs include:

* Total Inflow
* Total Outflow
* Net Flow
* Inventory Level
* Flow Imbalance
* Inventory Change
* Average Daily Flow
* Maximum Flow
* Minimum Flow
* Exception Periods

---

##  Planned Project Structure
enbridge-pipeline-flow-inventory-monitoring/
│
├── data/
│
├── sql/
│   ├── 01_data_exploration.sql
│   ├── 02_data_quality.sql
│   ├── 03_data_cleaning.sql
│   └── 04_operational_analysis.sql
│
├── python/
│   ├── 01_data_exploration.py
│   ├── 02_data_quality.py
│   ├── 03_data_cleaning.py
│   └── 04_analysis.py
│
├── powerbi/
│
├── visuals/
│
└── README.md

---

##  Project Roadmap

* Identify suitable dataset
* Understand the data structure
* Perform data exploration
* Perform data quality assessment
* Clean and transform the data
* Load data into MySQL
* Develop operational KPIs
* Perform flow and inventory analysis
* Identify potential imbalance periods
* Build Power BI dashboard
* Document operational insights
* Publish final project

---

##  Skills Demonstrated

This project is intended to demonstrate practical skills in:

**Data Analytics**

* Exploratory Data Analysis
* KPI development
* Trend analysis
* Exception analysis

**Data Engineering**

* Data ingestion
* Data cleaning
* SQL data preparation
* Relational data analysis

**Business & Operations Analytics**

* Pipeline operations
* Inventory monitoring
* Flow analysis
* Operational performance monitoring

**Visualization**

* Power BI
* Operational dashboards
* Data storytelling

---

##  Disclaimer

This is an independent educational portfolio project.

The project does not represent Enbridge's internal systems, processes, operational decisions, or confidential data.
