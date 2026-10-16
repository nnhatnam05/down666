# Down666 — Cài đặt và sử dụng

Down666 là ứng dụng Windows hỗ trợ trò chuyện theo vị trí trong The Isle trên các máy chủ tương thích, kết hợp danh sách người chơi, radar định hướng và bản đồ thực tế.

## Chức năng

- Tìm máy chủ theo tên, hỗ trợ tiếng Việt có dấu và không dấu.
- Trò chuyện theo vị trí: micro, nhấn để nói, tắt micro, thiết bị đầu vào/đầu ra và âm lượng từng người.
- Chế độ **Xem không vào thoại**: xem dữ liệu được máy chủ cung cấp mà không mở micro hoặc tham gia kênh âm thanh.
- Danh sách tên người chơi, Steam ID, khoảng cách và hướng tương đối; sắp xếp gần đến xa.
- Radar tùy chỉnh phạm vi; HUD định hướng; radar toàn màn hình trong Down666.
- Bản đồ thực tế, lớp nước ngọt, thu phóng bằng con lăn, theo tâm vị trí của bạn; tên/khoảng cách trên điểm và bảng thông tin bên phải.
- Quét toàn bộ: mở rộng phạm vi đến các tọa độ hợp lệ mà máy chủ đang cung cấp.
- Kích hoạt bằng giấy phép theo máy, kiểm tra hạn sử dụng và cập nhật trong ứng dụng.
- Gửi báo lỗi về hệ thống quản trị của chủ ứng dụng.

## Yêu cầu

- Windows 10/11 bản 64 bit; tài khoản Windows có quyền cài phần mềm cho chính mình.
- Internet hoạt động, Steam và The Isle; máy chủ chơi phải được hệ thống thoại/dữ liệu hỗ trợ.
- Giấy phép hợp lệ do chủ Down666 cấp. Tải bộ cài không đồng nghĩa có quyền sử dụng.
- Micro và quyền truy cập micro trong Windows nếu dùng thoại; tai nghe được khuyến nghị.
- Dùng cửa sổ không viền nếu muốn xem HUD phủ trên game.

Down666 hiện nhận vị trí từ nguồn dữ liệu máy chủ. Không cần cài Npcap để sử dụng bản này. Cài Npcap riêng không tự bổ sung dữ liệu vị trí hoặc góc camera cho ứng dụng.

## Cài mới

