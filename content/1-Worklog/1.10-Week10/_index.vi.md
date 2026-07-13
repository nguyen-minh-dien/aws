---
title: "Worklog Tuần 10"
date: 2026-07-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

# Worklog Tuần 10: Triển khai ứng dụng lên EC2 bằng AWS CodePipeline

**Thời gian thực hiện:** 22/06/2026 - 26/06/2026

## 1. Mục tiêu tuần

- Tập trung thực hành sâu quy trình triển khai ứng dụng lên EC2 bằng pipeline tự động.
- Chuẩn bị S3 bucket, Git credential, service role, instance profile và CodeDeploy Agent.
- Xây dựng pipeline gồm source, build và deploy để đưa ứng dụng Node.js lên EC2.
- Kiểm tra lỗi triển khai, trạng thái deployment và khả năng truy cập ứng dụng sau deploy.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Ôn lại kiến trúc DevOps và các thành phần CodeCommit/CodeBuild/CodeDeploy/CodePipeline. |  |
| Thứ 3 | Chuẩn bị hạ tầng EC2, S3 artifact bucket, Git credential và các IAM role cần thiết. |  |
| Thứ 4 | Cài đặt CodeDeploy Agent, tạo application source và cấu hình buildspec. |  |
| Thứ 5 | Tạo CodeDeploy Application, Deployment Group và hoàn thiện CodePipeline. |  |
| Thứ 6 | Kiểm thử pipeline, theo dõi log, xử lý lỗi và dọn dẹp tài nguyên không sử dụng. |  |

## 3. Kết quả đạt được

- Nắm rõ luồng CI/CD từ source đến build và deploy trên EC2.
- Hiểu vai trò của S3 artifact bucket, CodeBuild project và CodeDeploy Agent.
- Tạo được pipeline tự động giúp giảm thao tác deploy thủ công.
- Biết cách kiểm tra trạng thái pipeline, log và rollback/cập nhật khi triển khai lỗi.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000023 - Deploy applications to EC2 with AWS CodePipeline | [https://000023.awsstudygroup.com/](https://000023.awsstudygroup.com/) | Preparation, CodeDeploy Agent, CodeBuild, CodeDeploy, CodePipeline và cleanup. |
