# Addishiwot Teshome | Public Health Data Analytics & Informatics Specialist
📍 Nairobi, Kenya | ✉️ tesho004@alumni.umn.edu 

## Professional Overview
I am an MPH Epidemiologist and Health Data Informatics professional specializing in building end-to-end data pipelines for international public health interventions. My work bridges the gap between field-level healthcare data architectures and strategic donor performance reporting.

I structure my repositories around a core **4-Stage Public Health Data Pipeline**:
1. **EXTRACT:** Automated aggregate/tracker ingestion via DHIS2 APIs and KoboToolbox loops.
2. **MANAGE:** Structural data governance, missing-data imputation, and automated Data Quality Assessments (DQA).
3. **ANALYZE:** Programmatic biostatistics, multivariate stratified risk analysis, and epidemic tracking using R/RStudio.
4. **VISUALIZE:** Live business intelligence dash boarding (Power BI) mapped directly to donor LogFrames.

---

## 🛠️ Technical Stack
* **Health Information Systems:** DHIS2, OpenMRS, KenyaEMR, KoboToolbox, ODK
* **Data Management & Scripting:** R (tidyverse, dplyr, ggplot2, janitor), SQL, Python
* **Business Intelligence:** Power BI, Tableau Desktop
* **Biostatistics:** Epidemiological Surveillance Pipelines, Survey-Weighted Regressions, SAS, SPSS

---

## 📁 Core Portfolio Projects

### [1. End-to-End Automated Infectious Disease Surveillance Pipeline](https://github.com)
* **Pipeline Nodes:** Extract ➔ Manage ➔ Analyze
* **Description:** An automated R script that securely authenticates against the DHIS2 Web API sandbox, extracts raw weekly sentinel surveillance logs, executes automated schema standardization (`janitor`), filters invalid/outlier rows (DQA), and exports a polished, analysis-ready dataframe.
* **Tech:** R (httr, jsonlite, tidyverse), DHIS2 Sandbox API.

### [2. Mobile Field Epidemiology Framework: Mobile Data Ingestion & Data Quality Audits](https://github.com)
* **Pipeline Nodes:** Extract ➔ Manage
* **Description:** Contains an XLSForm architecture designed for tracking regional vector-borne disease outbreaks with built-in advanced skip-logic, variable constraints, and geolocation locks. Included is a companion R script that checks for duplicate participant IDs and audits incomplete field entries.
* **Tech:** XLSForm Syntax, KoboToolbox, ODK, R.

### 📉 [3. Strategic M&E Performance & Interactive Donor Dashboard](https://github.com)
* **Pipeline Nodes:** Visualize ➔ M&E Delivery
* **Description:** A production-ready Power BI dashboard connected directly to a simulated multi-country healthcare project database. The visuals are dynamically mapped to a Logical Framework (LogFrame) and an Indicator Tracking Table (ITT) to display baseline variances and target thresholds.
* **Tech:** Power BI Desktop, DAX Expressions, Star Schema Data Modeling.
* 
