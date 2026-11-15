# TÀI LIỆU YÊU CẦU DỰ ÁN (PROJECT REQUIREMENTS DOCUMENT)
**Tên dự án:** Website Kinh Doanh Văn Phòng Phẩm & Phụ Kiện Bàn Học Tập/Làm Việc

---

## 1. Mục tiêu dự án
* **Mục tiêu kinh doanh:**
  * Xây dựng nền tảng thương mại điện tử chuyên cung cấp văn phòng phẩm, phụ kiện trang trí bàn học và bàn làm việc đáp ứng xu hướng thẩm mỹ cao cho giới trẻ.
  * Tối ưu hóa quy trình bán hàng trực tuyến, cung cấp các gói Combo sản phẩm (nhập học, trang trí góc làm việc) giúp gia tăng giá trị trung bình trên mỗi đơn hàng (AOV).
  * Xây dựng kênh quản lý đơn hàng, kho hàng và báo cáo doanh thu tập trung cho quản trị viên.

* **Giá trị mang lại cho khách hàng:**
  * **Giải quyết nỗi đau mua sắm:** Khắc phục tình trạng mua lẻ từng món gây tốn kém phí vận chuyển hoặc sản phẩm bị phân tán qua việc cung cấp combo đầy đủ và bộ sưu tập đồng bộ.
  * **Trải nghiệm mua sắm minh bạch:** Thông tin chi tiết về kích thước, màu sắc, chất liệu và hình ảnh chuẩn xác giúp khách hàng dễ dàng hình dung sản phẩm.
  * **Tìm kiếm & Lựa chọn thông minh:** Tối ưu bộ lọc theo khoảng giá, ngân sách, màu sắc và thuộc tính sản phẩm giúp tiết kiệm thời gian tìm kiếm.
  * **Giao diện hiện đại & Thao tác nhanh chóng:** Trải nghiệm người dùng (UX/UI) tối ưu cho học sinh, sinh viên và người đi làm trẻ.

---

## 2. Phạm vi dự án
### 2.1. Trong phạm vi (In-Scope)
* **Khách tham quan / Khách chưa đăng nhập:**
  * Xem danh sách sản phẩm, bộ sưu tập, danh mục.
  * Xem thông tin chi tiết sản phẩm và các thuộc tính liên quan (màu sắc, kích thước, chất liệu, tồn kho).
  * Tìm kiếm nâng cao và lọc sản phẩm (theo từ khóa, danh mục, khoảng giá, thương hiệu).
  * Thêm/sửa/xóa sản phẩm vào giỏ hàng tạm thời.
  * Đăng ký tài khoản mới và đăng nhập hệ thống.

* **Khách hàng đã đăng nhập:**
  * Quản lý giỏ hàng và thanh toán trực tuyến/COD.
  * Nhập thông tin giao hàng và xác nhận đơn hàng.
  * Xem lịch sử đơn hàng và theo dõi trạng thái tiến trình xử lý đơn hàng.
  * Quản lý thông tin tài khoản cá nhân.

* **Nhân viên xử lý đơn:**
  * Quản lý danh sách đơn hàng được phân công.
  * Xem chi tiết đơn hàng và cập nhật trạng thái đơn (Xác nhận, Đóng gói, Đang giao, Hoàn tất, Hủy).

* **Quản trị viên (Admin):**
  * Quản lý danh mục và sản phẩm (Thêm, sửa, xóa, ẩn/huyện sản phẩm, quản lý hình ảnh, số lượng tồn kho).
  * Quản lý toàn bộ danh sách đơn hàng.
  * Quản lý danh sách người dùng và phân quyền (Khách hàng, Nhân viên, Admin).
  * Báo cáo thống kê cơ bản: Tổng doanh thu, số lượng đơn hàng, danh sách sản phẩm bán chạy.

### 2.2. Ngoài phạm vi (Out-of-Scope)
* Tích hợp cổng thanh toán trực tuyến qua bên thứ 3 (VNPay, MoMo, ZaloPay) dạng API trực tiếp thực tế (chỉ mô phỏng quy trình thanh toán chuyển khoản hoặc COD trong đồ án).
* Tích hợp API của các đơn vị vận chuyển thực tế (GHN, GHTK, Viettel Post) để tự động tính phí ship theo tọa độ/địa chỉ thực (phí vận chuyển sẽ áp dụng mức cố định hoặc quy tắc đơn giản).
* Hệ thống đánh giá/bình luận sản phẩm nâng cao kèm hình ảnh/video thực tế.
* Đa ngôn ngữ và đa tiền tệ (chỉ hỗ trợ Tiếng Việt và Việt Nam Đồng - VNĐ).
* Ứng dụng di động (Mobile App native trên iOS/Android) - chỉ tập trung responsive trên trình duyệt web di động.

---

