# AI USAGE LOG

Tài liệu ghi nhận quá trình sử dụng công cụ AI trong quá trình phân tích, thiết kế và phát triển website thương mại điện tử của nhóm.

Mỗi lần sử dụng AI được ghi nhận theo các nội dung:
- Công cụ AI được sử dụng.
- Mục đích sử dụng.
- Prompt đầu vào.
- Kết quả AI trả về.
- Đánh giá và quyết định của nhóm.

---

# 1. PHÂN TÍCH VÀ PHẢN BIỆN YÊU CẦU NGHIỆP VỤ

## 1.1. Hoạt động 1: Phân tích yêu cầu nghiệp vụ

**Công cụ:** Claude

**Mục đích:**

Sử dụng AI để hỗ trợ phân tích nghiệp vụ cho dự án website thương mại điện tử chuyên kinh doanh văn phòng phẩm, dụng cụ học tập và sản phẩm trang trí bàn học, bàn làm việc. AI được yêu cầu đề xuất mục tiêu, phạm vi, nhóm người dùng, chức năng, quy trình nghiệp vụ, yêu cầu phi chức năng, phạm vi MVP và các rủi ro triển khai.

### Prompt chính

Bạn là chuyên gia phân tích nghiệp vụ cho dự án thương mại điện tử.

Thông tin dự án:
- Tên dự án: Trang bán hàng TMDT văn phòng phẩm, dụng cụ học tập trang trí bàn học, bàn làm việc
- Sản phẩm hoặc dịch vụ: văn phòng phẩm, combo sản phẩm, dụng cụ học tập trang trí kệ để bút, khay tài liệu, bảng ghi chú, lót chuột,....
- Khách hàng mục tiêu: Sinh viên đại học, cao đẳng, người đi làm trẻ (khoảng 22 đến 30 tuổi), quan tâm tính thẩm mỹ, muốn bàn làm việc gọn đẹp. Có thể thêm nhóm mua làm quà tặng (quà tặng bạn bè, đồng nghiệp), nhưng chỉ là nhóm phụ.
- Vấn đề kinh doanh: Phân loại sản phẩm rõ ràng theo danh mục và nhu cầu sử dụng. Trang chi tiết sản phẩm đầy đủ thông tin, hình ảnh. Tìm kiếm và lọc theo loại sản phẩm, mức giá, thương hiệu (và thuộc tính riêng như màu, kích thước nếu có). Giỏ hàng và đặt hàng đơn giản để mua nhiều món trong một đơn.
Có thể thêm danh mục “Combo” (ví dụ: bộ nhập học, bộ trang trí bàn làm việc) để khách mua nhanh hơn.
- Website tham khảo:
  1. https://lacdau.com
  2. https://soigear.vn/lot-ban-phim-deskmat
  3. https://19stationery.com
- Thời gian thực hiện: Hiện tại đến ngày 20/12
- Quy mô nhóm: 6

Hãy đề xuất:
1. Mục tiêu và phạm vi dự án.
2. Các nhóm người dùng và quyền hạn.
3. Danh sách chức năng cần có.
4. Quy trình nghiệp vụ chính.
5. Yêu cầu phi chức năng.
6. Các chức năng nên hoàn thành ở phiên bản đầu tiên.
7. Các chức năng nâng cao có thể bổ sung.
8. Rủi ro khi triển khai và cách giảm thiểu.

Phân biệt rõ:
- Yêu cầu bắt buộc.
- Yêu cầu có thể phát triển sau.
- Đề xuất cần nhóm xác minh thêm.

Không giả định nhóm có đủ thời gian hoặc năng lực để triển khai.

### Kết quả AI

AI đề xuất các nội dung chính:

1. **Mục tiêu và phạm vi dự án:** Xây dựng website giúp sinh viên và người đi làm trẻ tìm kiếm, lựa chọn và mua nhiều sản phẩm trong một đơn hàng. Phạm vi gồm trang chủ, danh mục, chi tiết sản phẩm, tìm kiếm, lọc, giỏ hàng, đặt hàng, theo dõi đơn và quản trị sản phẩm, đơn hàng.

2. **Nhóm người dùng:** Khách chưa đăng nhập, khách hàng đã đăng nhập và quản trị viên. AI đề xuất thêm nhân viên xử lý đơn ở giai đoạn sau.

