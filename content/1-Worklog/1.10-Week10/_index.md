---
title: "Worklog Week 10"
date: 2026-07-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

# Worklog Week 10: Deploying applications to EC2 with AWS CodePipeline

**Time:** 22/06/2026 - 26/06/2026

## 1. Weekly objectives

- Practiced the complete workflow of deploying an application to EC2 using an automated pipeline.
- Prepared S3 bucket, Git credential, service role, instance profile and CodeDeploy Agent.
- Built a pipeline with source, build and deploy stages to deliver a Node.js application to EC2.
- Checked deployment errors, deployment status and application accessibility after deployment.

## 2. Implementation details

| Day | Work details | Date |
| --- | --- | --- |
| Mon | Reviewed DevOps architecture and CodeCommit/CodeBuild/CodeDeploy/CodePipeline components. |  |
| Tue | Prepared EC2 infrastructure, S3 artifact bucket, Git credential and required IAM roles. |  |
| Wed | Installed CodeDeploy Agent, created application source and configured buildspec. |  |
| Thu | Created CodeDeploy Application, Deployment Group and completed CodePipeline. |  |
| Fri | Tested pipeline, monitored logs, handled errors and cleaned up unused resources. |  |

## 3. Achieved results

- Understood CI/CD flow from source to build and deploy on EC2.
- Understood the role of S3 artifact bucket, CodeBuild project and CodeDeploy Agent.
- Built an automated pipeline to reduce manual deployment steps.
- Learned to inspect pipeline status, logs and handle rollback/update when deployment fails.

## 4. Reference sources

| Source | URL | Reference content |
| --- | --- | --- |
| 000023 - Deploy applications to EC2 with AWS CodePipeline | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) | Preparation, CodeDeploy Agent, CodeBuild, CodeDeploy, CodePipeline và cleanup. |
