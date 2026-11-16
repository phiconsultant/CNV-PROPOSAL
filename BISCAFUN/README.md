# BISCAFUN × CNV CDP — Proposal V5

## Nội dung
8 section: Hero, Bối cảnh, TMĐT & MT/GT (OHAR + Marukame), FMCG QR Unique (O’Food), Offline (ADOLPH + BCA), Affiliate, Case studies (Gấu Đỏ + Semir), Ngân sách từ bản V4.

## Assets
- `index.html` sử dụng các đường dẫn tương đối `assets/...`
- `assets/case-studies/` có 47 ảnh WebP chuyển từ các tư liệu người dùng gửi (giữ nguyên hình ảnh/nội dung).
- Logo Biscafun và CNV CDP, favicon được kế thừa từ V4.
- Mở `index.html` trực tiếp để xem; tải toàn thư mục lên GitHub Pages để xuất bản.

## Lưu ý quan trọng
- Case study minh họa: không suy diễn kết quả triển khai hoặc mức độ thành công chưa được chứng minh.
- 20.000 của Gấu Đỏ là mục tiêu chiến dịch, không phải số khách hàng đã thu thập.
- Một số ảnh gốc chứa tên và số điện thoại cá nhân nhìn thấy trên giao diện. **Cần kiểm tra quyền sử dụng, sự đồng ý của chủ thể và ẩn thông tin nhận diện nếu dùng website công khai.**
- Bảng giá nguyên theo Proposal V4; chưa thay đổi.


## Cập nhật V6
- Section Affiliate: bỏ 2 ảnh tổng quan, thay bằng 4 khối mô tả cơ chế và giữ nguyên 5 ảnh màn hình.
- Section báo giá: bỏ App nhân viên (Loyalty Hub); tổng các hạng mục tính phí năm đầu **490.400.000đ** và gia hạn **465.400.000đ** vẫn giữ theo báo giá; không còn dòng giảm giá App nhân viên trong phần tổng kết.
- Điều chỉnh kích thước chữ tổng gia hạn để không xuống hàng bất thường.
- Làm nổi bật giá vận hành tháng đầu **15.000.000đ** và tháng sau **10.500.000đ/tháng**.


## V9 — Cập nhật ngân sách (chỉ Section 08)
- Gói nền tảng gồm đúng 4 hạng mục: Loyalty & Ecom / Mini App; CNV CDP; Hạ tầng hệ thống; Kết nối API bên thứ ba.
- Tổng gói nền tảng: 158.400.000đ năm đầu; 133.400.000đ gia hạn.
- Nhóm add-on 6 hạng mục: 332.000.000đ năm đầu và gia hạn.
- Tổng giữ nguyên: 490.400.000đ năm đầu; 465.400.000đ gia hạn; vận hành 15.000.000đ tháng đầu, 10.500.000đ/tháng từ tháng 2.
- Thiết kế mới chỉ scope `.pricing`; 7 section khác được giữ nguyên.

## Hero V9
- Hero theo visual reference Biscafun, text/CTA/benefit cards là HTML có thể chỉnh sửa.
- Background được trích riêng từ ảnh tham khảo người dùng cung cấp và lưu ở `assets/biscafun-hero-products.webp`.
- Các section 02–08 giữ nguyên so với V7.

## V9 — Hero image alignment
- Fixed desktop and tablet hero product-image gap at top by changing the background fitting from `contain` to `cover` and anchoring to `right top`.
- All other sections and assets remain unchanged.

## V10 updates
- Hero uses `assets/biscafun-hero-products-v10.webp` from user-provided HERO IMAGE.png.
- Section 02: Mini App overview.
- Section 03: ecommerce QR journey before cases; removed the OHAR overview only.
- Section 04: QR Unique game journey before O’Food case.
- Section 05: offline sampling check-in journey before cases.
- All illustration images are separate relative WebP assets; use the existing global lightbox.
