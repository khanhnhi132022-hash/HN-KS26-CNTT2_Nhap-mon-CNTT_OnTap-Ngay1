# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Hoàng Khánh Nhi**
- **Lớp: CNTT02**
- **Link repository:**
- **Hệ điều hành (Windows/macOS): Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
B1 : pwd
B2 : ls -Force
B3 : mv .\lich_hoc.txt .\docs\
     mv .\logo_trung_tam.png .\media\
     mv .\anh_lop_hoc.jpg .\media\
B4 : cp .\media\logo_trung_tam.png .\archive\
B5 : rm .\temp_201.tmp
     rm .\temp_202.tmp
B6 : cd .\logs
     ls
     cd ..
B7 : cd .\docs
     cp ..\media\anh_lop_hoc.jpg ..\archive\
     cd ..
B8 : Get-ChildItem -Recurse -Force

```

### Kết quả B1 (pwd)

```
Path
----
C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

``` 
Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   8:21 PM                archive
d-----        10/20/2026   8:26 PM                data
d-----        10/20/2026   8:19 PM                docs
d-----        10/20/2026   8:26 PM                logs
d-----        10/20/2026   8:20 PM                media
-a----        10/19/2026  10:04 AM             83 .env


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM             67 lich_hoc.txt


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 access.log


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
