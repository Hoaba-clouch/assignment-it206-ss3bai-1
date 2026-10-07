# [Vận dụng cơ bản] BẮT LỖI BACKLOG CỦA THỰC TẬP SINH

## Phần 1 - Phân tích

Dưới đây là bảng phân tích hiện trạng bảng Trello của đội RikkeiGo:

| Hạng mục | Đúng/Sai | Vi phạm tiêu chí/quy tắc nào | Lý do (1 câu) |
|---|---|---|---|
| H1. Thẻ trên cùng cột Product Backlog: "Làm tính năng đi ghép" — chỉ có tiêu đề, không mô tả. | Sai | Tiêu chí D (Detailed Enough) của D.E.E.P. | Thẻ ở vị trí ưu tiên cao nhất nhưng thiếu mô tả chi tiết cần thiết để Developers có thể làm việc. |
| H2. Thẻ thứ 2 "Đổi màu giao diện theo mùa lễ hội" nằm trên thẻ thứ 3 "Tự động chia tiền cho các khách đi ghép". | Sai | Tiêu chí P (Prioritized) của D.E.E.P. | Thẻ "Đổi màu giao diện" có giá trị kinh doanh thấp hơn nhưng lại được ưu tiên cao hơn thẻ "Tự động chia tiền cho các khách đi ghép". |
| H3. Thẻ cuối cột: "Khách đánh giá bạn đi ghép" — chỉ có tiêu đề ngắn, kèm ước lượng sơ bộ "lớn". | Đúng | — | Thẻ ở cuối Product Backlog không yêu cầu chi tiết cao, có tiêu đề ngắn và ước lượng sơ bộ là phù hợp với tiêu chí D.E.E.P cho một hạng mục ưu tiên thấp. |
| H4. Tú tự thêm thẻ "Tối ưu tốc độ tải bản đồ" và kéo lên đầu cột Product Backlog vì thấy cần làm gấp. | Sai | Quy tắc nghiệp vụ về quyền sở hữu Product Backlog. | Developers (Tú) không có quyền tự ý thêm thẻ và sắp xếp thứ tự trong Product Backlog; đây là trách nhiệm của Product Owner. |
| H5. Bảng chỉ có 4 cột: Product Backlog → Sprint Backlog → In Progress → Done; thẻ code xong được kéo thẳng sang Done. | Sai | Luồng cột trên bảng Trello và quy tắc "chỉ thẻ đạt tiêu chuẩn 'xong' mới vào Done". | Thiếu các bước kiểm thử/đánh giá trung gian trước khi chuyển sang Done, và việc kéo thẳng thẻ "code xong" sang Done bỏ qua quy trình kiểm tra chất lượng. |

## Phần 2 - Sửa lỗi

Dưới đây là các hạng mục đã được sửa lại và các cột của bảng Trello đúng chuẩn:

*   **H1. Sửa:** Thẻ "Làm tính năng đi ghép" cần được bổ sung mô tả chi tiết về chức năng tìm kiếm, tạo và tham gia chuyến xe ghép.
*   **H2. Sửa:** Thẻ "Tự động chia tiền cho các khách đi ghép" phải được ưu tiên cao hơn thẻ "Đổi màu giao diện theo mùa lễ hội" trong Product Backlog.
*   **H3. Sửa:** Hạng mục này đã đúng chuẩn, không cần sửa đổi.
*   **H4. Sửa:** Product Owner là người duy nhất có quyền thêm thẻ "Tối ưu tốc độ tải bản đồ" vào Product Backlog và xác định vị trí ưu tiên của thẻ đó.
*   **H5. Sửa:** Cấu trúc bảng Trello đúng chuẩn cần có các cột: Product Backlog → Sprint Backlog → In Progress → Review/Test → Done.