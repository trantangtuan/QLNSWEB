<h2>Website Quản lí nhân sự công ty</h2>

### I. Giới thiệu chung

#### 1. Mục tiêu

> Mục tiêu của chủ đề tài website quản lý nhân sự công ty là tạo ra một hệ thống tiện lợi và hiệu quả để người dùng có quản lý, đánh giá nhân viên của mình trong một công ty. Với mong muốn phát triển một giao diện người dùng thân thiện và trực quan, giúp người dùng dễ dàng thao tác và theo dõi thông tin liên quan đến nhân sự một cách nhanh chóng. Hệ thống sẽ cung cấp các tính năng đa dạng như tạo và quản lý hồ sơ nhân viên, đánh giá khen thưởng và kỷ luật nhân viên. Bằng cách này, chúng em hy vọng nâng cao hiệu quả quản lý nhân sự, tạo điều kiện thuận lợi cho sự tương tác và hợp tác trong môi trường công ty.

#### 2. Nghiệp vụ của đề tài
- Chức năng xem cấu trúc công ty: Tại đây người dùng có thể xem tổ chức cây thư mục với các cấp từ công ty, chi nhánh đến phòng ban của công ty. 
- Cập nhật thông tin:  Người dùng có thể xem thông tin cá nhân của mình và có thể tiến hành thay đổi theo ý muốn. Ngoài ra còn có các chức năng như xem lịch sử công tác, xem khen thưởng kỷ luật của mình và thông tin của bản thân trong công ty.
- Chức năng gửi mail: Tại đây người dùng có thể gửi email đến cho người khác mà không cần đăng nhập vào gmail.
- Quản lí chi nhánh: Trang này sẽ hiển thị tất cả danh sách chi nhánh. Ngoài ra sẽ có các chức năng như tìm kiếm, hiển thị thông tin của giám đốc chi nhánh. Các chức năng cập nhật như thêm, sửa, xóa tên chi nhánh, giám đốc chi nhánh.
- Quản lý phòng ban: Trang này sẽ hiển thị tất cả danh sách phòng ban. Ngoài ra sẽ có các chức năng như tìm kiếm, hiển thị thông tin của trưởng phòng. Các chức năng cập nhật như thêm, sửa, xóa tên phòng ban, trưởng phòng.
- Quản lý nhân viên: Trang này sẽ hiển thị tất cả thông tin của nhân viên. Ngoài ra còn có các chức năng như tìm kiếm và thêm nhân viên từ file excel. Đối với mỗi nhân viên có các tùy chọn như khen thưởng và kỷ luật.
- Thống kê tiền lương: Trang này sẽ hiển thị danh sách nhân viên và thống kê số lương cơ bản và hệ số để tính toán số lương của một nhân viên. Ngoài ra còn có các chức năng khác như tìm kiếm, xuất file excel và tính tổng lương

### II. Công nghệ sử dụng
- Database: `MySQL`
- Backend: `JavaEE` (Servlet, JSP,  JDBC)

### III. Các sơ đồ thiết kế
#### 1. Database Diagram
![Alt text](./src/main/webapp/img/data.jpg?raw=true "Title")
#### 2. Use Case Diagram
![Alt text](./src/main/webapp/img/usecase.png?raw=true "Title")

### IV. Các giao diện chính
#### 1. Đăng nhập
![Alt text](./src/main/webapp/img/dangnhap.png?raw=true "Title")
#### 2. Đăng Quên mật khẩu
![Alt text](./src/main/webapp/img/quenMatKhau.png?raw=true "Title")
#### 3. Xem cấu trúc công ty
![Alt text](./src/main/webapp/img/CautrucCongTy.png?raw=true "Title")
#### 4. Cập nhật thông tin cá nhân
![Alt text](./src/main/webapp/img/CapNhatThongTin.png?raw=true "Title")
#### 5. Quản lí chi nhánh
![Alt text](./src/main/webapp/img/QuanLiChiNhanh.png?raw=true "Title")
#### 6. Quản lí phòng ban
![Alt text](./src/main/webapp/img/QuanLiPhongBan.png?raw=true "Title")
#### 7. Quản lí nhân viên
![Alt text](./src/main/webapp/img/QuanLiNhanVien.png?raw=true "Title")
#### 8. Thống kê tiền lương
![Alt text](./src/main/webapp/img/QuanLiLuong.png?raw=true "Title")
#### 9. Gửi mail
![Alt text](./src/main/webapp/img/GuiMail.png?raw=true "Title")

### V. Video demo
> [[Xem video]](https://youtu.be/n3d7_vWBM7A)

### VI. Các kết quả đạt được
-	Thiết kế giao diện, xây dựng website quản lý nhân sự cơ bản.
-	Chức năng quản lý hồ sơ của một nhân viên.
-	Quản lý cơ bản chi nhánh, phòng ban của công ty.
-	Tính năng xem cấu trúc của công ty.
-	Chức năng gửi mail và thống kê tiền lương.




