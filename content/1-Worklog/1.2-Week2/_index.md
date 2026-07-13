---
title: "Worklog Week 2"
date: 2026-07-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

# Worklog Week 2: IAM administration, MFA and AWS CLI

**Time:** 27/04/2026 - 01/05/2026

## 1. Weekly objectives

- Understood AWS security best practices by limiting daily use of the Root account.
- Practiced IAM identity management, users, groups and permissions.
- Configured multi-factor authentication (MFA).
- Set up secure access from local computer to AWS using AWS CLI.

## 2. Implementation details

| Day | Work details | Date |
| --- | --- | --- |
| Mon | Created IAM User admin-thuctap and IAM Group admins; attached AdministratorAccess to the group. | 27/04/2026 |
| Tue | Enabled MFA for the admin user; created Access Key for AWS CLI configuration. | 28/04/2026 |
| Wed | Configured AWS CLI identity locally and set default Region to ap-southeast-1. | 29/04/2026 |
| Thu | Practiced IAM-related AWS CLI commands to inspect and manage resources. | 30/04/2026 |
| Fri | Checked MFA/security configuration via CLI and summarized created IAM resources. | 01/05/2026 |

## 3. Achieved results

- Created IAM User and IAM Group with AdministratorAccess policy.
- Enabled MFA for the admin account.
- Configured AWS CLI locally using Access Key credentials.
- Used commands such as sts get-caller-identity, iam list-users and iam list-groups for resource administration.

## 4. Reference sources

| Source | URL | Reference content |
| --- | --- | --- |
| 000002 - AWS IAM | [https://000002.awsstudygroup.com/vi/](https://000002.awsstudygroup.com/vi/) | Tạo IAM User/Group, policy, role và bảo mật quyền truy cập. |
| 000011 - AWS CLI | [https://000011.awsstudygroup.com/vi/](https://000011.awsstudygroup.com/vi/) | Cấu hình profile, kiểm tra tài nguyên và thao tác qua CLI. |
