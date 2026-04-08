# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hà Minh Quân
**MSSV:** 1871002470
**Lớp/Nhóm:** CNTT18-01

---

## 1. Assets
- Asset 1: Cơ sở dữ liệu điểm số của sinh viên (Grade Database).
- Asset 2: Thông tin định danh và tài khoản người dùng (User Credentials).

---

## 2. Mapping CIA
- Sự cố A -> Availability (Tính khả dụng)
- Sự cố B -> Integrity (Tính toàn vẹn)
- Sự cố C -> Confidentiality (Tính bảo mật)

---

## 3. Phân tích sự cố B
- **Threat:** Kẻ tấn công hoặc sinh viên cố tình thay đổi điểm số để trục lợi cá nhân.
- **Vulnerability:** Hệ thống thiếu cơ chế phân quyền chặt chẽ hoặc tồn tại lỗ hổng SQL Injection cho phép can thiệp vào database.
- **Mitigation:** Triển khai cơ chế phân quyền Role-based Access Control và sử dụng Parameterized Queries để bảo vệ cơ sở dữ liệu.

---

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B (Integrity) trước tiên. Lý do là vì điểm số là tài sản cốt lõi và quan trọng nhất của hệ thống quản lý giáo dục. Nếu tính toàn vẹn bị vi phạm và kết quả học tập bị thao túng, hệ thống sẽ mất đi hoàn toàn sự công bằng, uy tín và giá trị sử dụng. Sau đó, em mới tập trung xử lý sự cố A để đảm bảo tính sẵn sàng và sự cố C để ngăn chặn rò rỉ thông tin.

---

## 5. Bonus Flag
Flag của em: **FIT4012{A-A-B-I-C-C}**