# KẾ HOẠCH VÀ PHÂN CÔNG CÔNG VIỆC DỰ ÁN (PROJECT PLAN & TASK ASSIGNMENT)

**Tên dự án:** Website Kinh Doanh Văn Phòng Phẩm & Phụ Kiện Bàn Học Tập/Làm Việc  
**Quy mô nhóm:** 6 thành viên  

---

## 1. Thành viên và vai trò

| STT | Thành viên | Vai trò | Công việc và trách nhiệm |
| :---: | :--- | :--- | :--- |
| 1 | **Trí** | Nhóm trưởng / Phân tích nghiệp vụ (BA) | Lập kế hoạch, phân chia nhiệm vụ, quản lý tiến độ, tổng hợp báo cáo, quản lý GitHub Issues/Board và điều phối nhóm. |
| 2 | **Duyên** | Thiết kế giao diện (UI/UX) | Thiết kế Wireframe, Prototype (Figma), định hình style guide, thiết kế giao diện trang chủ, danh mục, chi tiết sản phẩm, giỏ hàng, thanh toán và Admin. |
| 3 | **Quỳnh** | Lập trình Front-end (FE) | Xây dựng giao diện bằng HTML/CSS/JavaScript (hoặc React/Vue/Tailwind), xử lý tương tác người dùng, kết nối API hoặc Back-end. |
| 4 | **Tùng** | Lập trình Back-end & Database (BE Lead) | Thiết kế CSDL, xử lý API đăng nhập/đăng ký, quản lý sản phẩm, giỏ hàng, đơn hàng và các nghiệp vụ core hệ thống. |
| 5 | **Mẫn** | Lập trình Back-end & Admin (BE) | Đồng phát triển nghiệp vụ Back-end, xây dựng API cho Admin Dashboard, quản lý danh mục, xử lý đơn hàng và báo cáo thống kê. |
| 6 | **Bình** | Kiểm thử & QA/QC (Tester) | Viết Test Case, kiểm tra chức năng và giao diện, ghi nhận lỗi (Bug tracking), kiểm thử quy trình mua hàng, hỗ trợ triển khai và tài liệu hướng dẫn. |

---

## 2. Các giai đoạn thực hiện

* **Giai đoạn 1: Khảo sát và xác định yêu cầu** *(Tuần 1 - Tuần 2)*
  * Khảo sát thị trường/đối thủ, xác định yêu cầu nghiệp vụ, vai trò người dùng và chuẩn hóa yêu cầu hệ thống.
* **Giai đoạn 2: Thiết kế giao diện** *(Tuần 3 - Tuần 4)*
  * Thiết kế Wireframe/Prototype UI/UX trên Figma, thiết kế sơ đồ cơ sở dữ liệu (ERD) và API Specification.
* **Giai đoạn 3: Xây dựng các chức năng Front-end** *(Tuần 5 - Tuần 7)*
  * Dựng Layout base, phát triển UI các trang dành cho Khách hàng và Dashboard dành cho Admin.
* **Giai đoạn 4: Phát triển Back-end và Cơ sở dữ liệu** *(Tuần 5 - Tuần 8)*
  * Dựng database, phát triển các API Authentication, Sản phẩm, Giỏ hàng, Đơn hàng, Phân quyền và Báo cáo.
* **Giai đoạn 5: Tích hợp và kiểm thử** *(Tuần 9 - Tuần 10)*
  * Ghép nối Front-end với API Back-end, thực hiện Unit Test, Integration Test và UAT end-to-end.
* **Giai đoạn 6: Triển khai và hoàn thiện** *(Tuần 11 - Tuần 12)*
  * Triển khai website lên môi trường hosting/server, tối ưu hiệu năng, đóng gói báo cáo và chuẩn bị slide thuyết trình.

---

## 3. Danh sách công việc chi tiết (Task List)

### Giai đoạn 1: Khảo sát và xác định yêu cầu
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T1.1** | Khảo sát website đối thủ & Thu thập yêu cầu | Trí, Duyên | Báo cáo khảo sát 3 website đối thủ, danh sách tính năng | Tuần 1 | Hoàn thành |
| **T1.2** | Viết tài liệu yêu cầu (REQUIREMENTS.md) | Trí | File requirements hoàn chỉnh theo chuẩn | Tuần 1 | Hoàn thành |
| **T1.3** | Tạo GitHub Repository & Board phân công | Trí | Repo GitHub sẵn sàng, chia công việc chi tiết | Tuần 2 | Hoàn thành |
| **T1.4** | Lập kế hoạch kiểm thử (Test Plan) | Bình | File Kế hoạch kiểm thử & tiêu chí nghiệm thu | Tuần 2 | Hoàn thành |

