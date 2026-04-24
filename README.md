# 🧵 Fabric Datasets — Microsoft Fabric Data Engineering Resources

![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-Data%20Platform-742774?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Data Engineering](https://img.shields.io/badge/Data%20Engineering-Lakehouse-0078D4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This repository contains datasets and resources used for **Microsoft Fabric** data engineering experiments. Microsoft Fabric is an all-in-one analytics platform that integrates Data Factory, Synapse Analytics, Power BI, and Data Lake Storage into a unified SaaS solution.

---

## 🏗️ About Microsoft Fabric

Microsoft Fabric provides:
- **OneLake** — A single unified data lake across your organisation
- **Lakehouse** — Delta Lake-based storage with SQL and Spark access
- **Data Factory** — Low-code ETL/ELT pipeline builder
- **Synapse Data Engineering** — PySpark-based data transformation
- **Real-Time Analytics** — KQL-based streaming data analysis
- **Power BI** — Business intelligence and reporting

---

## 🎯 Use Cases

The datasets in this repository are used to demonstrate:
- **Data ingestion** from various source formats into OneLake
- **Lakehouse architecture** with Bronze → Silver → Gold medallion layers
- **ETL transformations** using Spark notebooks in Microsoft Fabric
- **SQL analytics** over Delta Lake tables

---

## 📐 Medallion Architecture

```
Raw Sources
    ↓
Bronze Layer (Raw ingestion — unmodified)
    ↓
Silver Layer (Cleaned & validated data)
    ↓
Gold Layer (Aggregated, analytics-ready)
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Microsoft Fabric | Unified analytics platform |
| OneLake | Centralised data lake storage |
| Apache Spark (PySpark) | Data transformation |
| Delta Lake | ACID-compliant table format |
| SQL Analytics Endpoint | Query Delta tables with SQL |

---

## 👨‍💻 Author

**Homeswar Rao Nelakurthi**
[![GitHub](https://img.shields.io/badge/GitHub-homeshwarnelakurthi-181717?style=flat&logo=github)](https://github.com/homeshwarnelakurthi)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
