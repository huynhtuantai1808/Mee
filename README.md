# Hướng Dẫn Tùy Chỉnh

Tất cả chỉnh sửa bạn cần làm đều nằm trong file `script.js`.

---

## 1. Thêm Ảnh

Để thêm ảnh vào thiên hà:

- Tìm dòng chứa `length: 40` trong `script.js`
- Thay đổi số `40` thành số lượng ảnh thực tế trong thư mục `images/img/`

---

## 2. Thay Đổi Text Vòng Quay

Để thay đổi các dòng chữ quay quanh hành tinh:

- Tìm mảng `ringTexts` trong `script.js`
- Sửa nội dung các dòng text theo ý bạn

---

## 3. Thay Đổi Nhạc

Để thay đổi file nhạc:

- Thay thế file `Happy Birthday to You.mp3` trong thư mục gốc
- Hoặc cập nhật đường dẫn trong `index.html`

---

## 4. Thay Đổi Lời Chúc 3D

Để thay đổi lời chúc 3D:

- Tìm hàm `createGreetingText()` trong `script.js`
- Thay đổi biến `text` bên trong hàm

---

## 5. Responsive

Trang web tự động điều chỉnh cho:

- Desktop (1920px+)
- Tablet (768px - 1024px)
- Mobile (nhỏ hơn 768px)
- Điện thoại xoay ngang sẽ hiện cảnh báo

---

## 6. GitHub Actions

Workflow tự động chạy khi:

- Push lên branch `main` hoặc `duong`
- Tạo Pull Request
- Chạy thủ công (`workflow_dispatch`)

Website sẽ được deploy tự động lên GitHub Pages.
