---
title: "Worklog Tuần 2"
date: 2026-07-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

# Worklog Tuần 2: Quản trị IAM, MFA và AWS CLI

**Thời gian thực hiện:** 27/04/2026 - 01/05/2026

## 1. Mục tiêu tuần

- Nắm vững chuẩn bảo mật AWS bằng cách hạn chế sử dụng tài khoản Root cho tác vụ hàng ngày.
- Thành thạo IAM để quản lý danh tính, phân quyền người dùng và nhóm người dùng.
- Thiết lập cơ chế bảo mật nâng cao thông qua xác thực đa yếu tố (MFA).
- Triển khai kết nối an toàn từ máy tính cá nhân tới AWS thông qua AWS CLI.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Tạo IAM User admin-thuctap và IAM Group admins; phân quyền AdministratorAccess cho nhóm. | 27/04/2026 |
| Thứ 3 | Kích hoạt MFA cho user quản trị; khởi tạo Access Key để cấu hình AWS CLI. | 28/04/2026 |
| Thứ 4 | Cấu hình định danh AWS CLI trên môi trường local, thiết lập Region ap-southeast-1. | 29/04/2026 |
| Thứ 5 | Thực hành lệnh AWS CLI với IAM để kiểm tra và quản lý tài nguyên. | 30/04/2026 |
| Thứ 6 | Kiểm tra cấu hình bảo mật MFA qua CLI và tổng kết tài nguyên IAM đã khởi tạo. | 01/05/2026 |

## 3. Kết quả đạt được

- Khởi tạo thành công IAM User và IAM Group với chính sách AdministratorAccess.
- Kích hoạt thành công MFA cho tài khoản quản trị.
- Cấu hình AWS CLI trên môi trường local bằng Access Key.
- Thực hiện được các lệnh như sts get-caller-identity, iam list-users, iam list-groups để quản trị tài nguyên.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000002 - AWS IAM | [https://000002.awsstudygroup.com/vi/](https://000002.awsstudygroup.com/vi/) | Tạo IAM User/Group, policy, role và bảo mật quyền truy cập. |
| 000011 - AWS CLI | [https://000011.awsstudygroup.com/vi/](https://000011.awsstudygroup.com/vi/) | Cấu hình profile, kiểm tra tài nguyên và thao tác qua CLI. |
