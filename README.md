# Tool Kiểm Tra v3.5

Công cụ hỗ trợ kiểm tra trạng thái kích hoạt Windows/Office, phát hiện dấu vết KMS/activator và thực hiện dọn dẹp có chọn lọc.

## Chức năng chính

- Kiểm tra trạng thái bản quyền Windows và Office.
- Phát hiện dấu vết KMS, crack và activator.
- Backup trước khi thực hiện thay đổi.
- Dọn dẹp service, scheduled task, file và Registry theo lựa chọn.
- Xuất báo cáo có tùy chọn che thông tin nhạy cảm.

## Cảnh báo

Công cụ cần quyền Administrator và có thể thay đổi cấu hình hệ thống. Hãy tạo điểm khôi phục và backup trước khi sử dụng chức năng dọn dẹp.

Đây không phải sản phẩm của Microsoft. Công cụ không cung cấp product key và không có chức năng kích hoạt trái phép.

## Tải xuống

Chỉ tải phiên bản chính thức tại mục **Releases** của kho lưu trữ này. Không tải từ link rút gọn hoặc nguồn đăng lại không rõ xuất xứ.

## Xác minh tệp

Mở PowerShell tại thư mục chứa file và chạy:

```powershell
Get-FileHash .\Tool-Kiem-Tra-v3.5.exe -Algorithm SHA256
Get-AuthenticodeSignature .\Tool-Kiem-Tra-v3.5.exe
