---
title: "Worklog Tuần 8"
date: 2026-07-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

# Worklog Tuần 8: AWS Transit Gateway và tối ưu chi phí EC2 bằng Lambda

**Thời gian thực hiện:** 08/06/2026 - 12/06/2026

## 1. Mục tiêu tuần

- Tìm hiểu AWS Transit Gateway và cách kết nối nhiều VPC trong cùng hệ thống.
- Tạo Transit Gateway và cấu hình Transit Gateway Attachments.
- Cấu hình Route Table để các VPC giao tiếp qua Transit Gateway.
- Tìm hiểu giải pháp tối ưu chi phí EC2 bằng AWS Lambda.
- Tạo IAM Role, Lambda Function và tự động bật/tắt EC2 theo lịch trình.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Nghiên cứu kiến trúc Transit Gateway và mô hình hub trung tâm thay cho nhiều VPC Peering. |  |
| Thứ 3 | Tạo Transit Gateway và Transit Gateway Attachments để kết nối các VPC. |  |
| Thứ 4 | Cấu hình Transit Gateway Route Tables và cập nhật Route Tables của các VPC. |  |
| Thứ 5 | Nghiên cứu tối ưu chi phí EC2 bằng Lambda; tạo Tag cho EC2 và IAM Role cho Lambda. |  |
| Thứ 6 | Xây dựng Lambda Function bật/tắt EC2 theo lịch, kiểm tra kết quả và cleanup tài nguyên. |  |

## 3. Kết quả đạt được

- Hiểu nguyên lý AWS Transit Gateway trong kết nối nhiều VPC.
- Tạo Transit Gateway và Transit Gateway Attachments thành công.
- Cấu hình Route Tables để định tuyến lưu lượng giữa các VPC.
- Kiểm tra giao tiếp giữa các EC2 thuộc các VPC khác nhau.
- Xây dựng Lambda Function tự động bật/tắt EC2 để giảm chi phí vận hành.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000020 - AWS Transit Gateway | [https://000020.awsstudygroup.com/vi/](https://000020.awsstudygroup.com/vi/) | Tạo TGW, attachment, route table và định tuyến VPC. |
| 000022 - Optimize EC2 cost with Lambda | [https://000022.awsstudygroup.com/vi/](https://000022.awsstudygroup.com/vi/) | Tạo IAM Role, Lambda start/stop EC2 và kiểm tra kết quả. |
