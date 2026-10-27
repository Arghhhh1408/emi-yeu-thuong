# Gửi Emi yêu thương ♡

Website lưu giữ những khoảnh khắc của Emi, có ảnh, video, bài hát *Viết cho con* và bức thư của gia đình.

## Đăng website lên GitHub Pages (không cần cài phần mềm)

1. Đăng nhập https://github.com/ (tạo tài khoản nếu cần).
2. Vào https://github.com/new, điền **Repository name:** `emi-yeu-thuong`.
3. Chọn **Public**, đánh dấu **Add a README file** (hoặc tạo repository không README, đều được), rồi chọn **Create repository**.
4. Trên trang repository: **Add file → Upload files**. **Giải nén file ZIP**, rồi kéo **toàn bộ nội dung bên trong** thư mục vừa giải nén vào khung upload: `index.html`, thư mục `assets` chứa ảnh/nhạc/video, `README.md`, `.nojekyll` (nếu hiển thị), v.v. **Không upload nguyên file ZIP** và **không để `index.html` nằm trong một thư mục con**.
5. Chờ tải lên xong, chọn **Commit changes** (nếu giao diện có nút **Propose changes**, làm theo hướng dẫn trên GitHub để hoàn tất commit vào nhánh `main`).
6. Vào **Settings → Pages** (thanh menu bên trái, mục Code and automation).
7. Ở **Build and deployment → Source**, chọn **Deploy from a branch**.
8. Ở phần **Branch**, chọn `main`, ở phần thư mục chọn `/(root)`, rồi nhấn **Save**.
9. Khi trang được xuất bản, ở cùng mục Pages nhấn **Visit site**. Địa chỉ thông thường sẽ là:

   `https://TEN-TAI-KHOAN.github.io/emi-yeu-thuong/`

   Thay `TEN-TAI-KHOAN` bằng tên người dùng GitHub của bạn (phải dùng đúng tên repository đã tạo).

GitHub có thể mất vài phút để xuất bản (tài liệu GitHub lưu ý thời gian có thể lên đến khoảng 10 phút). Nếu thấy lỗi 404, đảm bảo `index.html` nằm ở **gốc repository**, đã bật Pages và đã chọn đúng nhánh.

## Chỉnh sửa website sau này

- Thay đổi website: cập nhật `index.html`, nhấn **Commit changes**.
- Thay ảnh/video/nhạc: giữ đúng tên file trong thư mục `assets`, tải file thay thế lên và commit.
- Nếu trình duyệt vẫn hiển thị nội dung cũ, hãy tải lại bằng **Ctrl+F5**.

## Lưu ý về quyền riêng tư & nội dung

- GitHub Pages là trang web **công khai**. Người có đường dẫn hoặc biết nơi chứa tệp có thể truy cập và tải ảnh/video/nhạc.
- Mã PIN `2110` chỉ là hiệu ứng mở quà trên giao diện, **không phải hàng rào bảo mật**. Mã và đường dẫn tư liệu nằm trong mã website.
- Nên có sự đồng ý của gia đình Emi trước khi đăng ảnh/video của bé. Nếu cần chia sẻ thực sự riêng tư, hãy chọn nền tảng có giới hạn quyền truy cập thay cho GitHub Pages.
- Với bài hát *Viết cho con*, hãy đảm bảo bạn có quyền sử dụng và công bố trực tuyến.

## Cấu trúc website

```text
index.html                ← GitHub Pages mở file này
assets/                   ← Toàn bộ ảnh, video, nhạc
  final_surprise.mp4      ← Đã tối ưu dung lượng để upload qua trình duyệt
  viet_cho_con.mp3
  ...
.nojekyll                 ← Cho GitHub Pages phục vụ website tĩnh
README.md                 ← Hướng dẫn này
```

**Cách thử trên máy tính:** mở `index.html` trong Chrome/Edge. Mật khẩu trong trải nghiệm: `2110`.
