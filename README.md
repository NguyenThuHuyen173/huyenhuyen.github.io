# huyenhuyen.github.io
Quản lý admin: User: admin       Pass: admin
Link host:     http://mayanh.rf.gd/
Trang web hỗ trợ cho việc đẩy WEB lên hosting đó chính là :https://infinityfree.net/

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
Thứ 3 là bảng "feedback" để người dùng có thể đánh giá được sản phẩm .
![b3](https://user-images.githubusercontent.com/75211708/101357211-b7513080-38cb-11eb-89ca-db496120cc9b.PNG)
Thứ 4 là bảng "oder" khách hàng xem thông tin của sản phẩm sau đó thêm san phẩm vào gi hàng. Khách hàng có thể thêm một lúc nhiều sản phẩm cùng loại và khác loại cùng một lúc, giá tiền của từng loại  sẽ được hiện ra và tổng số tiền của đơn hàng mà bạn phải trả. 
![b4](https://user-images.githubusercontent.com/75211708/101358785-ee284600-38cd-11eb-8578-2ba0b5f84767.PNG)
Thứ 5 là bảng "products" bảng này là bảng các sản phẩm hiển thị: tên, giá, sản phẩm, ảnh, thông tin về sản phẩm giúp cho khách hàng có thể tìm hiểu kỹ hơn để chọn ra sản  phẩm mà mình mong muốn.
![he](https://user-images.githubusercontent.com/75211708/101360491-49f3ce80-38d0-11eb-8bb6-6e2
Bảng thứ 6 "user" đây là bảng người dùng thì thương tự như bảng admin nhưng có thêm một phần là "address" để người dùng cung cấp địa chỉ của mình.
![b6](https://user-images.githubusercontent.com/75211708/101360976-f1710100-38d0-11eb-82d9-f9813f3f5747.PNG)
Dưới đây là một số tài khoản người dùng đã được đăng kí:
![qlnguoidung](https://user-images.githubusercontent.com/75211708/101361238-4a409980-38d1-11eb-940a-81dc2f7cbca4.PNG)
Và cuối cùng là kết nối cơ sở dữ liệu để hiển thị mối liên hệ giữa các bảng với nhau :
![sql](https://user-images.githubusercontent.com/75211708/101361512-a4d9f580-38d1-11eb-96de-605ccaeed2b8.PNG)



