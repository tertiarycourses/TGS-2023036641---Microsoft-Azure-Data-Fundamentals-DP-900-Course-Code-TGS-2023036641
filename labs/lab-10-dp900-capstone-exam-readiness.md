# Lab 10 - DP-900 Capstone and Exam Readiness

## Objectives

- Review all DP-900 skill areas.
- Design an end-to-end Azure data platform.
- Match data scenarios to Azure services.
- Build a personal exam study plan.
- Clean up lab resources.

## Scenario

The retail company asks for a data platform recommendation that supports transactions, product images, customer profiles, analytics, real-time events, and dashboards.

## Steps

### 1. Build a Service Map

| Requirement | Data Type or Workload | Azure Service |
| --- | --- | --- |
| Online orders | Transactional relational | Azure SQL Database |
| Product images | Unstructured object data | Blob Storage |
| Shared files | File storage | Azure Files |
| Flexible product catalog | NoSQL document data | Azure Cosmos DB |
| Daily analytics | Analytical workload | Fabric lakehouse or warehouse |
| Event stream | Streaming workload | Event Hubs or Stream Analytics |
| Reports | Visualization | Power BI |

### 2. Draw the Architecture

Include:

```text
Transactional applications
Operational databases
Storage accounts
Ingestion pipelines
Analytical store
Power BI reports
Real-time event path
```

### 3. Review DP-900 Skill Areas

Rate confidence:

| Skill Area | Confidence 1-5 | Study Action |
| --- | --- | --- |
| Core data concepts |  |  |
| Relational data on Azure |  |  |
| Non-relational data on Azure |  |  |
| Analytics workloads on Azure |  |  |

### 4. Build an Exam Mistakes Log

For missed questions, record:

```text
Topic:
Wrong assumption:
Correct concept:
Service to review:
```

### 5. Clean Up Resources

If you created resources:

```bash
az group delete --name rg-dp900-lab --yes --no-wait
```

Confirm with your instructor before deleting shared resources.

### 6. Create a 7-Day Study Plan

1. Day 1: Core data concepts and workload types.
2. Day 2: Relational concepts and SQL.
3. Day 3: Azure SQL and open-source databases.
4. Day 4: Azure Storage and Cosmos DB.
5. Day 5: Analytics pipelines and data stores.
6. Day 6: Fabric, Databricks, real-time analytics, Power BI.
7. Day 7: Practice assessment and mistakes log review.

## Validation

You should have a service map, architecture diagram, confidence matrix, study plan, and cleanup confirmation.

## Checkpoint Questions

1. Which Azure data service is easiest for you to identify?
2. Which service names are most confusing?
3. What is the difference between transactional and analytical data?
4. What will you review before exam day?

## Exam Focus

DP-900 rewards service recognition and concept clarity. Focus on what each data service is for, not deep administration tasks.
