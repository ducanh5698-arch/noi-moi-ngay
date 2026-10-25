# Nói Mỗi Ngày

App học 1000 câu giao tiếp tiếng Anh theo kiểu nghe trước: nghe, đoán nghĩa, nhại theo, rồi chấm điểm phát âm bằng micro.

## Cài lên điện thoại Android

1. Mở link app bằng **Chrome** trên điện thoại.
2. Bấm dấu **⋮** ở góc trên bên phải, chọn **Cài đặt ứng dụng** (hoặc **Thêm vào màn hình chính**).
3. Mở app từ biểu tượng mới trên màn hình chính.
4. Lần đầu bấm **Nói & chấm điểm**, chọn **Cho phép** khi được hỏi quyền dùng micro.

## Lưu ý

- Chấm phát âm dùng bộ nhận giọng nói của Chrome nên cần có mạng. Các phần còn lại chạy được cả khi không có mạng.
- Tiến độ học lưu ngay trên điện thoại. Nếu xóa dữ liệu Chrome hoặc gỡ app thì tiến độ sẽ mất.
- Điểm phát âm cho biết máy nghe ra đúng bao nhiêu từ, tức là người nghe có hiểu bạn nói gì không. Điểm này không chấm riêng từng âm.

## Cấu trúc

- `index.html`: toàn bộ app
- `data/l1.json` … `data/l10.json`: 10 level, mỗi level 100 câu
- `manifest.webmanifest`, `sw.js`, `icon-*.png`: phần để cài đặt và chạy offline
