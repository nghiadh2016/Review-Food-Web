<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Hướng dẫn cài đặt:
- Tải và cài đặt xampp cho máy tính tại địa chỉ https://www.apachefriends.org/index.html
- Xóa sạch file htdocs và tạo lại 1 file htdocs mới, clone source code về file htdocs này.
- Set biến môi trường cho máy tính environment variables cho Php là tên_ổ_đĩa_cài_xampp:\xampp\php\
- Sau đó đứng trong folder htdocs này nhấn shift kích chuột phải chọn Open powershell window here
- Chạy lệnh php composer.phar install
- Chạy lệnh cp .env.example .env
- Chạy lệnh php artisan key:generate
- Cấu hình database trong file .env bao gồm 3 thuộc tính DB_DATABASE=homestead, DB_USERNAME=homestead, DB_PASSWORD=secret cần sửa lại cho đúng database đang dùng.
- Khởi động xampp
- Chạy localhost/phpmyadmin tạo database và thêm các bảng có sẵn từ file database trong project.
- Xem kết quả
## About Laravel
## Danh sách nhóm
#### Nguyễn Đức Tuấn
#### Nguyễn Đức Hoàng
#### Bùi Trọng Nghĩa
#### Lê Tiến THành
#### Lý Văn Trà
#### Phan Đinh Thiên Phúc