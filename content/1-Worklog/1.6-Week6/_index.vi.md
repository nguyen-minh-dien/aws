---
title: "Worklog Tuần 6"
date: 2026-07-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

# Worklog Tuần 6: Docker, Amazon ECR, Amazon ECS/Fargate và CI/CD

**Thời gian thực hiện:** 25/05/2026 - 29/05/2026

## 1. Mục tiêu tuần

- Tìm hiểu kiến trúc Docker Container và quy trình triển khai ứng dụng trên AWS.
- Nắm vững cách sử dụng Amazon ECR để lưu trữ Docker Images.
- Triển khai hệ thống bằng Amazon ECS và AWS Fargate.
- Hiểu quy trình xây dựng CI/CD Pipeline phục vụ tự động hóa Deploy ứng dụng.
- Rèn luyện kỹ năng giám sát hệ thống và dọn dẹp tài nguyên Cloud.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Tìm hiểu Docker Container, cài môi trường, tải source từ GitHub và chạy ứng dụng local bằng Docker. |  |
| Thứ 3 | Cấu hình Amazon RDS, EC2 Instance và Security Group; build Docker Image và push lên Amazon ECR. |  |
| Thứ 4 | Tạo Amazon ECS Cluster bằng Fargate; cấu hình Backend/Frontend Task Definition và ALB. |  |
| Thứ 5 | Triển khai ECS Services cho Frontend/Backend; thử Blue/Green Deployment và Scaling. |  |
| Thứ 6 | Thiết lập CI/CD với GitHub, GitLab, CodeBuild; theo dõi Container Insights và cleanup. |  |

## 3. Kết quả đạt được

- Hiểu quy trình đóng gói ứng dụng bằng Docker và triển khai trên AWS.
- Triển khai Docker Container trên EC2 và lưu trữ image trên Amazon ECR.
- Cấu hình ECS Cluster, Task Definition, ECS Service và Application Load Balancer.
- Thiết lập CI/CD Pipeline để tự động hóa Build và Deploy.
- Theo dõi trạng thái hệ thống bằng CloudWatch Container Insights.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000015 - Docker on AWS | [https://000015.awsstudygroup.com/vi/](https://000015.awsstudygroup.com/vi/) | Docker, RDS, EC2, ECR và Docker Compose. |
| 000016 - Amazon ECS | [https://000016.awsstudygroup.com/vi/](https://000016.awsstudygroup.com/vi/) | ECS Cluster, Task Definition, ALB, ECS Service và Fargate. |
| 000017 - CI/CD with ECS | [https://000017.awsstudygroup.com/](https://000017.awsstudygroup.com/) | GitLab/GitHub Actions/CodeBuild, Container Insights và FireLens. |
