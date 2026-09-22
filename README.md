# CarView Split Screen

Ứng dụng mở nhiều app trong các ô riêng trên Android Auto.

## Tải APK

Tải **CarView-Split-Screen-v1.0.1.apk** tại [Releases](https://github.com/carviewauto/CarView-Split-Screen/releases/latest). File `.sha256` đi kèm dùng để kiểm tra tính toàn vẹn của APK.

Kho này chỉ phân phối APK và hướng dẫn sử dụng. Mã nguồn và khóa ký không được công khai trong kho.

## Yêu cầu

- Android 10 trở lên, điện thoại đã root.
- Vector/LSPosed hoạt động và Android Auto tương thích.
- Cấp quyền root cho CarView Split Screen khi được hỏi.

## Cài đặt

1. Tải và cài APK từ Releases.
2. Trong Vector/LSPosed, bật module **CarView Split Screen** và chọn **Android Auto** cùng **Android Framework / System Framework**.
3. Khởi động lại điện thoại.
4. Mở CarView Split Screen trên Android Auto và chọn ứng dụng cho từng ô.

CarView Split Screen hoạt động độc lập, không yêu cầu cài CarView AA. Mỗi ứng dụng được mở trong ô vẫn giữ các yêu cầu tài khoản, giấy phép và quy tắc phát riêng của nó.

## Phiên bản 1.0.1

- Bổ sung xử lý cảm ứng bên trong app khi màn hình điện thoại tắt trên ROM Xiaomi đã thử nghiệm.
- Làm rối mã bản release, tắt debug và bỏ các quyền hệ thống không dùng.
- Kiểm tra đầu vào lệnh root và quyền Activity trước khi mở ứng dụng.

Bản Debug đã được xác nhận hoạt động khi tắt màn hình trên điện thoại Xiaomi Android 15 thử nghiệm. Bản Release đã qua build, kiểm thử lệnh, kiểm tra chữ ký và kiểm tra callback LSPosed; chưa xác nhận trực tiếp trên mọi xe/ROM.

Nếu app video có cơ chế đồng bộ phát riêng giữa điện thoại và Android Auto, nó có thể không phát trong ô Split Screen. Khả năng phát phụ thuộc ứng dụng đó; không bảo đảm mọi app đều tương thích.

## Cập nhật

Bản release 1.0.1 dùng cùng khóa ký với bản release 1.0.0. Bản Debug có chữ ký khác, không thể cài đè trực tiếp bằng APK release. Gỡ ứng dụng sẽ xóa cấu hình của ứng dụng.