### Giai đoạn 2: Thiết kế giao diện
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T2.1** | Thiết kế Wireframe các trang chính | Duyên | Wireframe: Trang chủ, Danh sách, Chi tiết, Giỏ hàng | Tuần 3 | Hoàn thành |
| **T2.2** | Thiết kế UI High-Fidelity & Prototype | Duyên | Bản Figma UI hoàn chỉnh có tương tác demo | Tuần 4 | Hoàn thành |
| **T2.3** | Thiết kế Cơ sở dữ liệu (ERD) | Tùng | Sơ đồ ERD, file Script SQL tạo cơ sở dữ liệu | Tuần 3 | Hoàn thành |
| **T2.4** | Xây dựng API Specification | Tùng, Mẫn | Tài liệu mô tả các API endpoint | Tuần 4 | Hoàn thành |

### Giai đoạn 3: Xây dựng các chức năng Front-end
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T3.1** | Dựng Cấu trúc dự án FE & Style Guide | Quỳnh | Cấu trúc thư mục, CSS/Tailwind, Icon, Font | Tuần 5 | Đang thực hiện |
| **T3.2** | Phát triển UI Client (Trang chủ, Sản phẩm, Chi tiết) | Quỳnh | Giao diện hiển thị sản phẩm, bộ lọc, responsive | Tuần 6 | Chưa bắt đầu |
| **T3.3** | Phát triển UI Giỏ hàng & Thanh toán | Quỳnh | Giao diện giỏ hàng, form nhập thông tin đặt hàng | Tuần 7 | Chưa bắt đầu |
| **T3.4** | Phát triển UI Admin Dashboard | Duyên, Quỳnh | Giao diện Quản lý sản phẩm, đơn hàng, thống kê | Tuần 7 | Chưa bắt đầu |

### Giai đoạn 4: Phát triển Back-end và Cơ sở dữ liệu
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T4.1** | Khởi tạo Server & Kết nối Cơ sở dữ liệu | Tùng | Structure dự án BE, kết nối DB thành công | Tuần 5 | Đang thực hiện |
| **T4.2** | Xây dựng API Auth & User (F04, F10) | Tùng | API Đăng ký, Đăng nhập (JWT), Phân quyền tài khoản | Tuần 6 | Chưa bắt đầu |
| **T4.3** | Xây dựng API Sản phẩm & Tìm kiếm (F01, F02, F03) | Tùng | API CRUD Sản phẩm, Tìm kiếm & Lọc nâng cao | Tuần 7 | Chưa bắt đầu |
| **T4.4** | Xây dựng API Giỏ hàng & Đặt hàng (F05, F06, F07) | Mẫn | API Giỏ hàng, Tạo đơn hàng, Lịch sử đơn hàng | Tuần 7 | Chưa bắt đầu |
| **T4.5** | Xây dựng API Admin & Báo cáo (F08, F09, F11) | Mẫn | API Quản lý đơn hàng, Thống kê doanh thu | Tuần 8 | Chưa bắt đầu |

### Giai đoạn 5: Tích hợp và kiểm thử
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T5.1** | Tích hợp API Client với Front-end | Quỳnh, Tùng | Luồng mua hàng hoạt động hoàn chỉnh với DB | Tuần 9 | Chưa bắt đầu |
| **T5.2** | Tích hợp API Admin với UI Dashboard | Quỳnh, Mẫn | Dashboard Admin hiển thị dữ liệu real-time | Tuần 9 | Chưa bắt đầu |
| **T5.3** | Viết Test Cases & Kiểm thử toàn bộ hệ thống | Bình | Bộ Test Cases & Báo cáo ghi nhận lỗi (Bug Report) | Tuần 10 | Chưa bắt đầu |
| **T5.4** | Sửa lỗi (Bug Fixing) & Tối ưu | Cả nhóm | Hệ thống đạt tiêu chuẩn, không còn lỗi nghiêm trọng | Tuần 10 | Chưa bắt đầu |

### Giai đoạn 6: Triển khai và hoàn thiện
| Mã CV | Công việc | Người phụ trách | Kết quả cần đạt | Thời hạn | Trạng thái |
| :---: | :--- | :--- | :--- | :---: | :---: |
| **T6.1** | Triển khai (Deploy) ứng dụng lên Server | Tùng, Mẫn | Website online qua domain/hosting công khai | Tuần 11 | Chưa bắt đầu |
| **T6.2** | Kiểm thử môi trường Production | Bình, Duyên | Website vận hành ổn định trên môi trường thực tế | Tuần 11 | Chưa bắt đầu |
| **T6.3** | Viết Tài liệu Hướng dẫn & Báo cáo đồ án | Trí, Bình | File Báo cáo đồ án PDF & User Guide | Tuần 12 | Chưa bắt đầu |
| **T6.4** | Chuẩn bị Slide & Kịch bản Demo | Trí, Cả nhóm | Slide thuyết trình sẵn sàng, kịch bản demo trơn tru | Tuần 12 | Chưa bắt đầu |