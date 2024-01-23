# Bài tập lớn môn Lập trình hướng đối tượng
## Giới thiệu
Bài làm của: Nhóm 6
Thành viên bao gồm:
  + Nguyễn Hữu Quân
  + Nguyễn Việt Hùng
  + Trần Bá Tài

Lớp tín chỉ: Lập trình hướng đối tượng-1-2-23(N03).

Đề: 6.Quản lý bán hàng siêu thị.

## Cấu trúc bài làm:

Toàn bộ chương trình được chứa trong trong thư mục "src".

![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/2a2aca40-4972-4ecc-a283-9bf9d070b846)


- File khởi động: ***App.java***
- Cơ sở dữ liệu: ***SanPhamxml.xml***

## Hướng dẫn sử dụng chương trình
### Khởi động
Sau khi chạy file ***App.java***, chương trình sẽ mở giao diện Login.


>Do chưa phát triển tính năng `Đăng ký`, nên để có thể sửa và thêm tài khoản, vui lòng truy cập `UserDAO.java` tại package `model` và thêm nội dung `ls.add(new User("user", "pass", true));` tại hàm UserDao() để chỉnh sửa, với "user" là tên đăng nhập và "pass" là mật khẩu.

### Đăng nhập thành công
Sau khi nhập đúng tài khoản, mật khẩu và nhấn Login, giao diện Login sẽ đóng lại và chương trình tự động mở giao diện quản lý và từ đây có thể truy cập giao diện bán hàng.

>Khi mở giao diện quản lý bán hàng, tại đây sau khi nhập thông tin về mặt hàng cần thêm vào và bấm "Lưu" thì hệ thống sẽ ghi nhận dữ liệu, ghi vào file SanPhamxml.xml và in ra tại bảng thống kê bên dưới về thông tin sản phẩm vừa nhập.

>Nút `Lưu` dùng để lưu dữ liệu vào database:
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/938ac02e-dbbe-48bf-aca2-11422491160a)

>Nút `Thêm` dùng để xoá toàn bộ thông tin đã nhập tại các TextField:
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/db1cda5c-5771-42f0-9b67-655e2058e783)

>Nút `Xoá` dùng để xoá dữ liệu đã nhập, chọn tại bảng thống kê ở dưới.
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/c637e2d6-0ccc-43bb-ba7e-709e872b069f)

>Sau khi chọn một mã sản phẩm ở dưới, điền lại thông tin vào bảng và bấm `Sửa` để thay đổi thông tin:
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/3f6f8ad3-7bc2-4722-9bee-009952a876a8)

>Nút `Thanh toán` để tính và trả ra tổng số tiền.
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/58aec56a-b81e-4138-b7d8-f84222daa678)

>Thanh công cụ tìm kiếm ở phía trên cùng:
>![image](https://github.com/ngnhonk/BT_luyencode/assets/121851963/85834be3-91ad-4647-9693-e87f79f0df40)

*Do đây là phiên bản `Beta` nên chưa được chỉn chu và còn nhiều thiếu sót, mong được sự thông cảm của cô và các bạn.
*Team6 sẽ cố hết sức để sau này có thể đưa ra phiên bản chính thức hoàn thiện hơn <3
