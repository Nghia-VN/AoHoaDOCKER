
# WEB_DEMO


## Công nghệ sử dụng

- Laravel 8
- Vue 2 + VueRouter + vue-progressbar + sweetalert2 + laravel-vue-pagination
- Laravel Passport
- Admin LTE 3 + Bootstrap 4 + Font Awesome 5
- PHPUnit Test Case/Test Coverage

## Tính năng

- Chức năng cơ bản Thêm, sửa, xóa, liệt kê danh sách, ...
- Đăng nhập, đăng ký, thay đổi mật khẩu
- Hồ sơ, Cập nhật hồ sơ, Thay đổi mật khẩu, Ảnh đại diện
- Quảnlý sản phẩm
- Quản lý người dùng
- Cài đặt: Danh mục, Thẻ
- Frontend và Backend User ACL với Gate Policy (loại: admin/user)
- Bảng điều khiển tĩnh đơn giản
- Xây dựng với Docker

## Cài đặt Docker Engine trên CentOS
- https://docs.docker.com/engine/install/centos/

## Cài đặt Docker Engine trên Debian
- https://docs.docker.com/engine/install/debian/

## Cài đặt Docker Engine trên ubuntu Ubuntu
- https://docs.docker.com/engine/install/ubuntu/

## Cài đặt Docker Desktop trên Windows
-https://docs.docker.com/desktop/install/windows-install/

## Hướng dẫn sử dụng Docker
Khởi động terminal và gõ lần lượt các commands sau:
docker compose up -d
- docker exec -it vue-starter /bin/bash
- composer install
- cp .env.example .env
- php artisan key:generate
- php artisan migrate
- php artisan db:seed
- php artisan passport:install
- Chạy app tại http://localhost:8008/
- Database http://localhost:8080/
- DBhost: yourIP:3307, user: root, Password: 123456
