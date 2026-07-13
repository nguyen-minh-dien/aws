---
title: "Worklog Tuần 11"
date: 2026-07-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

# Worklog Tuần 11: Amazon FSx for Windows File Server

**Thời gian thực hiện:** 29/06/2026 - 03/07/2026

## 1. Mục tiêu tuần

- Tìm hiểu kiến trúc Amazon FSx for Windows File Server và giao thức SMB.
- Tạo môi trường thực hành, triển khai SSD/HDD Multi-AZ file system.
- Tạo và ánh xạ file share, kiểm tra hiệu năng và giám sát dịch vụ.
- Thực hành các tính năng quản trị như data deduplication, shadow copies, session, quota và continuous access.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Nghiên cứu kiến trúc FSx, VPC, ENI, file server và cơ chế replication Multi-AZ. |  |
| Thứ 3 | Tạo môi trường, triển khai SSD Multi-AZ và HDD Multi-AZ file system. |  |
| Thứ 4 | Ánh xạ default file share và tạo file share mới phục vụ kiểm thử. |  |
| Thứ 5 | Kiểm tra hiệu năng, theo dõi metrics và log giám sát FSx. |  |
| Thứ 6 | Bật deduplication, shadow copies, quản lý user sessions/open files, quota và cleanup. |  |

## 3. Kết quả đạt được

- Hiểu kiến trúc FSx gồm file server, storage, VPC, ENI, replication và monitoring.
- Tạo được file system Multi-AZ và ánh xạ network drive trên Windows EC2.
- Kiểm tra được truy cập dữ liệu qua SMB và hiệu năng file share.
- Thực hành các tác vụ quản trị FSx giúp tối ưu vận hành hệ thống lưu trữ file.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000025 - Amazon FSx for Windows File Server | [https://000025.awsstudygroup.com/](https://000025.awsstudygroup.com/) | Create environment, file systems, file shares, performance test, monitoring and administration. |
