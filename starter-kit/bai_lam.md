# BÀI LÀM – HACKATHON 01

- **Mã đề:** 22
- **Họ tên:** Võ Thị Thanh Thùy
- **Lớp:** HCMKS26CNTT2
- **Link repository:** https://github.com/TT-IT108/HCM-KS26-CNTT2_Nhap-mon-CNTT_Hackathon01
- **Hệ điều hành (Windows/macOS):** Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell 
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

```
D:\starter-kit\rua-xe-website
ls -r 
Move-Item -Path "bang_quy_trinh.txt"  -Destination .\docs
Move-Item -Path "logo-rua-xe.PNG"  -Destination .\media
Copy-Item -Path ".\media\logo-rua-xe.PNG" -Destination .\backup
rm temp_305.tmp


### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
(
    Directory: D:\starter-kit\rua-xe-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   1:52 PM                backup
d-----        10/28/2026   1:52 PM                data
d-----        10/28/2026   2:09 PM                docs
d-----        10/28/2026   1:55 PM                logs
d-----        10/28/2026   2:10 PM                media
d-----        10/28/2026   2:05 PM                Rua Xe Website FINAL
-a----        10/27/2026   1:32 AM             64 .env
-a----        10/27/2026   1:32 AM           2227 bai_lam.md


    Directory: D:\starter-kit\rua-xe-website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6191 logo-rua-xe.PNG


    Directory: D:\starter-kit\rua-xe-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM             53 bang_quy_trinh.txt


    Directory: D:\starter-kit\rua-xe-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1029 car-wash.log


    Directory: D:\starter-kit\rua-xe-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6191 logo-rua-xe.PNG


    Directory: D:\starter-kit\rua-xe-website\Rua Xe Website FINAL


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM             64 .env
-a----        10/27/2026   1:32 AM             53 bang_quy_trinh.txt
-a----        10/27/2026   1:32 AM           1029 car_wash.log
-a----        10/27/2026   1:32 AM           6191 logo-rua-xe.PNG
-a----        10/27/2026   1:32 AM           6114 luot_rua_xe_thang_2.xlsx
)

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy
```shell
# Get-Content logs/car-wash.log  | Select-String "ERROR"

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-02-28 08:39:37 [ERROR] Het thoi gian cho (timeout)
2026-02-28 09:03:37 [ERROR] Dat lich that bai

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)
(Get-Content logs/car-wash.log  | Select-String "ERROR").Count
```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
6


```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/luot_rua_xe_thang_2.xlsx`, không cần ghi vào đây.
