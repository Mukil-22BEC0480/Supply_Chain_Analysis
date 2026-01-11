# Automated Data Analytics Pipeline using n8n, PostgreSQL & Quadratic



## 📌 Overview
This project demonstrates an end-to-end, cloud-based data analytics workflow using automation, databases, and prompt-driven analysis. Source spreadsheets are received via email, automatically monitored and ingested using n8n, stored in a cloud-hosted PostgreSQL database, and analyzed in Quadratic to generate business insights and dashboards.

The project showcases skills in data automation, database integration, and modern analytics tooling.

---

## 📊 Dataset
The source data consists of spreadsheet files received via email, containing structured business and transactional information.

- Source format: **Excel spreadsheets**
- Ingestion method: **Email-based automation**
- Storage: **PostgreSQL database (hosted on Supabase)**

A sample source file is included in the repository for reference.

---

## 🛠️ Tools & Technologies
- **n8n** – AI agentic automation for email monitoring and data ingestion  
- **PostgreSQL** – Relational database for structured data storage  
- **Supabase** – Cloud hosting for PostgreSQL  
- **Quadratic** – Prompt-based data analysis and calculations  
- **Excel** – Source data format  
- **GitHub** – Version control and documentation  

---

## 🔄 Project Workflow
1. Source spreadsheet files are received via email  
2. n8n monitors the mailbox and detects new files  
3. Data is automatically ingested into PostgreSQL  
4. PostgreSQL is hosted on the cloud using Supabase  
5. Quadratic connects to PostgreSQL and pulls the data  
6. Prompt-based analysis and calculations are performed in Quadratic  
7. Insights and dashboard-ready outputs are generated

### 🔄 n8n Workflow

[![n8n Workflow](n8n%20Workflow%20Screenshot%20(Reference).png)](n8n%20Workflow%20Screenshot%20(Reference).png)

This workflow uses n8n to monitor incoming emails, extract spreadsheet attachments, and ingest the data into a PostgreSQL database hosted on Supabase.

### 📊 Quadratic Analysis

[![Quadratic Analysis](Quadratic%20Screenshot%20(Reference).png)](Quadratic%20Screenshot%20(Reference).png)

Quadratic connects directly to the PostgreSQL database and performs prompt-based analysis, calculations, and KPI generation on the ingested data.


---




## 📌 Results & Insights
- Automated ingestion of spreadsheet data from email  
- Centralized, cloud-based data storage  
- Faster analysis using prompt-driven workflows  
- Reduced manual data handling and processing  

---

## ▶️ How to Run
1. Configure email access and credentials in n8n  
2. Import the provided n8n workflow JSON  
3. Set up a PostgreSQL database on Supabase  
4. Update database connection details in n8n  
5. Connect Quadratic to the PostgreSQL database  
6. Run prompts in Quadratic to perform analysis and generate insights  

---

## 📜 License
This project is licensed under the MIT License.
