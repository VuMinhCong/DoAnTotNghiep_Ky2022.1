<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Hướng dẫn cài đặt và chạy project

Để chạy một project cần thực hiện các bước sau:

Bước 1: Tải project Laravel đã có sẵn về máy tính và cài đặt các môi trường như trong phần Công nghệ sử dụng đã hướng dẫn.

Bước 2: Mở Command Prompt hoặc Terminal và di chuyển đến thư mục của dự án Laravel bằng lệnh "cd path/to/project".

Bước 3: Cài đặt các gói phụ thuộc của dự án bằng lệnh "composer install".

Bước 4: Tạo file .env bằng cách sao chép nội dung từ file .env.example và chỉnh sửa các thông tin cấu hình cho cơ sở dữ liệu và ứng dụng của bạn.

Bước 5: Chạy lệnh php "artisan key:generate" để tạo ra một khóa ứng dụng mới.

Bước 6: Chạy các lệnh tạo bảng và seed dữ liệu mẫu bằng cách chạy lệnh "php artisan migrate --seed".

Bước 7: Khởi động máy chủ phát triển Laravel bằng lệnh "php artisan serve".

Sau khi máy chủ phát triển được khởi động, có thể truy cập vào ứng dụng bằng địa chỉ http://localhost:8000 trên trình duyệt.