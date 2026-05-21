# README.md

## Phân tích và lập báo cáo đánh giá rủi ro (Risk Assessment)

Đây là tài liệu tiểu luận môn học **Phân tích lỗ hổng và kiểm thử**, thực hiện bởi nhóm sinh viên lớp 14DHBM02, Trường Đại học Công Thương TP. Hồ Chí Minh.

### Giới thiệu
Trong bối cảnh chuyển đổi số, các hệ thống ứng dụng web đóng vai trò then chốt nhưng cũng đối mặt với nhiều rủi ro an ninh phức tạp như SQL Injection, XSS, lỗi cấu hình, v.v. Đồ án này tập trung xây dựng quy trình đánh giá rủi ro toàn diện thay vì chỉ tập trung vào việc phát hiện lỗi kỹ thuật.

### Mục tiêu nghiên cứu
* Xây dựng quy trình đánh giá rủi ro an ninh thông tin theo hướng hệ thống (xác định tài sản, nhận diện mối đe dọa/lỗ hổng, phân tích rủi ro).
* Phân tích và đánh giá mức độ rủi ro dựa trên khả năng xảy ra (Likelihood) và mức độ tác động (Impact).
* Đề xuất các giải pháp kỹ thuật và quản lý (giảm thiểu, tránh, chuyển giao, chấp nhận rủi ro).

### Nội dung chính
1.  **Cơ sở lý thuyết:** Nghiên cứu các tiêu chuẩn (NIST SP 800-30, ISO/IEC 27005, OWASP Top 10).
2.  **Quy trình đánh giá:**
    * Xác định tài sản: Dữ liệu khách hàng, tài khoản người dùng, Web Server.
    * Nhận diện mối đe dọa & Lỗ hổng: SQLi, XSS, Broken Authentication, v.v.
    * Xây dựng ma trận rủi ro để phân loại và đánh giá.
3.  **Triển khai thực nghiệm:**
    * Sử dụng môi trường mô phỏng **DVWA (Damn Vulnerable Web Application)** trên máy ảo (Ubuntu, Apache, PHP, MySQL).
    * Kiểm chứng thực tế các lỗ hổng (SQL Injection, XSS) để minh chứng cho quá trình phân tích rủi ro.
      
*Ngày thực hiện: 22/04/2026*
