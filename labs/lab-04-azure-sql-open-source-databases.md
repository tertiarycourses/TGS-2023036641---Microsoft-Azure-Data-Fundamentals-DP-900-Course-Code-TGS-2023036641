# Lab 04 - Azure SQL and Open-Source Databases on Azure

## Objectives

- Describe the Azure SQL family.
- Compare Azure SQL Database, Azure SQL Managed Instance, and SQL Server on Azure VMs.
- Identify open-source database services on Azure.
- Match relational services to scenarios.

## Scenario

The retail company wants to migrate existing relational databases to Azure. Some apps use SQL Server, while others use PostgreSQL and MySQL.

## Steps

### 1. Compare Azure SQL Options

| Service | Best Fit |
| --- | --- |
| Azure SQL Database | Modern cloud app needing managed PaaS database |
| Azure SQL Managed Instance | SQL Server compatibility with managed service benefits |
| SQL Server on Azure VMs | Maximum OS and instance-level control |

### 2. Compare Open-Source Database Services

Document:

```text
Azure Database for PostgreSQL
Azure Database for MySQL
Azure Database for MariaDB legacy considerations
```

### 3. Match Migration Scenarios

Choose a service:

1. New cloud-native app using SQL Server engine.
2. Existing SQL Server app needing instance-level compatibility.
3. Legacy app requiring OS-level control.
4. Web app using PostgreSQL.
5. App using MySQL.

### 4. Review Managed Service Benefits

Write how managed database services help with:

- Patching.
- Backup.
- High availability.
- Scaling.
- Monitoring.
- Security.

### 5. Security and Cost Notes

Document:

```text
Authentication
Firewall or private access
Backup retention
Performance tier
Scaling choice
```

## Validation

You should have comparison tables, scenario answers, managed service benefits, and security/cost notes.

## Checkpoint Questions

1. When is Azure SQL Database appropriate?
2. Why choose SQL Server on Azure VMs?
3. What is a managed database service?
4. Which Azure services support PostgreSQL and MySQL?

## Exam Focus

Know the Azure relational database service families and when each option fits.
