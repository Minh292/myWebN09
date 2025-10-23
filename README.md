# myWebN09 application : Dự án Laravel Food Store
## I. Thành viên
 1. Vũ Minh Nguyệt - MSSV : 23010129
 2.  Trung     - MSSV : 23010591
    
## II. Tính năng
+ Trang chủ hiện đại với phần hero, sản phẩm nổi bật, giới thiệu, liên hệ
+ Thiết kế responsive, ưu tiên di động, hiệu ứng mượt mà
+ CSS nâng cao với các mẫu thiết kế hiện đại
+ Quản lý đơn hàng cho admin: cập nhật trạng thái, giao hàng, hoàn thành
+ Phân quyền quản trị cho các chức năng admin
+ Quản lý sản phẩm, người dùng, bình luận
+ Đã tích hợp Laravel Breeze cho xác thực và quản lý người dùng
  
## III. Quy trình trạng thái đơn hàng
+ Đơn hàng có thể chuyển qua các trạng thái: pending, processing, shipping, completed, cancelled
+ Admin có thể chuyển đơn sang trạng thái giao hàng hoặc hoàn thành từ dashboard
  
## IV. Cấu trúc thư mục
+ app/Models/ - Model Eloquent
+ app/Http/Controllers/ - Controller cho web và admin
+ resources/views/ - Giao diện Blade cho frontend và admin
+ public/css/ - File CSS
+ database/migrations/ - File migration cho database
+ routes/ - Định nghĩa route
