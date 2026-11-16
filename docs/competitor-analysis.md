# Phân tích website đối thủ và tham khảo

**Dự án:** Website thương mại điện tử bán văn phòng phẩm, dụng cụ học tập và phụ kiện trang trí bàn học, bàn làm việc  
**Phạm vi:** Khảo sát tối thiểu 3 website tương tự để xác định các chức năng và phương án thiết kế phù hợp.

## 1. Bảng so sánh chi tiết

| Tiêu chí | A. Lắc Đầu Shop | B. Sói Gear | C. 19 Stationery | Đề xuất cho dự án |
|---|---|---|---|---|
| **Trang chủ** | Nhiều nhóm hàng, có danh mục nổi bật, tìm kiếm, giỏ hàng và khu vực thiết kế lót chuột riêng. | Giao diện định hướng phụ kiện công nghệ, menu nhiều tầng, có tìm kiếm và tài khoản. | Menu ngắn gọn, hiển thị hàng mới, bán chạy, sản phẩm giảm giá và câu chuyện thương hiệu. | Chọn giao diện đơn giản như C; bổ sung banner bộ sưu tập, sản phẩm nổi bật và khuyến mãi như A. |
| **Danh mục sản phẩm** | Phân loại lót chuột theo kích thước, chất liệu và mục đích sử dụng. | Deskmat nằm trong nhóm Switch & Phụ kiện; ngoài ra phân loại theo nhiều nhóm bàn phím, keycap. | Phân loại trực tiếp thành Postcard, Keychain, Sticker, Magnet. | Phân loại theo loại sản phẩm; bổ sung nhóm bộ sưu tập và chủ đề thiết kế. |
| **Tìm kiếm và lọc** | Có tìm kiếm, lọc giá, hãng, độ dày, kích thước; sắp xếp giá và hàng mới. | Có tìm kiếm, lọc thương hiệu, khoảng giá, loại; sắp xếp tên, giá, mới nhất, tồn kho. | Có tìm kiếm theo từ khóa và điều hướng danh mục; chưa ghi nhận bộ lọc nâng cao trên trang sticker. | Tìm kiếm theo tên; lọc loại sản phẩm, giá, chủ đề, kích thước; sắp xếp theo giá và mới nhất. |
| **Chi tiết sản phẩm** | Hiển thị mã, giá, khuyến mãi, kích thước, chất liệu, đánh giá, nút mua ngay và thêm giỏ. | Có nhiều ảnh, thương hiệu, mã hàng, thông số, tùy chọn kích thước, số lượng, mua ngay và thêm giỏ. | Có nhiều ảnh, mã mẫu, giá, chất liệu, kích cỡ, mô tả, sản phẩm liên quan. | Kết hợp thông số kỹ thuật của A/B với cách giới thiệu bộ sưu tập của C. |
| **Giỏ hàng và đặt hàng** | Có giỏ hàng, mua ngay, đăng nhập và hướng dẫn thanh toán. | Có giỏ hàng, mua ngay, chỉnh số lượng, tài khoản. | Trang sản phẩm ghi nhận đơn hàng được xử lý qua Shopee/TikTok Shop. | Xây dựng giỏ hàng và quy trình đặt hàng trực tiếp trên website; hỗ trợ thanh toán phù hợp. |
| **Điểm có thể cải thiện** | Menu và danh mục quá nhiều tầng đối với shop nhỏ. | Bộ lọc giá rộng, có nhiều khoảng giá không phù hợp với deskmat. | Chưa có bộ lọc nâng cao rõ ràng; việc xử lý đơn qua sàn hạn chế khả năng kiểm soát toàn bộ hành trình trên website. | Giao diện gọn, bộ lọc phù hợp từng danh mục, checkout trực tiếp, liên kết sản phẩm cùng collection. |

## 2. Đánh giá từng website

### 2.1. Website A — Lắc Đầu Shop

**Đường dẫn:** https://lacdau.com

**Ưu điểm:** Hệ thống phân loại lót chuột rất chi tiết, cho phép tìm kiếm sản phẩm theo kích thước, độ dày và khoảng giá. Trang chi tiết cung cấp thông số, giá bán, mức giảm giá và thao tác mua hàng.

**Hạn chế:** Hệ thống danh mục bao gồm quá nhiều loại phụ kiện, thiết bị và mô hình. Nếu áp dụng nguyên cấu trúc này vào dự án có số lượng sản phẩm ban đầu ít, giao diện có thể trở nên phức tạp không cần thiết.

**Bài học áp dụng:** Nên học hỏi cách xây dựng bộ lọc thuộc tính và hiển thị thông số lót chuột. Chưa nên triển khai chức năng thiết kế lót chuột tùy chỉnh vì cần xử lý tải tệp, kiểm tra chất lượng hình ảnh và xem trước thiết kế.

### 2.2. Website B — Sói Gear

**Đường dẫn:** https://soigear.vn/lot-ban-phim-deskmat

**Ưu điểm:** Trang chi tiết deskmat có nhiều hình ảnh, mô tả chất liệu, kích thước và đóng gói. Ví dụ mẫu *Thời Báo* cho phép lựa chọn kích thước 800 × 300 × 5 mm, 900 × 400 × 5 mm và 1000 × 500 × 5 mm.

**Hạn chế:** Bộ lọc giá của danh mục có các khoảng lên đến hàng chục triệu đồng, trong khi nhiều mẫu deskmat được niêm yết ở mức vài trăm nghìn đồng. Điều này làm giảm tính phù hợp của bộ lọc với danh mục cụ thể.

**Bài học áp dụng:** Thiết kế thuộc tính sản phẩm linh hoạt, cho phép một mẫu lót chuột có nhiều kích thước. Mỗi danh mục nên có bộ lọc phù hợp riêng.

### 2.3. Website C — 19 Stationery

**Đường dẫn:** https://19stationery.com

**Ưu điểm:** Danh mục rõ ràng, nội dung sản phẩm gần với dự án. Sticker được trình bày theo bộ sưu tập, có nhiều mẫu thiết kế và sản phẩm liên quan. Website còn có câu chuyện thương hiệu giúp tăng tính nhận diện.

**Hạn chế:** Chưa ghi nhận bộ lọc theo giá, chủ đề hoặc chất liệu trên trang sticker được khảo sát. Trang sản phẩm thông báo việc xử lý đơn hàng qua Shopee/TikTok Shop, thay vì thể hiện đầy đủ quy trình thanh toán trực tiếp.

**Bài học áp dụng:** Học cách giới thiệu sản phẩm mang tính sáng tạo và phát triển bộ sưu tập. Đồng thời bổ sung khả năng đặt hàng trực tiếp, tìm kiếm theo chủ đề và mua nhiều sản phẩm cùng một collection.

## 3. Tổng kết và định hướng áp dụng

Từ ba website khảo sát, nhóm rút ra những định hướng sau:

1. **Giao diện:** Ưu tiên bố cục gọn, menu dễ hiểu, sản phẩm nổi bật và hình ảnh rõ ràng.
2. **Danh mục và tìm kiếm:** Phân loại sản phẩm theo nhu cầu học tập, làm việc; hỗ trợ tìm kiếm theo tên và lọc theo giá, loại sản phẩm.
3. **Trang chi tiết:** Hiển thị đầy đủ mô tả, chất liệu, kích thước, giá và hình ảnh sản phẩm.
4. **Mua hàng:** Xây dựng giỏ hàng và quy trình đặt hàng trực tiếp trên website.
5. **Điểm khác biệt:** Khuyến khích mua theo combo sản phẩm để giảm bất tiện khi khách phải tìm nhiều món riêng lẻ.


