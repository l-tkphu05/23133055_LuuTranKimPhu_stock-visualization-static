# 📊 Stock Data Visualization Simulator

**MSSV**: 23133055  
**Sinh viên**: Lưu Trần Kim Phú  
**Đề tài**: Mô phỏng quy trình phân tích dữ liệu cổ phiếu

## 🌟 Giới thiệu

Ứng dụng web tương tác mô phỏng 10 bước phân tích dữ liệu cổ phiếu SZL (Sonadezi Long Thành) từ tháng 8-9/2023.

## 🎯 Tính năng chính

- ✅ Upload và validate file CSV
- 📊 Phân tích thống kê cơ bản
- 📈 Tạo các cột thông tin Info01, Info02
- 🔍 Phân tích xu hướng và tương quan
- 📉 Trực quan hóa dữ liệu qua biểu đồ
- 🤖 Xây dựng mô hình hồi quy tuyến tính
- 💾 Xuất kết quả phân tích

## 📁 Cấu trúc thư mục

```
stock-visualization-static/
├── index.html           # Trang chính
├── css/
│   └── styles.css      # CSS styles (sẽ tạo)
├── js/
│   └── app.js          # JavaScript logic (sẽ tạo)
├── data/               # Thư mục cho file CSV
│   ├── vnstock_listing_companies.csv
│   └── SZL.csv
└── README.md           # File này
```

## 🚀 Cách triển khai

### Option 1: Mở trực tiếp (Local)

1. Mở file `index.html` bằng trình duyệt web
2. Không cần server, chạy trực tiếp từ file system

### Option 2: Sử dụng Live Server (VSCode)

1. Cài đặt extension "Live Server" trong VSCode
2. Click chuột phải vào `index.html` → "Open with Live Server"
3. Trang web sẽ tự động mở tại `http://localhost:5500`

### Option 3: Python HTTP Server

```bash
cd stock-visualization-static
python -m http.server 8000
```

Truy cập: `http://localhost:8000`

### Option 4: Node.js HTTP Server

```bash
npm install -g http-server
cd stock-visualization-static
http-server -p 8080
```

Truy cập: `http://localhost:8080`

## 🌐 Deploy lên hosting miễn phí

### 1. GitHub Pages

```bash
# Tạo repository trên GitHub
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/stock-visualization.git
git push -u origin main

# Vào Settings > Pages > chọn main branch
```

URL: `https://username.github.io/stock-visualization`

### 2. Netlify

1. Kéo thả folder `stock-visualization-static` vào https://app.netlify.com/drop
2. Hoặc kết nối với GitHub repository
3. Netlify tự động deploy

### 3. Vercel

```bash
npm i -g vercel
cd stock-visualization-static
vercel
```

### 4. Render

1. Đăng nhập https://render.com
2. New > Static Site
3. Kết nối với GitHub repo
4. Deploy

## 📦 Yêu cầu

- Trình duyệt hiện đại (Chrome, Firefox, Edge, Safari)
- JavaScript enabled
- Không cần cài đặt thêm gì

## 🎨 Công nghệ sử dụng

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Responsive Design

## 📊 Dữ liệu

- File `vnstock_listing_companies.csv`: Danh sách công ty
- File `SZL.csv`: Lịch sử giao dịch cổ phiếu SZL

## 🔧 Tùy chỉnh

Bạn có thể tùy chỉnh:
- Màu sắc trong file `css/styles.css` (CSS variables)
- Logic xử lý trong file `js/app.js`
- Nội dung HTML trong `index.html`

## 📝 Ghi chú

- Ứng dụng chạy hoàn toàn trên client-side
- Không cần backend hay database
- Dữ liệu được mô phỏng, không kết nối API thật

## 👨‍💻 Tác giả

**Lưu Trần Kim Phú**  
MSSV: 23133055  
Email: [your-email@example.com]

## 📄 License

MIT License - Free to use for educational purposes

---

⭐ Nếu project hữu ích, hãy cho một star!
