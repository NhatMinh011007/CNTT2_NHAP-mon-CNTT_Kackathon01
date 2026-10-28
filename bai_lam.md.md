**BÀI LÀM – HACKATHON 01**  
- **Mã đề:** 21  
- **Họ tên:Nguyễn Đức Nhật Minh**  
- **Lớp:HCM_CNTT2**  
- **Link repository:**  
- **Hệ điều hành (Windows/macOS):Windows**  
**4.2. Thao tác máy tính cơ bản bằng CLI**  
**Các lệnh đã chạy**  
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng  
   
 gci *.log  
New-Item -Path "docs", "media", "data", "logs", "backup" -ItemType Directory -Force  
   
   
   
**Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)**  
(Dán kết quả vào đây – xoá dòng này)  
 gci   
**4.3. Lọc log thủ công**  
**Lệnh đã chạy**  
# Ghi lệnh vào đây (xoá dòng này)  
   
  get-childitem -filter *.log -r   
Select-string “ERROR”  
**2 dòng lỗi đầu tiên trong daily_report.txt**  
(Dán kết quả vào đây – xoá dòng này)  
   
   
**4.4. Thao tác với tài liệu Markdown (README.md)**  
*README.md được chấm trực tiếp trên file * *README.md* * ở gốc dự án. Đánh dấu * *[x]* * vào các mục đã làm để tự kiểm tra.*  
- Heading 1: tên dự án  
- Mô tả ngắn có cả **in đậm** và *in nghiêng*  
- Bảng Thư mục | Nội dung, ít nhất 3 dòng dữ liệu  
- Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án  
- Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành  
- Blockquote nhắc không upload .env  
**4.5. Chạy script auto_report (.ps1 hoặc .sh)**  
**Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)**  
# Ghi lệnh vào đây (xoá dòng này)  
   
   
**Kết quả hiển thị**  
(Dán kết quả vào đây – xoá dòng này)  
   
   
**4.6. Đếm số dòng lỗi**  
**Lệnh**  
# Ghi lệnh vào đây (xoá dòng này)  
   
   
**Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)**  
(Dán kết quả vào đây – xoá dòng này)  
   
   
**4.7. Báo cáo tổng hợp**  
**Các lệnh đã chạy**  
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)  
   
   
**Nội dung file logs/tong_hop.txt**  
(Dán kết quả vào đây – xoá dòng này)  
   
   
**4.8. Excel**  
*Phần Excel được chấm trực tiếp trên file * *data/don_qua_thang_12.xlsx* *, không cần ghi vào đây.*  
