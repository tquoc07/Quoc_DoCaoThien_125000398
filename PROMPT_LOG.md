# NHẬT KÝ PROMPT ENGINEERING (VIBE CODING LOG)

- **Họ và tên:** [Điền họ tên sinh viên]
- **MSSV:** [Điền mã số sinh viên]
- **Tên đề tài Website:** KFC
- **Công cụ AI đã sử dụng:** ChatGPT
- **Công nghệ sử dụng:** HTML5, CSS3, JavaScript, Animate.css, AOS

## 1. Yêu cầu ban đầu (System/Initial Prompt)

**Prompt đã sử dụng:**

> Hãy xây dựng cho tôi một website giới thiệu các món ăn nổi tiếng tại Việt Nam với giao diện hiện đại, chuyên nghiệp, sử dụng tông màu sáng. Website cần có bố cục rõ ràng, hình ảnh món ăn đẹp, nội dung bằng tiếng Việt, tương thích với máy tính và điện thoại. Sử dụng Semantic HTML5, CSS Variables, Flexbox hoặc CSS Grid, Animate.css, AOS và hiệu ứng hover/focus. Bổ sung chức năng lọc món ăn theo vùng miền và giỏ hàng minh họa bằng JavaScript.

**Kết quả AI tạo ra:**

AI tạo khung website gồm phần đầu trang, thanh điều hướng, khu vực giới thiệu, danh mục ẩm thực ba miền, danh sách món ăn, phần giới thiệu văn hóa ẩm thực và chân trang.

**Nhận xét và tinh chỉnh của sinh viên:**

Tôi định hướng nội dung tập trung vào văn hóa ẩm thực Việt Nam thay vì một website bán đồ gia dụng. Tôi yêu cầu thay đổi hình ảnh, nội dung, tên thương hiệu và các danh mục để phù hợp với đề tài.

## 2. Quá trình tinh chỉnh và giải quyết sự cố (Iteration Iterations)

### Lần 1: Xây dựng cấu trúc Semantic HTML5 và CSS Variables

- **Prompt đã dùng:**

> Hãy tổ chức website bằng các thẻ Semantic HTML5 phù hợp như header, nav, main, section, article và footer. Hạn chế sử dụng div không cần thiết. Khai báo CSS Variables trong :root để quản lý màu sắc, font chữ, khoảng cách và các thuộc tính giao diện dùng chung.

- **Kết quả AI tạo ra:**

Website có phần điều hướng trong header, nội dung chính trong main, các section chia theo chủ đề và footer chứa thông tin cuối trang. CSS Variables được sử dụng để quản lý màu nền, màu chủ đạo, font chữ, bóng đổ và khoảng cách.

- **Nhận xét và tinh chỉnh của sinh viên:**

Tôi kiểm tra cấu trúc HTML và bổ sung biến khoảng cách để giúp việc chỉnh sửa giao diện nhất quán hơn. Các thẻ article được dùng cho những thẻ món ăn và nội dung giới thiệu phù hợp.

### Lần 2: Tích hợp Animate.css và AOS

- **Prompt đã dùng:**

> Tích hợp thư viện Animate.css để tạo hiệu ứng xuất hiện cho nội dung giới thiệu và nút kêu gọi hành động. Tích hợp AOS để các danh mục và thẻ món ăn xuất hiện khi cuộn trang. Hãy sử dụng hiệu ứng vừa phải, không gây rối mắt và hỗ trợ người dùng ưu tiên giảm chuyển động.

- **Kết quả AI tạo ra:**

Animate.css được liên kết qua CDN và áp dụng cho phần giới thiệu. AOS được dùng cho hình ảnh, danh mục, thẻ món ăn và các khối nội dung. JavaScript khởi tạo AOS khi thư viện được tải.

- **Nhận xét và tinh chỉnh của sinh viên:**

Tôi yêu cầu hiệu ứng đồng nhất, không lạm dụng chuyển động. Website có thêm quy tắc CSS `prefers-reduced-motion` để giảm hiệu ứng cho người dùng có tùy chọn hạn chế chuyển động.

### Lần 3: Chuyển nội dung sang ẩm thực Việt Nam

- **Prompt đã dùng:**

