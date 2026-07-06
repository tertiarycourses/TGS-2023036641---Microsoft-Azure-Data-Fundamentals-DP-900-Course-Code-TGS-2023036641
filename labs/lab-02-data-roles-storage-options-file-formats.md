# Lab 02 - Data Roles, Storage Options, File Formats

## Objectives

- Identify data workload roles and responsibilities.
- Compare common file formats.
- Match storage options to use cases.
- Understand common data store categories.

## Scenario

The retail company is forming a data team. Management asks which people and services are needed for databases, pipelines, analytics, and reports.

## Steps

### 1. Identify Data Roles

Create a table:

| Role | Main Responsibility |
| --- | --- |
| Database administrator | Manage database availability, performance, backup, and security |
| Data engineer | Build data pipelines and prepare data for analytics |
| Data analyst | Build reports, models, and insights |

Add examples of tasks for each role.

### 2. Compare File Formats

| Format | Common Use |
| --- | --- |
| CSV | Simple tabular exchange |
| JSON | Semi-structured API and event data |
| Parquet | Columnar analytics data |
| XML | Structured document exchange |
| Avro | Data serialization in pipelines |

### 3. Match Storage Options

| Requirement | Possible Store |
| --- | --- |
| Store images and backups | Blob storage |
| Shared file access | Azure Files |
| Key-value style entities | Azure Table Storage |
| Relational application database | Azure SQL Database |
| Globally distributed NoSQL app | Azure Cosmos DB |
| Large-scale analytics | Data lake, warehouse, Fabric lakehouse |

### 4. Draw a Simple Data Platform

Use diagrams.net:

```text
Source systems -> Ingestion -> Storage -> Processing -> Analytics -> Visualization
```

### 5. Record Service Selection Rules

Write one sentence for when to use relational, non-relational, object storage, and analytical stores.

## Validation

You should have role notes, file format comparison, storage mapping, and a platform diagram.

## Checkpoint Questions

1. What does a data engineer do?
2. Why is Parquet common in analytics?
3. When would Blob storage be appropriate?
4. Why do analytics platforms separate storage and compute?

## Exam Focus

Know the roles and responsibilities for data workloads and common storage formats.
