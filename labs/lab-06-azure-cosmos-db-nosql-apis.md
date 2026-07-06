# Lab 06 - Azure Cosmos DB, NoSQL, APIs

## Objectives

- Explain non-relational data concepts.
- Describe Azure Cosmos DB capabilities.
- Identify common Cosmos DB APIs.
- Match NoSQL patterns to scenarios.

## Scenario

The retail company wants a globally distributed product catalog and user profile store that can handle flexible schemas and low-latency reads.

## Steps

### 1. Explain NoSQL Fit

Write why NoSQL can help with:

- Flexible schema.
- High scale.
- Global distribution.
- Low-latency access.
- JSON document data.

### 2. Review Cosmos DB Capabilities

Document:

```text
Global distribution
Low latency
Throughput with request units
Partitioning
Consistency levels
Multiple APIs
```

### 3. Identify Cosmos DB APIs

Create a table:

| API | Common Fit |
| --- | --- |
| NoSQL | JSON document applications |
| MongoDB | MongoDB-compatible apps |
| Cassandra | Wide-column workloads |
| Gremlin | Graph workloads |
| Table | Key-value/table workloads |

### 4. Design a Product Catalog Document

Create example JSON:

```json
{
  "id": "P1001",
  "category": "Laptop",
  "name": "Training Laptop",
  "price": 1200,
  "tags": ["business", "portable"]
}
```

### 5. Review Partitioning

Explain why a good partition key distributes data and workload evenly.

## Validation

You should have NoSQL notes, Cosmos DB capability notes, API mapping, sample document, and partition key explanation.

## Checkpoint Questions

1. When is Cosmos DB a good fit?
2. What is a request unit?
3. Why does partitioning matter?
4. Which API supports graph workloads?

## Exam Focus

Know Cosmos DB capabilities, APIs, and common NoSQL use cases.
