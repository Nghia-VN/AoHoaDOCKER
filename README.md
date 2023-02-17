
# WEB_DEMO


## Công nghệ 

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

##Install Docker Engine on CentOS
- https://docs.docker.com/engine/install/centos/

##Install Docker Engine on Debian
- https://docs.docker.com/engine/install/debian/

##Install Docker Engine on Ubuntu
- https://docs.docker.com/engine/install/ubuntu/

##Install Docker Desktop on Windows
-https://docs.docker.com/desktop/install/windows-install/

## Hướng dẫn sử dụng Docker
- docker compose up -d
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