## 3. Người dùng và phân quyền
| Vai trò | Mô tả | Quyền hạn |
| :--- | :--- | :--- |
| **Khách chưa đăng nhập** | Người truy cập website chưa có tài khoản hoặc chưa xác thực | Xem thông tin công khai (sản phẩm, giá, khuyến mãi, danh mục), tìm kiếm/lọc sản phẩm, thêm sản phẩm vào giỏ hàng tạm. Yêu cầu đăng ký/đăng nhập khi tiến hành đặt hàng. |
| **Khách hàng (Customer)** | Khách hàng đã đăng ký tài khoản và đăng nhập | Thực hiện quy trình đặt hàng, quản lý giỏ hàng, xem chi tiết lịch sử đơn hàng, cập nhật thông tin cá nhân. |
| **Nhân viên xử lý đơn (Staff)** | Nhân viên phụ trách vận hành và kho | Xem danh sách đơn hàng, tìm kiếm đơn hàng, cập nhật trạng thái tiến trình xử lý đơn (Xác nhận, Đang đóng gói, Đang giao, Hoàn tất, Hủy). Không có quyền sửa giá hay xóa sản phẩm. |
| **Quản trị viên (Admin)** | Người quản lý toàn bộ hệ thống | Toàn quyền quản trị hệ thống: Quản lý sản phẩm, danh mục, phân quyền tài khoản người dùng, quản lý đơn hàng, xem báo cáo doanh thu và thống kê kinh doanh. |

---

## 4. Yêu cầu chức năng

| Mã YC | Tên chức năng | Mô tả chi tiết | Người sử dụng | Mức độ ưu tiên | Tiêu chí nghiệm thu |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **F01** | Xem danh sách sản phẩm | Hiển thị danh sách các sản phẩm (bút, sổ, giấy ghi chú, phụ kiện bàn...) phân theo danh mục hoặc bộ sưu tập/combo. | Khách, Khách hàng | Bắt buộc | Hiển thị danh sách dạng lưới/danh sách với đầy đủ ảnh, tên, giá bán, nhãn mác (nếu có). Phân trang mượt mà nếu danh sách dài. |
| **F02** | Xem chi tiết sản phẩm | Hiển thị chi tiết một sản phẩm bao gồm: bộ ảnh, tên, giá bán, chất liệu, kích thước, thương hiệu, mô tả chi tiết, tình trạng tồn kho. | Khách, Khách hàng | Bắt buộc | Hiển thị đúng thông tin dữ liệu từ database, có ô chọn số lượng, chọn thuộc tính (màu sắc/kích thước nếu có), nút "Thêm vào giỏ hàng". |
| **F03** | Tìm kiếm & Lọc sản phẩm | Tìm kiếm sản phẩm theo tên từ khóa; Lọc danh sách theo danh mục, khoảng giá (ngân sách), thương hiệu. | Khách, Khách hàng | Bắt buộc | Kết quả hiển thị tức thì hoặc chính xác theo tiêu chí lọc; thông báo rõ ràng khi không tìm thấy sản phẩm phù hợp. |
| **F04** | Đăng ký & Đăng nhập | Cho phép người dùng tạo tài khoản mới (họ tên, email, mật khẩu, số điện thoại) và đăng nhập vào hệ thống. | Khách | Bắt buộc | Kiểm tra trùng lặp email, mã hóa mật khẩu, báo lỗi cụ thể khi sai thông tin. Đăng nhập thành công sẽ lưu session/token chính xác. |
| **F05** | Quản lý giỏ hàng | Thêm sản phẩm vào giỏ, thay đổi số lượng, xóa từng sản phẩm hoặc xóa toàn bộ giỏ hàng, tính tổng tiền tự động. | Khách, Khách hàng | Bắt buộc | Cập nhật tổng tiền tức thì khi thay đổi số lượng. Lưu trữ giỏ hàng trong session hoặc cơ sở dữ liệu đối với người dùng đã đăng nhập. |
| **F06** | Đặt hàng & Thanh toán | Khách hàng nhập thông tin giao hàng (Họ tên, SĐT, Địa chỉ), chọn phương thức thanh toán (COD / Chuyển khoản) và xác nhận đơn hàng. | Khách hàng | Bắt buộc | Tự động tạo đơn hàng mới với mã đơn duy nhất, trừ số lượng tồn kho tương ứng, chuyển sản phẩm khỏi giỏ hàng và gửi phản hồi thành công. |
| **F07** | Theo dõi & Xem lịch sử đơn hàng | Khách hàng xem danh sách các đơn hàng đã đặt và chi tiết từng đơn kèm trạng thái hiện tại (Đang xử lý, Đang giao, Đã giao, Đã hủy). | Khách hàng | Bắt buộc | Hiển thị chính xác lịch sử mua hàng cá nhân. Cho phép hủy đơn hàng nếu đơn vẫn ở trạng thái "Chờ xác nhận". |
| **F08** | Quản lý sản phẩm & danh mục | Quản trị viên thêm mới, cập nhật thông tin, thay đổi số lượng tồn kho, tải ảnh sản phẩm, ẩn hoặc xóa sản phẩm/danh mục. | Admin | Bắt buộc | Dữ liệu được lưu trữ đúng vào cơ sở dữ liệu; giao diện CRUD dễ sử dụng, validate dữ liệu kỹ lưỡng (giá tiền > 0, tồn kho >= 0). |
| **F09** | Quản lý đơn hàng | Xem danh sách toàn bộ đơn hàng, lọc đơn hàng theo trạng thái, cập nhật trạng thái đơn (Chờ xác nhận -> Đang đóng gói -> Đang giao -> Hoàn tất / Hủy). | Admin, Staff | Bắt buộc | Đơn hàng chuyển trạng thái chính xác; log lại thông tin thời gian cập nhật; gửi thông báo hoặc hiển thị trạng thái mới cho khách hàng. |
| **F10** | Quản lý người dùng | Hiển thị danh sách người dùng, thay đổi vai trò (phân quyền Admin/Staff/Customer), kích hoạt hoặc khóa tài khoản. | Admin | Nâng cao | Khóa tài khoản thành công khiến tài khoản đó không thể đăng nhập. Không cho phép Admin tự xóa chính tài khoản của mình. |
| **F11** | Báo cáo & Thống kê | Thống kê tổng doanh thu theo thời gian (ngày/tháng/năm), thống kê số lượng đơn hàng thành công/hủy, danh sách top sản phẩm bán chạy. | Admin | Nâng cao | Hiển thị dữ liệu chính xác dưới dạng số liệu tổng quan hoặc biểu đồ trực quan (nếu áp dụng), hỗ trợ lọc theo mốc thời gian. |

