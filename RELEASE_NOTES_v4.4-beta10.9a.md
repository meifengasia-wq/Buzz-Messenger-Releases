# 🐝 Buzz! Messenger v4.4-beta10.9a — Code 113 (Android Open Beta candidate)

> **Trạng thái:** APK Release đã được kiểm tra chữ ký và tính toàn vẹn; **chưa đăng file APK lên GitHub Releases**, chưa xác nhận kiểm thử chạy thật.

## Bản Android dự kiến phân phối

- File: `BuzzMessenger_v4.4-beta10.9a_Code113_release.apk`
- Package: `com.buzz.messenger`
- Version name: `4.4-beta10.9a-admin-lifetime`
- Version code: **113**
- Android tối thiểu: Android 8.0 (API 26)
- Android target: API 37
- Kích thước: **119.175.700 byte**
- SHA-256: `37658dd43f5abbc371ce45c13999a83333f5281088ee3832f10ae65d008b3de1`
- Chứng thư ký (SHA-256 fingerprint): `643798b942aa1b70344482ac5583e6e20147f415caff6ff717ca7390bad29771`

Đã xác minh bằng phép kiểm tra chữ ký APK v2, chữ ký trên signed data và digest từng khối của toàn bộ APK. Chứng thư ký **trùng với bản Release Code 112** trước đó, giúp đảm bảo tính liên tục chữ ký khi cập nhật app giữa các bản Release.

## Nội dung Beta

- Buzz ID, Chat 1-1, danh sách bạn bè.
- BUZZ!!!, Cộng Đồng Buzz!, Room chat, Passcode, quyền chủ phòng, playlist YouTube.
- Story, Post, Music, Me.
- Giao diện hệ thống Free/Premium; **Premium thương mại chưa mở bán**.
- Admin có `admin_lifetime` từ server Supabase và nhận Premium vô hạn.

## Kiểm tra bổ sung trước khi đăng rộng

- [ ] Cài file Release Code 113 trên điện thoại thật; kiểm tra đăng nhập, chat, Room, quản lý Admin, thông báo và quy trình đăng xuất.
- [ ] Rà `android:allowBackup=true`; bảo đảm dữ liệu nhạy cảm/tokens được loại trừ khỏi bản sao lưu hoặc tắt backup theo đúng kế hoạch.
- [ ] Rà `android:usesCleartextTraffic=true`; giới hạn các kết nối HTTP không mã hóa, ưu tiên HTTPS.
- [ ] Xác nhận thông tin chủ chứng thư ký được phép xuất hiện công khai.
- [ ] Kiểm tra không chứa khóa API bí mật hoặc private key; **không bao giờ đăng keystore**.
- [ ] Tải asset công khai về và đối chiếu SHA-256 ở trên.

## Đăng bản phát hành đầu tiên

1. Vào **Releases → Draft a new release**.
2. Tạo tag `v4.4-beta10.9a`, chọn **Set as a pre-release**.
3. Tải lên file `BuzzMessenger_v4.4-beta10.9a_Code113_release.apk` sau khi hoàn tất checklist.
4. Dán các ghi chú chính và SHA-256 vào phần mô tả; sau đó mới **Publish release**.
5. Chuyển trang Blogger **Tải về** từ chế độ chuẩn bị sang liên kết asset chính thức; không đưa link chưa tồn tại.

## Báo lỗi

Khi thử nghiệm, người dùng có thể tạo GitHub Issues hoặc liên hệ qua kênh hỗ trợ Buzz được công bố. Tuyệt đối không đăng số điện thoại, email đăng nhập, OTP, token hoặc nội dung Chat riêng tư trong Issues công khai.
