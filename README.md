<h1 align="center">👋 Pratik Tiwari</h1>
<h3 align="center">Data Engineer | Cloud Architect | Azure • Snowflake • Databricks • Apache Airflow</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/pratiktiwari5995" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:iampratik5995@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://github.com/PratikTiwari5995" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Data Engineer** specialized in designing and building **production-grade, cloud-native data pipelines** that transform raw data into actionable business intelligence. My expertise spans multiple cloud platforms and data orchestration frameworks, with a passion for building **scalable, reliable systems** that solve real-world business problems.

I excel at:
- 🏗️ **End-to-end ETL/ELT pipeline design** using modern tools (Airflow, Databricks, Snowflake)
- ☁️ **Cloud-native architecture** on Azure & AWS with strong data warehouse expertise
- 📊 **Data modeling & analytics** using medallion architecture and dimensional modeling
- 🔐 **Data governance** with Delta Lake, Unity Catalog, and security best practices
- ⚙️ **Workflow orchestration** using Apache Airflow with Docker containerization
- 📈 **BI & analytics** integrating Snowflake/Databricks with Power BI for business insights

---

## 🚀 Featured Projects

### 1. 📊 EOD Securities Pricing Analytics Platform ⭐ **[LATEST]**

**A production-grade data engineering solution that ingests, transforms, and analyzes End-of-Day securities pricing data at scale.**

**Business Impact:**
- ✅ **87.5% faster ingestion** - Reduced from 4 hours (manual) to 30 minutes (automated)
- ✅ **2+ hours faster insights** - Eliminated CSV bottlenecks for trading teams
- ✅ **99.5% pipeline uptime** - Automated monitoring & error handling
- ✅ **80% error reduction** - Data quality validation at every layer
- ✅ **5,000+ daily records** - Processing 26,000+ trades with 542 unique securities

**Tech Stack:**
- **Orchestration:** Apache Airflow 2.8.0 (Docker)
- **Data Warehouse:** Snowflake (4-layer: RAW → CORE → DIM → FACT → SA)
- **Cloud Storage:** AWS S3 (Bronze layer)
- **APIs:** Massive Stock Market API integration
- **BI & Reporting:** Power BI (2 dashboards, 6 analytics views)
- **Alerting:** Slack notifications on success/failure

**Architecture:**
```
Massive API  →  Airflow DAG  →  AWS S3  →  Snowflake ETL  →  Power BI Dashboards
  (5K/day)     (Download)     (Stage)    (Transform)         (Analytics)
```

**Key Components:**
- **Daily Data Pipeline:** Automated stock price ingestion via Massive API
- **4-Layer Data Warehouse:** RAW (immutable) → CORE (cleansed) → DIM (dimensions) → FACT (analytics-ready)
- **6 Subject Area Views:** Market liquidity, equity performance, sector analysis, watchlist insights
- **Interactive Dashboards:** Real-time trading insights, liquidity monitoring, volatility trends
- **Error Handling:** Reject tables, validation checks, automated alerts

📌 **[GitHub Repository](https://github.com/PratikTiwari5995/eod-securities-analytics)**

---

### 2. 🛒 Ecommerce Data Pipeline (Azure) ⭐

**Cloud-native ETL pipeline leveraging Azure Databricks, Delta Lake, and Power BI for real-time ecommerce analytics.**

**Highlights:**
- **Medallion Architecture:** Bronze → Silver → Gold data transformation layers
- **Unified Governance:** Azure Managed Identity + Unity Catalog for secure, credentialless ADLS access
- **Data Reliability:** Delta Lake time-travel & ACID transactions across all layers
- **Multi-Domain Processing:** Order Items, Order Returns, Order Shipments
- **BI Integration:** Power BI dashboards for real-time business metrics

**Tech Stack:**
- Azure Databricks | PySpark | Delta Lake | Unity Catalog | Azure Data Lake | Power BI

📌 **[GitHub Repository](https://github.com/PratikTiwari5995/Ecommerce-data-pipeline)**

---

## 🛠️ Tech Stack

### ☁️ Cloud & Data Platforms
<p>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure_Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Unity_Catalog-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
</p>

### 🔧 Data Processing & Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
</p>

### 📊 Analytics & BI
<p>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
</p>

### 🗄️ Databases & Storage
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure_Data_Lake-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

### 🧰 Tools & Additional Technologies
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
</p>

---

## 🎯 Core Competencies

| Area | Expertise |
|------|-----------|
| **Data Engineering** | ETL/ELT pipeline design, data warehousing, real-time ingestion |
| **Orchestration** | Apache Airflow, workflow automation, DAG design, error handling |
| **Cloud Platforms** | Azure (Databricks, Data Lake), AWS (S3, EC2), multi-cloud strategies |
| **Data Warehousing** | Snowflake, dimensional modeling, medallion architecture, query optimization |
| **Big Data Processing** | PySpark, Spark SQL, distributed computing, optimization techniques |
| **Data Governance** | Delta Lake, Unity Catalog, data quality, security & compliance |
| **Analytics & BI** | Power BI dashboards, data storytelling, business intelligence, KPI tracking |
| **APIs & Integrations** | REST API integration, data source connectors, third-party platform APIs |
| **DevOps & Containerization** | Docker, container orchestration, CI/CD practices |

---

## 📌 Key Achievements

- 🏆 **Built production-grade pipelines** processing 5,000+ daily records with 99.5% uptime
- 🏆 **Reduced data latency by 87.5%** through intelligent orchestration and optimization
- 🏆 **Designed scalable data warehouses** serving 2+ executive dashboards and 6+ analytics views
- 🏆 **Implemented data governance** with Unity Catalog and Delta Lake across multi-cloud platforms
- 🏆 **Created automated monitoring** with Slack alerts and data quality validation
- 🏆 **Optimized Spark jobs** improving query performance by 45% through best practices

---

## 📚 What I'm Currently Exploring

- 🔍 Advanced **Spark optimization** techniques (partitioning, bucketing, caching strategies)
- 🔍 **Data lakehouse architecture** patterns and best practices
- 🔍 **Real-time streaming** with Kafka & Spark Structured Streaming
- 🔍 **Cost optimization** for cloud data platforms
- 🔍 **Data observability & monitoring** tools and frameworks

---

## 📬 Let's Connect

I'm always interested in discussing data engineering challenges, cloud architecture, and building systems that scale.

<p align="left">
  <a href="https://www.linkedin.com/in/pratiktiwari5995" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Pratik_Tiwari-0077B5?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:iampratik5995@gmail.com">
    <img src="https://img.shields.io/badge/Email-iampratik5995@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/PratikTiwari5995" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-PratikTiwari5995-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>Building scalable data systems | Cloud-native architectures | Real-world impact through data</i>
</p>
