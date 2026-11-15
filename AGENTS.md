
# AGENTS.md

# TÀI LIỆU HƯỚNG DẪN DÀNH CHO AI AGENT

## 1. Tổng quan dự án

Dự án xây dựng website thương mại điện tử chuyên kinh doanh văn phòng phẩm, phụ kiện trang trí bàn học tập và bàn làm việc.

Đối tượng khách hàng hướng đến là học sinh, sinh viên và nhân viên văn phòng trẻ.

**Các mục tiêu chính:**

- Cung cấp nền tảng xem và mua sắm sản phẩm trực tuyến.
- Hỗ trợ tìm kiếm, lọc và lựa chọn sản phẩm.
- Cung cấp chức năng giỏ hàng và đặt hàng.
- Hỗ trợ khách hàng theo dõi lịch sử và trạng thái đơn hàng.
- Hỗ trợ quản trị viên quản lý sản phẩm, danh mục, người dùng và đơn hàng.
- Cung cấp báo cáo doanh thu và thống kê kinh doanh cơ bản.

AI Agent cần hiểu rõ mục tiêu dự án trước khi đề xuất hoặc thực hiện bất kỳ thay đổi nào.

## 2. Phạm vi dự án

AI Agent PHẢI tuân thủ các chức năng được quy định trong tài liệu `REQUIREMENTS.md`.

Chỉ triển khai những chức năng đã được nhóm thống nhất.

**Các chức năng thuộc phạm vi dự án:**

- **F01:** Xem danh sách sản phẩm.
- **F02:** Xem chi tiết sản phẩm.
- **F03:** Tìm kiếm và lọc sản phẩm.
- **F04:** Đăng ký và đăng nhập.
- **F05:** Quản lý giỏ hàng.
- **F06:** Đặt hàng và thanh toán.
- **F07:** Theo dõi và xem lịch sử đơn hàng.
- **F08:** Quản lý sản phẩm và danh mục.
- **F09:** Quản lý đơn hàng.
- **F10:** Quản lý người dùng.
- **F11:** Báo cáo và thống kê.

Không tự ý bổ sung chức năng nằm ngoài phạm vi dự án.

## 3. Công nghệ sử dụng

AI Agent phải kiểm tra mã nguồn và các file cấu hình hiện có để xác định chính xác công nghệ mà dự án đang sử dụng.

**Các nguyên tắc:**

- Giữ nguyên công nghệ và framework hiện tại.
- Không tự ý thay đổi ngôn ngữ lập trình hoặc framework.
- Không tự ý thêm thư viện hoặc công cụ mới khi chưa được nhóm đồng ý.
- Ưu tiên sử dụng các thư viện và thành phần đã có trong dự án.
- Chỉ đề xuất thay đổi công nghệ khi thực sự cần thiết và phải giải thích lý do.

## 4. Cấu trúc dự án

Trước khi chỉnh sửa mã nguồn, AI Agent phải kiểm tra cấu trúc thư mục hiện tại.

**Các nguyên tắc:**

- Tuân thủ cách tổ chức thư mục hiện có.
- Đặt file mới đúng vị trí và đúng chức năng.
- Không tự ý di chuyển hoặc đổi tên các thư mục quan trọng.
- Không tạo thêm các thư mục không cần thiết.
- Không giả định một file hoặc thư mục tồn tại khi chưa kiểm tra.

## 5. Quy tắc viết mã nguồn

AI Agent phải tuân thủ các nguyên tắc sau:

- Viết mã nguồn rõ ràng, dễ đọc và dễ bảo trì.
- Sử dụng cách đặt tên biến, hàm, lớp và thành phần nhất quán.
- Tránh viết mã nguồn trùng lặp.
- Chia nhỏ chức năng hợp lý.
- Tận dụng lại các hàm, thành phần và tiện ích đã có.
- Chỉ thêm chú thích khi cần giải thích logic phức tạp.
- Tuân thủ quy tắc định dạng mã nguồn hiện tại của dự án.
- Ưu tiên giải pháp đơn giản, phù hợp với quy mô đồ án sinh viên.

