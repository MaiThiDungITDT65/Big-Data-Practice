# Big Data 80 — Luyện trắc nghiệm

Web ôn thi Big Data 80 câu, giao diện trắng + xanh lá, chữ **Nunito** bo tròn, tối ưu điện thoại.

## Tính năng
- **Làm trắc nghiệm:** hiện đủ bốn lựa chọn A, B, C, D; chọn 10, 20, 40 hoặc 80 câu; tùy chọn đảo thứ tự câu.
- **Ôn lại câu sai:** các câu trả lời sai được lưu vào trình duyệt; làm đúng lại sẽ tự loại khỏi danh sách cần ôn.
- Đáp án hiện sau khi chọn. Kết quả và tiến độ lưu trong `localStorage` trên chính thiết bị.
- Câu 39 chọn đáp án D, các câu còn lại theo bài review 79/80.

## Triển khai GitHub Pages
1. Tạo repository public trên GitHub, chẳng hạn `bigdata-80-quiz`.
2. **Upload tất cả file bên trong thư mục** `bigdata-80-quiz` vào thư mục gốc repo (để `index.html` ở root).
3. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
4. Link: `https://TEN-TAI-KHOAN.github.io/bigdata-80-quiz/`.

Nếu đã có repo, ghi đè các file cũ. Có thể cần tải lại tab để nhận bản mới do cache của PWA.

Trang cần Internet để tải font Nunito lần đầu; nếu offline, sẽ dùng font sans bo tròn dự phòng. Website không yêu cầu tài khoản hay backend.
