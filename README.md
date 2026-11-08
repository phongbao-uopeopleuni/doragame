# doragame

Trò chơi giúp bé nhận biết True và False qua âm thanh, dùng trên điện thoại và tablet.

## Cách chơi

1. Hỏi bé một câu, ví dụ: "Đây là con mèo phải không?"
2. Bấm True: máy reo "It's true!" rồi khen bé. Mỗi lần là một cảnh ăn mừng khác nhau, có nhạc tiệc riêng: pháo giấy, bóng bay, pháo hoa, mưa sao hoặc bóng nảy. Trong lúc ăn mừng, bé chạm vào màn hình để bóp bóng bay, bắn pháo hoa, rắc sao hoặc làm bóng nảy lên.
3. Bấm False: máy đọc nhẹ nhàng "It's false.", không phát nhạc.
4. Muốn nghe bài hát, bấm "Phát nhạc". Bài hát gồm vài giai điệu có sẵn và file nhạc tự thêm trên máy.

Mọi âm thanh của True và False được tạo ngay trong trang, không cần tải file nào. Việc dựng nhạc chạy trong một Web Worker để hình không bị khựng; nơi nào chặn worker thì trang tự dựng nhạc trên luồng chính.

## Các file

- `index.html`: toàn bộ trò chơi, không cần bước build.

File nhạc thêm trong trang chỉ được lưu trên máy đang dùng.

## Chạy thử trên máy

Trang cần chạy qua một máy chủ web, ví dụ:

```bash
npx serve .
```
