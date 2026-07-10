# Microsoft Azure Data Fundamentals (DP-900) - Learner Guide

**Course Code:** TGS-2023036641  
**Version:** 1.0  
**Effective Date:** 8 July 2026  
**Training Provider:** Tertiary Infotech Academy Pte Ltd (UEN: 201200696W)

## Table of Contents

- How to Use This Guide
- Course Information
- DP-900 Visual Maps
- Learning Outcomes
- Lab Guide
  - Topic 01: Core Data Concepts
    - Lab 1: Core Data Concepts, Data Types, Workloads
    - Lab 2: Data Roles, Storage Options, File Formats
  - Topic 02: Relational Data on Azure
    - Lab 3: Relational Data, SQL, Normalization, Database Objects
    - Lab 4: Azure SQL and Open-Source Databases on Azure
  - Topic 03: Non-Relational Data on Azure
    - Lab 5: Azure Storage, Blob, Files, Tables
    - Lab 6: Azure Cosmos DB, NoSQL, APIs
  - Topic 04: Analytics Workloads on Azure
    - Lab 7: Analytics, Ingestion, Processing, Analytical Data Stores
    - Lab 8: Microsoft Fabric, Azure Databricks, Real-Time Analytics
  - Topic 05: Power BI and Exam Readiness
    - Lab 9: Power BI, Data Models, Visualizations
    - Lab 10: DP-900 Capstone and Exam Readiness
- Assessment Flow

## How to Use This Guide

Work through the labs in order. Each lab includes objectives, scenario, step-by-step activities, validation checks, checkpoint questions and exam focus.

## Course Information

- **Course Title:** Microsoft Azure Data Fundamentals (DP-900)
- **Course Code:** TGS-2023036641
- **Training Provider:** Tertiary Infotech Academy Pte Ltd (UEN: 201200696W)
- **Duration:** 2 days, 16 training hours
- **Labs:** 10 guided labs aligned to DP-900 fundamentals

## DP-900 Visual Maps

![DP-900 Data Platform Flow](assets/dp900-data-platform-flow.png)

![Lab-to-Service Map](assets/dp900-lab-service-map.png)

## Learning Outcomes

- Describe structured, semi-structured and unstructured data.
- Compare transactional and analytical workloads.
- Identify common data roles and data store options.
- Explain relational concepts, SQL, normalization and database objects.
- Describe Azure SQL and open-source database services on Azure.
- Describe Azure Storage, Azure Cosmos DB and NoSQL patterns.
- Explain ingestion, processing, analytical data stores, batch and streaming analytics.
- Describe Microsoft Fabric, Azure Databricks, real-time analytics and Power BI concepts.
- Match data scenarios to appropriate Azure data services for DP-900 exam readiness.

## Lab Guide

### Topic 01: Core Data Concepts

Data types, workloads, roles, stores and file formats

#### Lab 1: Core Data Concepts, Data Types, Workloads

**Objectives**

- Distinguish structured, semi-structured, and unstructured data.
- Compare transactional and analytical workloads.
- Identify common data store use cases.
- Build a data concepts glossary.

**Scenario**

A retail company stores sales transactions, customer profiles, product images, web logs, invoices, and analytics reports. You must classify the data and decide which workloads are transactional or analytical.

**Step-by-step**

1. **Classify Data Types**

   Create a table:


   | Data Example | Type | Reason |
   | --- | --- | --- |
   | Sales order table | Structured | Fixed rows and columns |
   | JSON web event | Semi-structured | Flexible fields with structure |
   | Product photo | Unstructured | Binary media file |


   Add at least five more examples.

2. **Compare Workloads**

   Create a table:


   | Workload | Purpose | Example |
   | --- | --- | --- |
   | Transactional | Supports day-to-day operations | Online order processing |
   | Analytical | Supports reporting and insight | Monthly sales trend analysis |

3. **Identify Workload Characteristics**

   For each scenario, choose transactional or analytical:


   1. Insert a customer order.
   2. Update inventory quantity.
   3. Analyze five years of sales data.
   4. Create a Power BI dashboard.
   5. Stream click events for real-time monitoring.

4. **Create a Glossary**

   Define:


   Database
   Table
   File
   Data lake
   Data warehouse
   Transactional workload
   Analytical workload


**Validation**

You should have a data type table, workload table, classification answers, and glossary.

**Checkpoint Questions**

1. What is structured data?
2. What is semi-structured data?
3. Why is unstructured data common in modern systems?
4. How does an analytical workload differ from a transactional workload?