3. **Danh sách chức năng:** Đề xuất 20 nhóm chức năng, từ hiển thị sản phẩm, tìm kiếm, giỏ hàng, đặt hàng, quản trị đến các chức năng nâng cao như bộ sưu tập, biến thể sản phẩm, mã giảm giá, đánh giá và thanh toán trực tuyến.

4. **Quy trình nghiệp vụ:** Đề xuất quy trình mua hàng, quản trị đơn hàng, quản lý sản phẩm và xử lý chuyển khoản thủ công.

5. **Yêu cầu phi chức năng:** Responsive, validation dữ liệu, phân quyền, mã hóa mật khẩu, bảo vệ thông tin trong repository, sử dụng dữ liệu mẫu và tổ chức mã nguồn rõ ràng.

6. **Phiên bản MVP:** Đề xuất ưu tiên các chức năng F01–F08, F05b, F10 và F09 nếu nhóm quyết định giữ chức năng combo.

7. **Chức năng nâng cao:** Sản phẩm liên quan, bộ sưu tập, biến thể sản phẩm, lọc thuộc tính, mã giảm giá, đánh giá, thanh toán trực tuyến và cá nhân hóa sản phẩm.

8. **Rủi ro triển khai:** Thời gian hạn chế, phạm vi dự án mở rộng, năng lực không đồng đều, xung đột Git, bản quyền hình ảnh, bảo mật và phụ thuộc quá nhiều vào AI.

AI cũng đưa ra các vấn đề nhóm cần xác minh thêm, đặc biệt là công nghệ, chức năng combo, bộ sưu tập và năng lực triển khai thực tế.

### Đánh giá và quyết định của nhóm

Nhóm sử dụng kết quả AI làm cơ sở tham khảo để xây dựng danh sách yêu cầu ban đầu, không áp dụng toàn bộ đề xuất.

- **Giữ lại:** Mục tiêu dự án, nhóm người dùng cơ bản, quy trình mua hàng, quy trình quản trị đơn, các chức năng cốt lõi và yêu cầu phi chức năng.
- **Điều chỉnh:** Chức năng combo được định hướng triển khai ở mức đơn giản. Mỗi kích thước được quản lý như một sản phẩm riêng trong phiên bản đầu tiên.
- **Loại bỏ:** Vai trò nhân viên xử lý đơn riêng, bộ sưu tập, biến thể sản phẩm, lọc thuộc tính nâng cao, mã giảm giá, đánh giá, thanh toán trực tuyến và cá nhân hóa sản phẩm.
- **Cần kiểm tra thêm:** Chức năng sản phẩm liên quan, thống kê doanh thu, kiến trúc hệ thống và cách hiển thị thông tin chuyển khoản mẫu.

Nhóm quyết định giới hạn phạm vi MVP nhằm bảo đảm thời gian thực hiện, năng lực lập trình và khả năng hoàn thành sản phẩm.

---

## 1.2. Hoạt động 2: Phản biện yêu cầu nghiệp vụ

**Công cụ:** Gemini

**Mục đích:**

Sử dụng một công cụ AI độc lập để phản biện kết quả phân tích của Claude. Qua đó, nhóm kiểm tra tính phù hợp của các yêu cầu, phát hiện chức năng chưa cần thiết, các thiếu sót trong quy trình nghiệp vụ và rủi ro kỹ thuật trước khi thống nhất yêu cầu dự án.

### Prompt chính

Bạn là người phản biện độc lập cho một dự án website thương mại điện tử
do nhóm sinh viên thực hiện trong một học phần.

Tôi sẽ cung cấp:
1. Mô tả đề tài.
2. Vấn đề kinh doanh và khách hàng mục tiêu.
3. Kết quả khảo sát ba website.
4. Danh sách yêu cầu do một công cụ AI khác đề xuất.

Hãy phản biện các yêu cầu theo những khía cạnh:
- Có thực sự giải quyết vấn đề kinh doanh không?
- Có yêu cầu nào trùng lặp hoặc không cần thiết không?
- Có chức năng nào vượt quá phạm vi của nhóm không?
- Có thiếu chức năng cơ bản hoặc quy trình nghiệp vụ nào không?
- Có rủi ro về dữ liệu, bảo mật hoặc quyền riêng tư không?
- Có yêu cầu nào chưa đủ rõ để lập trình và kiểm thử không?

Với mỗi vấn đề, hãy nêu lý do và đề xuất điều chỉnh.

Không mặc định rằng phương án của công cụ AI trước là đúng.
Không tự ý thay đổi toàn bộ đề tài.

### Kết quả AI

