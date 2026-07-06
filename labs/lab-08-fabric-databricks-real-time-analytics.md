# Lab 08 - Microsoft Fabric, Azure Databricks, Real-Time Analytics

## Objectives

- Describe Microsoft Fabric at a high level.
- Describe Azure Databricks use cases.
- Identify real-time analytics services.
- Match analytics services to scenarios.

## Scenario

The retail company is comparing analytics platforms for reporting, data engineering, machine learning, and real-time dashboards.

## Steps

### 1. Review Microsoft Fabric Concepts

Document:

```text
OneLake
Lakehouse
Warehouse
Data Factory
Real-Time Intelligence
Power BI
```

### 2. Review Azure Databricks Concepts

Explain how Databricks can support:

- Apache Spark processing.
- Data engineering notebooks.
- Machine learning workloads.
- Delta Lake patterns.
- Collaborative analytics.

### 3. Identify Real-Time Analytics

Match:

| Requirement | Possible Service |
| --- | --- |
| Ingest event streams | Event Hubs |
| Process streaming data | Stream Analytics |
| Real-time analytics in Fabric | Real-Time Intelligence |
| Visualize live metrics | Power BI real-time dashboards |

### 4. Compare Services

Create a decision table:

| Scenario | Better Fit |
| --- | --- |
| Business reporting workspace | Microsoft Fabric |
| Spark-heavy engineering workloads | Azure Databricks |
| Simple stream processing | Azure Stream Analytics |
| Event ingestion at scale | Event Hubs |

### 5. Draw an Analytics Architecture

```text
Point of sale -> Event stream -> Real-time processing -> Dashboard
Daily exports -> Lakehouse -> Transformations -> Power BI report
```

## Validation

You should have Fabric notes, Databricks notes, real-time service mapping, and architecture diagram.

## Checkpoint Questions

1. What is Microsoft Fabric?
2. What is Azure Databricks commonly used for?
3. What is real-time analytics?
4. Which service can ingest event streams?

## Exam Focus

Know the high-level purpose of Fabric, Databricks, and Microsoft real-time analytics services.
