# Bài 4 : Rủi ro đánh cắp mật khẩu từ trình duyệt

### 1. Bảng so sánh

| Tiêu chí | Google Chrome | Bitwarden |
|---|---|---|
| Khả năng chống Infostealer | Thấp hơn vì mã độc có thể tìm cách lấy dữ liệu mật khẩu lưu trong trình duyệt. | Tốt hơn nhờ cơ chế mã hóa và yêu cầu Master Password để mở khóa. |
| Zero-Knowledge Architecture | Không sử dụng kiến trúc Zero-Knowledge theo mô hình của Bitwarden. | Có. Dữ liệu được mã hóa trước khi đồng bộ, nhà cung cấp không đọc được mật khẩu gốc. |
| Đồng bộ chéo nền tảng | Đồng bộ qua tài khoản Google, hỗ trợ nhiều thiết bị. | Hỗ trợ Windows, macOS, Linux, Android, iOS và nhiều trình duyệt. |
| Tính tiện lợi | Cao, lưu và tự động điền mật khẩu nhanh chóng. | Cần thêm thao tác mở khóa bằng Master Password hoặc phương thức mở khóa an toàn khác. |

### 2. Tại sao Bitwarden có lợi thế về bảo mật?
- Mã hóa dữ liệu: Bitwarden mã hóa mật khẩu trước khi đồng bộ lên máy chủ.
- Master Password: Người dùng cần Master Password để mở khóa kho mật khẩu.
- Zero-Knowledge: Ngay cả nhân viên Bitwarden cũng không thể đọc mật khẩu gốc của người dùng.
- Giảm nguy cơ lộ dữ liệu: Khi kho mật khẩu đang khóa, dữ liệu được bảo vệ tốt hơn trước việc đánh cắp trực tiếp.

### 3. Kết luận và đề xuất
Công ty nên bắt buộc nhân viên sử dụng Bitwarden thay vì lưu mật khẩu trực tiếp trên Google Chrome.

Mặc dù Bitwarden cần thêm thao tác nhập Master Password, nhưng đổi lại giúp bảo vệ mật khẩu tốt hơn nhờ cơ chế mã hóa và Zero-Knowledge.

Lưu ý: Bitwarden không thể chống hoàn toàn Infostealer. Nếu máy tính đã nhiễm mã độc hoặc kho mật khẩu đang mở khóa, kẻ tấn công vẫn có thể lấy cắp thông tin. Vì vậy, công ty cần kết hợp cập nhật phần mềm, quét mã độc và khóa Bitwarden khi không sử dụng
