# Chính sách bảo mật

**Ứng dụng:** Thẻ Kỹ Năng - Học Mỗi Ngày
**Tên gói (package):** app.skillcards.vn
**Ngày hiệu lực:** 2026-09-09

Chính sách bảo mật này mô tả cách Thẻ Kỹ Năng ("chúng tôi") thu thập, sử dụng, lưu trữ và bảo vệ thông tin của bạn khi bạn sử dụng ứng dụng. Chúng tôi cam kết tôn trọng quyền riêng tư của bạn và chỉ xử lý dữ liệu cần thiết để vận hành ứng dụng.

## 1. Dữ liệu chúng tôi thu thập

### 1.1. Dữ liệu tài khoản
- **Email và tên hiển thị:** khi bạn đăng ký bằng email hoặc đăng nhập bằng Google, chúng tôi nhận email (và tên hiển thị nếu bạn nhập) thông qua dịch vụ xác thực.
- **Tài khoản ẩn danh:** nếu bạn chưa đăng nhập, ứng dụng tạo một tài khoản ẩn danh tạm thời để đồng bộ dữ liệu; tài khoản này không gắn với email của bạn.

### 1.2. Dữ liệu học tập
- **Nội dung học:** các thẻ bạn học, lượt vuốt "đã học"/"bỏ qua", tiến độ hàng ngày, chuỗi ngày (streak), huy hiệu đã mở, lịch sử học và kết quả ôn tập (SRS).
- **Cài đặt cá nhân:** các chủ đề bạn chọn, cài đặt giao diện, ngôn ngữ và tùy chọn thông báo.
- **Bảng xếp hạng:** tên hiển thị và số thẻ đã học được hiển thị trên bảng xếp hạng chung; bạn có thể xóa bằng cách xóa tài khoản (xem mục 6).

### 1.3. Dữ liệu phân tích (Analytics)
- Khi bạn **bật** tùy chọn "Gửi dữ liệu phân tích", ứng dụng ghi nhận các sự kiện ẩn danh như lượt vuốt, chuỗi ngày, màn hình đã mở để cải thiện ứng dụng. **Nội dung thẻ không bao giờ được gửi.**
- Bạn có thể **tắt** hoàn toàn tùy chọn này trong màn "Cá nhân → Tuỳ chọn" bất cứ lúc nào; khi tắt, ứng dụng ngừng thu thập.

### 1.4. Dữ liệu thiết bị / thông báo
- **Token thông báo (FCM):** được tạo để gửi thông báo nhắc học; không dùng cho mục đích khác.
- **Không thu thập vị trí:** ứng dụng **không** thu thập, theo dõi hoặc chia sẻ vị trí địa lý của bạn dưới bất kỳ hình thức nào.

## 2. Mục đích sử dụng dữ liệu

Chúng tôi sử dụng dữ liệu của bạn để:
- Cung cấp, đồng bộ và duy trì tính năng học tập (thẻ, tiến độ, chuỗi ngày, huy hiệu, bảng xếp hạng);
- Đồng bộ dữ liệu giữa các thiết bị khi bạn đăng nhập tài khoản;
- Gửi thông báo nhắc học (khi bạn bật);
- Cải thiện trải nghiệm và chất lượng ứng dụng (chỉ khi bạn bật Analytics);
- Hỗ trợ kỹ thuật và xử lý sự cố.

## 3. Chia sẻ dữ liệu với bên thứ ba

Ứng dụng sử dụng các dịch vụ của **Google / Firebase** để vận hành:

| Dịch vụ | Mục đích |
|---|---|
| Firebase Authentication (Google) | Đăng ký/đăng nhập bằng email hoặc Google |
| Firebase Cloud Firestore (Google) | Lưu trữ và đồng bộ dữ liệu học tập của bạn |
| Firebase Cloud Messaging (Google) | Gửi thông báo đẩy |
| Google Analytics for Firebase (Google) | Thống kê sử dụng (chỉ khi bạn bật Analytics) |

- **Quảng cáo:** ứng dụng **KHÔNG** sử dụng AdMob, không tích hợp bất kỳ mạng quảng cáo nào, và **không** bán hoặc cho thuê dữ liệu của bạn.
- Dữ liệu chỉ được chia sẻ với các bên trên theo đúng mục đích nêu trong bảng, và được xử lý theo Chính sách bảo mật của Google.

## 4. Lưu trữ và bảo mật

- Dữ liệu được lưu trữ trên cơ sở hạ tầng điện toán đám mây của Google (Firebase), có bảo mật SSL/TLS khi truyền tải.
- Truy cập dữ liệu chỉ giới hạn cho các chức năng của chính bạn và cho việc vận hành kỹ thuật khi cần thiết.
- Dữ liệu cục bộ trên thiết bị được lưu trong bộ nhớ trong; chúng tôi không thể truy cập dữ liệu cục bộ của thiết bị bạn ngoài phạm vi ứng dụng.

## 5. Quyền trên thiết bị

Ứng dụng sử dụng các quyền tối thiểu cần thiết:
- **INTERNET / trạng thái mạng:** để đồng bộ dữ liệu, đăng nhập và nhận thẻ mới;
- **Thông báo (POST_NOTIFICATIONS):** để gửi nhắc học hằng ngày khi bạn bật;
- Các quyền do hệ thống tự cấp (nhận thông báo, khởi động lại sau khi thiết bị khởi động) phục vụ đúng mục đích thông báo.

## 6. Quyền của bạn

Bạn có toàn quyền kiểm soát dữ liệu của mình:
- **Xuất dữ liệu:** trong màn "Cá nhân → Chia sẻ & xuất báo cáo", bạn có thể xuất toàn bộ lịch sử học ra file CSV;
- **Tắt Analytics:** tùy chọn "Gửi dữ liệu phân tích" trong "Cá nhân → Tuỳ chọn";
- **Xóa lịch sử học cục bộ:** trong màn "Lịch sử học";
- **Xóa tài khoản vĩnh viễn:** trong màn "Cá nhân → Vùng nguy hiểm → Xoá tài khoản vĩnh viễn". Thao tác này xóa toàn bộ chuỗi ngày, lịch sử học, huy hiệu và thứ hạng của bạn khỏi máy chủ;
- **Yêu cầu xóa dữ liệu / khiếu nại:** liên hệ với chúng tôi qua email bên dưới.

## 7. Liên hệ

Nếu bạn có thắc mắc hoặc yêu cầu liên quan đến quyền riêng tư, vui lòng liên hệ:

- **Email:** nhut00090@gmail.com

## 8. Thay đổi chính sách

Chúng tôi có thể cập nhật chính sách này theo thời gian. Khi có thay đổi quan trọng, chúng tôi sẽ cập nhật ngày hiệu lực mới ở đầu tài liệu và đăng nội dung cập nhật tại cùng địa chỉ này. Phiên bản có hiệu lực là phiên bản mới nhất được đăng tải.

---
