Azure Databricks Data Lake Project
Intern: ARJUN SINGH (AMITY UNIVERSITY PUNJAB - BTECH 7th SEM) 
Position: Data Engineering Intern, Celebal Technologies
Project Date Submission: Monday, July 21, 2025


📌 Problem Statement
As part of my data engineering internship at Celebal Technologies, I was tasked to:

Build a data pipeline using Azure Databricks that connects to Azure Data Lake Storage Gen2, reads multiple file formats (CSV, JSON, TSV, TXT, etc.), performs queries and transformations using PySpark and SQL, and saves the processed results as Delta tables for analytics and reporting.

Key project requirements:

Authenticate securely to ADLS Gen2.

Read and validate different data files.

Create Spark SQL temp views and Delta tables.

Document all steps and results.

🚀 My Solution & Workflow
1. Set Up Azure Environment
Deployed and configured an Azure Databricks workspace.

Set up a new Azure Data Lake Gen2 account and created storage containers for the project.

2. Cluster & Authentication
Started and configured a Databricks cluster matching account quotas.

Used a Service Principal for secure OAuth authentication between Databricks and ADLS Gen2.

3. Data Ingestion & Exploration
Mounted the cloud storage in Databricks using dbutils and validated file access.

Loaded CSV, JSON, TSV, and TXT files as Spark DataFrames.

4. Transformation & SQL Analytics
Registered DataFrames as temp SQL views.

Ran queries for data validation and filtering (example: all customers with non-null emails).

Performed aggregations and group-bys as required.

5. Delta Table Creation
Used CTAS (Create Table As Select) to write clean data to Delta tables in the data lake.

Validated Delta table creation and content with SQL queries.

6. Documentation
Took process screenshots and structured evidence at each major step.

This folder contains the entire workflow, code, and outputs for reproducibility.

📁 Repository Structure
Based on the attached screenshot:

Jupyter Notebook/ — Contains the main code notebook exported from Databricks.

project_files=6/ — Raw data files (total 6 formats) used for loading and testing.

screenshots/ — Visual evidence of every important step (mounting, reading, querying, Delta table, etc.).

README.md — This documentation.

WORKFLOW — Visual or written workflow for pipeline reference.

🧑‍💻 How To Run This Project
Open the notebook in your own Databricks workspace.

Edit authentication config cells with your own Azure service principal details.

Run each cell step-by-step. Outputs, temp views, and Delta tables will be shown in the notebook and in /screenshots.

⚙️ Requirements
Azure Databricks (active cluster)

Azure Data Lake Gen2 account & container

Azure service principal (Client ID, Secret, Tenant ID)

Sample data files (CSV, JSON, TSV, TXT...)

📷 Screenshots
All screenshots validating each step (mount, reading files, running queries, Delta table creation) are in the screenshots/ folder and mapped in the code/README at each corresponding phase.

🗂 What Each Folder/File Contains
Jupyter Notebook/ — The code to reproduce all data pipeline steps.

project_files=6/ — The six different input files used.

screenshots/ — Step-by-step images confirming process/results.

WORKFLOW PNG — Visual workflow of the project steps.

README.md — This file explaining project logic, structure, and reproducibility.

If you have further questions or need to review the exact code, please follow the notebook and mapped screenshots for reference.
This project was submitted as part of the Data Engineering Internship at Celebal Technologies, July 2025.
