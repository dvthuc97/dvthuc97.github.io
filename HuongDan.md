# Cách đưa giao diện mới lên trang dvthuc97.github.io

Trang chủ nằm trong file `index.html`; trang tra cứu firmware modem nằm trong `firmware.html` (mỗi trang đã gộp CSS + JS, không cần `style.css` cũ nữa). Cần đưa cả hai file lên thư mục gốc của repo.
Ảnh avatar vẫn dùng sẵn `img/avatar.jpg` cũ trong repo nên khỏi cần tải thêm.

## Bước 1: Mở file index.html trong repo

1. Vào **github.com** → đăng nhập tài khoản `dvthuc97`
2. Mở repo **`dvthuc97.github.io`**
3. Bấm vào file **`index.html`** → bấm biểu tượng bút chì ✏️ **Edit this file**

## Bước 2: Cập nhật cả hai trang

1. Mở file `index.html` trong repo và thay bằng nội dung từ file `index.html` mới trên máy.
2. Thêm file `firmware.html` mới vào thư mục gốc repo (GitHub: **Add file → Upload files**).
3. Kiểm tra cả `index.html` và `firmware.html` đều nằm cùng thư mục gốc.
4. **Commit changes** các thay đổi.

## Bước 3: Xem kết quả

Mở `https://dvthuc97.github.io/` để xem trang chủ hoặc `https://dvthuc97.github.io/firmware.html` để xem trang firmware — nếu chưa thấy mới thì:
- `Ctrl+F5` (tải lại không dùng cache), hoặc
- chờ 1–2 phút rồi mở lại

## Xóa file không còn dùng (tùy chọn, cho repo gọn)

Trong repo, mở `style.css` → bấm biểu tượng thùng rác 🗑 **Delete this file** → **Commit changes**.
(File `style.css`, `img/home.png`… không còn được dùng nữa, nhưng để lại cũng không sao.)

---

## Cách kiểm tra nhanh trên máy trước khi đưa lên

Bấm đúp trực tiếp vào file `index.html` là mở được bằng trình duyệt.
(Ảnh avatar sẽ không hiện vì máy không có thư mục `img/` — lên GitHub thì có, yên tâm.)
