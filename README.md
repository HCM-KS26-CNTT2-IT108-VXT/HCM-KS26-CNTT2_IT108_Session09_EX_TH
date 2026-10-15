# &#x20;SmartCampus

SmartCampus là **ứng dụng di động** hỗ trợ sinh viên PTIT tra cứu lịch học, phòng học trống và nhận *thông báo mới nhất* từ nhà trường.

## &#x20;Giới thiệu tính năng

- **Tra cứu lịch học**
  - Tìm lịch học theo mã sinh viên.
- **Tra cứu phòng trống**
  - Xem danh sách phòng trống theo tòa nhà.

[lms-student.rikkei.edu.vn](https\:lms-student.rikkei.edu.vn/dashboard)



> Dự án đang trong giai đoạn phát triển, chưa sử dụng cho mục đích chính thức.

---

## Hướng dẫn cài đặt

Yêu cầu: sử dụng các lệnh giả lập dưới đây để cài đặt dự án.

```bash
git clone https://github.com/lms-student.rikkei.edu.vn/smartcampus.git
npm install
npm start
```

## &#x20;Tiến độ phát triển

- [x] Tra cứu lịch học theo mã sinh viên
- [x] Xem danh sách phòng trống theo tòa nhà
- [ ] Thông báo đẩy (push notification)
- [ ] Đăng nhập bằng tài khoản trường

## Thư viện sử dụng

| Thư viện     | Phiên bản | Mục đích                              |
| :----------- | :-------: | :------------------------------------ |
| React Native |    0.74   | Xây giao diện đa nền tảng iOS/Android |
| Axios        |    1.6    | Gọi API lấy dữ liệu lịch học          |

## &#x20;Lưu ý cú pháp Markdown

Để hiển thị nguyên văn ký tự \*, cần thêm dấu Escape `\` phía trước.

## Ghi chú ôn tập

### Phần 4: Kiểm tra lỗi cú pháp

**Lỗi 1:** Bảng thiếu dòng phân cách giữa tiêu đề và dữ liệu.

**Lỗi 2:** Task List thiếu dấu cách sau dấu gạch ngang `-`, cần viết `- [x]` thay vì `-[x]`.

Đoạn Markdown sau khi sửa:

| Tính năng         | Trạng thái |
| ----------------- | ---------- |
| Tra cứu lịch học  | Xong       |
| Push notification | Đang làm   |

- [ ] Push notification
