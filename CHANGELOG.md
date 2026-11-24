# v1.1 – Premium Editor
- Giữ màu, thương hiệu, năm font và các tính năng gốc.
- Canvas chung cho preview và PNG; kích thước chữ quy chiếu khung ngang 350 đơn vị, không phụ thuộc màn hình.
- 42 màu mỗi bảng, nhập HEX, trạng thái màu chọn.
- Căn dọc, lề ngang/dọc, cảnh báo tràn và chặn xuất khi tràn.
- PNG gốc, 2K, 4K (cạnh dài); tạo ảnh trước rồi chia sẻ/tải bằng thao tác riêng.
- Sửa chuyển lại font riêng trong phiên; tăng vùng chạm; cache phiên bản mới.

## v1.1.1
- Nút lưu vào Ảnh iPhone sử dụng Web Share với file PNG, không kèm tiêu đề; không tự tải file khi thiếu hỗ trợ.
- Hướng dẫn lưu bằng nhấn giữ ảnh; giữ tải PNG dự phòng.


### v1.1.2
Cập nhật bộ đếm ngay khi nhập, xử lý compositionend và pageshow, cảnh báo tĩnh nếu trình xem không chạy JavaScript. Cần mở qua Safari HTTPS; không thể bật JavaScript từ HTML trong trình xem bị hạn chế.


## v1.1.3
- Ô nhập đặt cạnh preview; thu nhỏ khung khi focus trên màn hình nhỏ.
- Mẫu gốc nhúng trong HTML, nút áp dụng kiểu mẫu không đổi nội dung; nút thử câu mẫu có xác nhận.
- Màu nền #D9CBBE, chữ #100D0D, Mali (font gợi ý, không xác nhận trùng mẫu), vân giấy tùy chọn dùng chung Canvas.
- Kiểm tra Safari HTTPS trên iPhone thật vẫn cần thực hiện.

## v1.1.4
- Xác nhận áp dụng mẫu ngay dưới nút; bảo toàn nội dung; báo lỗi rõ ràng; vô hiệu hóa nút mẫu cho đến khi JavaScript khởi tạo.
- Không khắc phục được trình xem chặn JavaScript hoặc font mạng không tải.

## v1.1.5
- Chọn ảnh mẫu trực tiếp qua bộ chọn ảnh iOS, dùng chung ảnh tham khảo.
- Giữ tải font thật trong mục thu gọn. Bỏ nút điền nội dung mẫu.


## v1.1.6
- Thêm nút "Áp dụng theo ảnh mẫu" ngay trong khu vực ảnh mẫu chữ viết tay.
- Nhúng ảnh mẫu chuẩn để đối chiếu phong cách trực tiếp trong ứng dụng.
- Đặt lại thiết kế về preset gần giống ảnh mẫu hơn.
- Làm rõ giới hạn: chưa thể tái tạo 100% nét chữ từ ảnh nếu chưa có font gốc hoặc AI tạo font.

## v1.1.7
- Xóa toàn bộ mục Ảnh tham khảo cuối trang và mã xử lý riêng của mục này. Giữ chọn ảnh mẫu và áp dụng preset ở mục kiểu chữ.


## v1.1.8 – Live Preview
- Cập nhật Canvas ngay khi nhập chữ hoặc áp dụng mẫu; tự cuộn tới kết quả khi áp dụng ảnh mẫu.
- Thêm trạng thái xem trước và nút Xem kết quả chữ.
- Giữ nguyên nội dung, preset Mali gần đúng, không có AI tạo font.
- Không khôi phục mục ảnh tham khảo đã xóa.
- Cần Safari HTTPS để nghiệm thu iPhone thực tế.

## v1.1.9
- Đo màu nền/chữ, tỷ lệ, cỡ và bố cục từ ảnh tải lên; font Mali gần đúng. Không nhận diện font AI.


## v1.1.10
- Bỏ tùy chọn vân giấy kem nhẹ; nền phẳng trong Preview và PNG.

## v1.2 experimental
Signature contour renderer; explicit missing glyph handling.

## v1.2.1
Ghép dấu tiếng Việt, dựng Đ/D, làm mượt contour, khoảng dòng theo biên nét, bỏ ô vuông preview.

## v1.2.2
- Xóa nút Áp dụng mẫu mặc định; giữ áp dụng ảnh tải lên.
- Chưa thay đổi bộ nét Signature.

## v1.2.3
Thay toàn bộ font cũ bằng bộ nét vector Form Chữ Viết Tay do người dùng cung cấp. Ký tự ngoài bộ nét dùng chữ hệ thống như bản nguồn.

## v1.2.6
- Bỏ chỉnh lề và vị trí dọc.
- Thêm giao diện trắng/đen, lưu lựa chọn cục bộ.
- Giữ 7 bộ chữ từ v1.2.5.


## v1.2.7
- Header: V/M LETTER căn giữa, bỏ tên và phụ đề cũ, giữ nút theme góc phải.

## v1.2.8
- Sửa lỗi khởi tạo 7 bộ chữ do truy cập canvas #cv không tồn tại.
- Tăng phiên bản cache PWA.
- Kiểm thử Chromium: khởi động, 7 lựa chọn chữ, theme, tự căn, xuất PNG 2K. Chưa kiểm thử Safari thực tế.

## v1.2.9
- Theme chỉ đổi nền ứng dụng trắng/đen, giữ nguyên khung, chữ, màu thiết kế. Biểu tượng mặt trời/trăng có hiệu ứng chuyển.

## v1.2.10
- Sửa thanh khoảng cách dòng: mức tối thiểu an toàn cộng thêm khoảng cách theo thanh kéo, dùng chung cho preview, tự căn và PNG.
- Hỗ trợ cả input và change; tăng phiên bản cache PWA.

## v1.2.11
- Khoảng cách dòng dùng trực tiếp hệ số × cỡ chữ, bỏ phần cộng dư. Mặc định 1.4; phạm vi 1–2.5.

## v1.2.15
- Đo biên nét thực tế, đặt từng dòng theo khoảng an toàn; tự căn giữ giãn dòng và giảm cỡ chữ khi cần.

## v1.2.15
- Nhập tay cỡ chữ, giãn dòng và giãn chữ; đồng bộ thanh kéo, giới hạn giá trị hợp lệ.

## v1.2.16
- Sửa nét ngang Đ, dấu hỏi và dấu ghép; bỏ chấm i khi có dấu thanh phía trên, trên 7 bộ chữ.

## v1.2.17
- Làm rõ dấu tiếng Việt trên 7 bộ vector, tăng khoảng trống dấu kép, giữ nguyên thân chữ.

## v1.3.0
- Icon V/M LETTER, manifest, hướng dẫn cài iPhone, cache offline và cập nhật Netlify. Giữ nguyên engine chữ v1.2.17.

## v1.3.2
- Icon nền đen, chữ trắng V/M LETTER; cập nhật Apple touch icon, manifest và cache PWA.

## v1.3.2
- Thay icon PWA bằng logo ảnh người dùng cung cấp, giữ nguyên màu gốc.