Gemini đưa ra các nhận xét và đề xuất điều chỉnh trên sáu khía cạnh:

1. **Mức độ phù hợp với vấn đề kinh doanh:** Đồng ý rằng các chức năng MVP đáp ứng được luồng mua hàng cơ bản. Đề xuất giữ combo F09 ở mức đơn giản vì đây là điểm khác biệt của dự án.

2. **Chức năng trùng lặp hoặc chưa cần thiết:** Không nên ưu tiên bộ sưu tập F13. Có thể thay bằng việc hiển thị 3–4 sản phẩm cùng danh mục tại trang chi tiết mà không cần xây dựng bảng dữ liệu riêng.

3. **Chức năng vượt phạm vi:** Không triển khai combo tùy biến. Combo nên là sản phẩm cố định do quản trị viên tạo sẵn.

4. **Thiếu sót trong quy trình:** Cần quy định rõ khi số lượng sản phẩm trong giỏ về 0 thì tự động xóa. Đồng thời, kiểm tra tồn kho trước khi lưu đơn hàng để tránh đặt hàng vượt số lượng thực tế.

5. **Rủi ro bảo mật:** Validation không đủ để chống SQL Injection. Cần sử dụng Prepared Statements hoặc ORM, escape HTML và bổ sung file `.env.example`, đồng thời đưa `.env` vào `.gitignore`.

6. **Quy tắc nghiệp vụ chưa rõ:** Cần xác định đơn hàng từ trạng thái Đang giao trở đi không được hủy trực tiếp. Khi hủy đơn, hệ thống phải hoàn kho đúng số lượng sản phẩm trong đơn và có ca kiểm thử tương ứng.

### Đánh giá và quyết định của nhóm

Nhóm đối chiếu đề xuất của Gemini với kết quả Claude và yêu cầu dự án để thống nhất các điều chỉnh:

| Nội dung | Quyết định của nhóm |
|---|---|
| MVP | Giữ lại các chức năng cốt lõi |
| Combo F09 | Giữ trong MVP ở mức đơn giản. Admin tạo combo cố định, không cho khách tùy biến |
| Sản phẩm liên quan F12 | Có thể triển khai nếu còn thời gian bằng truy vấn cùng danh mục |
| Bộ sưu tập F13 | Loại khỏi đồ án, thay thế bằng sản phẩm liên quan |
| Nhân viên xử lý đơn | Loại bỏ, chỉ sử dụng vai trò Admin |
| F14, F17, F18, F20 | Loại khỏi phạm vi đồ án |
| Giỏ hàng F04 | Bổ sung tiêu chí tự động xóa sản phẩm khi số lượng về 0 |
| Đặt hàng F05 | Bổ sung kiểm tra tồn kho trước khi lưu đơn |
| SQL Injection và XSS | Điều chỉnh yêu cầu bảo mật: sử dụng Prepared Statements hoặc ORM, escape HTML và validation hai phía |
| Bảo mật Git | Bổ sung `.env.example` và đưa `.env` vào `.gitignore` |
| Hủy đơn F08 | Từ trạng thái Đang giao trở đi không được hủy trực tiếp |
| Hoàn kho | Bổ sung ca kiểm thử đặt hàng, hủy đơn và đối chiếu tồn kho trước, sau |

**Kết luận:**

Nhóm tiếp thu các phản biện phù hợp của Gemini, điều chỉnh một số yêu cầu chức năng và phi chức năng để làm rõ quy tắc nghiệp vụ, tăng tính khả thi và hạn chế rủi ro khi triển khai.

Nhóm không sao chép nguyên trạng kết quả của AI mà chủ động đối chiếu, đánh giá và quyết định phạm vi thực hiện.

---

---

# 2. Xây dựng tài liệu hướng dẫn cho AI (AGENTS.md)

**Công cụ:** ChatGPT

**Mục đích:**
Xây dựng tài liệu AGENTS.md nhằm cung cấp các nguyên tắc và hướng dẫn để AI hỗ trợ dự án đúng phạm vi đã thống nhất. Tài liệu định hướng AI về bối cảnh dự án, phạm vi chức năng, nguyên tắc lập trình, kiến trúc, nghiệp vụ, bảo mật và quy trình làm việc.

### Prompt chính

### Project Instructions for AI

### 1. Project context
Đây là dự án website thương mại điện tử của sinh viên.

### 2. Scope
Chỉ triển khai các chức năng đã được nhóm thống nhất
trong REQUIREMENTS.md.

