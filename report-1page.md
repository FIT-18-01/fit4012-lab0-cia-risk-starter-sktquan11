# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm số của sinh viên (Grade Database).
- Thông tin định danh và tài khoản đăng nhập người dùng.

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Sinh viên cố tình thay đổi điểm số trái phép để trục lợi.
- Vulnerability: Hệ thống thiếu cơ chế phân quyền chặt chẽ hoặc bị lỗi SQL Injection.
- Mitigation: Sử dụng Role-based Access Control và Parameterized Queries.

### 4. Kết luận ngắn
Qua bài lab này, em đã học được cách áp dụng mô hình CIA để phân loại rủi ro an toàn thông tin. Phần khó nhất là việc xác định đúng lỗ hổng bảo mật thực tế đằng sau một sự cố. Khi phân tích, cần ưu tiên bảo vệ những tài sản có giá trị cao nhất như tính chính xác của dữ liệu điểm trước khi xử lý các vấn đề về đường truyền.