> Hãy chuyển nội dung website sang chủ đề các món ăn nổi tiếng tại Việt Nam. Chia nội dung thành ba miền Bắc, Trung, Nam. Giới thiệu phở bò Hà Nội, bún bò Huế, bánh mì Sài Gòn và cơm tấm Sài Gòn. Sử dụng nội dung tiếng Việt tự nhiên, hình ảnh phù hợp và giao diện sáng, tinh tế.

- **Kết quả AI tạo ra:**

Website được đổi tên thành “Hương Vị Việt”, có phần giới thiệu ẩm thực ba miền, thẻ món ăn, giá minh họa và nội dung về văn hóa ẩm thực Việt Nam.

- **Nhận xét và tinh chỉnh của sinh viên:**

Tôi kiểm tra lại tên món ăn, nhãn vùng miền, nội dung giới thiệu và cách trình bày để website thống nhất với đề tài.

### Lần 4: Hoàn thiện tương tác và giao diện responsive

- **Prompt đã dùng:**

> Bổ sung chức năng lọc món ăn theo miền Bắc, miền Trung và miền Nam. Hoàn thiện giỏ hàng demo bằng JavaScript, cập nhật số lượng và tổng tiền. Kiểm tra menu trên điện thoại, hiệu ứng hover/focus và bố cục CSS Grid/Flexbox ở các kích thước màn hình khác nhau.

- **Kết quả AI tạo ra:**

Người dùng có thể lọc món ăn theo vùng miền, thêm món vào giỏ hàng, xem số lượng và tổng tiền minh họa. Menu điều hướng có thể mở trên màn hình nhỏ.

- **Nhận xét và tinh chỉnh của sinh viên:**

Tôi lưu ý rằng giỏ hàng chỉ phục vụ mục đích minh họa, chưa tích hợp cơ sở dữ liệu hoặc cổng thanh toán. Tôi cần kiểm tra các nút, bộ lọc và menu trên trình duyệt trước khi nộp bài.

- **Thách thức gặp phải:**

Các thư viện hiệu ứng được tải từ CDN nên hiệu ứng có thể không chạy nếu kết nối mạng bị gián đoạn. Hình ảnh bên ngoài cũng phụ thuộc vào nguồn cung cấp ảnh.

- **Cách sửa prompt (Debug prompt):**

> Kiểm tra việc khởi tạo AOS khi thư viện đã tải thành công. Không để website phụ thuộc hoàn toàn vào hiệu ứng chuyển động; nội dung chính vẫn phải đọc được khi thư viện không tải. Bổ sung trạng thái focus rõ ràng và quy tắc giảm chuyển động.

## 3. Đánh giá cá nhân về quá trình Vibe Coding

### AI đã giúp tiết kiệm thời gian ở phần nào nhất?

AI giúp tôi xây dựng nhanh cấu trúc HTML, định hình giao diện, viết CSS responsive và triển khai các tương tác JavaScript cơ bản. Nhờ đó, tôi có thể dành nhiều thời gian hơn để kiểm tra nội dung, bố cục và mức độ phù hợp với yêu cầu đề tài.

### Bài học rút ra khi đặt câu hỏi (Prompt) cho AI trong thiết kế web

Tôi nhận thấy prompt càng cụ thể thì kết quả càng sát yêu cầu. Khi giao nhiệm vụ cho AI, cần nêu rõ chủ đề, cấu trúc HTML, công nghệ bắt buộc, phong cách giao diện, chức năng và tiêu chí kiểm tra.

Ngoài ra, không nên chỉ chấp nhận kết quả ban đầu. Cần kiểm tra mã nguồn, thử các chức năng thực tế, phát hiện điểm chưa phù hợp rồi đưa ra prompt tinh chỉnh. AI hỗ trợ quá trình lập trình, nhưng sinh viên vẫn phải hiểu và chịu trách nhiệm về sản phẩm cuối cùng.

## 4. Kết luận

Website “Hương Vị Việt” được xây dựng nhằm giới thiệu những món ăn nổi tiếng của Việt Nam và nét đặc trưng của ẩm thực ba miền. Quá trình Vibe Coding giúp tôi hiểu hơn cách sử dụng AI để phát triển giao diện web, kết hợp Semantic HTML5, CSS Variables, Flexbox/Grid và các thư viện hiệu ứng.

**Lưu ý:** Cần tự kiểm tra sản phẩm trên trình duyệt, cập nhật họ tên và MSSV, đồng thời điều chỉnh nhật ký để phản ánh chính xác quá trình làm bài thực tế trước khi nộp.