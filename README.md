# Down666 — Thoại theo vị trí, radar và bản đồ cho The Isle

**Phiên bản kỹ thuật 0.2.20 · Hiển thị V.0.1.10 · Windows 64 bit**

Down666 giúp người chơi trong các server tương thích dễ tìm nhau, xác định hướng và khoảng cách để phối hợp qua thoại. Giao diện tiếng Việt, tông than/bạc/xanh ô liu, logo nền trong suốt và bố cục đơn giản.

## Có gì trong ứng dụng?

- Thoại theo vị trí; micro mở hoặc nhấn để nói; chọn thiết bị và chỉnh âm lượng.
- Xem dữ liệu không cần vào thoại, khi nguồn máy chủ hỗ trợ.
- Tên Steam, Steam ID, số mét và hướng; danh sách từ gần đến xa.
- Radar tùy chỉnh phạm vi, HUD trên game và chế độ toàn màn hình.
- Bản đồ thực tế với lớp nước ngọt, zoom bằng con lăn, theo vị trí của bạn và danh sách người chơi bên phải.
- Tìm kiếm máy chủ, kiểm tra giấy phép, cập nhật trong app và gửi báo lỗi.

## Bản này sửa gì?

- Bổ sung xử lý nâng cấp từ IsleVOIP tên cũ sang Down666: giải phóng tiến trình đúng thư mục và giữ dữ liệu kích hoạt/cài đặt.
- Dừng hook phím toàn cục trước khi cài; chặn bấm cập nhật nhiều lần tạo nhiều yêu cầu cài đặt.
- Kiểm tra lại chữ ký và nội dung bộ cài ngay trước khi khởi động cài đặt.
- Ghi nhật ký chuẩn bị cài đặt để hỗ trợ xác định lỗi trên máy khách.

## Tải và cài

Trong **Assets**, tải **Down666-Setup-0.2.20.exe**, chạy bộ cài và làm theo hướng dẫn. Sau khi mở app, liên hệ chủ ứng dụng bằng đường dẫn trên màn hình kích hoạt để mua/thuê, cung cấp mã máy và nhận giấy phép.

**Nếu đang bị lỗi bộ cài cũ:** đóng thông báo lỗi/bộ cài cũ rồi chạy bộ cài mới này một lần. Không xóa `%APPDATA%\isle-voip-overlay` để tránh mất định danh kích hoạt và cài đặt. Từ bản đã nâng cấp, dùng chức năng cập nhật trong app cho các bản tiếp theo.

**Yêu cầu:** Windows 10/11 x64, Internet, Steam/The Isle, giấy phép còn hiệu lực; micro và quyền micro nếu dùng thoại; server phải hỗ trợ nguồn dữ liệu tương ứng. Cài Npcap riêng không bổ sung vị trí/camera cho bản này.

**Hướng dẫn đầy đủ:** tải **HUONG-DAN.md** ở Assets để xem cài đặt, kích hoạt, thao tác thoại/radar/bản đồ, cập nhật và xử lý lỗi.

Phạm vi radar chỉ lọc hiển thị. Dữ liệu tên, vị trí và số lượng người phụ thuộc nguồn server/Steam; không cam kết nhìn thấy toàn bộ người chơi hay dữ liệu không có độ trễ. Tải bộ cài công khai không cấp quyền dùng miễn phí; cần giấy phép do chủ Down666 cấp. Giá thuê/mua và hỗ trợ theo thông tin liên hệ trong ứng dụng.


## Liên kết

- [Tải bộ cài mới nhất](https://github.com/nnhatnam05/down666/releases/latest)
- [Đọc hướng dẫn sử dụng đầy đủ](HUONG-DAN.md)

Kho này chỉ phát hành bộ cài và tài liệu. Mã nguồn ứng dụng được quản lý riêng tư.
