# Huu Tin To — Portfolio

Trang portfolio cá nhân: https://huutinto.github.io

---

## Cách đưa lên mạng (GitHub Pages) — làm 1 lần, ~5 phút

### Bước 1 — Tạo repository

1. Vào https://github.com/new
2. **Repository name**: gõ chính xác `huutinto.github.io`
   (phải trùng tên tài khoản, nếu không link sẽ dài và xấu hơn)
3. Chọn **Public**
4. **KHÔNG** tick "Add a README file" (thư mục này đã có sẵn)
5. Bấm **Create repository**

### Bước 2 — Tải file lên

1. Ở trang repo vừa tạo, bấm link **"uploading an existing file"**
   (hoặc vào `Add file` → `Upload files`)
2. Mở thư mục này trên máy, **chọn hết** rồi kéo thả vào trình duyệt:
   - `index.html`
   - `CV.pdf`
   - `README.md`
   - `.nojekyll`  ← file này bị ẩn, xem cách hiện bên dưới
   - cả thư mục `images/`
3. Bấm **Commit changes**

> **File `.nojekyll` bị ẩn?**
> - Windows: File Explorer → tab `View` → tick `Hidden items`
> - macOS: nhấn `Cmd + Shift + .` (dấu chấm)
>
> File này rỗng nhưng cần thiết — thiếu nó GitHub có thể bỏ qua một số file.

### Bước 3 — Bật GitHub Pages

1. Trong repo → tab **Settings** → menu trái chọn **Pages**
2. Mục **Source**: chọn `Deploy from a branch`
3. **Branch**: chọn `main`, thư mục `/ (root)` → bấm **Save**
4. Đợi 1–2 phút, tải lại trang → sẽ thấy link hiện ra

**Xong!** Web sẽ chạy tại: **https://huutinto.github.io**

---

## Sau này muốn sửa nội dung

**Sửa chữ:**
Vào repo → bấm `index.html` → bấm icon cây bút ✏️ → sửa → `Commit changes`.
Đợi ~1 phút là web tự cập nhật.

**Thay CV mới:**
Vào repo → bấm `CV.pdf` → nút `...` góc phải → `Upload new version`
(hoặc xoá file cũ rồi upload file mới, nhớ đặt đúng tên `CV.pdf`).

**Thay ảnh:**
Vào thư mục `images/` → upload file mới **trùng tên** file cũ để ghi đè.

---

## Cấu trúc

```
.
├── index.html      ← toàn bộ trang (HTML + CSS + JS trong 1 file)
├── CV.pdf          ← nút "Download CV" trỏ tới file này
├── .nojekyll       ← file rỗng, bắt buộc cho GitHub Pages
├── images/         ← 8 ảnh (avatar, minh hoạ, doodle, logo công ty)
└── README.md
```

> **Lưu ý:** `index.html` và thư mục `images/` phải luôn nằm cạnh nhau.

---

## Các phần của trang

1. **Hero** — tên, chức danh, nút Download CV / Contact Me (mở phong bì thư)
2. **What I do** — tuyên ngôn + 3 số liệu
3. **Selected Research** — 2 công trình nghiên cứu
4. **About me** — ảnh polaroid + giới thiệu + chữ ký
5. **Work Experience** — Bigo Live & YAN Digital
6. **Education** — MFA I-Shou + BBA Saigon University (kèm thành tích)
7. **Leadership & International Engagement**
8. **References** — 2 giáo sư
9. **Contact** — footer

---

## Ghi chú kỹ thuật

- HTML/CSS/JS thuần, không dùng thư viện ngoài.
- Font tải từ Google Fonts (cần mạng để hiện đúng font).
- Responsive: chạy tốt trên điện thoại (iOS/Android) và máy tính.
- Tôn trọng chế độ "giảm chuyển động" của hệ điều hành.
- Đã có thẻ Open Graph → link chia sẻ lên Facebook/LinkedIn sẽ hiện ảnh đẹp.

## Muốn dùng tên miền riêng?

Nếu sau này mua tên miền (vd `huutinto.com`): Settings → Pages → mục
**Custom domain** → nhập tên miền → làm theo hướng dẫn trỏ DNS.
