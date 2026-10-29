# Hi, I'm Vishnu Dorigundla

**Data Engineer | Azure · Microsoft Fabric · Databricks · AWS · Power BI | Applied GenAI and ML**

Data and analytics professional with hands-on experience designing cloud data pipelines on Azure and Microsoft Fabric, building Power BI reporting solutions, and developing ML and GenAI applications.

Analyst at HCLTech, Chennai, delivering Power BI dashboards, Power Platform solutions and Power Automate workflows, with exposure to Microsoft Fabric and Databricks.

Seeking data engineering roles focused on Azure, Microsoft Fabric and AWS.

---

## Featured projects

### 1. Spotify medallion pipeline on Azure
**Azure SQL → Azure Data Factory → ADLS Gen2 → Databricks (PySpark, declarative pipelines)**
- ADF pipelines load data incrementally using a change-date column and a lookup of the last load, and loop over a list of tables with a ForEach. A web activity is wired in for alerts.
- Databricks builds silver dimensions in a notebook and gold tables (`DimDate`, `DimTrack`, `DimUser`, `FactStream`) as declarative pipeline tables with data-quality expectations.
- The Databricks side is deployed as an Asset Bundle (`databricks.yml`).
- Repo: [azureproject](https://github.com/vishnudorigundla/azureproject)

### 2. Microsoft Fabric lakehouse for an LMS portal
**Raw → Landing → Bronze → Silver → Gold, orchestrated in a Fabric pipeline**
- Four Fabric notebooks (raw to landing, landing to bronze, silver, gold) chained in one end-to-end pipeline with a dynamic run-date parameter.
- The bronze, silver and gold notebooks use `MERGE` upserts so re-delivered records update instead of duplicating.
- Power BI report on the gold layer (`LMS_report.pbix`).
- Repo: [Fabric-end-to-end-project-for-LMS-portal](https://github.com/vishnudorigundla/Fabric-end-to-end-project-for-LMS-portal)

### 3. Blinkit sales dashboard in Power BI
- KPI cards (total sales, average sales, number of items, average rating) built with DAX, plus charts by item type, fat content, outlet size, outlet age and location.
- Repo: [blinkit-power-bi-dashboard](https://github.com/vishnudorigundla/blinkit-power-bi-dashboard)

### 4. GenAI apps (Streamlit)
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
