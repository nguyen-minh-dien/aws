---
title: "Worklog Tuần 9"
date: 2026-07-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

# Worklog Tuần 9: DevOps CI/CD, Amazon FSx và IAM Permission Boundary

**Thời gian thực hiện:** 15/06/2026 - 19/06/2026

## 1. Mục tiêu tuần

- Tìm hiểu DevOps, CI/CD và triển khai ứng dụng lên EC2 bằng CodePipeline, CodeBuild và CodeDeploy.
- Chuẩn bị hạ tầng gồm EC2, S3 Bucket, Git credential, Service Role và Instance Profile.
- Cài CodeDeploy Agent, tạo nguồn mã, cấu hình build project và deploy Node.js lên EC2.
- Tìm hiểu Amazon FSx for Windows File Server và file share qua SMB.
- Thực hành IAM Permission Boundary để giới hạn quyền user.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Nghiên cứu DevOps/CI/CD và vai trò CodeCommit, CodeBuild, CodeDeploy, CodePipeline, CloudWatch Events, S3, KMS. |  |
| Thứ 3 | Chuẩn bị hạ tầng: EC2, S3 Bucket, Git credential, Git connection, Service Role, IAM User, Instance Profile, CodeDeploy Agent. |  |
| Thứ 4 | Tạo repository, CodeBuild project, CodeDeploy Application/Deployment Group và CodePipeline. |  |
| Thứ 5 | Triển khai Amazon FSx for Windows File Server, tạo file system Multi-AZ và ánh xạ file share. |  |
| Thứ 6 | Kiểm tra hiệu năng FSx, bật dedup/shadow copies/quota; thực hành IAM Permission Boundary và cleanup. |  |

## 3. Kết quả đạt được

- Hiểu vai trò DevOps và CI/CD trong tự động hóa build, test và deploy.
- Cấu hình CodeBuild, CodeDeploy, Deployment Group và CodePipeline để triển khai Node.js lên EC2.
- Tạo và sử dụng file share trên Amazon FSx, ánh xạ network drive trên EC2 Windows.
- Hiểu nguyên tắc IAM Permission Boundary và quyền hiệu lực là phần giao giữa identity policy và boundary.
- Nâng cao kỹ năng triển khai ứng dụng, quản trị bảo mật và vận hành lưu trữ file trên AWS.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000023 - CodePipeline to EC2 | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) | CodeCommit, CodeBuild, CodeDeploy, CodePipeline, S3 và KMS. |
| 000025 - Amazon FSx for Windows File Server | [https://000025.awsstudygroup.com/](https://000025.awsstudygroup.com/) | File share SMB, Multi-AZ file system, monitoring và quản trị FSx. |
| 000030 - IAM Permission Boundary | [https://000030.awsstudygroup.com/](https://000030.awsstudygroup.com/) | Restriction policy, limited IAM User và kiểm tra giới hạn quyền. |