**Exam Focus:** DP-900 frequently tests the difference between data representations and workload types.

#### Lab 2: Data Roles, Storage Options, File Formats

**Objectives**

- Identify data workload roles and responsibilities.
- Compare common file formats.
- Match storage options to use cases.
- Understand common data store categories.

**Scenario**

The retail company is forming a data team. Management asks which people and services are needed for databases, pipelines, analytics, and reports.

**Step-by-step**

1. **Identify Data Roles**

   Create a table:


   | Role | Main Responsibility |
   | --- | --- |
   | Database administrator | Manage database availability, performance, backup, and security |
   | Data engineer | Build data pipelines and prepare data for analytics |
   | Data analyst | Build reports, models, and insights |


   Add examples of tasks for each role.

2. **Compare File Formats**

   | Format | Common Use |
   | --- | --- |
   | CSV | Simple tabular exchange |
   | JSON | Semi-structured API and event data |
   | Parquet | Columnar analytics data |
   | XML | Structured document exchange |
   | Avro | Data serialization in pipelines |

3. **Match Storage Options**

   | Requirement | Possible Store |
   | --- | --- |
   | Store images and backups | Blob storage |
   | Shared file access | Azure Files |
   | Key-value style entities | Azure Table Storage |
   | Relational application database | Azure SQL Database |
   | Globally distributed NoSQL app | Azure Cosmos DB |
   | Large-scale analytics | Data lake, warehouse, Fabric lakehouse |

4. **Draw a Simple Data Platform**

   Use diagrams.net:


   Source systems -> Ingestion -> Storage -> Processing -> Analytics -> Visualization

5. **Record Service Selection Rules**

   Write one sentence for when to use relational, non-relational, object storage, and analytical stores.


**Validation**

You should have role notes, file format comparison, storage mapping, and a platform diagram.

**Checkpoint Questions**

1. What does a data engineer do?
2. Why is Parquet common in analytics?
3. When would Blob storage be appropriate?
4. Why do analytics platforms separate storage and compute?

**Exam Focus:** Know the roles and responsibilities for data workloads and common storage formats.

### Topic 02: Relational Data on Azure

Relational design, SQL, Azure SQL and open-source databases

#### Lab 3: Relational Data, SQL, Normalization, Database Objects

**Objectives**

- Explain relational data concepts.
- Identify tables, rows, columns, keys, and relationships.
- Understand normalization.
- Recognize common SQL statements and database objects.

**Scenario**

The retail company stores customers, orders, products, and order lines in a relational database. You must explain how the data is structured and queried.

**Step-by-step**

1. **Draw a Relational Model**

   Create entities:


   Customers
   Orders
   OrderItems
   Products


   Add primary keys and foreign keys.

2. **Explain Normalization**

   Answer:


   1. Why should product data not be repeated on every order line?
   2. How do separate tables reduce update errors?
   3. What is the tradeoff of normalization?

3. **Identify SQL Statement Types**

   Create a table:


   | SQL Statement | Purpose |
   | --- | --- |
   | SELECT | Read data |
   | INSERT | Add data |
   | UPDATE | Modify data |
   | DELETE | Remove data |
   | CREATE | Create objects |

4. **Review Database Objects**

   Define:


   Table
   View
   Index
   Stored procedure
   Schema
   Primary key
   Foreign key

5. **Write Example Queries**

   SELECT ProductName, Price
   FROM Products;


   SELECT c.CustomerName, o.OrderDate
   FROM Customers c
   JOIN Orders o ON c.CustomerID = o.CustomerID;


**Validation**

You should have a relational diagram, normalization notes, SQL table, object definitions, and example queries.

**Checkpoint Questions**

1. What is a primary key?
2. What is a foreign key?
3. Why is normalization used?
4. What does SELECT do?

**Exam Focus:** DP-900 expects recognition of relational concepts and common SQL statements, not advanced SQL programming.

#### Lab 4: Azure SQL and Open-Source Databases on Azure

**Objectives**

- Describe the Azure SQL family.
- Compare Azure SQL Database, Azure SQL Managed Instance, and SQL Server on Azure VMs.
- Identify open-source database services on Azure.
- Match relational services to scenarios.

**Scenario**

The retail company wants to migrate existing relational databases to Azure. Some apps use SQL Server, while others use PostgreSQL and MySQL.

**Step-by-step**

