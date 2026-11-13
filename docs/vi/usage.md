# Hướng dẫn sử dụng

## 1 Bắt đầu

Truy cập [Bing](https://bing.com/search?q=pagetual) và cuộn xuống, trang tiếp theo sẽ tự động được nối vào.

-----

## 2 Thanh phân cách trang

Khi chuyển trang, sẽ có các thanh khoảng trắng nằm giữa các trang. Biểu tượng Thái Cực ở bên trái thanh khoảng trắng dùng để quay lại đầu trang, và biểu tượng ở bên phải dùng để đi đến cuối trang. Từ "Page" ở giữa là liên kết của trang tiếp theo.

### 2.1 Trải nghiệm liền mạch

Thanh phân cách trang có thể được ẩn đi trong trang cấu hình. Bạn có thể có trải nghiệm liền mạch bằng cách ẩn các thanh phân cách và thêm thanh bên (sidebar).

### 2.2 Số trang tùy chỉnh

Nếu có một `pageNum` được thiết lập trong quy tắc hiện tại, bạn có thể nhấp vào số sau chữ `Page` để nhập một số trang để nhảy đến trang đó.

### 2.3 Dừng bộ phân trang

Nhấp vào thanh phân cách trang có thể dừng quá trình phân trang.

-----

## 3 Menu lệnh

Nhấp vào biểu tượng Tampermonkey và bạn sẽ thấy ba tùy chọn dưới "Pagetual".

### 3.1 Cấu hình

Nhấp vào đây để đi đến trang cấu hình, nơi có tất cả các cấu hình cá nhân và tùy chỉnh quy tắc.

### 3.2 Vô hiệu hóa trên trang web này

Nhấp vào đây để vô hiệu hóa Pagetual trên trang web hiện tại.

### 3.3 Buộc tham gia

Nhấp vào đây nếu quy tắc thông minh bị lỗi. Tập lệnh sẽ bật chế độ nối trang bắt buộc, tất cả nội dung trên trang tiếp theo sẽ được nối vào chân trang nếu bạn chọn `join full body` (nối toàn bộ nội dung). Nếu không, Pagetual sẽ tải nội dung động trong một iframe và trả về chúng.

### 3.4 Cập nhật quy tắc trực tuyến

Nhấp vào đây để cập nhật các mục quy tắc bạn đã nhập trực tuyến. Pagetual sẽ tự động cập nhật các quy tắc trực tuyến theo mặc định mỗi hai ngày.

-----

## 4 Cài đặt cá nhân

Sau khi vào trang cấu hình, bạn có thể thực hiện các cài đặt cá nhân, chẳng hạn như giá trị trong suốt của thanh phân cách, viết lịch sử, mở một trang tab mới, và liệu có nên ẩn thanh phân cách khi nhấp đúp hay không, v.v..

Bạn có thể nhập các liên kết quy tắc được viết bởi người khác, hoặc bạn có thể tự tùy chỉnh các quy tắc trong ô nhập liệu. Các quy tắc từ liên kết hỗ trợ sắp xếp và cập nhật nóng. Nhấp vào các mũi tên lên và xuống phía trước liên kết để sắp xếp, và nhấp vào thời gian cập nhật để cập nhật các quy tắc.

### 4.1 Ghi lịch sử

Khi tùy chọn này được bật, Pagetual sẽ ghi URL của trang tiếp theo vào lịch sử mỗi khi bạn chuyển trang. Khi bạn nhấp vào liên kết và quay lại trang trước, nó sẽ quay lại số trang bạn đã duyệt lần trước.

### 4.2 Mở một tab mới

Khi tùy chọn này được bật, tất cả các liên kết được nối vào trang hiện tại sẽ được mở trong các tab mới.

### 4.3 Tải trước trang tiếp theo để tăng tốc độ duyệt web

Khi mở tùy chọn này, Pagetual sẽ tải trước tất cả các hình ảnh trên trang tiếp theo trong khi bạn đang đọc trang hiện tại.

-----

## 5 [Quy tắc tùy chỉnh](/rule.md)
![Custom rules](https://s3.bmp.ovh/imgs/2024/01/10/fa4f00c3e9f77878.gif)

### 5.1 Chọn bằng hình ảnh (Visual grab)

Sau khi nhấp vào `Edit rule for current` (Chỉnh sửa quy tắc cho trang hiện tại), một hộp màu xanh lam sẽ xuất hiện trên trang hiện tại theo con trỏ chuột. Tại thời điểm này, hãy nhấp vào phần tử tương ứng để chọn nội dung bạn muốn nối và chuyển đổi nó thành mã chọn (selector code).

### 5.2 Điều chỉnh bộ chọn

Sau khi bạn đã chọn nội dung chính, di chuột qua mã chọn để mở rộng toàn bộ văn bản. Bạn có thể nhấp vào để chuyển sang nút cha (parent node). Khi bạn nhập thủ công một bộ chọn vào ô nhập liệu, hãy kiểm tra phần tử tương ứng của bộ chọn bằng cách nhấp vào nút kiểm tra `√`.

### 5.3 Bắt đầu chỉnh sửa

Khi bạn đã sẵn sàng, chỉ cần nhấp vào biểu tượng cây bút chì để chuyển đến trang cấu hình và bắt đầu chỉnh sửa quy tắc.

### 5.4 Quy tắc tùy chỉnh đầu tiên của bạn

Ví dụ:

```json
   {
     "name":"beauty", // tên quy tắc
     "url":"^https://www\\.beautyxxx\\.com/", // quy tắc khớp với URL của trang
     "pageElement":"p>img" // Phần tử bạn muốn chèn vào trang tiếp theo
   }
```

Các mục khác có thể được thêm vào tùy theo nhu cầu, chẳng hạn như "bộ chọn cho nút trang tiếp theo", "phương thức chọn phần tử", "khoảng thời gian chuyển trang", v.v..

### 5.5 Di chuyển cửa sổ menu

Kéo và thả tiêu đề menu để di chuyển cửa sổ menu.

### 5.6 Tạm dừng việc chọn bằng hình ảnh

Nhấp vào biểu tượng Thái Cực ở phía bên trái của thanh tiêu đề menu để tạm dừng việc chọn bằng hình ảnh.

### 5.7 Chỉnh sửa nhanh

Nhấp vào biểu tượng 🔽 bên dưới để mở chức năng chỉnh sửa nhanh. Xác minh và sao chép bộ chọn thông qua hộp nhập bộ chọn ở trên, dán nó vào thuộc tính tương ứng, và nhấp vào biểu tượng lưu sau khi hoàn thành.