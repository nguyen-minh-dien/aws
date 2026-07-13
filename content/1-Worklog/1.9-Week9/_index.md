---
title: "Worklog Week 9"
date: 2026-07-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

# Worklog Week 9: DevOps CI/CD, Amazon FSx and IAM Permission Boundary

**Time:** 15/06/2026 - 19/06/2026

## 1. Weekly objectives

- Studied DevOps, CI/CD and EC2 application deployment with CodePipeline, CodeBuild and CodeDeploy.
- Prepared infrastructure including EC2, S3 Bucket, Git credential, Service Role and Instance Profile.
- Installed CodeDeploy Agent, created source repository, configured build project and deployed Node.js to EC2.
- Studied Amazon FSx for Windows File Server and SMB file shares.
- Practiced IAM Permission Boundary to limit user permissions.

## 2. Implementation details

| Day | Work details | Date |
| --- | --- | --- |
| Mon | Studied DevOps/CI/CD and roles of CodeCommit, CodeBuild, CodeDeploy, CodePipeline, CloudWatch Events, S3 and KMS. |  |
| Tue | Prepared EC2, S3 Bucket, Git credential, Git connection, Service Role, IAM User, Instance Profile and CodeDeploy Agent. |  |
| Wed | Created repository, CodeBuild project, CodeDeploy Application/Deployment Group and CodePipeline. |  |
| Thu | Deployed Amazon FSx for Windows File Server, created Multi-AZ file systems and mapped file shares. |  |
| Fri | Tested FSx performance, enabled dedup/shadow copies/quota; practiced IAM Permission Boundary and cleaned up. |  |

## 3. Achieved results

- Understood DevOps and CI/CD roles in automating build, test and deployment.
- Configured CodeBuild, CodeDeploy, Deployment Group and CodePipeline for Node.js deployment to EC2.
- Created and used Amazon FSx file shares and mapped network drives on Windows EC2.
- Understood IAM Permission Boundary and effective permissions as intersection between identity policy and boundary.
- Improved application deployment, security management and AWS file storage operations skills.

## 4. Reference sources

| Source | URL | Reference content |
| --- | --- | --- |
| 000023 - CodePipeline to EC2 | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) | CodeCommit, CodeBuild, CodeDeploy, CodePipeline, S3 và KMS. |
| 000025 - Amazon FSx for Windows File Server | [https://000025.awsstudygroup.com/](https://000025.awsstudygroup.com/) | File share SMB, Multi-AZ file system, monitoring và quản trị FSx. |
| 000030 - IAM Permission Boundary | [https://000030.awsstudygroup.com/](https://000030.awsstudygroup.com/) | Restriction policy, limited IAM User và kiểm tra giới hạn quyền. |
