# Volunteer & Travel for Education — Landing Page

Bộ code tĩnh cho website giới thiệu dự án du lịch thiện nguyện kết hợp dạy học STEM.

## Phiên bản cập nhật

- Thay phần lớn hình minh họa SVG bằng ảnh chụp trong thư mục `assets/`.
- Bổ sung section **Quy trình tham gia** để người xem hiểu các bước đăng ký, chuẩn bị, đồng hành và theo dõi minh bạch.
- Bổ sung section **Khoảnh khắc** dạng gallery để landing page có cảm xúc hơn.
- Cập nhật hero bằng ảnh nền ruộng bậc thang và ảnh lớp học/thí nghiệm.

## Cấu trúc file

```txt
volunteer-stem-website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── logo.svg
    ├── logo-light.svg
    ├── favicon.svg
    ├── photo-mucangchai.jpg
    ├── photo-rice-valley.jpg
    ├── photo-science-closeup.jpg
    ├── photo-teacher-student.jpg
    ├── photo-learning-child.jpg
    ├── photo-hiking-group.jpg
    ├── photo-hiker-vietnam.jpg
    ├── photo-wooden-bridge.jpg
    ├── mountain-pattern.svg
    └── torn-paper.svg
```

Một số file SVG cũ vẫn được giữ lại để bạn có thể dùng làm icon/phương án dự phòng.

## Cách chạy

Mở trực tiếp `index.html` trong trình duyệt.

Hoặc chạy local server:

```bash
python -m http.server 8000
```

Sau đó mở:

```txt
http://localhost:8000
```

## Thay ảnh bằng ảnh của dự án

Bạn chỉ cần ghi đè các file ảnh trong `assets/` bằng ảnh của nhóm, giữ nguyên tên file. Ví dụ:

- Thay ảnh hero: ghi đè `assets/photo-mucangchai.jpg`
- Thay ảnh lớp học/STEM: ghi đè `assets/photo-teacher-student.jpg`
- Thay ảnh gallery: ghi đè các file `photo-*.jpg`

Nên dùng ảnh ngang cho hero và ảnh gallery lớn, ảnh dọc cho các card nhỏ. Kích thước gợi ý: chiều rộng 1200–1800px, định dạng JPG, dung lượng dưới 700KB/ảnh.

## Ghi chú nguồn ảnh mẫu

Các ảnh hiện tại là ảnh mẫu để dựng giao diện. Khi triển khai chính thức, nên thay bằng ảnh do dự án tự chụp để tránh nhầm lẫn ngữ cảnh.

## Tuỳ chỉnh nhanh

- Sửa nội dung trong `index.html`
- Sửa màu sắc trong `:root` của `styles.css`
- Form hiện đang là frontend mẫu; muốn gửi dữ liệu thật thì thay phần xử lý trong `script.js`

## Gợi ý triển khai

Có thể deploy nhanh lên Netlify, Vercel, GitHub Pages hoặc hosting tĩnh bất kỳ.
