1. Mục tiêu của đề tài:  
Mục tiêu chính của đề tài là xây dựng và triển khai thành công một hệ thống website bán hàng. Hệ thống này sẽ cung cấp một giao diện trực tuyến thuận tiện cho người dùng có thể mua hàng và kiểm tra các thông tin trong quá trình mua hàng, đồng thời tối ưu hóa quy trình mua hàng, tiết kiệm nhiều thời gian và các tác vụ xử lý nhanh chóng, tiện lợi.  
Cải thiện quy trình bán hàng, nâng cao năng suất lao động, tăng năng lực cạnh tranh của doanh nghiệp, tự động hóa các quy trình, giảm sai sót và nâng cao hiệu quả hoạt động giúp các nhà quản lý ra các quyết định chiến lược và điều hành chính xác hơn. Đồng thời, hỗ trợ dự báo nhu cầu, quản lý nguồn cung và lập kế hoạch kinh doanh từ đó đưa ra các quyết định chiến lược và điều hành chính xác hơn.

2. Đặc tả hệ thống:  
Hệ thống website bán hàng được xây dựng cho việc kinh doanh bán túi xách với mục tiêu tập trung vào quản lý các thông tin liên quan đến sản phẩm, khách hàng, doanh thu bán hàng và đơn hàng. Người dùng được phân ra thành hai vai trò chính: Quản trị viên và Khách hàng, mỗi vai trò có các quyền hạn và khả năng truy cập khác nhau vào hệ thống.  
Quản trị viên có toàn quyền truy cập và quản lý tất cả các chức năng của hệ thống, bao gồm quản lý thông tin sản phẩm, khách hàng, doanh thu bán hàng và đơn hàng. Người dùng có quyền mua hàng, đăng nhập tài khoản để xác nhận thanh toán, thêm giỏ hàng, và được xem chi tiết đơn hàng của mình qua việc đặt hàng các sản phẩm bán túi xách trên Website.  
Các chức năng chính của hệ thống website bán túi xách bao gồm trang Admin quản lý thông tin sản phẩm (thêm, sửa, xóa, tìm kiếm), quản lý thông tin khách hàng, quản lý doanh thu bán hàng (theo tháng, số lượng đã bán, doanh thu, lợi nhuận) và quản lý đơn hàng (tiếp nhận, theo dõi trạng thái, cập nhật đơn hàng), phân quyền các chức năng đăng nhập của người dùng là admin, hoặc User. Đối với trang User bao gồm chức năng xem sản phẩm, thêm giỏ hàng, mua hàng, đặt hàng thanh toán và xem đơn hàng của người dùng theo quyền truy cập đăng nhập đã được phân quyền. Đây là các tính năng cần thiết để hỗ trợ hoạt động kinh doanh của doanh nghiệp và tạo ra trải nghiệm thuận tiện và linh hoạt cho người dùng.

**3. Phân tích thiết kế hệ thống  **
**3.1. Sơ đồ hệ thống  **
Hình dưới đây là mô tả các chức năng mua hàng của trang website bán túi xách, bao gồm việc mua hàng, thêm giỏ hàng, thanh toán, đăng nhập, đăng ký để đặt hàng. Ngoài ra còn có xem chi tiết đơn hàng, trạng thái đơn hàng, thông tin liên hệ của cửa hàng. Đối với trang admin sẽ quản lý danh mục, sản phẩm, thống kê doanh thu, phân quyền đăng ký cho user hoặc admin,…  
![image](https://github.com/user-attachments/assets/b8aa5827-2f76-4522-95c6-692510cba2af)  
**3.2 Sơ đồ Use-case hệ thống (Use-Case Diagram)  **
**3.2.1. Sơ đồ Usecase tổng quát:  **
![image](https://github.com/user-attachments/assets/3c25a2f3-e5f3-4eb4-8e3d-5748acb7615a)
Mô tả các actor:  
Người dùng (khách hàng): là những người dùng trực tiếp các chức năng trên hệ thống như là đặt hàng, xem chi tiết sản phẩm, thanh toán, thêm sản phẩm vào giỏ hàng, xem đơn hàng, thông tin liên hệ, thông tin về cửa hàng….  
Quản trị viên: là người quản trị cao nhất của hệ thống, quản trị viên có quyền quản lý các thông tin của hệ thống như đơn hàng, người dùng theo phân quyền truy cập, danh mục sản phẩm, quản lý sản phẩm, quản lý phân loại, phân loại Size… Quản trị có quyền thêm xem, sửa xoá các thông tin của hệ thống website.
**3.2.2 Sơ đồ Use Case thành phần:**
**Use case đăng nhập:**
Actor: Quản trị viên, khách hàng(người dùng)
Mô tả: Quản trị viên, khách hàng (người dùng) phải đăng nhập vào hệ thống bằng tài khoản và mật khẩu cá nhân đã đăng ký trước đó. Do theo phân quyền của quản trị viên mà vào đúng tài khoản truy cập của hệ thống.
![image](https://github.com/user-attachments/assets/49ede923-3c7a-45e0-a3f9-11dafea7880f)
**Use case quản lý sản phẩm:**
Tác nhân: Admin (quản trị viên)
Mô tả: Trong quản lý sản phẩm admin được phân quyền với chức năng thêm, sửa, xóa sản phẩm và xem danh sách sản phẩm cho các danh mục của sản phẩm.  