1. **Compare Azure SQL Options**

   | Service | Best Fit |
   | --- | --- |
   | Azure SQL Database | Modern cloud app needing managed PaaS database |
   | Azure SQL Managed Instance | SQL Server compatibility with managed service benefits |
   | SQL Server on Azure VMs | Maximum OS and instance-level control |

2. **Compare Open-Source Database Services**

   Document:


   Azure Database for PostgreSQL
   Azure Database for MySQL
   Azure Database for MariaDB legacy considerations

3. **Match Migration Scenarios**

   Choose a service:


   1. New cloud-native app using SQL Server engine.
   2. Existing SQL Server app needing instance-level compatibility.
   3. Legacy app requiring OS-level control.
   4. Web app using PostgreSQL.
   5. App using MySQL.

4. **Review Managed Service Benefits**

   Write how managed database services help with:


   - Patching.
   - Backup.
   - High availability.
   - Scaling.
   - Monitoring.
   - Security.

5. **Security and Cost Notes**

   Document:


   Authentication
   Firewall or private access
   Backup retention
   Performance tier
   Scaling choice


**Validation**

You should have comparison tables, scenario answers, managed service benefits, and security/cost notes.

**Checkpoint Questions**

1. When is Azure SQL Database appropriate?
2. Why choose SQL Server on Azure VMs?
3. What is a managed database service?
4. Which Azure services support PostgreSQL and MySQL?

**Exam Focus:** Know the Azure relational database service families and when each option fits.

### Topic 03: Non-Relational Data on Azure

Azure Storage, Blob, Files, Tables and Cosmos DB

#### Lab 5: Azure Storage, Blob, Files, Tables

**Objectives**

- Describe Azure Blob Storage.
- Describe Azure Files.
- Describe Azure Table Storage.
- Match storage services to scenarios.
- Review access tiers and redundancy concepts.

**Scenario**

The retail company needs to store product images, shared documents, application logs, and simple key-value data.

**Step-by-step**

1. **Map Storage Needs**

   | Requirement | Azure Storage Service |
   | --- | --- |
   | Product images | Blob Storage |
   | Shared file share | Azure Files |
   | Simple key-value customer preferences | Table Storage |
   | Queue messages | Azure Queue Storage |

2. **Review Blob Storage Concepts**

   Define:


   Container
   Blob
   Block blob
   Access tier
   Lifecycle management

3. **Review Azure Files Concepts**

   Explain:


   - SMB and NFS file shares.
   - Lift-and-shift file server scenarios.
   - Shared access for applications.

4. **Review Table Storage Concepts**

   Explain:


   - Partition key.
   - Row key.
   - Entity.
   - Schemaless design.

5. **Compare Redundancy**

   Write a short note on locally redundant, zone-redundant, and geo-redundant storage.


**Validation**

You should have storage mappings, concept definitions, and redundancy notes.

**Checkpoint Questions**

1. When should you use Blob Storage?
2. When should you use Azure Files?
3. What is Azure Table Storage?
4. Why does redundancy matter?

**Exam Focus:** DP-900 expects recognition of Azure Storage services and their common use cases.

#### Lab 6: Azure Cosmos DB, NoSQL, APIs

**Objectives**

- Explain non-relational data concepts.
- Describe Azure Cosmos DB capabilities.
- Identify common Cosmos DB APIs.
- Match NoSQL patterns to scenarios.

**Scenario**

The retail company wants a globally distributed product catalog and user profile store that can handle flexible schemas and low-latency reads.

**Step-by-step**

1. **Explain NoSQL Fit**

   Write why NoSQL can help with:


   - Flexible schema.
   - High scale.
   - Global distribution.
   - Low-latency access.
   - JSON document data.

2. **Review Cosmos DB Capabilities**

   Document:


   Global distribution
   Low latency
   Throughput with request units
   Partitioning
   Consistency levels
   Multiple APIs

3. **Identify Cosmos DB APIs**

   Create a table:


   | API | Common Fit |
   | --- | --- |
   | NoSQL | JSON document applications |
   | MongoDB | MongoDB-compatible apps |
   | Cassandra | Wide-column workloads |
   | Gremlin | Graph workloads |
   | Table | Key-value/table workloads |

4. **Design a Product Catalog Document**

   Create example JSON:


   {
     "id": "P1001",
     "category": "Laptop",
     "name": "Training Laptop",
     "price": 1200,
     "tags": ["business", "portable"]
   }

5. **Review Partitioning**

   Explain why a good partition key distributes data and workload evenly.


**Validation**

