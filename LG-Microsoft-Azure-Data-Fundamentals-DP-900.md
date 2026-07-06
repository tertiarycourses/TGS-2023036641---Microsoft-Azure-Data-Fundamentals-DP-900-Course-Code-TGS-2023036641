# Learner Guide - Microsoft Azure Data Fundamentals (DP-900)

## Course Information

| Item | Details |
| --- | --- |
| Course Code | TGS-2023036641 |
| Course Title | Microsoft Azure Data Fundamentals (DP-900) |
| Registration | https://www.tertiarycourses.com.sg/wsq-microsoft-azure-data-fundamentals-dp-900.html |
| Microsoft Study Guide | https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-900 |

## Course Goal

This course helps learners understand foundational data concepts and Microsoft Azure data services. Learners will identify data types, compare transactional and analytical workloads, understand relational and non-relational services, recognize large-scale analytics patterns, and explain Power BI visualization concepts.

## Prerequisites

- Basic computer literacy.
- Basic cloud computing awareness is helpful.
- No prior database administration, data engineering, or data analytics experience is required.
- Access to Microsoft Learn, Azure portal, or an instructor-provided Azure environment.

## Learning Outcomes

By the end of the course, learners should be able to:

- Describe structured, semi-structured, and unstructured data.
- Compare transactional and analytical workloads.
- Identify common data roles such as database administrator, data engineer, and data analyst.
- Explain relational concepts, normalization, SQL statements, and database objects.
- Describe Azure SQL Database, Azure SQL Managed Instance, and SQL Server on Azure Virtual Machines.
- Identify Azure database services for open-source systems.
- Describe Azure Blob Storage, Azure Files, Azure Table Storage, and Azure Cosmos DB.
- Explain data ingestion, processing, analytical data stores, batch analytics, and streaming analytics.
- Describe Microsoft Fabric, Azure Databricks, real-time analytics, and Power BI capabilities.

## Recommended Course Flow

### Day 1 - Core Data and Relational Foundations

1. Course briefing and DP-900 exam overview.
2. Lab 01: Core Data Concepts, Data Types, Workloads.
3. Lab 02: Data Roles, Storage Options, File Formats.
4. Lab 03: Relational Data, SQL, Normalization, Database Objects.
5. Lab 04: Azure SQL and Open-Source Databases on Azure.
6. Review: relational and transactional concepts.

### Day 2 - Non-Relational Data and Analytics

1. Recap of Day 1.
2. Lab 05: Azure Storage, Blob, Files, Tables.
3. Lab 06: Azure Cosmos DB, NoSQL, APIs.
4. Lab 07: Analytics, Ingestion, Processing, Analytical Data Stores.
5. Lab 08: Microsoft Fabric, Azure Databricks, Real-Time Analytics.
6. Lab 09: Power BI, Data Models, Visualizations.
7. Lab 10: DP-900 Capstone and Exam Readiness.

## Lab Environment Setup

### Step 1 - Confirm Azure Access

1. Open https://portal.azure.com/.
2. Sign in with the account provided by your instructor or your own Azure account.
3. Confirm you can view subscriptions and resource groups.
4. If using a personal subscription, set a budget alert before creating resources.

### Step 2 - Create a Resource Group

Use Azure Cloud Shell:

```bash
az group create --name rg-dp900-lab --location southeastasia
```

### Step 3 - Create a Notes File

Create:

```text
dp900-lab-notes.md
```

Record:

```text
Subscription:
Resource group:
Region:
Data services reviewed:
Key learning points:
```

### Step 4 - Cost Control

1. Use free tiers, trials, samples, and documentation walkthroughs where available.
2. Avoid creating high-cost analytics clusters unless instructed.
3. Delete any training resources at the end of the course.
4. Do not upload real confidential or personal data into lab services.

## Lab Completion Standard

For each lab, learners should complete:

1. Scenario interpretation.
2. Guided task or design activity.
3. Validation questions.
4. Service selection note.
5. Cleanup review.
6. One exam-style takeaway.

## Final Exam Readiness Checklist

Before attempting DP-900, confirm that you can:

- Distinguish structured, semi-structured, and unstructured data.
- Distinguish transactional and analytical workloads.
- Explain relational tables, keys, normalization, SQL, views, indexes, and stored procedures.
- Choose between Azure SQL Database, Managed Instance, SQL Server on Azure VMs, and open-source database services.
- Explain Blob, Files, Tables, queues, and Cosmos DB at a high level.
- Compare batch and streaming analytics.
- Describe data ingestion, transformation, storage, analytics, and visualization stages.
- Explain Microsoft Fabric, Azure Databricks, and Power BI roles in analytics.