---

## 5. Yêu cầu phi chức năng
* **NFR01 - Giao diện & Trải nghiệm (UI/UX):**
  * Giao diện theo phong cách hiện đại, tối giản, thu hút đối tượng học sinh, sinh viên và nhân viên văn phòng trẻ.
  * Đáp ứng hiển thị mượt mà trên nhiều kích thước màn hình khác nhau (Responsive design: Desktop, Tablet, Mobile).
* **NFR02 - Bảo mật (Security):**
  * Mật khẩu người dùng phải được mã hóa an toàn (ví dụ: BCrypt, Argon2) trước khi lưu vào cơ sở dữ liệu.
  * Kiểm tra và ràng buộc phân quyền nghiêm ngặt đối với các đường dẫn/API dành riêng cho Admin và Staff (tránh lỗ hổng IDOR, Unauthorized Access).
  * Bảo vệ hệ thống khỏi các lỗ hổng cơ bản: SQL Injection, Cross-Site Scripting (XSS), CSRF.
  * Không công khai các thông tin bí mật như file cấu hình, khóa JWT, credentials trong mã nguồn công khai.
* **NFR03 - Kiểm soát dữ liệu đầu vào (Data Validation):**
  * Kiểm tra (validate) toàn bộ dữ liệu ở cả giao diện client và phía server (định dạng email, độ dài mật khẩu, số điện thoại hợp lệ, số lượng mua hợp lệ).
* **NFR04 - Hiệu năng & Khả năng mở rộng (Performance & Maintainability):**
  * Thời gian phản hồi trang trung bình dưới 2 giây cho các tác vụ thông thường.
  * Mã nguồn được tổ chức cấu trúc rõ ràng theo mô hình tiêu chuẩn (như MVC hoặc Client-Server separation), dễ bảo trì và mở rộng.

---

## 6. Giới hạn và giả định (Constraints & Assumptions)
### 6.1. Giới hạn (Constraints)
* **Thời gian:** Dự án được hoàn thành trong phạm vi thời gian thực hiện đồ án học phần (khoảng 8 - 12 tuần).
* **Công nghệ:**
  * Frontend: HTML5, CSS3, JavaScript (hoặc ReactJS/VueJS/Tailwind CSS).
  * Backend: Node.js (Express) / PHP (Laravel) / Java (Spring Boot) / Python (Django).
  * Cơ sở dữ liệu: MySQL / PostgreSQL / MongoDB.
* **Nguồn lực:** Thực hiện bởi nhóm sinh viên (Nhiệm vụ phát triển ứng dụng), hạn chế về chi phí vận hành server thực tế cũng như ngân sách mua các dịch vụ API trả phí.

### 6.2. Giả định (Assumptions)
* Đối tượng người dùng thử nghiệm có kiến thức cơ bản về thao tác với website thương mại điện tử.
* Dữ liệu hình ảnh sản phẩm được chuẩn bị sẵn với kích thước chuẩn và dung lượng tối ưu.
* Quy trình giao hàng và thanh toán trực tuyến trong đồ án được giả định là hoạt động thành công mà không cần kết nối cổng thanh toán ngân hàng thực tế.