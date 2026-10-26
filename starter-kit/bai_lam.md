# BÀI LÀM – THI THỬ HACKATHON 02 (GAMEZONE)

- **Họ tên:Trần Minh Hiển** 
- **Lớp:** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** 

## 4.2. Thao tác CLI

### Các lệnh đã chạy

```shell
# Ghi lệnh vào đây
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> pwd
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> ls -Recurse -Force
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> mv '.\Cap Nhat.txt' .\docs\
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> mv '.\Logo GameZone.PNG' .\media\
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> cd .\logs\
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website\logs> ls
```
### Kết quả liệt kê toàn bộ dự án

```text
 Directory: D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/26/2026   1:23 PM            986 Game.log

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Ghi lệnh vào đây
 
PS D:\rikkei-app\Thực Hành MarkDown.Minh Hiển\de-on-tap-game\starter-kit\gamezone-website> Get-Content .\logs\Game.log |Select-String "ERROR" > .\logs\daily_report.txt```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```
2025-11-05 08:03:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:09:15 [ERROR] Mat ket noi may chu game

```

## 4.4. README.md

> Chấm trực tiếp trên `README.md` ở gốc dự án.

- [x] Heading 1
- [x] Mô tả in đậm + in nghiêng
- [x] Bảng `Thư mục | Nội dung` (≥3 dòng)
- [x] Code block lệnh liệt kê
- [x] Task list (≥2 việc, ≥1 đã xong)
- [x] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report

### Lệnh chạy

```shell
# Ghi lệnh vào đây
.\auto_report.ps1

```

### Nội dung file logs/auto_report.txt

```text
=== BAO CAO LOI GAMEZONE ===

2025-11-05 08:03:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:09:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:12:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:39:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:42:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:51:15 [ERROR] Loi luu tien trinh choi

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây
 (Get-Content .\logs\Game.log | Select-String "ERROR").Count
```

### Kết quả đếm

```text
6

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lệnh vào đây

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây)

```

## 4.8. Excel

> Chấm trực tiếp trên file `data/giao_dich_thang_11.xlsx`.
