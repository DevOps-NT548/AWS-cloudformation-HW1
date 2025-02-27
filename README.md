<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: 5;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<!-- Title -->
<h1 align="center"><b>NT548.P11 - Công nghệ DevOps và ứng dụng</b></h1>

## BẢNG MỤC LỤC

- [ Giới thiệu môn học](#gioithieumonhoc)
- [ Giảng viên hướng dẫn](#giangvien)
- [ Thành viên nhóm](#thanhvien)

## GIỚI THIỆU MÔN HỌC

<a name="gioithieumonhoc"></a>

- **Tên môn học**: Công nghệ DevOps và ứng dụng
- **Mã môn học**: NT548.P11
- **Năm học**: 2024-2025

## GIẢNG VIÊN HƯỚNG DẪN

<a name="giangvien"></a>

- Ths **Lê Thanh Tuấn**

## THÀNH VIÊN NHÓM

<a name="thanhvien"></a>
| STT | MSSV | Họ và Tên | Github | Email |
| ------ |:-------------:| ----------------------:|-----------------------------------------------------:|-------------------------:
| 1 | 22520914 | Nguyễn Hải Nam |[NamSee04](https://github.com/NamSee04) |22520914@gm.uit.edu.vn |
| 2 | 22520673 | Lê Hữu Khoa |[kevdn](https://github.com/kevdn) |22520673@gm.uit.edu.vn |
| 3 | 22520864 | Làu Trường Minh |[LiuChangMinh88](https://github.com/LiuChangMing88) |22520864@gm.uit.edu.vn |

## HƯỚNG DẪN CHẠY

<a name="huongdan"></a>

- Để chạy cloudformation ta cần quyền truy cập vào server AWS bằng cách sử dụng AWS credentials key.

#### Ta thực hiện các bước sau:

#### 1. Cấu hình AWS credentials key:

```
[default]
aws_access_key_id=<your-key>
aws_secret_access_key=<your-key>
```

#### 2. Chạy scripts:

- Ta cd vào thư mục ./scripts.
- Ta chạy những dòng lệnh sau để cho phép thực thi 2 scripts deploy.sh và destroy.sh:

```
chmod +x deploy.sh
chmod +x destroy.sh
```

- Chạy scripts:

```
./deploy.sh
```

- Sau khi chạy xong, ta destroy cho ngăn nắp:

```
./destroy.sh
```
