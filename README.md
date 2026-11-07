# doragame

Trò chơi giúp bé nhận biết True và False qua âm thanh, dùng trên điện thoại và tablet.

## Cách chơi

1. Hỏi bé một câu, ví dụ: "Đây là con mèo phải không?"
2. Người chơi cùng bấm đáp án đúng ở hàng nút phía trên để bé nghe tiếng của đáp án đó.
3. Bé bấm một nút to. Chọn đúng thì có pháo giấy, lời khen rồi nhạc tự phát. Chọn nhầm thì bé nghe lại và chọn lại.

## Các file

- `index.html`: toàn bộ trò chơi, không cần bước build.
- `songs.json`: danh sách bài hát trên YouTube, mỗi dòng gồm tên bài và mã video.

Bài hát thêm ngay trong trang chỉ được lưu trên máy đang dùng. Muốn mọi máy cùng thấy một bài, hãy thêm bài đó vào `songs.json`.

## Chạy thử trên máy

Trang cần chạy qua một máy chủ web, ví dụ:

```bash
npx serve .
```
