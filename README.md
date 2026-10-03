# [Bài tập] Tạo Form Đơn Giản & Đăng Ký Học Viên

Dự án thực hành xây dựng các biểu mẫu HTML5 và định dạng CSS theo tiêu chuẩn giáo trình CodeGym.

---

## 📁 Cấu trúc thư mục

```text
├── index.html           # Trang chủ chứa giao diện điều hướng và tab hiển thị cả Phần 1 & Phần 2
├── part1.html           # Phần 1: Form đơn giản độc lập
├── part2.html           # Phần 2: Form đăng ký học viên độc lập
├── simpleform.html      # Tương thích tên file bài thực hành CodeGym (Phần 1)
└── README.md            # Tài liệu hướng dẫn chi tiết
```

---

## 📋 Chi tiết yêu cầu bài tập

### 🔹 Phần 1: Tạo form đơn giản
- **Họ và tên**: Thẻ `<input type="text">`, thuộc tính `name="yourname"`.
- **Email**: Thẻ `<input type="email">`, thuộc tính `name="email"`.
- **Sở thích**: Các thẻ `<input type="checkbox">` có cùng thuộc tính `name="hobby"`.
- **Nút gửi thông tin**: Thẻ `<button type="submit">` gửi dữ liệu form.
- **Nút nhập lại**: Thẻ `<button type="reset">` đặt lại toàn bộ form về mặc định.
- **Thiết kế**: Font chữ Google Fonts Plus Jakarta Sans hiện đại, căn lề chuẩn, viền bo tròn, hiệu ứng hover/focus mượt mà.

### 🔹 Phần 2: Tạo form đăng ký học viên
- **Họ và tên**: `<input type="text" name="fullname">`
- **Email**: `<input type="email" name="email">`
- **Số điện thoại**: `<input type="tel" name="phone">`
- **Ngày sinh**: `<input type="date" name="birthday">`
- **Giới tính**: Radio Button nhóm `name="gender"` gồm các giá trị: `Nam`, `Nữ`, `Khác`.
- **Hình thức học**: Radio Button nhóm `name="study_type"` gồm: `Online`, `Offline`.
- **Khóa học**: Select box `<select name="course">` gồm:
  - HTML & CSS
  - JavaScript
  - Java
  - Python
- **Sở thích**: Checkbox nhóm `name="hobby"` gồm nhiều lựa chọn.
- **Địa chỉ**: Thẻ `<textarea name="address">`.
- **Ghi chú**: Thẻ `<textarea name="note">`.
- **Nút Đăng ký**: `<button type="submit">`.
- **Nút Nhập lại**: `<button type="reset">`.

---

## 🚀 Hướng dẫn mở và kiểm tra bài làm

1. Mở file [index.html](index.html) trực tiếp bằng trình duyệt (Google Chrome, Microsoft Edge, Firefox,...).
2. Dùng thanh Tab chuyển đổi giữa **Phần 1: Form Đơn Giản** và **Phần 2: Form Đăng Ký Học Viên**.
3. Có thể mở riêng lẻ từng trang:
   - [part1.html](part1.html)
   - [part2.html](part2.html)
   - [simpleform.html](simpleform.html)
4. Nhập dữ liệu thử nghiệm, nhấn nút gửi (Submit) để xem kết quả hiển thị trực quan hoặc nhấn "Nhập lại" (Reset) để xóa trắng form.
