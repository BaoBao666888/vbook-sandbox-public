# vBook Sandbox

App Android chạy bản sao ứng dụng trong sandbox không root, giữ nguyên APK và chữ ký gốc. Package host: `bao.vbooksandbox`. Ưu tiên Android 12/API 31.
Engine ARMv7 tùy chọn được nhúng trong APK ARM64, có vùng ứng dụng và dữ liệu riêng.
Engine32 cần Android có môi trường chạy 32 bit.

- Nhập APK/APKS/split hoặc sao chép bộ APK đã cài.
- Điều khiển dừng/thoát, Google setup và module libxposed API 101/102 hoặc Legacy.
- Có tài liệu module trong app, phạm vi áp dụng do người dùng chọn.

Thư mục này chỉ chứa tài liệu phát hành công khai. Kiểm tra bản mới trong Cài đặt → Cập nhật sandbox.

Xem ghi chú từng bản trong [notes](notes/), quyền riêng tư trong [PRIVACY.md](PRIVACY.md) và giấy phép thư viện trong [licenses](licenses/). Cài bản cập nhật cùng package và chữ ký để giữ dữ liệu.
Engine 32 bit có dữ liệu riêng, không tự chuyển dữ liệu giữa hai vùng.
