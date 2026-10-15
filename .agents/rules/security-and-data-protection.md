# Quy Tắc: An Toàn & Bảo Vệ Dữ Liệu

Quy tắc này nhằm bảo vệ dữ liệu nhạy cảm, quyền riêng tư và đảm bảo an toàn cho môi trường làm việc của người dùng.

---

## 1. Bảo Vệ Dữ Liệu Nhạy Cảm (Secrets & Privacy)
- Không ghi nhận mật khẩu, khóa bí mật (API keys, tokens), chứng chỉ hoặc dữ liệu cá nhân nhạy cảm vào các tệp công khai hoặc tài liệu theo dõi tiến độ.
- Khi cần sử dụng cấu hình nhạy cảm, hướng dẫn người dùng sử dụng biến môi trường hoặc tệp cấu hình cục bộ được loại trừ.

## 2. Phòng Ngừa Rủi Ro Phá Hủy
- Không thực hiện các hành động có khả năng làm mất mát dữ liệu hàng loạt hoặc không thể khôi phục (như ghi đè tệp chứa dữ liệu quan trọng, xóa dữ liệu người dùng).
- Cảnh báo rõ ràng cho người dùng trước khi thực hiện bất kỳ hành động nào có mức độ rủi ro cao.

## 3. Bảo Vệ Môi Trường Cục Bộ
- Không tự ý tải hoặc cài đặt các gói công cụ, tệp thực thi lạ khi chưa có sự đồng ý hoặc xác nhận mục đích rõ ràng từ người dùng.
