---
title: "Worklog Tuần 4"
date: 2026-07-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

# Worklog Tuần 4: Amazon RDS, VPC, DB Subnet Group và kết nối EC2 tới Database

**Thời gian thực hiện:** 11/05/2026 - 15/05/2026

## 1. Mục tiêu tuần

- Tìm hiểu kiến trúc và làm chủ Amazon RDS trên AWS.
- Quy hoạch hạ tầng VPC và DB Subnet Group cho cơ sở dữ liệu.
- Cấu hình Security Group để cách ly database và chỉ cho phép EC2 truy cập.
- Cài đặt công cụ truy xuất, xử lý lỗi phát sinh và kết nối từ EC2 tới RDS.
- Nắm quy trình Backup/Snapshot và Cleanup để tối ưu chi phí Cloud.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Khởi tạo Custom VPC, định tuyến mạng và DB Subnet Group. |  |
| Thứ 3 | Tạo EC2 Security Group và RDS Security Group; mở luồng nội bộ qua cổng 3306. |  |
| Thứ 4 | Khởi chạy EC2 Web Server và Amazon RDS Database Instance MySQL. |  |
| Thứ 5 | Cài MySQL Client trên EC2, xử lý lỗi GPG và kết nối an toàn tới RDS Endpoint. |  |
| Thứ 6 | Xử lý lỗi timeout bằng Security Group, hoàn tất lab và dọn dẹp EC2/RDS. |  |

## 3. Kết quả đạt được

- Cấu hình thành công kiến trúc mạng VPC và Security Group bảo vệ database.
- Nắm vững vòng đời quản trị cơ sở dữ liệu trên Cloud từ khởi tạo, cấu hình đến vận hành.
- Rèn luyện kỹ năng troubleshooting qua lỗi GPG và Connection Timeout.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000005 - Amazon RDS | [https://000005.awsstudygroup.com/vi/](https://000005.awsstudygroup.com/vi/) | VPC, DB Subnet Group, RDS instance, EC2 connection and deployment. |
