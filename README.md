# ETL Incremental S3 to Redshift (DataOps)

🚀 **Project Overview**  
This project implements an **incremental ETL pipeline** that processes **new data added to Amazon S3** and loads it into **Amazon Redshift** using a **star schema**. The pipeline is orchestrated using **Apache Airflow** and deployed with **Terraform** as part of a **DataOps workflow**.

## 📌 **Project Scope**
- **Provision AWS Infrastructure**: Deploy **S3, Redshift, and EC2** using **Terraform**
- **Extract**: Detect and process only new data from an S3 bucket
- **Transform**: Structure the data into a **dimensional model (star schema)**
- **Load**: Store the transformed data in **Amazon Redshift**
- **Orchestrate**: Automate the pipeline using **Apache Airflow DAGs**

## ⚡ **Tech Stack**
- **AWS Services**: S3, Redshift, IAM, EC2
- **ETL Tools**: Python (Pandas/PySpark)
- **Orchestration**: Apache Airflow
- **Infrastructure as Code**: Terraform
- **Storage Format**: Parquet

## 🛠 **Setup (WIP)**
> 🚧 **This project is currently under development. A detailed setup guide will be added soon.**
