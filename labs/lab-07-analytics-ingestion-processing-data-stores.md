# Lab 07 - Analytics, Ingestion, Processing, Analytical Data Stores

## Objectives

- Describe analytics workload stages.
- Explain data ingestion and processing.
- Compare batch and streaming.
- Identify analytical data stores.
- Map services to analytics scenarios.

## Scenario

The retail company wants daily sales reports, customer behavior analytics, and near-real-time alerting from web clickstream data.

## Steps

### 1. Map an Analytics Pipeline

Create a flow:

```text
Data sources
Ingestion
Raw storage
Transformation
Analytical store
Semantic model
Visualization
```

### 2. Compare Batch and Streaming

| Mode | Description | Example |
| --- | --- | --- |
| Batch | Processes data in groups on a schedule | Daily sales summary |
| Streaming | Processes events continuously | Live website activity |

### 3. Identify Analytical Stores

Document:

```text
Data lake
Data warehouse
Lakehouse
Semantic model
```

### 4. Choose Azure Services

| Need | Possible Service |
| --- | --- |
| Data ingestion and orchestration | Data Factory or Fabric Data Factory |
| Big data processing | Azure Databricks |
| Lakehouse analytics | Microsoft Fabric |
| Real-time event processing | Event Hubs, Stream Analytics, Fabric Real-Time Intelligence |
| Visualization | Power BI |

### 5. Review Data Transformation

Explain the difference between raw, cleaned, curated, and aggregated data.

## Validation

You should have pipeline diagram, batch/streaming comparison, analytical store notes, and service mapping.

## Checkpoint Questions

1. What is data ingestion?
2. What is the difference between batch and streaming?
3. What is a data warehouse?
4. What is a lakehouse?

## Exam Focus

DP-900 analytics questions test high-level pipeline patterns and service selection.
