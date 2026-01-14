# VP Computer - Website Thương Mại Điện Tử Bán Linh Kiện PC

![VP Computer Screenshot](https://raw.githubusercontent.com/TranHuuDat2004/vpcomputer.com/main/img/screenshot.png) 

Đây là dự án mã nguồn cho website **VP Computer**, một trang thương mại điện tử chuyên cung cấp linh kiện máy tính, gaming gear và các giải pháp PC tùy chỉnh. Dự án được xây dựng hoàn toàn bằng HTML, CSS và JavaScript thuần túy, không phụ thuộc vào các framework lớn, tập trung vào hiệu năng, khả năng tùy biến và trải nghiệm người dùng mượt mà.

## ✨ Các Tính Năng Nổi Bật

### 👤 Giao Diện Khách Hàng (Client-Side)
- **Thiết kế Hiện đại & Responsive:** Giao diện sạch sẽ, chuyên nghiệp, hiển thị đẹp mắt trên mọi thiết bị từ desktop, tablet đến mobile.
- **Trang chủ Năng động:** Slider quảng cáo, danh mục nổi bật, sản phẩm bán chạy được tải động.
- **Trang Sản phẩm Thông minh:**
    - Bộ lọc đa điều kiện (Danh mục, Giá, Thương hiệu).
    - Sắp xếp sản phẩm (Mặc định, Giá tăng/giảm).
    - Hiển thị sản phẩm ngẫu nhiên để tăng khả năng khám phá.
- **Trang Chi tiết Sản phẩm:**
    - Gallery ảnh với hiệu ứng zoom.
    - Hiển thị giá khuyến mãi, thông số kỹ thuật, đánh giá.
    - Logic kiểm tra tình trạng kho hàng.
- **Công cụ Xây dựng Cấu hình (PC Builder):**
    - Cho phép người dùng tự chọn linh kiện.
    - Tự động kiểm tra tính tương thích (Socket CPU & Mainboard, chuẩn RAM, công suất nguồn).
- **Hệ thống Giỏ hàng:**
    - Sidebar giỏ hàng tiện lợi, không cần tải lại trang.
    - Lưu trữ giỏ hàng bằng LocalStorage, không mất khi đóng trình duyệt.
- **Quy trình Thanh toán Hoàn chỉnh:**
    - Trang giỏ hàng chi tiết.
    - Trang thanh toán tối giản.
    - Tự động tạo và tải hóa đơn PDF sau khi đặt hàng.
- **Hệ thống Trang Tĩnh:** Giới thiệu, Tuyển dụng, Chính sách, FAQ... được thiết kế chuyên nghiệp.

### 🔐 Giao Diện Quản Trị (Admin Dashboard)
- **Tách biệt & Bảo mật:** Nằm trong thư mục `/admin` với trang đăng nhập riêng.
- **Tổng quan Trực quan:** Biểu đồ doanh thu, lợi nhuận, và các chỉ số quan trọng.
- **Quản lý Dữ liệu:** Các trang quản lý Sản phẩm, Đơn hàng, Khách hàng với giao diện bảng biểu và responsive.
- **Cấu trúc Module hóa:** Dễ dàng mở rộng thêm các tính năng quản lý mới.

## 🚀 Công Nghệ Sử Dụng

- **Frontend:**
  - **HTML5:** Cấu trúc ngữ nghĩa
  - **CSS3:**
    - Flexbox & Grid Layout cho bố cục responsive.
    - CSS Variables (Biến CSS) để dễ dàng thay đổi theme.
    - Animation & Transition cho các hiệu ứng mượt mà.
  - **JavaScript (ES6+):**
    - Hoàn toàn không sử dụng framework, tập trung vào JavaScript thuần túy (Vanilla JS).
    - DOM Manipulation để tạo giao diện động.
    - LocalStorage để lưu trữ dữ liệu phía client.
    - Sử dụng Web Components (Custom Elements) để module hóa Header, Footer, Sidebar.
- **Thư viện:**
  - **Font Awesome:** Cho các icon.
  - **jsPDF:** Để tạo hóa đơn PDF phía client.

## ⚙️ Cài Đặt và Chạy Dự Án

Dự án này là một website tĩnh (static website) nên không yêu cầu cài đặt phức tạp.

1.  **Clone a repository:**
    ```bash
    git clone https://github.com/TranHuuDat2004/vpcomputer.com.git
    ```
2.  **Mở file `index.html`:**
    - Cách đơn giản nhất là mở file `index.html` ở thư mục gốc trực tiếp bằng trình duyệt.
    - **Khuyến nghị:** Sử dụng một server ảo để tránh các lỗi liên quan đến CORS khi làm việc với file. Tiện ích **Live Server** trên Visual Studio Code là một lựa chọn tuyệt vời.
      - Cài đặt Live Server trên VS Code.
      - Nhấp chuột phải vào file `index.html` và chọn "Open with Live Server".




## ✒️ Tác giả

Được phát triển và thiết kế bởi Trần Hữu Đạt.

---
_Dự án được xây dựng với mục tiêu học hỏi và tạo ra một nền tảng website TMĐT hoàn chỉnh bằng các công nghệ web cơ bản._
