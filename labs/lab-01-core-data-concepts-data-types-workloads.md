# Lab 01 - Core Data Concepts, Data Types, Workloads

## Objectives

- Distinguish structured, semi-structured, and unstructured data.
- Compare transactional and analytical workloads.
- Identify common data store use cases.
- Build a data concepts glossary.

## Scenario

A retail company stores sales transactions, customer profiles, product images, web logs, invoices, and analytics reports. You must classify the data and decide which workloads are transactional or analytical.

## Steps

### 1. Classify Data Types

Create a table:

| Data Example | Type | Reason |
| --- | --- | --- |
| Sales order table | Structured | Fixed rows and columns |
| JSON web event | Semi-structured | Flexible fields with structure |
| Product photo | Unstructured | Binary media file |

Add at least five more examples.

### 2. Compare Workloads

Create a table:

| Workload | Purpose | Example |
| --- | --- | --- |
| Transactional | Supports day-to-day operations | Online order processing |
| Analytical | Supports reporting and insight | Monthly sales trend analysis |

### 3. Identify Workload Characteristics

For each scenario, choose transactional or analytical:

1. Insert a customer order.
2. Update inventory quantity.
3. Analyze five years of sales data.
4. Create a Power BI dashboard.
5. Stream click events for real-time monitoring.

### 4. Create a Glossary

Define:

```text
Database
Table
File
Data lake
Data warehouse
Transactional workload
Analytical workload
```

## Validation

You should have a data type table, workload table, classification answers, and glossary.

## Checkpoint Questions

1. What is structured data?
2. What is semi-structured data?
3. Why is unstructured data common in modern systems?
4. How does an analytical workload differ from a transactional workload?

## Exam Focus

DP-900 frequently tests the difference between data representations and workload types.
