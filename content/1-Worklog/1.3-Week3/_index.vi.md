---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:
* Nắm vững kiến thức quản lý cơ sở dữ liệu quan hệ với Amazon RDS.
* Triển khai ứng dụng mở rộng tự động và cân bằng tải (Auto Scaling & ELB).
* Quản lý, kiểm soát và tối ưu hóa chi phí bằng AWS Budgets.
* Giám sát toàn diện hệ thống, tài nguyên và ứng dụng qua Amazon CloudWatch.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| :--- | :--- | :--- | :--- | :--- |
| 2 | **Amazon RDS:** Tìm hiểu các engine cơ sở dữ liệu, tùy chọn lưu trữ, tính sẵn sàng cao (HA), khắc phục thảm họa (DR), bảo mật và sao lưu tự động. | 04/05/2026 | 04/05/2026 | https://000005.awsstudygroup.com/ |
| 3 | **Auto Scaling & ELB:** Tạo Launch Template, thiết lập Load Balancer và cấu hình Auto Scaling Group để tự động mở rộng ứng dụng FCJ Management theo biến động lưu lượng. | 05/05/2026 | 05/05/2026 | https://000006.awsstudygroup.com/ |
| 4 | **AWS Budgets:** Tìm hiểu 4 loại ngân sách (Cost, Usage, RI, Savings Plans). Phân tích chi phí, thiết lập mục tiêu và cấu hình ngưỡng cảnh báo. | 06/05/2026 | 06/05/2026 | https://000007.awsstudygroup.com/ |
| 5-7 | **Amazon CloudWatch:** Thu thập metric và log. Cấu hình CloudWatch Alarm để tự động hóa phản hồi, xây dựng Dashboard trực quan và tìm hiểu Container Insights. | 07/05/2026 | 09/05/2026 | https://000008.awsstudygroup.com/ |
| 7 | **Sự kiện:** Tham gia sự kiện Event 1. | 09/05/2026 | 09/05/2026 | [Xem báo cáo Event 1](/4-eventparticipated/4.1-event1/) |

### Kết quả đạt được tuần 3:
* **Cơ sở dữ liệu (RDS):** Nắm vững nền tảng về CSDL quan hệ trên AWS. Hiểu rõ sự khác biệt giữa các tùy chọn lưu trữ, khi nào cần dùng Multi-AZ để đảm bảo tính sẵn sàng cao và các trường hợp tối ưu cho tải OLTP.
* **Kiến trúc mở rộng (Auto Scaling & ELB):** Triển khai thành công kiến trúc có tính sẵn sàng cao và chịu lỗi tốt. Ứng dụng tự động điều chỉnh tài nguyên theo lưu lượng, duy trì hiệu suất mượt mà đồng thời tối ưu chi phí khi nhu cầu thấp.
* **Kiểm soát chi phí (AWS Budgets):** Chủ động theo dõi và kiểm soát chi phí AWS. Cấu hình thành công cảnh báo vượt mức theo thời gian thực và hiểu rõ ưu điểm linh hoạt của Savings Plans so với Reserved Instances.
* **Giám sát hệ thống (CloudWatch):** Khả năng quan sát toàn diện hạ tầng và ứng dụng. Hoàn thiện kỹ năng thiết lập báo động (Alarm) giúp giảm thời gian phục hồi (MTTR) và tạo Dashboard tùy chỉnh để theo dõi tình trạng hệ thống theo thời gian thực.