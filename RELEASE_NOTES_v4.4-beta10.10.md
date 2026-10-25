# 🐝 Buzz! Messenger v4.4-beta10.10 — Code 114

> **Ứng viên Hotfix cho Android Open Beta.** Đây là ghi chú chuẩn bị phát hành; file APK chưa được đính kèm vào GitHub Releases tại thời điểm lập tài liệu.

## Tính năng được sửa

- **Lưu ảnh Chat 1-1:** mở ảnh toàn màn hình → **Lưu ảnh vào máy**, hoặc nhấn giữ ảnh → **Lưu ảnh vào thư viện**.
- **Android 10 trở lên:** lưu vào thư viện tại `Pictures/Buzz` qua MediaStore. **Android 8/9:** chọn nơi lưu bằng trình chọn tệp hệ thống.
- **Reply Jump:** chạm vào ô trích dẫn Reply để cuộn đến tin nhắn gốc đang có trong danh sách và làm nổi bật bằng viền.

## Giới hạn đang biết

- Các Reply cũ chỉ chứa **nội dung trích dẫn, không có ID tin nhắn gốc**. Buzz dò những tin đã tải (khoảng 100 tin); tin trùng nội dung, đã xóa hoặc quá cũ có thể không tìm đúng.
- Lưu ảnh Google Drive cũ vẫn cần quyền truy cập/token Google Drive còn hiệu lực.
- Cần nghiệm thu trên máy Android thật với ảnh nhận từ tài khoản khác, tin Reply và tin nhắn cũ trước khi quảng bá rộng rãi.

## Thông tin APK được kiểm tra

- **Tên file:** `BuzzMessenger_v4.4-beta10.10_Code114_release.apk`
- **Phiên bản:** `4.4-beta10.10-chat-hotfix`
- **Version code:** `114`
- **Package:** `com.buzz.messenger`
- **Android tối thiểu:** API 26 (Android 8.0)
- **Kích thước:** 119192088 bytes
- **SHA-256:** `2a6e1cf08ca13555b54f445a491d57fe361ffd46fed241391205b2ae7f8a5318`
- **Chứng thư ký SHA-256:** `643798b942aa1b70344482ac5583e6e20147f415caff6ff717ca7390bad29771`
- **Chữ ký APK v2 và digest nội dung:** đã xác minh hợp lệ.
- **Khóa ký:** cùng khóa Release với Code 113; `versionCode 114 > 113` nên có thể nâng cấp trực tiếp từ bản 113 (về chữ ký và versionCode).
- **Không bật `debuggable`.**
- **Còn cần đánh giá:** `allowBackup=true` và `usesCleartextTraffic=true` (đã tồn tại ở bản trước).

## Phát hành qua GitHub Releases

1. Vào **Releases → Draft a new release** trên repository này.
2. Tạo tag mới **`v4.4-beta10.10`**, target `main`, chọn **Pre-release**.
3. Title: **Buzz! Messenger 4.4 Beta 10.10 — Code 114 Chat Hotfix**.
4. Đính kèm `BuzzMessenger_v4.4-beta10.10_Code114_release.apk` và đối chiếu đúng **119192088 bytes**, SHA-256 ở trên.
5. Chỉ bấm **Publish release** sau khi kiểm tra trên thiết bị. **Không xóa Release Code 113**.
6. Sau khi công khai, cập nhật liên kết tải trên Blogger nếu muốn chuyển người dùng sang Code 114.

**Lưu ý:** GitHub *Source code (zip/tar.gz)* là source của repository phát hành, không phải mã nguồn Android Studio hoặc bản APK. Người dùng cần tải asset .apk.
