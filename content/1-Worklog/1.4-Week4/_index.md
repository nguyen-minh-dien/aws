---
title: "Worklog Week 4"
date: 2026-07-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

# Worklog Week 4: Amazon RDS, VPC, DB Subnet Group and EC2-to-database connection

**Time:** 11/05/2026 - 15/05/2026

## 1. Weekly objectives

- Studied Amazon RDS architecture and administration.
- Planned VPC infrastructure and DB Subnet Group for the database.
- Configured Security Groups to isolate the database and allow EC2 access only.
- Installed database clients, troubleshot issues and connected from EC2 to RDS.
- Practiced Backup/Snapshot and Cleanup to optimize cloud cost.

## 2. Implementation details

| Day | Work details | Date |
| --- | --- | --- |
| Mon | Created Custom VPC, routing configuration and DB Subnet Group. |  |
| Tue | Created EC2 Security Group and RDS Security Group; opened internal traffic on port 3306. |  |
| Wed | Launched EC2 Web Server and Amazon RDS MySQL database instance. |  |
| Thu | Installed MySQL Client on EC2, fixed GPG issues and connected securely to RDS endpoint. |  |
| Fri | Resolved timeout issues by tuning Security Groups, completed lab and cleaned up EC2/RDS. |  |

## 3. Achieved results

- Configured VPC network architecture and Security Groups to protect the database.
- Understood the cloud database lifecycle from creation and configuration to operation.
- Practiced troubleshooting with GPG and Connection Timeout issues.

## 4. Reference sources

| Source | URL | Reference content |
| --- | --- | --- |
| 000005 - Amazon RDS | [https://000005.awsstudygroup.com/vi/](https://000005.awsstudygroup.com/vi/) | VPC, DB Subnet Group, RDS instance, EC2 connection and deployment. |
