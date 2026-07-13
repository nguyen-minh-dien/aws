---
title: "Worklog Tuần 7"
date: 2026-07-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

# Worklog Tuần 7: VPC Peering, Network ACL và Cross-Peer DNS

**Thời gian thực hiện:** 01/06/2026 - 05/06/2026

## 1. Mục tiêu tuần

- Tìm hiểu kiến trúc mạng AWS và cơ chế giao tiếp giữa các VPC.
- Triển khai hạ tầng mạng bằng AWS CloudFormation.
- Thực hành tạo Security Group, EC2 Instance và cấu hình Network ACL.
- Tìm hiểu VPC Peering và Cross-Peer DNS Resolution.
- Kiểm tra khả năng kết nối giữa máy chủ thuộc các VPC khác nhau.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Nghiên cứu VPC Peering; khởi tạo My VPC Stack và HG VPC Stack bằng CloudFormation. |  |
| Thứ 3 | Tạo Security Group cho hai VPC; cấu hình Inbound/Outbound rules. |  |
| Thứ 4 | Khởi tạo EC2 Instance trong My VPC và HG VPC; kiểm tra SSH và trạng thái máy chủ. |  |
| Thứ 5 | Cập nhật Network ACL, tạo VPC Peering Connection và cấu hình Route Table. |  |
| Thứ 6 | Kích hoạt Cross-Peer DNS Resolution, kiểm tra ping giữa hai EC2 và cleanup tài nguyên. |  |

## 3. Kết quả đạt được

- Hiểu nguyên lý hoạt động của VPC Peering trong AWS.
- Triển khai hai môi trường mạng độc lập bằng CloudFormation.
- Tạo và cấu hình Security Group cho từng VPC.
- Thiết lập VPC Peering Connection giữa My VPC và HG VPC.
- Cấu hình Network ACL, Route Table và Cross-Peer DNS Resolution.
- Kiểm tra thành công khả năng giao tiếp giữa EC2 thuộc hai VPC khác nhau.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000019 - VPC Peering | [https://000019.awsstudygroup.com/vi/](https://000019.awsstudygroup.com/vi/) | CloudFormation, Security Group, EC2, Network ACL, Peering, Route Table và Cross-Peer DNS. |
