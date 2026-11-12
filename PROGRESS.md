# CV Website - Tiến độ & Hướng dẫn tiếp tục

## 📁 Cấu trúc dự án
```
C:\Users\nnamiuvan\.gemini\antigravity\scratch\cv-website\
├── index.html          # Trang HTML chính
├── styles.css          # File CSS (dark theme, responsive)
├── script.js           # JavaScript (particles, typewriter, animations)
├── images/
│   ├── profile.jpg     # Ảnh chân dung (ảnh 1 - phong cách chuyên nghiệp)
│   └── photo2.jpg      # Ảnh selfie (ảnh 2 - dùng trong phần About)
└── PROGRESS.md         # File này
```

## 👤 Thông tin CV (trích từ PDF gốc + bổ sung)

### Thông tin cá nhân
- **Họ tên:** Ngô Văn Nam
- **Ngày sinh:** 07/10/2005
- **Điện thoại:** 0862971205
- **Email:** ngonam0710205@gmail.com
- **Địa chỉ:** Phú Diễn - Bắc Từ Liêm - Hà Nội
- **GitHub:** https://github.com/ngonam0710
- **Vị trí ứng tuyển:** Thực tập sinh Business Analyst

### Học vấn
- 2023 – Hiện tại: Đại học Công nghiệp Hà Nội, ngành Hệ Thống Thông Tin

### Mục tiêu nghề nghiệp
- **Ngắn hạn:** Áp dụng kiến thức HTTT và kỹ năng công cụ (Figma, Draw.io, SQL) vào dự án thực tế. Thành thạo quy trình phân tích yêu cầu người dùng, viết User Stories/Use Cases chuẩn xác.
- **Dài hạn:** Trở thành BA chuyên nghiệp, sâu sát nghiệp vụ (Domain Knowledge) lẫn tư duy dữ liệu, tối ưu hóa quy trình vận hành.

### Kỹ năng
- **Chuyên môn:** Phân tích thiết kế hệ thống, thu thập yêu cầu & đặc tả phần mềm, mô hình hóa nghiệp vụ (UML, BPMN), thiết kế CSDL, ứng dụng GenAI (ChatGPT, Gemini) hỗ trợ phân tích
- **Công cụ:** SQL (MySQL/PostgreSQL), Figma, Draw.io, Docker, GitHub
- **Kỹ năng mềm:** Làm việc nhóm, giao tiếp, quản lý dự án, tư duy logic, chủ động học hỏi

### Kinh nghiệm & Dự án
1. **2024 - 2025:** Nghiên cứu mô hình khai phá dữ liệu và xây dựng ứng dụng gợi ý sản phẩm mới (Trưởng nhóm) → Đạt giải 4
2. **3/2025 – 6/2025:** Hệ thống tra cứu trường đại học có ngành học CNTT (Trưởng nhóm) → Website triển khai trên GitHub
3. **2025 - 2026:** *(BỔ SUNG)* Nghiên cứu mô hình ZSL và ứng dụng phân loại ảnh y tế → Khảo sát thực trạng phân loại ảnh y tế, nghiên cứu Zero-Shot Learning, xây dựng mô hình phù hợp
4. **9/2026 – Nay:** Hệ thống phân tích phản hồi khách hàng và theo dõi chất lượng dịch vụ (BA) → Đặc tả nghiệp vụ, Use Case Diagram, Sequence Diagram, thiết kế CSDL 3NF

### Hoạt động
- 2023 - 2024: Chủ nhiệm CLB Nghệ thuật trường CNTT & TT HAUI

## ✅ Đã hoàn thành (Phiên 1)
1. Đọc và trích xuất nội dung từ file PDF (`My_CV.pdf`)
2. Tạo trang web CV hoàn chỉnh gồm 3 file: `index.html`, `styles.css`, `script.js`
3. Copy 2 ảnh vào thư mục `images/`
4. Bổ sung thông tin GitHub và dự án ZSL vào CV

## ✅ Đã hoàn thành (Phiên 2)
1. Sửa badge "Thực tập" → "Dự án" ở timeline item cuối cùng (dự án phân tích phản hồi khách hàng)
2. Bỏ hoàn toàn dòng "Vị trí ứng tuyển" và typewriter effect ở Hero section
3. Redesign phần "Chuyên môn" từ progress bars → card grid với icon, mô tả chi tiết, hover effects

### Tính năng website đã có:
- **Dark theme** hiện đại với gradient tím-xanh
- **Particle background** canvas animation
- **Typewriter effect** cho các vai trò (ĐÃ BỎ theo yêu cầu phiên 2)
- **Responsive design** (desktop, tablet, mobile)
- **Navigation** sticky với scroll effect
- **Hero section** với ảnh profile và floating badges
- **About section** với ảnh, stats counter, thông tin cá nhân, mục tiêu
- **Skills section** với progress bars và skill tags
- **Timeline** hiển thị kinh nghiệm/dự án (bao gồm dự án ZSL mới bổ sung - highlight đặc biệt)
- **Activities section** cho hoạt động ngoại khóa
- **Contact section** với thẻ liên hệ
- **Footer** với links
- **Scroll animations** cho các element
- **Mobile hamburger menu**

## 🔜 Có thể phát triển thêm (cho các phiên sau)
- [ ] Thêm hiệu ứng 3D tilt cho ảnh profile
- [ ] Thêm dark/light mode toggle
- [ ] Thêm form liên hệ hoạt động
- [ ] Thêm section portfolio chi tiết cho từng dự án
- [ ] Deploy lên GitHub Pages
- [ ] Thêm animation phức tạp hơn (GSAP, Three.js)
- [ ] Thêm multi-language support (VN/EN)
- [ ] SEO optimization
- [ ] Thêm download CV PDF button

## 🛠 Cách mở/test website
```bash
# Mở trực tiếp file HTML trong trình duyệt:
start "C:\Users\nnamiuvan\.gemini\antigravity\scratch\cv-website\index.html"

# Hoặc dùng Live Server (nếu có Node.js):
cd "C:\Users\nnamiuvan\.gemini\antigravity\scratch\cv-website"
npx serve .
```

## 📝 Ghi chú kỹ thuật
- Website sử dụng Font Awesome 6.5.1 (CDN) cho icons
- Google Fonts: Inter (body text), JetBrains Mono (code)
- Không dùng framework JS - vanilla JS thuần
- CSS custom properties cho dễ thay đổi theme
- Ảnh gốc từ user: `media_1794474097590_304eb742.jpg` (profile) và `media_1794474097596_c9f91c7c.jpg` (photo2)