You should have NoSQL notes, Cosmos DB capability notes, API mapping, sample document, and partition key explanation.

**Checkpoint Questions**

1. When is Cosmos DB a good fit?
2. What is a request unit?
3. Why does partitioning matter?
4. Which API supports graph workloads?

**Exam Focus:** Know Cosmos DB capabilities, APIs, and common NoSQL use cases.

### Topic 04: Analytics Workloads on Azure

Ingestion, processing, analytical stores, Fabric, Databricks and real-time analytics

#### Lab 7: Analytics, Ingestion, Processing, Analytical Data Stores

**Objectives**

- Describe analytics workload stages.
- Explain data ingestion and processing.
- Compare batch and streaming.
- Identify analytical data stores.
- Map services to analytics scenarios.

**Scenario**

The retail company wants daily sales reports, customer behavior analytics, and near-real-time alerting from web clickstream data.

**Step-by-step**

1. **Map an Analytics Pipeline**

   Create a flow:


   Data sources
   Ingestion
   Raw storage
   Transformation
   Analytical store
   Semantic model
   Visualization

2. **Compare Batch and Streaming**

   | Mode | Description | Example |
   | --- | --- | --- |
   | Batch | Processes data in groups on a schedule | Daily sales summary |
   | Streaming | Processes events continuously | Live website activity |

3. **Identify Analytical Stores**

   Document:


   Data lake
   Data warehouse
   Lakehouse
   Semantic model

4. **Choose Azure Services**

   | Need | Possible Service |
   | --- | --- |
   | Data ingestion and orchestration | Data Factory or Fabric Data Factory |
   | Big data processing | Azure Databricks |
   | Lakehouse analytics | Microsoft Fabric |
   | Real-time event processing | Event Hubs, Stream Analytics, Fabric Real-Time Intelligence |
   | Visualization | Power BI |

5. **Review Data Transformation**

   Explain the difference between raw, cleaned, curated, and aggregated data.


**Validation**

You should have pipeline diagram, batch/streaming comparison, analytical store notes, and service mapping.

**Checkpoint Questions**

1. What is data ingestion?
2. What is the difference between batch and streaming?
3. What is a data warehouse?
4. What is a lakehouse?

**Exam Focus:** DP-900 analytics questions test high-level pipeline patterns and service selection.

#### Lab 8: Microsoft Fabric, Azure Databricks, Real-Time Analytics

**Objectives**

- Describe Microsoft Fabric at a high level.
- Describe Azure Databricks use cases.
- Identify real-time analytics services.
- Match analytics services to scenarios.

**Scenario**

The retail company is comparing analytics platforms for reporting, data engineering, machine learning, and real-time dashboards.

**Step-by-step**

1. **Review Microsoft Fabric Concepts**

   Document:


   OneLake
   Lakehouse
   Warehouse
   Data Factory
   Real-Time Intelligence
   Power BI

2. **Review Azure Databricks Concepts**

   Explain how Databricks can support:


   - Apache Spark processing.
   - Data engineering notebooks.
   - Machine learning workloads.
   - Delta Lake patterns.
   - Collaborative analytics.

3. **Identify Real-Time Analytics**

   Match:


   | Requirement | Possible Service |
   | --- | --- |
   | Ingest event streams | Event Hubs |
   | Process streaming data | Stream Analytics |
   | Real-time analytics in Fabric | Real-Time Intelligence |
   | Visualize live metrics | Power BI real-time dashboards |

4. **Compare Services**

   Create a decision table:


   | Scenario | Better Fit |
   | --- | --- |
   | Business reporting workspace | Microsoft Fabric |
   | Spark-heavy engineering workloads | Azure Databricks |
   | Simple stream processing | Azure Stream Analytics |
   | Event ingestion at scale | Event Hubs |

5. **Draw an Analytics Architecture**

   Point of sale -> Event stream -> Real-time processing -> Dashboard
   Daily exports -> Lakehouse -> Transformations -> Power BI report


**Validation**

You should have Fabric notes, Databricks notes, real-time service mapping, and architecture diagram.

**Checkpoint Questions**

1. What is Microsoft Fabric?
2. What is Azure Databricks commonly used for?
3. What is real-time analytics?
4. Which service can ingest event streams?

**Exam Focus:** Know the high-level purpose of Fabric, Databricks, and Microsoft real-time analytics services.

### Topic 05: Power BI and Exam Readiness

Models, visualizations, service mapping and capstone review

#### Lab 9: Power BI, Data Models, Visualizations

