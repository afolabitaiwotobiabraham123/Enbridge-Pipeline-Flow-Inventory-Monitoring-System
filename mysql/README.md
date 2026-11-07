# MySQL Analysis

This folder contains the SQL scripts used for database setup, pipeline flow analysis, inventory analysis, operational KPI calculations, and flow imbalance analysis.

MySQL will be used to store and analyse the cleaned and prepared pipeline operational datasets produced during the Python data preparation stage.

## SQL Scripts

### 01_database_setup.sql
Creates the database and prepares the required tables for storing pipeline operational data.

### 02_pipeline_flow_analysis.sql
Analyses incoming and outgoing pipeline volumes and examines flow patterns over time.

### 03_inventory_analysis.sql
Examines inventory movements and changes over time, where supported by the available dataset.

### 04_operational_kpi_calculations.sql
Calculates relevant pipeline operational performance indicators.

### 05_flow_imbalance_analysis.sql
Identifies and analyses differences between incoming and outgoing pipeline flows.

## Tool

- MySQL

## Workflow

Prepared Data → Database Setup → SQL Analysis → KPI Calculations → Operational Insights
