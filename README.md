# Portfolio Website - Hướng Dẫn

Đây là một website portfolio cá nhân được tạo bằng HTML, CSS và JavaScript.

## 🎯 Cấu Trúc Website

Website này gồm 4 phần chính:
1. **Giới thiệu** - Phần hero với thông tin cơ bản về bạn
2. **Dự án** - Hiển thị các dự án của bạn với ảnh và link GitHub
3. **Chứng chỉ** - Hiển thị các chứng chỉ/giấy chứng nhận của bạn
4. **Liên hệ** - Thông tin liên hệ và các link mạng xã hội

## 📝 Các Bước Để Chỉnh Sửa

### 1. Chỉnh sửa thông tin giới thiệu
- Mở file `index.html`
- Tìm phần `<section id="intro" class="hero">`
- Thay thế:
  - "Nguyễn Lương Hoàng Long" bằng tên của bạn
  - "Lập trình viên | Nhà phát triển Web" bằng chuyên môn của bạn
  - Phần mô tả bằng giới thiệu của bạn

### 2. Thêm dự án
- Thêm ảnh dự án vào thư mục `images/` với tên như `project1.jpg`, `project2.jpg`, v.v.
- Trong file `index.html`, tìm section `<section id="projects">`
- Thay thế các thông tin:
  - `Tên Dự Án 1` → Tên thực của dự án
  - `Mô tả dự án 1` → Mô tả ngắn về dự án
  - `href="#"` của button → Link GitHub của dự án

Ví dụ:
```html
<a href="https://github.com/yourusername/your-repo" class="btn btn-secondary" target="_blank">GitHub</a>
```

### 3. Thêm chứng chỉ
- Thêm ảnh chứng chỉ vào thư mục `images/` với tên như `cert1.jpg`, `cert2.jpg`, v.v.
- Trong file `index.html`, tìm section `<section id="certifications">`
- Thay thế `Tên Chứng Chỉ 1` bằng tên thực của chứng chỉ

### 4. Cập nhật thông tin liên hệ
- Trong file `index.html`, tìm section `<section id="contact">`
- Cập nhật:
  - Email: thay `your.email@example.com` bằng email của bạn
  - Điện thoại: thay `+84123456789` bằng số điện thoại của bạn
  - Địa chỉ: thay "Thành phố HCM, Việt Nam" bằng địa chỉ của bạn
  - Các link mạng xã hội (Facebook, LinkedIn, GitHub)

## 🖼️ Quản lý ảnh

**Tên ảnh dự án:** 
- `images/project1.jpg`
- `images/project2.jpg`
- `images/project3.jpg`
- (Thêm nhiều hơn nếu cần)

**Tên ảnh chứng chỉ:**
- `images/cert1.jpg`
- `images/cert2.jpg`
- `images/cert3.jpg`
- `images/cert4.jpg`
- (Thêm nhiều hơn nếu cần)

**Kích thước ảnh được khuyến nghị:**
- Dự án: 500x350px hoặc 800x600px
- Chứng chỉ: 500x500px hoặc 800x800px

## 🎨 Tùy chỉnh Giao Diện

Các màu chủ yếu được định nghĩa trong `style.css`:

```css
:root {
    --primary-color: #667eea;      /* Màu xanh chính */
    --secondary-color: #764ba2;    /* Màu tím phụ */
    --text-dark: #333;              /* Màu chữ đen */
    --text-light: #666;             /* Màu chữ xám */
}
```

Bạn có thể thay đổi các mã màu này để phù hợp với style cá nhân.

## 🚀 Các Tính Năng

✅ Responsive design (hoạt động tốt trên điện thoại, máy tính bảng, máy tính)
✅ Smooth scrolling khi click vào menu
✅ Animation khi scroll trang
✅ Hover effects trên các card
✅ Gradient background đẹp mắt
✅ Footer đơn giản

## 📦 Các File Trong Dự Án

```
.
├── index.html          # File HTML chính
├── style.css           # Styling (CSS)
├── script.js           # Interactivity (JavaScript)
├── README.md           # File hướng dẫn này
└── images/             # Thư mục chứa ảnh
    ├── project1.jpg
    ├── project2.jpg
    ├── cert1.jpg
    └── ...
```

## 💡 Mẹo Bổ Sung

1. **Thêm icon xã hội:** Bạn có thể thêm các icon từ Font Awesome hoặc tương tự
2. **Thêm form liên hệ:** Có thể tích hợp dịch vụ như Formspree hoặc EmailJS
3. **Deploy trang web:**
   - GitHub Pages (miễn phí)
   - Netlify (miễn phí)
   - Vercel (miễn phí)

## ❓ Cần Giúp Đỡ?

Nếu bạn gặp vấn đề khi chỉnh sửa, hãy kiểm tra:
- Các tên file và đường dẫn có đúng không
- Cú pháp HTML/CSS có chính xác không
- Ảnh có được đặt trong thư mục `images/` không

---

**Chúc bạn thành công với website portfolio của mình! 🎉**
