# myWebN09 application : 

## I. Thành viên 

1.VŨ MINH NGUYỆT - 23010129

## II. MỤC ĐÍCH DỰ ÁN 

Dự án của bạn là một web quản lý phòng khám / bệnh viện nhỏ, có các chức năng:

👨‍⚕️ Quản lý bệnh nhân (medical_records)

📅 Quản lý cuộc hẹn (appointments)

🧾 Theo dõi lịch sử truy cập (access_logs)

🔐 Có hệ thống đăng ký / đăng nhập / phân quyền (permissions) với bcrypt + session

👤 Trang hồ sơ cá nhân (profile)

📊 Trang dashboard tổng hợp dữ liệu sau khi đăng nhập

Hệ thống này xây dựng theo chuẩn Laravel MVC — nghĩa là Model (dữ liệu), View (giao diện), Controller (xử lý logic) được tách riêng.

## III. CÁCH SỬ DỤNG DỰ ÁN

 1. Chạy server

```
   + php artisan serve
```

→ Mở trình duyệt: http://localhost:8000

 2. Tạo tài khoản / Đăng nhập

   + Truy cập /register để đăng ký

   + Hoặc /login để đăng nhập

   + (đã tạo sẵn user “minh@example.com
 / 12345678” bằng Tinker )

 3. Vào trang chính sau khi đăng nhập

   + Mở /dashboard

   + Từ đây có thể truy cập các chức năng:

       + /appointments

       + /medical_records

       + /access_logs

       + /profile
