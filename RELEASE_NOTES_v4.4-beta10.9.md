# Buzz! Messenger v4.4-beta10.9 — Android Beta

> **Trạng thái:** Thông tin chuẩn bị phát hành. APK **chưa** được tải lên GitHub Releases tại thời điểm tạo ghi chú này.

## Thông tin bản build đã kiểm tra

- Tên APK gốc: `app-release.apk`
- Android package: `com.buzz.messenger`
- Version name: `4.4-beta10.9-community-premium-room`
- Version code: `112`
- Android tối thiểu: API 26 (Android 8.0)
- Dung lượng: 119175712 byte
- SHA-256: `3d10fc53cff61f7f388b385c13407ccd1a3fe3722a856d87eab56fb5a0e0152c`
- Chứng thư ký Release SHA-256: `643798b942aa1b70344482ac5583e6e20147f415caff6ff717ca7390bad29771`
- APK Signature Scheme v2: Chữ ký mật mã **và** digest nội dung APK đều được xác minh.
- Không bật `android:debuggable`.

## Điểm phải rà trước khi mở phát hành công khai

- `android:allowBackup=true`: cân nhắc vô hiệu hóa backup dữ liệu đăng nhập/cục bộ hoặc cấu hình danh sách loại trừ phù hợp.
- `android:usesCleartextTraffic=true`: kiểm tra nguồn HTTP nào còn cần thiết và giới hạn phạm vi, ưu tiên HTTPS.
- Chứng thư ký chứa tên cá nhân trong trường subject; xác nhận chấp nhận công khai trước khi phát hành lần đầu.
- Cài thử chính file Release trên thiết bị thực tế, kiểm tra đăng nhập, Chat, Room, thông báo và nâng cấp sau này.
- Đây là Code 112, **không** phải Code 112a/versionCode 113.

## Tính năng thử nghiệm

- Buzz ID, Chat 1-1, Buddy List
- Buzz!!!, Room cộng đồng, passcode và quyền quản lý Room
- Playlist YouTube, Story, bài viết và Music
- Giao diện xem trước các quyền Premium (chưa mở bán)

## Hướng dẫn phát hành

1. Chọn `Releases → Draft a new release` trong repository này.
2. Tạo tag `v4.4-beta10.9`, đánh dấu **Set as a pre-release**.
3. Chỉ tải lên APK Release sau khi hoàn tất kiểm tra quyền riêng tư và nghiệm thu.
4. Dán ghi chú phát hành và SHA-256; kiểm tra lại asset tải xuống trước khi cập nhật link trong Blogger.
5. **Không đăng file Debug** và **không đưa keystore hoặc mật khẩu lên GitHub**.

### Người dùng báo lỗi

Gửi báo lỗi qua GitHub Issues, không đăng thông tin cá nhân, mật khẩu, token hoặc nội dung Chat riêng tư.
