# Yêu cầu dự án: Vietjet Landing Page

Tệp này ghi lại các yêu cầu chi tiết về giao diện, tính năng và nội dung của trang Landing Page Vietjet.

## 1. Yêu cầu chung
- **Chủ đề**: Trang web bán vé máy bay (tour, vé, hãng bay...) của Vietjet.
- **Tệp chính**: Toàn bộ mã nguồn (HTML, CSS, JavaScript) được gộp chung vào một tệp `index.html`.
- **Backend**: Tuyệt đối không sử dụng bất kỳ ngôn ngữ backend nào. Chỉ render giao diện frontend.
- **Màu sắc chủ đạo**:
  - Trắng (White): `#f2f2f2` (Thường dùng cho background).
  - Đỏ (Red): `#ee1d23` (Màu thương hiệu Vietjet, dùng cho nút bấm, tiêu đề, điểm nhấn).

## 2. Các thành phần trang web (UI Sections)

### 2.1. Header / Navbar
- **Nội dung**: Logo thương hiệu Vietjet và menu điều hướng đơn giản (Ví dụ: Trang chủ, Chuyến bay, Khuyến mãi, Liên hệ).
- **Tài nguyên**: Logo được tải từ thư mục `images/`.
- **Màu sắc**: Có thể sử dụng nền đỏ hoặc trắng, chữ tương phản dễ đọc.

### 2.2. Hero Section
- **Bố cục**: Chia làm 2 cột (hoặc bố cục flex/grid phù hợp).
- **Bên trái**: 
  - Tiêu đề chính (Ví dụ: "Bay khắp chốn, đón niềm vui cùng Vietjet").
  - Đoạn mô tả ngắn gọn về dịch vụ.
  - 1 Nút kêu gọi hành động (Call to Action - CTA) nổi bật (Ví dụ: "Đặt vé ngay"), sử dụng màu `#ee1d23`.
- **Bên phải**:
  - Hình ảnh một chiếc máy bay của Vietjet.
  - **Tài nguyên**: Hình ảnh lấy từ thư mục `images/`.

### 2.3. Features Section (Danh sách chuyến bay)
- **Nội dung**: Hiển thị danh sách các chuyến bay nổi bật hoặc đang khuyến mãi.
- **Định dạng hiển thị**: Danh sách dạng thẻ (cards) hoặc bảng đơn giản.
- **Dữ liệu mẫu**:
  - `TPHCM - Hà Nội (một chiều): 4.000.000 VND`
  - `TPHCM - Đà Nẵng (một chiều): 1.500.000 VND`
  - `Hà Nội - Phú Quốc (một chiều): 2.200.000 VND`

### 2.4. Footer
- **Nội dung**: 
  - Thông tin bản quyền (Copyright © 2026 Vietjet Air).
  - Thông tin liên hệ cơ bản (Hotline, Email).
- **Màu sắc**: Nền tối hoặc nền đỏ `#ee1d23` với chữ trắng.