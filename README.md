# Turnwood

Website bán nội thất của Turnwood, dạng phòng trưng bày 3D. Cuộn trang để trượt ngang qua tám thiết kế, mỗi thiết kế đặt trên một phông màu riêng. Bạn có thể đổi gỗ, vải và ánh sáng ngay trên mô hình, rồi xem giá cập nhật theo cấu hình.

## Tính năng

- Sân khấu 3D dựng bằng [three.js](https://threejs.org/) (r147), toàn bộ mô hình được dựng bằng code, không cần file 3D ngoài.
- Tuỳ chỉnh tại chỗ: gỗ khung, vải bọc, kim loại, ánh sáng Trưa / Chiều / Tối, đường đo kích thước thật.
- Phần Cấu tạo: ghế Sương tách lớp theo cuộn trang, có đường chỉ dẫn tới từng lớp.
- Sổ danh mục có bộ lọc và ảnh mẫu đi theo con trỏ.
- Giỏ hàng dạng phiếu đặt hàng, lưu trên trình duyệt (localStorage).

## Chạy thử

Toàn bộ trang nằm trong một file `index.html`. Mở file đó bằng trình duyệt là chạy được, hoặc phục vụ qua một máy chủ tĩnh bất kỳ:

```bash
npx serve .
```

Để đưa lên mạng miễn phí, bật **GitHub Pages** trong *Settings → Pages* của repo, chọn nhánh `main` và thư mục gốc.

## Ghi chú

Đây là website mẫu: giá, số liệu xưởng và địa chỉ showroom mang tính minh hoạ, chưa có bước thanh toán thật. Phông chữ tải từ Google Fonts, thư viện three.js tải từ jsDelivr.