1. Mở [trang phát hành chính thức](https://github.com/nnhatnam05/down666/releases/latest).
2. Tải **Down666-Setup-0.2.20.exe** trong phần **Assets**. Không tải mục Source code để cài ứng dụng.
3. Chạy bộ cài, chọn thư mục và hoàn tất. Bộ cài có thể đóng Down666/IsleVOIP đang chạy để giải phóng tệp; hãy kết thúc cuộc thoại trước.
4. Mở Down666, sao chép mã máy và liên hệ chủ ứng dụng qua dòng liên hệ trên màn hình kích hoạt.
5. Nhập mã giấy phép được cấp, bấm **Kích hoạt**. Không chia sẻ mã giấy phép cho người khác.

## Nâng cấp từ bản cũ hoặc khắc phục lỗi “Không thể gỡ các tệp của phiên bản cũ”

1. Nếu bộ cài cũ đang báo lỗi, bấm OK và đóng bộ cài đó.
2. Tải bộ cài mới nhất từ liên kết chính thức ở trên và chạy một lần. Bộ cài mới xử lý tiến trình Down666 và tên cũ IsleVOIP tại đúng thư mục cài đặt, đồng thời giữ dữ liệu người dùng khi chuyển đổi bản cũ.
3. Không xóa thư mục `%APPDATA%\isle-voip-overlay`: thư mục này chứa cài đặt và định danh kích hoạt.
4. Nếu vẫn gặp lỗi, khởi động lại Windows rồi chạy lại bộ cài mới nhất. Không chạy nhiều bộ cài đồng thời.
5. Gửi ảnh lỗi và nhật ký `%LOCALAPPDATA%\Down666\Installer\install.log` cho chủ ứng dụng. Nhật ký này không chứa mã giấy phép hay khóa Steam.

Các bản cũ đã cài không thể tự nhận phần sửa mã đang chạy trước khi nâng cấp thành công. Khi mắc kẹt ở bộ cài cũ, cần dùng bộ cài mới một lần.

## Bắt đầu sử dụng

1. Đăng nhập Steam trong Down666 và mở The Isle.
2. Vào **Danh sách máy chủ**, dùng ô **Tìm máy chủ** để tìm đúng server đang chơi.
3. Chọn **Xem không vào thoại** nếu chỉ cần danh sách/radar/bản đồ; hoặc chọn chế độ/kênh thoại để nói chuyện.
4. Trong **Cài đặt**, chọn micro, tai nghe, chế độ nhấn để nói hoặc micro mở và phím tắt phù hợp.
5. Nhập phạm vi radar theo mét. Phạm vi này lọc phần hiển thị, không thay đổi cự ly nghe do hệ thống thoại quyết định.
6. Bật HUD hoặc toàn màn hình; chọn **Xem trên bản đồ thực tế** để dùng bản đồ. Dùng con lăn để thu phóng, **Vừa phạm vi** để bao quát vòng tròn đã đặt, **Toàn bản đồ** để xem toàn cảnh.
7. Xem tên, Steam ID, số mét và hướng ở bảng bên phải. Điểm trên bản đồ hiển thị tên và khoảng cách.

## Giấy phép và cập nhật

- Vào **Cài đặt → Giấy phép** để xem trạng thái, mã máy, hạn sử dụng, kiểm tra hoặc gỡ kích hoạt.
- Giấy phép có thể bị khóa khi hết hạn hoặc bị chủ ứng dụng thu hồi. Ứng dụng cần kết nối máy chủ giấy phép; mất mạng kéo dài có thể làm khóa phiên sử dụng.
- Đổi máy cần được gỡ kích hoạt/cấp lại theo chính sách của chủ ứng dụng.
- Ứng dụng kiểm tra và tải cập nhật; khi báo bản mới đã sẵn sàng, kết thúc cuộc thoại rồi chọn khởi động lại để cập nhật.

## Hiểu đúng dữ liệu

- Số người có tọa độ có thể ít hơn tổng người trong server. Ứng dụng chỉ hiển thị vị trí khi nhận được tọa độ hợp lệ và còn mới; không tự tạo vị trí cho người chưa có dữ liệu.
- Quét toàn bộ không vượt qua giới hạn dữ liệu phía máy chủ và không bảo đảm thấy mọi người trong game.
- Tên bổ sung từ Steam là tên hồ sơ Steam công khai; có thể khác biệt danh trong game và cần thời gian tra cứu.
- Khoảng cách danh sách tính trong không gian 3D; vòng tròn lọc trên bản đồ dùng khoảng cách ngang.
- Hướng hiện dựa trên góc dino/dữ liệu nguồn đã có. Không quảng cáo là góc camera thật khi nguồn không cung cấp dữ liệu camera.
- Bản đồ và vị trí cập nhật khi có mẫu mới từ máy chủ; không cam kết độ trễ bằng không hoặc chính xác tuyệt đối.
- Người chưa tham gia thoại có thể xuất hiện trong dữ liệu, nhưng không thể nghe/nói với họ nếu họ không tham gia hệ thống thoại tương ứng.

## Hỗ trợ

Dùng nút **Báo lỗi** trong Down666, mô tả thao tác, tên máy chủ, thời điểm xảy ra và hiện tượng. Chủ ứng dụng nhận báo cáo trong web quản trị. Liên hệ mua/thuê và hỗ trợ theo đường dẫn do chủ ứng dụng cấu hình trên màn hình kích hoạt. Giá, thời hạn và điều kiện đổi máy do chủ ứng dụng thông báo trước khi cấp mã.

Down666 là công cụ hỗ trợ cộng đồng, không phải sản phẩm chính thức của nhà phát hành The Isle. Các chức năng phụ thuộc dịch vụ liên quan và quy định máy chủ đang chơi.
