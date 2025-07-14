# Mama-Baby Store FE

Mama-Baby là nền tảng thương mại điện tử chuyên cung cấp các sản phẩm sữa dinh dưỡng chất lượng cao dành cho mẹ bầu và trẻ nhỏ. Dự án này là giao diện người dùng (frontend) được xây dựng bằng ReactJS, sử dụng Material UI, Redux Toolkit và nhiều thư viện hiện đại khác.

## Giới thiệu

Mama-Baby hướng tới việc hỗ trợ sức khỏe và dinh dưỡng cho mẹ bầu, trẻ sơ sinh và trẻ nhỏ thông qua các sản phẩm sữa giàu dưỡng chất, cùng các dịch vụ tư vấn, chăm sóc khách hàng tận tâm.

### Sứ mệnh

- Đảm bảo chất lượng sản phẩm sữa cho mẹ và bé.
- Cung cấp dịch vụ tư vấn dinh dưỡng, hỗ trợ khách hàng.
- Đáp ứng nhu cầu mua sắm tiện lợi, an toàn, nhanh chóng.

## Tính năng chính

### Đối với khách hàng (Member)

- Đăng ký, đăng nhập, quản lý tài khoản cá nhân.
- Duyệt, tìm kiếm, lọc sản phẩm theo độ tuổi, thương hiệu, danh mục.
- Thêm sản phẩm vào giỏ hàng, đặt hàng, thanh toán trực tuyến (VNPay), sử dụng voucher.
- Xem lịch sử đơn hàng, đánh giá sản phẩm, tích điểm đổi quà.
- Theo dõi các chương trình khuyến mãi, ưu đãi.
- Đăng ký mở cửa hàng (nâng cấp lên Staff).

### Đối với nhân viên cửa hàng (Staff)

- Quản lý sản phẩm, đơn hàng, đổi/trả hàng, voucher, bài viết, gói sản phẩm.
- Xem dashboard thống kê doanh thu, đơn hàng, hoàn tiền, đổi trả.
- Quản lý thông tin cửa hàng cá nhân.

### Đối với quản trị viên (Admin)

- Quản lý tài khoản người dùng, phê duyệt yêu cầu mở cửa hàng.
- Quản lý danh mục, thương hiệu, độ tuổi, gói sản phẩm.
- Quản lý hệ thống cửa hàng, thống kê tổng quan toàn hệ thống.

## Công nghệ sử dụng

- ReactJS 18
- Material UI 5
- Redux Toolkit
- React Router DOM
- Axios
- Chart.js, react-chartjs-2
- Bootstrap
- Socket.io-client
- VNPay tích hợp thanh toán

## Cài đặt & Chạy dự án

1. **Clone repo:**
   ```bash
   git clone <repo-url>
   cd Mama_Baby_Store_FE
   ```
2. **Cài đặt dependencies:**
   ```bash
   npm install
   ```
3. **Chạy ứng dụng:**
   ```bash
   npm start
   ```
   Ứng dụng sẽ chạy tại [http://localhost:3000](http://localhost:3000)

## Scripts

- `npm start`: Chạy chế độ phát triển
- `npm run build`: Build production
- `npm test`: Chạy test
- `npm run eject`: Eject cấu hình CRA

## Thông tin thêm

- Dự án sử dụng Create React App làm nền tảng khởi tạo.
- Kết nối API backend qua các file trong `src/api/`.
- Quản lý trạng thái với Redux Toolkit và redux-persist.
- Giao diện responsive, tối ưu cho cả desktop và mobile.

---

Nếu có thắc mắc hoặc cần hỗ trợ, vui lòng liên hệ nhóm phát triển.
