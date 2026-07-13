---
title: "Worklog Tuần 12"
date: 2026-07-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

# Worklog Tuần 12: Giới hạn quyền người dùng với IAM Permission Boundary

**Thời gian thực hiện:** 06/07/2026 - 12/07/2026

## 1. Mục tiêu tuần

- Tổng hợp kiến thức IAM User, Group, Policy và Role trong bối cảnh giới hạn quyền.
- Tìm hiểu IAM Permission Boundary và cách xác định quyền tối đa cho user/group.
- Tạo Restriction Policy và IAM User bị giới hạn quyền.
- Kiểm tra quyền hiệu lực của user theo policy được gán và boundary giới hạn.
- Tổng kết toàn bộ quá trình thực tập và rút ra bài học triển khai AWS.

## 2. Chi tiết công việc triển khai

| Thứ | Nội dung công việc | Thời gian |
| --- | --- | --- |
| Thứ 2 | Nghiên cứu IAM Permission Boundary và tình huống chống leo thang đặc quyền. |  |
| Thứ 3 | Chuẩn bị môi trường IAM, xác định phạm vi quyền cần giới hạn. |  |
| Thứ 4 | Tạo Restriction Policy để giới hạn quyền quản trị theo dịch vụ hoặc Region. |  |
| Thứ 5 | Tạo IAM Limited User, gán policy và Permission Boundary. |  |
| Thứ 6 | Kiểm tra giới hạn quyền, cleanup tài nguyên và tổng kết báo cáo thực tập. |  |

## 3. Kết quả đạt được

- Hiểu được Permission Boundary là lớp giới hạn quyền tối đa cho user/group.
- Tạo được restriction policy và áp dụng cho IAM User.
- Kiểm tra được quyền hiệu lực của user là phần giao giữa identity-based policy và permission boundary.
- Nâng cao nhận thức về least privilege, bảo mật tài khoản và quản trị quyền trên AWS.
- Hoàn thiện nội dung tổng kết quá trình thực tập từ 20/04/2026 đến 12/07/2026.

## 4. Nguồn tài liệu tham khảo

| Nguồn | Đường dẫn | Nội dung tham khảo |
| --- | --- | --- |
| 000030 - IAM Permission Boundary | [https://000030.awsstudygroup.com/](https://000030.awsstudygroup.com/) | Create restriction policy, create limited IAM user, test permissions and cleanup. |
