# huyenhuyen.github.io
Quản lý admin: User: admin       Pass: admin
Link host:     http://mayanh.rf.gd/

Mô tả:
 Khách hàng:
 Đăng ký: Muốn mua hàng người dùng cần đăng ký tài khoản gồm: họ tên, tên tài khoản, email, điện thoạt, địa chỉ, mật khẩu.
 Sau đó đăng nhập để vào mua sản phẩm từ trang WEB.
 Khách hàng chọn sản phẩm cần mua sau đó thêm vào giỏ hàng, có thể mua nhiêu sản phẩm cùng lúc sau đó thanh toán.
 Người quản trị:
 Quản lý các chức năng của trang WEB gồm : Thêm sản phẩm, quản lý sản phẩm, quản lý người dùng, quản lý phản hồi, đăng xuất.
![index](https://user-images.githubusercontent.com/75211708/101355879-d058e200-38c9-11eb-9ec8-ddc209b49fc9.PNG)
Phân tích cơ sở dữ liệu: Tên cơ sở dữ liệu là "nice_camera" được tạo trên Xampp trong : http://localhost:8080/phpmyadmin/
Trong "nice_camera thì gồm có 6. Đầu tiên là bảng "admin_accounts: trong bảng gồm có "id", "name", "username", "mail", "phone", "password".
![b1](https://user-images.githubusercontent.com/75211708/101356880-4ad63180-38cb-11eb-8b3e-25124f575467.PNG)
Thứ hai là bảng "band" đây là bảng để hiển thị các tên hàng.
![b2](https://user-images.githubusercontent.com/75211708/101357127-9ab4f880-38cb-11eb-97d9-115691040081.PNG)
Thứ 3 là bảng "feedbac" để người dùng có thể đánh giá được sản phẩm .
![b3](https://user-images.githubusercontent.com/75211708/101357211-b7513080-38cb-11eb-89ca-db496120cc9b.PNG)
Thứ 4 là bảng "oder" khách hàng xem thông tin của sản phẩm sau đó thêm san phẩm vào gi hàng. Khách hàng có thể thêm một lúc nhiều sản phẩm cùng loại và khác loại cùng một lúc, giá tiền của từng loại  sẽ được hiện ra và tổng số tiền của đơn hàng mà bạn phải trả. 

