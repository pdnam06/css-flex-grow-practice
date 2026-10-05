# Thực hành CSS flex-grow

Ví dụ gồm 5 Flex Item; Item thứ hai có `flex-grow: 1`, bốn Item còn lại có `flex-grow: 0`.

## Chạy bài

Mở `index.html` bằng trình duyệt. Các quy tắc CSS nằm trong `style.css`.

## Kết quả

Container rộng 800px, gap 10px, mỗi Item có flex-basis 100px và box-sizing border-box. Không gian còn trống là 260px. Item 2 nhận toàn bộ phần này nên rộng 360px, các Item còn lại rộng 100px.

`flex-grow` chỉ có tác dụng với Flex Item và phân phối phần không gian dương còn lại; không phải tỉ lệ trực tiếp của chiều rộng cuối cùng. Giá trị mặc định là 0; `initial` đưa về 0; `inherit` lấy giá trị từ cha.

Trên điện thoại, cuộn ngang bên trong khung ví dụ để giữ nguyên thông số thực hành.

## Ảnh nộp bài

- `flex-grow-desktop.png`: toàn bộ trang desktop.
- `flex-grow-example.png`: ảnh riêng ví dụ 5 Item.
- `flex-grow-mobile.png`: giao diện mobile.
