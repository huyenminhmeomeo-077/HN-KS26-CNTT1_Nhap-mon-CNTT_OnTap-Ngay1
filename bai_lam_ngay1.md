# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Đặng Minh Huyền 
- **Lớp:** HN-KS26-CNTT1
- **Link repository:** https://github.com/huyenminhmeomeo-077/HN-KS26-CNTT1_Nhap-mon-CNTT_OnTap-Ngay1
- **Hệ điều hành (Windows/macOS):** macOS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# B1
pwd
# B2
ls -a
# B3
mv lich_hoc.txt docs/
mv logo_trung_tam.PNG media/
mv anh_lop_hoc.JPG media/
# B4
cp media/logo_trung_tam.PNG archive/
# B5
rm temp_201.tmp
rm temp_202.tmp
# B6
cd logs
ls
cd ..
# B7
cd docs
cp ../media/anh_lop_hoc.JPG ../archive/
cd ..
```

### Kết quả B1 (pwd)

```text
/Users/dangminhhuyen/Downloads/starter-kit/trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

Lệnh đã chạy: `ls -aR`

```text
.			bai_lam_ngay1.md	logs
..			data			media
archive			docs

./archive:
.			anh_lop_hoc.JPG
..			logo_trung_tam.PNG

./data:
.			..			hoc_vien_khoa_3.xlsx

./docs:
.		..		lich_hoc.txt

./logs:
.		..		access.log

./media:
.			anh_lop_hoc.JPG
..			logo_trung_tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
