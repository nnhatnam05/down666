# Down666 — Bộ cài và cập nhật Windows

[Tải bản mới nhất](https://github.com/nnhatnam05/down666-releases/releases/latest)

## Cài đặt lần đầu hoặc chuyển từ V.0.1.0

1. Mở trang bản mới nhất và tải tệp `Down666-Setup-<version>.exe`.
2. Đóng Down666 rồi chạy Setup. Nếu đã cài, chọn cùng vị trí và cùng phạm vi người dùng để cài đè. Không cần gỡ trước.
3. Mở ứng dụng. Các bản mới sau đó được tải trong nền và áp dụng khi thoát hoặc bấm khởi động lại.

Bản mới nhất hiện tại hiển thị V.0.1.2, kỹ thuật 0.2.12. File phù hợp Windows 64 bit. Các bản V.0.1.0 đã tắt updater nên cần cài đè một lần để chuyển sang cập nhật tự động.

## Cập nhật tự động

Ứng dụng kiểm tra lúc mở và mỗi 10 phút. Có thể kiểm tra thủ công trong Cài đặt. Không cần tài khoản GitHub. Không tự đóng ứng dụng khi đang sử dụng. Khi mất mạng hoặc xác minh thất bại, bản đang cài vẫn hoạt động và có thể thử lại.

Các tệp `latest.yml`, `.blockmap`, `.sig.json`, `.sha256` phục vụ cập nhật và kiểm tra; người dùng chỉ cần Setup. Bản cập nhật được xác minh bằng chữ ký Ed25519 Down666. Đây không phải chứng thư Authenticode Windows; bộ cài chưa có chứng thư Windows.

Repo này chỉ lưu hướng dẫn và bản phát hành. Mã nguồn được lưu riêng tư; không có khóa phát hành hoặc dữ liệu đăng nhập người dùng tại đây.

Ứng dụng cần Internet, dịch vụ VOIP/relay và máy chủ hỗ trợ nguồn dữ liệu tương ứng. Chỉ số dino dùng đăng nhập IslePilot riêng.
