# Bài 6 : Sự cố tài liệu dự án trên GitHub

## Phần 1. Phân tích cốt lõi
-   **2 sai lầm của Nam:**
    - Hiểu sai định dạng: File `.docx` là file nhị phân nén ZIPnhiều XML, GitHub không thể đọc và hiển thị nội dung trực tiếp trên web.
    - iểu sai cơ chế Git: Git theo dõi thay đổi theo từng dòng văn bản đổi 1 dấu phẩy trong Word làm xáo trộn toàn bộ mã nhị phân, khiến Git báo toàn bộ file.     
-   **Markdown an toàn & nhẹ hơn:** 
    - Chống hư hại:File `.docx` mất 1 byte sẽ hỏng toàn bộ cấu trúc nén không mở được. File `.md` (mất 1 byte chỉ mất đúng ký tự đó, phần còn lại vẫn nguyên vẹn.     
    - Dung lượng:Markdown chỉ vài KB vì chỉ chứa ký tự chữ thuần, không gánh XML và định dạng ẩn    
## Phần 2. Nội dung `README.md` 
Markdown
```
# GreenTech: Nông Nghiệp Thông Minh IoT
> **GreenTech** là hệ thống tự động hóa vi khí hậu và giám sát môi trường vườn thông minh theo thời gian thực.

## Mục Tiêu
- [x] Giảm 40% lượng nước tưới bằng cảm biến độ ẩm.
- [x] Tự động cảnh báo và điều hòa khi cây bị sốc nhiệt.

## Thành Viên
* **Nguyễn Vương Anh Minh:** Quản lý tài liệu & Phần cứng IoT.
* **Nhóm phát triển:** Lập trình vi điều khiển & Giao diện Dashbo
```