**Objectives**

- Describe Power BI capabilities.
- Explain data models and semantic models.
- Choose appropriate visualizations.
- Build a simple report plan.

**Scenario**

The retail company wants a dashboard for sales, products, regions, and trends. You must explain how Power BI supports data analysis.

**Step-by-step**

1. **Identify Power BI Components**

   Document:


   Power BI Desktop
   Power BI service
   Dataset or semantic model
   Report
   Dashboard
   Workspace
   Data refresh

2. **Design a Simple Data Model**

   Create tables:


   Sales
   Products
   Customers
   Dates
   Regions


   Identify relationships and keys.

3. **Choose Visualizations**

   | Question | Visualization |
   | --- | --- |
   | Sales by month | Line chart |
   | Sales by product category | Bar chart |
   | Sales by region | Map or filled map |
   | Market share by category | Donut chart or treemap |
   | Detailed sales records | Table |

4. **Add Measures and Filters**

   Define examples:


   Total Sales
   Order Count
   Average Order Value
   Year
   Region
   Product Category

5. **Review Good Dashboard Design**

   Write five rules for clear dashboards, such as consistent labels, useful filters, and avoiding clutter.


**Validation**

You should have Power BI component notes, data model design, visualization choices, and dashboard rules.

**Checkpoint Questions**

1. What is Power BI used for?
2. What is a semantic model?
3. Why are relationships important?
4. Which visualization is suitable for trends over time?

**Exam Focus:** Power BI questions test capabilities, data models, and choosing appropriate visualizations.

#### Lab 10: DP-900 Capstone and Exam Readiness

**Objectives**

- Review all DP-900 skill areas.
- Design an end-to-end Azure data platform.
- Match data scenarios to Azure services.
- Build a personal exam study plan.
- Clean up lab resources.

**Scenario**

The retail company asks for a data platform recommendation that supports transactions, product images, customer profiles, analytics, real-time events, and dashboards.

**Step-by-step**

1. **Build a Service Map**

   | Requirement | Data Type or Workload | Azure Service |
   | --- | --- | --- |
   | Online orders | Transactional relational | Azure SQL Database |
   | Product images | Unstructured object data | Blob Storage |
   | Shared files | File storage | Azure Files |
   | Flexible product catalog | NoSQL document data | Azure Cosmos DB |
   | Daily analytics | Analytical workload | Fabric lakehouse or warehouse |
   | Event stream | Streaming workload | Event Hubs or Stream Analytics |
   | Reports | Visualization | Power BI |

2. **Draw the Architecture**

   Include:


   Transactional applications
   Operational databases
   Storage accounts
   Ingestion pipelines
   Analytical store
   Power BI reports
   Real-time event path

3. **Review DP-900 Skill Areas**

   Rate confidence:


   | Skill Area | Confidence 1-5 | Study Action |
   | --- | --- | --- |
   | Core data concepts |  |  |
   | Relational data on Azure |  |  |
   | Non-relational data on Azure |  |  |
   | Analytics workloads on Azure |  |  |

4. **Build an Exam Mistakes Log**

   For missed questions, record:


   Topic:
   Wrong assumption:
   Correct concept:
   Service to review:

5. **Clean Up Resources**

   If you created resources:


   az group delete --name rg-dp900-lab --yes --no-wait


   Confirm with your instructor before deleting shared resources.

6. **Create a 7-Day Study Plan**

   1. Day 1: Core data concepts and workload types.
   2. Day 2: Relational concepts and SQL.
   3. Day 3: Azure SQL and open-source databases.
   4. Day 4: Azure Storage and Cosmos DB.
   5. Day 5: Analytics pipelines and data stores.
   6. Day 6: Fabric, Databricks, real-time analytics, Power BI.
   7. Day 7: Practice assessment and mistakes log review.


**Validation**

You should have a service map, architecture diagram, confidence matrix, study plan, and cleanup confirmation.

**Checkpoint Questions**

1. Which Azure data service is easiest for you to identify?
2. Which service names are most confusing?
3. What is the difference between transactional and analytical data?
4. What will you review before exam day?

**Exam Focus:** DP-900 rewards service recognition and concept clarity. Focus on what each data service is for, not deep administration tasks.

## Assessment Flow

1. TRAQOM: scan the QR code on the LMS.
2. Take Assessment digital attendance.
3. Complete Written Assessment and Practical Performance.
4. Submit answers on the LMS.
5. Sign the Assessment Summary Record.
