# Big Data 80 — Học trắc nghiệm theo nhóm

Website ôn thi Big Data 80 câu, tối ưu điện thoại, phong cách trắng/xanh lá và font Nunito.

## Cách học đề xuất
1. Chọn **Làm trắc nghiệm** và chọn 10, 20, 40 hoặc 80 câu.
2. Sau khi làm xong, chọn **Ôn lại nhóm vừa làm** (ôn tất cả câu, kể cả những câu khoanh đúng).
3. Lặp lại nhóm đó đến khi thuộc; nhấn **Làm nhóm câu mới** để luyện các câu *chưa gặp*, không lặp trong cùng vòng 80 câu.
4. **Ôn câu sai trong nhóm** chỉ lấy các câu sai thuộc đúng nhóm vừa làm (ví dụ sai 4/10 thì ôn đúng 4 câu đó), không gom câu sai ở nhóm trước. Khi trả lời đúng lại, câu sai được gỡ khỏi danh sách. Nút **Ôn lại nhóm vừa làm** luôn lấy đủ 10 câu ban đầu, kể cả sau khi vừa ôn 4 câu sai.

## Tiếng Anh
- **Chạm vào từng từ trong câu hỏi** hoặc đáp án đúng đã công bố để hiện nghĩa tiếng Việt. Các từ cơ bản/chuyên ngành có sẵn trong từ điển offline; từ ngoài từ điển thử dịch trực tuyến và có liên kết Google Dịch để tra thêm.
- Bấm **Dịch câu hỏi** để xem bản dịch viết sẵn cho đủ 80 câu (không cần Internet).
- Sau khi chọn đáp án, hiển thị **nghĩa tiếng Việt của đáp án đúng** (đủ 80 đáp án, không cần Internet).
- Có nút **Dịch thêm 3 đáp án còn lại** thông qua dịch máy trực tuyến (cần Internet, đôi khi không khả dụng). Bản dịch tự động có thể chưa đúng ngữ cảnh thuật ngữ.

## Tiến độ
- Trong một vòng, khi chọn 10 câu mới rồi chọn thêm 10, web lấy từ những câu chưa trả lời. Sau khi đã gặp cả 80 câu, web mới bắt đầu vòng mới.
- Ôn lại nguyên nhóm **không trừ số câu mới còn lại**.
- Lưu tiến độ, câu sai và nhóm vừa làm vào `localStorage` của trình duyệt. Không đồng bộ giữa thiết bị; dùng lại đúng trình duyệt và không xóa dữ liệu trang web.
- Kết quả đúng/sai trước đây từ bản cũ được giữ lại nếu dùng trên cùng trình duyệt. Lịch sử câu đã gặp của bản cũ không có nên **vòng chống lặp bắt đầu từ bản cập nhật này**.
- Đáp án câu 39 là **D**, theo lần kiểm tra bài.

## Deploy lên GitHub Pages
Giải nén và copy **toàn bộ file** vào thư mục gốc repository GitHub (cùng cấp với `index.html`), sau đó:

```bash
git add .
git commit -m "Add vocabulary translation and smart review batches"
git push
```

Nếu GitHub Pages đã bật trước đó thì không cần bật lại. Repo trong cuộc hội thoại: `https://github.com/MaiThiDungITDT65/Big-Data-Practice`; URL web: `https://maithidungitdt65.github.io/Big-Data-Practice/`.

> Lưu ý: font Nunito cần tải mạng lần đầu. Website, câu hỏi và bản dịch đã viết sẵn được cache để học offline sau khi tải thành công, nhưng dịch máy trực tuyến vẫn cần Internet.
