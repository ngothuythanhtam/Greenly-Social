# 🌿 Greenly App – Hệ thống hỗ trợ chiến dịch xanh và cộng đồng sống bền vững

Ứng dụng hỗ trợ người dùng ghi lại hoạt động sống xanh, tham gia chiến dịch cộng đồng và trò chuyện theo nhóm chiến dịch. Hệ thống gồm 2 phần: **Website quản trị quy trình** và **Ứng dụng di động hỗ trợ người dùng**.

---

## 📱 Tính năng chính

### ✨ Ứng dụng Di động (Flutter)
- 🔐 Đăng ký / Đăng nhập / Xác thực người dùng
- 📝 Tạo, chỉnh sửa, xóa và chia sẻ bài viết "khoảnh khắc xanh"
- 🗺 Bản đồ xanh – hiển thị hoạt động xanh theo vị trí
- 📚 Thư viện xanh – tài liệu hướng dẫn bảo vệ môi trường
- 📣 Tạo và tham gia chiến dịch cộng đồng
- 💬 Nhóm trò chuyện (Group Chat) theo chiến dịch – dùng Socket.IO
- ❤️ Tương tác (like, bình luận, chia sẻ) bài viết

### 🖥 Website Quản trị
- 🔐 Đăng nhập quản trị viên
- ⚙ Thiết kế & quản lý **quy trình tĩnh** và **quy trình động** theo chuẩn BPMN
- 📄 Tạo tài liệu hướng dẫn, liên kết với thư viện xanh trên mobile
- 🔁 Đồng bộ dữ liệu sang ứng dụng di động

---

## ⚙️ Kiến trúc hệ thống

- **Frontend Web**: ReactJS + BPMN.io
- **Frontend Mobile**: Flutter (Dart)
- **Backend API**: Node.js + Express
- **Cơ sở dữ liệu**: MySQL
- **Realtime Messaging**: Socket.IO
- **Quản lý trạng thái (Flutter)**: Provider
- **API**: RESTful API + JSON
- **Bảo mật**: Token-based authentication (email xác thực)

---

## 🔌 Tính năng đặc biệt – Group Chat chiến dịch

- Một chiến dịch tương ứng với một phòng chat.
- Người tham gia campaign sẽ tự động join vào nhóm chat.
- Tin nhắn được phân loại `text` hoặc `moment` (chia sẻ bài viết).
- Sử dụng Socket.IO để gửi và nhận tin nhắn realtime.
- Giao diện chat tùy biến với định dạng bài viết chia sẻ (moment).

---

## 📂 Cấu trúc thư mục chính