## 6. Quy tắc về kiến trúc hệ thống

- Giữ nguyên kiến trúc hiện tại của dự án.
- Không tự ý thay đổi kiến trúc tổng thể khi chưa được nhóm đồng ý.
- Đảm bảo phân chia trách nhiệm hợp lý giữa giao diện, xử lý nghiệp vụ và cơ sở dữ liệu theo kiến trúc hiện có.
- Không đưa logic nghiệp vụ phức tạp vào những thành phần không phù hợp.
- Hạn chế phụ thuộc không cần thiết giữa các thành phần.
- Không tự ý xóa hoặc làm hỏng các chức năng đang hoạt động.

## 7. Quy tắc nghiệp vụ

AI Agent phải tuân thủ các quy tắc nghiệp vụ được mô tả trong `REQUIREMENTS.md`.

Một số nguyên tắc quan trọng:
### 7.1. Sản phẩm

- Giá sản phẩm phải lớn hơn 0.
- Số lượng tồn kho không được âm.
- Thông tin sản phẩm phải được kiểm tra trước khi lưu.
- Không cho phép mua số lượng vượt quá tồn kho.

### 7.2. Giỏ hàng

- Tính tổng tiền chính xác khi thêm, sửa hoặc xóa sản phẩm.
- Kiểm tra số lượng sản phẩm hợp lệ.
- Đồng bộ dữ liệu giỏ hàng theo cơ chế lưu trữ hiện tại.

### 7.3. Đặt hàng

- Kiểm tra đầy đủ thông tin giao hàng.
- Hỗ trợ phương thức COD và chuyển khoản mô phỏng.
- Tạo mã đơn hàng duy nhất.
- Cập nhật tồn kho phù hợp khi đặt hàng thành công.
- Xóa các sản phẩm đã đặt khỏi giỏ hàng.
- Đảm bảo dữ liệu đơn hàng được lưu trữ nhất quán.

### 7.4. Quản lý đơn hàng

- Tuân thủ quy trình chuyển trạng thái đơn hàng.
- Không cho phép người dùng thực hiện thao tác vượt quá quyền hạn.
- Khách hàng chỉ được xem và quản lý đơn hàng của chính mình.
- Ghi nhận thời điểm cập nhật trạng thái đơn hàng.

### 7.5. Phân quyền

- Khách hàng chỉ được sử dụng các chức năng dành cho khách hàng.
- Nhân viên chỉ được thực hiện các thao tác được phân quyền.
- Quản trị viên được sử dụng các chức năng quản trị theo yêu cầu.
- Việc kiểm tra quyền phải được thực hiện ở phía máy chủ, không chỉ dựa vào giao diện.

## 8. Quy định bảo mật

AI Agent phải đảm bảo các nguyên tắc bảo mật sau:

- Không đưa mật khẩu, API Key, JWT Secret hoặc Token vào mã nguồn.
- Không lưu mật khẩu dưới dạng văn bản thuần.
- Sử dụng thuật toán băm mật khẩu an toàn như BCrypt hoặc Argon2.
- Kiểm tra và xác thực dữ liệu đầu vào ở cả phía giao diện và máy chủ.
- Sử dụng truy vấn có tham số hoặc cơ chế truy vấn an toàn của ORM.
- Kiểm tra xác thực và phân quyền đối với các chức năng quan trọng.
- Chú ý phòng chống SQL Injection, XSS, CSRF và IDOR.
- Không tự ý vô hiệu hóa các cơ chế bảo mật hiện có.
- Không sử dụng dữ liệu cá nhân thật khi chưa được cho phép.
- Không công khai thông tin cấu hình hoặc dữ liệu nhạy cảm.

## 9. Quy trình làm việc của AI Agent

### 9.1. Trước khi sửa mã nguồn

AI Agent BẮT BUỘC thực hiện các bước:

