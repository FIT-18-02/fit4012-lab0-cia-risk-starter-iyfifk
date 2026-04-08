# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** .........Nguyễn Gia Huân...............................

**MSSV:** .............1871020264................................

**Lớp/Nhóm:** .............CNTT 18-02............................

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Cơ sở dữ liệu khách hàng (Customer Database): Chứa thông tin cá nhân, lịch sử giao dịch và thông tin nhạy cảm.
- Asset 2:Mã nguồn ứng dụng (Application Source Code): Tài sản trí tuệ cốt lõi của công ty.
- Asset 3 (nếu có):Hệ thống máy chủ dịch vụ (Production Servers): Đảm bảo dịch vụ luôn sẵn sàng phục vụ người dùng.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality (Tính bảo mật): Dữ liệu bị truy cập bởi người không có thẩm quyền.
- Sự cố B ->Integrity (Tính toàn vẹn): Dữ liệu không còn chính xác hoặc đã bị sửa đổi trái phép.
- Sự cố C ->Availability (Tính sẵn sàng): Người dùng hợp pháp không thể truy cập vào dịch vụ.

---

## 3. Phân tích sự cố B
- Threat:Hacker phát tán phần mềm độc hại (Malware) hoặc mã độc mã hóa dữ liệu qua email phishing.
- Vulnerability:Nhân viên thiếu kỹ năng nhận biết email lừa đảo hoặc hệ điều hành chưa được cập nhật bản vá bảo mật mới nhất.
- Mitigation:Triển khai chương trình đào tạo nhận thức bảo mật cho nhân viên, cài đặt phần mềm diệt virus (Endpoint Protection) và thực hiện sao lưu dữ liệu (Backup) định kỳ.

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài thực hành này, em đã hiểu rõ hơn về tầm quan trọng của mô hình CIA trong việc định hình các chiến lược bảo mật. Việc xác định đúng Asset giúp chúng ta ưu tiên nguồn lực bảo vệ những thứ quan trọng nhất. Phân tích Threat và Vulnerability cho thấy bảo mật không chỉ là vấn đề kỹ thuật mà còn nằm ở yếu tố con người. Em nhận ra rằng một hệ thống an toàn cần sự kết hợp đồng bộ giữa công nghệ, quy trình và ý thức người dùng. Cuối cùng, việc chuẩn bị các phương án Mitigation là chìa khóa để giảm thiểu thiệt hại khi có sự cố thực sự xảy ra.


---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-Confidentiality-B-Integrity-C-Availability}

