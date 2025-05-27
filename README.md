
### **Automated Movie Monitoring Dashboard Using Azure Databricks**

#### Overview

This project implements an end-to-end automated data pipeline on Azure Databricks to ingest, process, and visualize movie data from TMDB API. It uses the Medallion Architecture with Delta Lake for reliable data storage, Change Data Capture (CDC) for incremental updates, and Slowly Changing Dimension (SCD) Type 1 for dimension management. The final output is an interactive Power BI dashboard for real-time movie trend and new analysis.

#### Features

- Incremental data ingestion using CDC with timestamp-based filtering  
- Data transformation and cleaning with Databricks SQL and PySpark  
- Medallion architecture layers: Bronze (raw), Silver (cleaned), Gold (aggregated)  
- SCD Type 1 implementation for dimension tables  
- Automated CI/CD pipelines with GitHub Actions  
- Power BI dashboard with auto-refresh and dynamic filters  

#### Prerequisites

- Azure subscription with Databricks workspace and Data Lake Storage Gen2  
- Python 3.7+ and PySpark environment  
- Power BI Desktop or Power BI Service account  
- Git and GitHub account for version control and CI/CD  

#### License

This project is licensed under the MIT License.

#### Acknowledgments

- TMDB API for movie data  
- Azure Databricks and Microsoft Azure for cloud infrastructure  
- Power BI for data visualization  

![](path)


