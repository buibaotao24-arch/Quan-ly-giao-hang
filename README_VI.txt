QUẢN LÝ GIAO HÀNG – MVP 01

CÓ SẴN:
- Giao diện navy tối ưu điện thoại.
- Tạo/lưu thông tin tuyến.
- Danh bạ địa chỉ: thêm, tìm, mở Google Maps, xóa.
- Lịch sử tuyến.
- Báo cáo cơ bản (số liệu điểm giao sẽ có khi giai đoạn sau bổ sung điểm dừng).
- Xuất/khôi phục bản sao lưu JSON.
- Nhắc sao lưu sau 7 ngày.
- PWA/service worker để cài trên Android khi host qua HTTPS.

CHƯA CÓ TRONG GIAI ĐOẠN 1:
- Nhập Excel.
- Thêm điểm giao vào tuyến.
- Tối ưu thứ tự/chia chặng.
- Theo dõi trạng thái từng điểm.
- Bản đồ nhúng hoặc xác minh tọa độ.
- Đồng bộ đám mây.

CÀI THỬ:
1. Giải nén ZIP.
2. Mở index.html bằng Chrome để xem giao diện; mở file trực tiếp chỉ dùng thử cơ bản.
3. Muốn cài như app và dùng offline: host toàn bộ thư mục trên HTTPS (ví dụ GitHub Pages miễn phí).
4. Trên GitHub tạo repository mới, tải các file trong thư mục này lên nhánh main ở thư mục gốc.
5. Vào Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
6. Chờ GitHub tạo địa chỉ dạng https://TEN-TAI-KHOAN.github.io/TEN-REPO/
7. Mở địa chỉ đó bằng Chrome Android > menu ⋮ > Install app hoặc Add to Home screen.
8. Mở biểu tượng QUẢN LÝ GIAO HÀNG trên màn hình chính.

SAO LƯU:
- Vào Cài đặt > Xuất file, lưu JSON vào Google Drive.
- Không xóa dữ liệu Chrome/site data trước khi sao lưu.
- Khi đổi máy, mở app trên máy mới > Cài đặt > Chọn file để khôi phục.

LƯU Ý QUYỀN RIÊNG TƯ:
Dữ liệu nằm trong bộ nhớ trình duyệt của thiết bị. File sao lưu có thể chứa thông tin khách hàng; hãy giữ riêng tư.

GIAI ĐOẠN 2 DỰ KIẾN:
Đọc Excel nhiều Sheet, làm sạch dữ liệu, phát hiện trùng/thiếu địa chỉ, quản lý điểm giao và đưa điểm vào từng tuyến.
