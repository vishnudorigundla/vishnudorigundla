# Hi, I'm Vishnu Dorigundla

**Data Engineer | Azure · Microsoft Fabric · Databricks · AWS · Power BI | Applied GenAI and ML**

Data and analytics professional with hands-on experience designing cloud data pipelines on Azure and Microsoft Fabric, Databricks,building Power BI reporting solutions, and developing ML and GenAI applications.

Analyst at HCLTech, Chennai, delivering Power BI dashboards, Power Platform solutions and Power Automate workflows, with exposure to Microsoft Fabric and Databricks.

Seeking data engineering roles focused on Azure, Microsoft Fabric and AWS.

---

## Featured projects

### 1. Metadata-driven healthcare analytics lakehouse on Microsoft Fabric
**GitHub and Lakehouse files → Landing → Bronze → Silver → Gold → Semantic model → Power BI**
- One set of Fabric pipelines and three parameterized PySpark notebooks load five healthcare sources (patients, doctors, hospitals, claims, pharmacy) in CSV, JSON and Parquet, instead of a separate copy activity per source.
- Config tables in a Fabric SQL warehouse (`Metadata_Config`, `Watermark_Control`, `Pipeline_Run_Log`) drive what loads, from where, in which format and since when. Adding a source is one config row.
- Incremental loads use a `ModifiedDate` watermark. Silver and Gold upsert on the business key with Delta `MERGE`, with schema evolution turned on.
- Gold is a star schema (`Gold_Dim_Patient`, `Gold_Dim_Doctor`, `Gold_Dim_Hospital`, `Gold_Fact_Claims`, `Gold_Fact_Pharmacy`) feeding a semantic model and a Power BI report.
- Repo: [healthcare-files](https://github.com/vishnudorigundla/healthcare-files)

### 2. Spotify medallion pipeline on Azure
**Azure SQL → Azure Data Factory → ADLS Gen2 → Databricks (PySpark, declarative pipelines)**
- ADF pipelines load data incrementally using a change-date column and a lookup of the last load, and loop over a list of tables with a ForEach. A web activity is wired in for alerts.
- Databricks builds silver dimensions in a notebook and gold tables (`DimDate`, `DimTrack`, `DimUser`, `FactStream`) as declarative pipeline tables with data-quality expectations.
- The Databricks side is deployed as an Asset Bundle (`databricks.yml`).
- Repo: [azureproject](https://github.com/vishnudorigundla/azureproject)

### 3. Microsoft Fabric lakehouse for an LMS portal
**Raw → Landing → Bronze → Silver → Gold, orchestrated in a Fabric pipeline**
- Four Fabric notebooks (raw to landing, landing to bronze, silver, gold) chained in one end-to-end pipeline with a dynamic run-date parameter.
- The bronze, silver and gold notebooks use `MERGE` upserts so re-delivered records update instead of duplicating.
- Power BI report on the gold layer (`LMS_report.pbix`).
- Repo: [Fabric-end-to-end-project-for-LMS-portal](https://github.com/vishnudorigundla/Fabric-end-to-end-project-for-LMS-portal)

### 4. Blinkit sales dashboard in Power BI
- KPI cards (total sales, average sales, number of items, average rating) built with DAX, plus charts by item type, fat content, outlet size, outlet age and location.
- Repo: [blinkit-power-bi-dashboard](https://github.com/vishnudorigundla/blinkit-power-bi-dashboard)

### 5. GenAI apps (Streamlit)
- **AI Email Reply Assistant:** drafts replies in English or Telugu with Gemini. [repo](https://github.com/vishnudorigundla/-AI-Email-Reply-Assistant)
- **YouTube Video Summarizer:** pulls a video transcript and summarizes it with Gemini. [repo](https://github.com/vishnudorigundla/Youtube-video-summary-Generator)
- **AI Travel Planner:** itinerary drafts from Perplexity through LangChain, with Google Places links and WhatsApp delivery. [repo](https://github.com/vishnudorigundla/AI-Travel-Planner)

---

## Skills

| Area | What I use |
|---|---|
| Azure data platform | Azure Data Factory, ADLS Gen2, Azure SQL Database, Microsoft Fabric (lakehouse, pipelines, notebooks), Azure Databricks |
| Data engineering | PySpark, Spark SQL, Delta Lake, medallion architecture, incremental loads, `MERGE` upserts, data-quality checks, pipeline orchestration and parameterization |
| BI and automation | Power BI (DAX, Power Query, semantic models), Power Automate, requirements gathering |
| Machine learning | Python, pandas, NumPy, scikit-learn, TensorFlow, Keras, PyTorch |
| GenAI | Gemini API, LangChain, prompt design, Streamlit apps |
| Databases and languages | SQL, Python |
| Engineering tools | Git and GitHub, VS Code, Jupyter, Databricks Asset Bundles |

### Learning on AWS
Building the same patterns on AWS, with a focus on data engineering and ML:
- **Data engineering:** S3 (data lake), AWS Glue (ETL and catalog), Athena, Redshift, Lambda, Step Functions
- **Machine learning:** Amazon SageMaker (training, deployment and pipelines)

---

## Certifications

![Azure Data Scientist Associate](https://img.shields.io/badge/Microsoft-Azure%20Data%20Scientist%20Associate-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Databricks Associate](https://img.shields.io/badge/Databricks-Associate-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Fabric Data Engineer](https://img.shields.io/badge/Microsoft-Fabric%20Data%20Engineer-117865?style=for-the-badge&logo=microsoft&logoColor=white)
![Fabric Data Analyst](https://img.shields.io/badge/Microsoft-Fabric%20Data%20Analyst-117865?style=for-the-badge&logo=microsoft&logoColor=white)
![Power BI Data Analyst](https://img.shields.io/badge/Microsoft-Power%20BI%20Data%20Analyst-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![GitHub Copilot](https://img.shields.io/badge/GitHub-Copilot-181717?style=for-the-badge&logo=githubcopilot&logoColor=white)

| Certification | Issuer | Focus |
|---|---|---|
| Azure Data Scientist Associate | Microsoft | Building and deploying machine learning models on Azure |
| Databricks Associate | Databricks | Spark and Delta Lake on the Databricks lakehouse |
| Fabric Data Engineer | Microsoft | Ingestion, transformation, lakehouses and pipelines in Fabric |
| Fabric Data Analyst | Microsoft | Semantic models and analytics on Fabric |
| Power BI Data Analyst | Microsoft | Data modelling, DAX and reporting in Power BI |
| GitHub Copilot | GitHub | AI-assisted development |

### Other learning
- IBM Data Science Professional Certificate (Coursera)
- Microsoft AI Skills Certification
- HCLTech Training Certification

---

## Experience

**Graduate Engineer Trainee, HCLTech** (Oct 2025 – present, Chennai)
Power BI reporting, requirements gathering for Power Platform solutions, and Power Automate workflows. Tools: Microsoft Fabric, Databricks, Power BI, Power Automate, Python, SQL.

**Data Analyst Intern, Accenture** (Jun 2024 – Aug 2024)
Data analysis and visualization, project scoping and requirement analysis.

---

## Contact

Email: vishnudorigundla453@gmail.com
