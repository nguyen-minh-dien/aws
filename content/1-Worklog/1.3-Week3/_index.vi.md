---
title: "Worklog Tuần 3"
date: 2026-07-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

# Worklog Tuần 3: VPC, Security Group, EC2 Windows/Linux, Snapshot và AMI

**Thời gian thực hiện:** 04/05/2026 - 08/05/2026

## 1. Mục tiêu tuần

- Nắm vững kiến trúc mạng AWS thông qua việc khởi tạo VPC và quy hoạch Subnet.
- Hiểu và cấu hình Security Group để kiểm soát luồng truy cập Inbound/Outbound.
- Triển khai, khởi chạy và kết nối từ xa vào EC2 trên Windows và Linux.
- Nắm bắt phương pháp sao lưu và tối ưu hệ thống bằng Sysprep, EBS Snapshot và Custom AMI.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Khởi tạo hai VPC độc lập Linux-vpc và Windows-vpc; quy hoạch Public Subnet. |  |
| Thứ 3 | Thiết lập Security Group cho Linux và Windows; mở SSH, RDP, HTTP, HTTPS và ICMP. |  |
| Thứ 4 | Khởi chạy 1 Windows-instance và 1 Linux-instance thuộc các VPC tương ứng. |  |
| Thứ 5 | Kết nối Linux bằng MobaXterm/SSH và Windows Server bằng Remote Desktop Connection. |  |
| Thứ 6 | Thực hiện Sysprep, tạo EBS Snapshot 30 GiB và đóng gói Custom AMI. |  |

## 3. Kết quả đạt được

- Xây dựng thành công hệ thống mạng VPC cô lập và cấu hình Subnet rõ ràng.
- Kiểm soát lưu lượng mạng thông qua Security Group đúng với từng loại ứng dụng.
- Làm chủ kỹ năng vận hành và kết nối đa nền tảng hệ điều hành trên Cloud.
- Thiết lập quy trình sao lưu bằng Snapshot và Custom AMI để phục hồi hoặc nhân bản hệ thống.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000003 - Amazon VPC | [https://000003.awsstudygroup.com/vi/](https://000003.awsstudygroup.com/vi/) | Thiết kế VPC, subnet, routing và Site-to-Site VPN. |
| 000004 - Amazon EC2 | [https://000004.awsstudygroup.com/vi/](https://000004.awsstudygroup.com/vi/) | EC2 Windows/Linux, Security Group, EBS Snapshot và AMI. |