### 3. Coding principles
- Giữ mã nguồn dễ đọc và dễ bảo trì.
- Không thay đổi kiến trúc lớn khi chưa được nhóm đồng ý.
- Không tự ý xóa chức năng đang hoạt động.
- Ưu tiên thay đổi nhỏ, có thể kiểm tra.

### 4. Workflow
Trước khi sửa mã nguồn:
1. Đọc các tài liệu liên quan.
2. Phân tích hiện trạng.
3. Đề xuất phương án.
4. Chờ nhóm xác nhận.

Sau khi sửa mã nguồn:
1. Giải thích các thay đổi.
2. Nêu file đã sửa.
3. Hướng dẫn chạy và kiểm thử.
4. Báo cáo các giới hạn còn tồn tại.

### 5. Security
- Không đưa mật khẩu, API key hoặc token vào mã nguồn.
- Không tự ý vô hiệu hóa kiểm tra bảo mật.
- Không sử dụng dữ liệu cá nhân thật khi chưa được phép.

### 6. Communication
Nếu yêu cầu chưa rõ, hãy hỏi lại trước khi triển khai.

### Kết quả AI

ChatGPT đã tạo nội dung tài liệu AGENTS.md gồm 13 nhóm hướng dẫn:

1. **Tổng quan dự án:** Mô tả website thương mại điện tử, sản phẩm kinh doanh, khách hàng mục tiêu và mục tiêu hệ thống.
2. **Phạm vi dự án:** Xác định các chức năng dự kiến triển khai và yêu cầu AI tuân thủ REQUIREMENTS.md.
3. **Công nghệ sử dụng:** Hướng dẫn AI kiểm tra cấu hình hiện có, giữ nguyên framework và không tự ý thêm thư viện.
4. **Cấu trúc dự án:** Yêu cầu kiểm tra cấu trúc thư mục trước khi chỉnh sửa, không tự ý di chuyển hoặc đổi tên tệp.
5. **Quy tắc lập trình:** Ưu tiên mã nguồn dễ đọc, dễ bảo trì, tái sử dụng và hạn chế trùng lặp.
6. **Kiến trúc hệ thống:** Giữ kiến trúc hiện tại, không tự ý thay đổi lớn hoặc xóa chức năng đang hoạt động.
7. **Quy tắc nghiệp vụ:** Đưa ra các nguyên tắc liên quan đến sản phẩm, tồn kho, giỏ hàng, đặt hàng, đơn hàng và phân quyền.
8. **Bảo mật:** Không để lộ thông tin bí mật, sử dụng cơ chế băm mật khẩu, kiểm tra dữ liệu đầu vào và hạn chế các rủi ro bảo mật phổ biến.
9. **Quy trình làm việc:** Yêu cầu AI đọc tài liệu, phân tích hiện trạng, đề xuất phương án và chờ xác nhận trước khi sửa mã nguồn; sau khi thực hiện phải báo cáo thay đổi.
10. **Kiểm thử:** Hướng dẫn kiểm tra chức năng sau khi chỉnh sửa và báo cáo kết quả thực tế.
11. **Giao tiếp:** Ưu tiên trao đổi bằng tiếng Việt, hỏi lại khi yêu cầu chưa rõ và giải thích các thay đổi.
12. **Chức năng ngoài phạm vi:** Liệt kê các chức năng không thuộc phạm vi triển khai như thanh toán trực tuyến qua cổng thực tế, tích hợp đơn vị vận chuyển và ứng dụng di động.
13. **Thứ tự ưu tiên:** Ưu tiên yêu cầu trong tài liệu dự án, bảo mật, giữ nguyên kiến trúc và hạn chế thay đổi ngoài phạm vi được duyệt.

### Đánh giá và quyết định của nhóm

Nhóm sử dụng nội dung AI đề xuất làm cơ sở xây dựng tài liệu hướng dẫn cho các công cụ AI hỗ trợ quá trình phát triển website. Nội dung được tham khảo nhằm định hướng AI tuân thủ phạm vi dự án, nguyên tắc lập trình, bảo mật và quy trình làm việc.

Trong quá trình triển khai, nhóm sẽ đối chiếu các hướng dẫn trong AGENTS.md với REQUIREMENTS.md và tình hình thực tế của mã nguồn để điều chỉnh khi cần thiết. Các nội dung chưa phù hợp với phạm vi hoặc chưa được xác nhận sẽ không mặc nhiên được xem là yêu cầu chính thức của dự án.