1. Đọc các tài liệu liên quan, đặc biệt là `REQUIREMENTS.md` và `AGENTS.md`.
2. Kiểm tra cấu trúc thư mục và các file liên quan.
3. Phân tích hiện trạng và xác định nguyên nhân vấn đề.
4. Đề xuất phương án giải quyết.
5. Liệt kê các file dự kiến cần thay đổi.
6. Giải thích ảnh hưởng và rủi ro có thể xảy ra.
7. Chờ nhóm xác nhận trước khi thực hiện.

**Không tự ý sửa mã nguồn khi chưa nhận được sự đồng ý của nhóm.**

### 9.2. Sau khi được nhóm xác nhận

AI Agent thực hiện:

1. Chỉ triển khai nội dung đã được phê duyệt.
2. Ưu tiên thay đổi nhỏ và tập trung.
3. Giữ nguyên các chức năng đang hoạt động.
4. Kiểm tra lại phần mã nguồn đã thay đổi.
5. Chạy các bài kiểm thử phù hợp nếu có.
6. Kiểm tra ảnh hưởng đến các chức năng liên quan.

### 9.3. Sau khi hoàn thành

AI Agent phải báo cáo:

- Những nội dung đã thay đổi.
- Danh sách file đã sửa hoặc tạo mới.
- Mục đích của từng thay đổi.
- Hướng dẫn chạy dự án.
- Hướng dẫn kiểm thử chức năng.
- Kết quả kiểm thử thực tế.
- Những lỗi hoặc giới hạn còn tồn tại.

Không được khẳng định kiểm thử thành công nếu chưa thực sự thực hiện kiểm thử.

## 10. Quy định kiểm thử

- Kiểm tra chức năng sau khi chỉnh sửa.
- Kiểm tra các trường hợp nhập dữ liệu hợp lệ và không hợp lệ.
- Kiểm tra các trường hợp người dùng không đủ quyền truy cập.
- Kiểm tra tính chính xác của dữ liệu lưu trong cơ sở dữ liệu.
- Kiểm tra các chức năng liên quan để tránh phát sinh lỗi ngoài ý muốn.
- Ưu tiên kiểm thử theo tiêu chí nghiệm thu trong `REQUIREMENTS.md`.
- Báo cáo rõ những trường hợp chưa thể kiểm thử.

## 11. Quy tắc giao tiếp

AI Agent cần:

- Trao đổi bằng tiếng Việt, rõ ràng và dễ hiểu.
- Hỏi lại khi yêu cầu chưa rõ ràng.
- Giải thích phương án trước khi thực hiện.
- Không tự suy đoán các yêu cầu nghiệp vụ chưa được thống nhất.
- Chờ xác nhận trước khi sửa mã nguồn.
- Báo cáo trung thực kết quả thực hiện.
- Không tự ý quyết định những thay đổi ảnh hưởng lớn đến toàn bộ dự án.

## 12. Những chức năng nằm ngoài phạm vi

AI Agent không tự ý triển khai các chức năng sau:

- Tích hợp cổng thanh toán thực tế VNPay, MoMo, ZaloPay.
- Tích hợp API vận chuyển thực tế GHN, GHTK, Viettel Post.
- Hệ thống đánh giá và bình luận nâng cao kèm hình ảnh, video.
- Ứng dụng di động native trên iOS và Android.
- Hỗ trợ đa ngôn ngữ và đa tiền tệ.

Hệ thống chỉ hỗ trợ tiếng Việt và Việt Nam Đồng (VNĐ).

Các chức năng ngoài phạm vi chỉ được xem xét khi nhóm có yêu cầu và phê duyệt thay đổi phạm vi dự án.

## 13. Nguyên tắc ưu tiên

Khi thực hiện công việc, AI Agent phải ưu tiên theo thứ tự:

1. Tuân thủ `REQUIREMENTS.md`.
2. Bảo toàn các chức năng hiện có.
3. Đảm bảo an toàn và bảo mật hệ thống.
4. Tuân thủ kiến trúc và công nghệ hiện tại.
5. Đảm bảo mã nguồn dễ đọc, dễ bảo trì.
6. Hạn chế tối đa những thay đổi không cần thiết.
7. Chỉ thực hiện thay đổi sau khi được nhóm xác nhận.
