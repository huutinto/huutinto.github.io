# Huu Tin To — Portfolio Website

Trang portfolio cá nhân, dùng cho hồ sơ ứng tuyển PhD.

## Cách mở

Giải nén cả thư mục ra, rồi nhấp đúp `index.html` **ở bên trong thư mục đó**.

> **QUAN TRỌNG:** `index.html` và thư mục `images/` phải luôn nằm cạnh nhau.
> Nếu chỉ tải mỗi `index.html` ra chỗ khác → ảnh sẽ mất hết (hiện icon ảnh vỡ).

## Cấu trúc

```
portfolio/
├── index.html      ← toàn bộ nội dung + CSS + JS nằm trong 1 file này
├── CV.pdf          ← nút "Download CV" trỏ tới file này
├── images/
│   ├── avatar.jpg              (ảnh tròn trên thanh nav)
│   ├── hero-illustration.webp  (nhân vật ngồi với laptop)
│   ├── doodle-notes.webp       (sổ Research Notes)
│   ├── doodle-laptop.webp      (laptop biểu đồ)
│   ├── doodle-books.webp       (chồng sách + ly cà phê)
│   └── polaroid-photo.webp     (ảnh trong khung polaroid)
├── source-assets/  ← file gốc độ phân giải cao (để sửa lại sau này)
└── README.md
```

## Các phần của trang

1. **Hero** — tên, chức danh, CTA
2. **What I do** — câu tuyên ngôn (hiệu ứng đổi màu cầu vồng khi cuộn) + 3 số liệu
3. **Selected Research** — 2 công trình nghiên cứu
4. **About me** — ảnh polaroid + giới thiệu + chữ ký
5. **Work Experience** — timeline Bigo & YAN Digital
6. **Education** — MFA I-Shou + BBA Saigon University (kèm thành tích)
7. **Leadership & International Engagement** — hoạt động lãnh đạo, tình nguyện
8. **References** — 2 giáo sư
9. **Contact** — footer

## Việc còn phải làm

- [x] ~~Gắn file CV~~ — đã xong, nút "Download CV" đang trỏ tới `CV.pdf`.
      Khi có bản CV mới, chỉ cần ghi đè file `CV.pdf` là được.
- [x] ~~Link LinkedIn~~ — đã nối tới https://www.linkedin.com/in/huutinto/
- [ ] Cân nhắc bổ sung: Google Scholar / ORCID.

## Muốn sửa nội dung?

Mở `index.html` bằng bất kỳ trình soạn thảo nào (VS Code, Notepad++...).
Phần chữ nằm ở nửa dưới file, trong các thẻ có chú thích tiếng Việt
(ví dụ `<!-- ================= EDUCATION ================= -->`).

## Muốn đưa lên mạng?

Cách nhanh & miễn phí: kéo cả thư mục này thả vào https://app.netlify.com/drop
→ có link web ngay. Hoặc dùng GitHub Pages / Vercel.

## Ghi chú kỹ thuật

- Không dùng thư viện ngoài — chỉ HTML/CSS/JS thuần, chạy offline được.
- Font tải từ Google Fonts (cần mạng để hiện đúng font chữ).
- Responsive: chạy tốt trên điện thoại (iOS/Android) và máy tính.
- Có tôn trọng chế độ "giảm chuyển động" của hệ điều hành.
