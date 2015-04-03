> Chú ý: Hướng dẫn nâng cấp này chỉ áp dụng đối với các site đang sử dụng bản [NukeViet 4.0.10](https://github.com/nukeviet/nukeviet/releases/tag/4.0.10) và chỉ nâng cấp hệ thống cùng với các module hệ thống.

# Bước 1

Backup toàn bộ site và CSDL.

Đăng nhập admin, vào cấu hình => cấu hình chung, tại chỗ kích hoạt chức năng tối ưu site chọn "không kích hoạt".

# Bước 2
Kiểm tra thư mục install trên website có tồn tại không, nếu không tồn tại, upload lại thư mục này từ bản cài đặt NukeViet 4.0.12.

# Bước 3
Download file thư mục install về giải nén và upload các thư mục giải nén được lên website.

# Bước 4
Đăng nhập admin, nhận được thông báo nâng cấp, nhấp vào link nâng cấp và thực hiện tiếp tục các công việc tại trang nâng cấp.

# Bước 5

Sửa dòng $fixthemes = 'default10'; ứng với theme của bạn để chương trình fix tự động các thay đổi giao diện

Upload file toolfix_change.php

Chạy file http://domain.my/toolfix_change.php

# Bước 6
Kiểm tra và chỉnh sửa giao diện:
Copy lại hai file sau trong giao diện mặc định chuyển sang giao diện của bạn

themes/default/modules/users/info.tpl
themes/default/modules/users/register.tpl

Sửa lại giao diện cho tương thích
