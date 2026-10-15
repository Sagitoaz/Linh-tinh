# Quy Tắc: Quản Lý Thay Đổi

Quy tắc này giúp kiểm soát phạm vi thay đổi, ngăn ngừa lỗi phát sinh và bảo toàn cấu trúc hiện hữu của dự án.

---

## 1. Tôn Trọng Phạm Vi (Scope Isolation)
- Chỉ sửa đổi hoặc bổ sung những tệp, thành phần được người dùng yêu cầu trực tiếp hoặc bắt buộc phải thay đổi để hoàn thành mục tiêu.
- Không can thiệp, dọn dẹp hoặc tái cấu trúc các phần nằm ngoài phạm vi được chỉ định.

## 2. Nguyên Tắc Thay Đổi Tối Thiểu
- Thực hiện các chỉnh sửa cục bộ, đúng trọng tâm thay vì viết lại toàn bộ tệp khi không cần thiết.
- Bảo toàn nguyên vẹn các ghi chú, cấu hình hoặc đoạn nội dung sẵn có của người dùng.

## 3. An Toàn Dữ Liệu Khi Thay Đổi
- Luôn kiểm tra nội dung hiện có của tệp trước khi cập nhật.
- Không tự ý xóa bỏ tệp tin, thư mục hoặc dữ liệu mà không có xác nhận rõ ràng từ người dùng.
