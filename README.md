# Enbridge Pipeline Flow & Inventory Monitoring

**Energy, Supply Chain & Operations Analytics Portfolio Project**

**Project Status:** In Progress

## 1. Project Overview

This project focuses on analyzing pipeline flow and inventory-related operational data within the oil and gas transportation sector.

Using a simulated or publicly available operational dataset, the project will examine incoming and outgoing pipeline flows, inventory movements, flow imbalances, and operational performance over time.

The objective is to demonstrate how data analytics can support pipeline monitoring, operational decision-making, and supply chain performance management.

**Industry Context:** Enbridge operates major energy transportation infrastructure across North America. This independent portfolio project uses pipeline operations as its business context.

**Disclaimer:** This is an independent portfolio project. It is not affiliated with Enbridge and does not use confidential company data or represent an official Enbridge operational system.

## 2. Business Problem

Pipeline operations require continuous monitoring of the movement of energy products through transportation networks.

Differences between incoming and outgoing volumes can affect inventory levels and may indicate operational conditions that require further investigation.

Without effective monitoring and analysis, it can be difficult to identify:

- Periods of significant flow imbalance.
- Changes in pipeline inventory or linepack.
- Unusual variations in incoming and outgoing flows.
- Recurring operational performance patterns.
- Potential issues requiring operational investigation.

This project explores how data analytics can help identify these patterns and provide useful operational insights.

## 3. Project Objectives

The objectives are to:

1. Collect and organize pipeline-related operational data.
2. Explore incoming and outgoing flow patterns.
3. Assess data quality and identify inconsistencies.
4. Clean and prepare the dataset for analysis.
5. Analyze pipeline flow and inventory movements.
6. Calculate relevant operational performance indicators.
7. Identify periods of potential flow imbalance.
8. Develop an interactive Power BI dashboard.
9. Present findings and data-driven operational recommendations.

## 4. Scope of Analysis

The analysis will cover the following areas:

### Pipeline Flow Analysis
- Incoming pipeline volumes.
- Outgoing pipeline volumes.
- Daily and monthly flow patterns.
- Flow variations over time.
- Differences between inflow and outflow.

### Inventory Monitoring
- Inventory or linepack movements, where supported by the dataset.
- Changes in inventory over time.
- Relationship between incoming and outgoing volumes.
- Periods of inventory increase or decrease.

### Flow Imbalance Analysis
- Inflow and outflow differences.
- Magnitude and frequency of flow imbalances.
- Periods of sustained imbalance.
- Recurring patterns requiring investigation.

### Operational Performance
- Average and maximum flow rates.
- Flow variability.
- Operational exceptions.
- Performance trends across available periods.

## 5. Data Sources

The project will use publicly available or simulated pipeline operational data.

Potential data sources include:

- Publicly available energy and pipeline operational datasets.
- Energy industry reports and publications.
- Relevant operational data APIs.
- Simulated datasets where actual operational data is unavailable.

All data sources, collection methods, limitations, and assumptions will be documented.

No confidential Enbridge data will be used.

## 6. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data acquisition and analysis |
| Jupyter Notebook | Step-by-step data exploration and preparation |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical analysis |
| MySQL | Structured data storage and SQL analysis |
| Power BI | Interactive dashboards and visualization |
| GitHub | Project documentation and version control |

## 7. Key Performance Indicators (KPIs)

The project will investigate the following KPIs, depending on the fields and measurements available in the selected dataset:

| KPI | Description |
|---|---|
| Total Inflow | Total volume entering the pipeline |
| Total Outflow | Total volume leaving the pipeline |
| Net Flow | Difference between incoming and outgoing volume |
| Inventory Level | Recorded pipeline inventory or linepack |
| Flow Imbalance | Difference between inflow and outflow |
| Inventory Change | Change in recorded inventory over a period |
| Average Flow | Average recorded pipeline flow |
| Maximum Flow | Highest recorded flow |
| Minimum Flow | Lowest recorded flow |
| Imbalance Periods | Periods identified for further investigation |

KPI formulas, units, assumptions, and limitations will be documented after examining the actual dataset.

## 8. Project Workflow

The project will follow this analytical workflow:

1. Data source identification.
2. Data acquisition using Python.
3. Exploratory data analysis using Python and Jupyter Notebook.
4. Data quality assessment using Python and Jupyter Notebook.
5. Data cleaning and preparation using Python and Jupyter Notebook.
6. Loading prepared datasets into MySQL.
7. SQL-based pipeline flow and inventory analysis.
8. Operational KPI calculations using SQL.
9. Dashboard development using Power BI.
10. Reporting, insights, and operational recommendations.

## 9. Repository Structure

```text
enbridge-pipeline-flow-inventory-monitoring/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── python/
│   ├── 01_data_acquisition.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_quality_assessment.ipynb
│   └── 04_data_cleaning_and_preparation.ipynb
│
├── mysql/
│   ├── 01_database_setup.sql
│   ├── 02_pipeline_flow_analysis.sql
│   ├── 03_inventory_analysis.sql
│   ├── 04_operational_kpi_calculations.sql
│   └── 05_flow_imbalance_analysis.sql
│
├── power_bi/
│   ├── dashboard/
│   └── screenshots/
│
├── reports/
│   ├── data_quality_report.md
│   ├── pipeline_flow_analysis.md
│   ├── inventory_analysis.md
│   └── operational_insights.md
│
├── docs/
│   ├── data_sources.md
│   ├── data_dictionary.md
│   └── kpi_definitions.md
│
├── requirements.txt
│
└── .gitignore
```

## 10. Expected Deliverables

- Documented data sources.
- Raw and processed datasets.
- Python/Jupyter data acquisition and preparation notebooks.
- MySQL database and analysis scripts.
- Operational KPI calculations.
- Interactive Power BI dashboard.
- Data quality and analysis reports.
- Business insights and operational recommendations.

## 11. Business Value

This project demonstrates how supply chain and operations analytics can support pipeline performance monitoring.

The intended business value includes:

- Better visibility into pipeline flow performance.
- Improved monitoring of inventory movements.
- Earlier identification of unusual flow patterns.
- More informed operational investigation.
- Data-driven decision support for energy transportation operations.

## 12. Project Disclaimer

This is an independent educational and professional portfolio project developed to demonstrate skills in supply chain analytics, operations analytics, data analysis, and business intelligence.

It does not represent Enbridge's internal systems, actual operational performance, or official business recommendations.

---

**Focus Areas:** Supply Chain Analytics | Operations Analytics | Pipeline Operations | Inventory Monitoring | Energy Analytics | Oil & Gas Data Analysis
