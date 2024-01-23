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

>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/2cb4cbe1-e32c-4408-bc3e-ca72a29ff596)


- File khởi động: ***App.java***
- Cơ sở dữ liệu: ***SanPhamxml.xml***

## Hướng dẫn sử dụng chương trình
### Khởi động
Sau khi chạy file ***App.java***, chương trình sẽ mở giao diện Login:

>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/6c401d51-14a7-4f86-b9ef-4551fc1ab312)

>Do chưa phát triển tính năng `Đăng ký`, nên để có thể sửa và thêm tài khoản, vui lòng truy cập `UserDAO.java` tại package `model` và thêm nội dung `ls.add(new User("user", "pass", true));` tại hàm UserDao() để chỉnh sửa, với "user" là tên đăng nhập và "pass" là mật khẩu.


### Đăng nhập thành công
Sau khi nhập đúng tài khoản, mật khẩu và nhấn Login, giao diện Login sẽ đóng lại và chương trình tự động mở giao diện quản lý và từ đây có thể truy cập giao diện bán hàng:

>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/12fe7ced-c4e8-4745-a5a2-b84132727928)

>Khi mở giao diện quản lý bán hàng, tại đây sau khi nhập thông tin về mặt hàng cần thêm vào và bấm "Lưu" thì hệ thống sẽ ghi nhận dữ liệu, ghi vào file SanPhamxml.xml và in ra tại bảng thống kê bên dưới về thông tin sản phẩm vừa nhập:

>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/f039ca4a-f554-4996-ae67-3692ca1ca4a0)


>Nút `Lưu` dùng để lưu dữ liệu vào database:
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/00e04234-1a88-47f4-ab84-34a94e327068)


>Nút `Thêm` dùng để xoá toàn bộ thông tin đã nhập tại các TextField:
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/48c10cd2-11ca-4249-8208-80888b540fe8)


>Nút `Xoá` dùng để xoá dữ liệu đã nhập, chọn tại bảng thống kê ở dưới.
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/16803aa0-d282-446f-b46a-c69d03947244)


>Sau khi chọn một mã sản phẩm ở dưới, điền lại thông tin vào bảng và bấm `Sửa` để thay đổi thông tin:
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/dd23f88f-c4f0-4193-bff8-97cdf3237791)


>Nút `Thanh toán` để tính và trả ra tổng số tiền.
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/3d5a761e-0aa0-461e-8e93-baa9b8386162)


>Thanh công cụ tìm kiếm ở phía trên cùng:
>![image](https://github.com/ngnhonk/Java-Basic/assets/121851963/819fad4a-5d80-4b32-9911-33692d7f428c)



*Do đây là phiên bản `Beta` nên chưa được chỉn chu và còn nhiều thiếu sót, mong được sự thông cảm của cô và các bạn.
*Team6 sẽ cố hết sức để sau này có thể đưa ra phiên bản chính thức hoàn thiện hơn <3
