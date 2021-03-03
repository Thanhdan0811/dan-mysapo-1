## Tiêu đề : thực hiện yêu cầu 1 tạo sản phẩm 

## Giới thiệu : Tạo sản phẩm với các thông tin như mẫu sau

https://ega-women-shoes.mysapo.net/giay-de-xuong-01-test-dac-biet

## Chi tiết :
- Thực hiện thêm theme base test vào trang.
- Tiếp tục tạo sản phẩm có các phiên bản tương tự như link ở trên
- Do có 1 số phiên bản không có sản phẩm (đánh dấu X như trong link sản phẩm mẫu) : với theme mới khi tạo và nếu click vào sẽ bị báo lỗi.
- Khắc phục : ở file product.bwt dòng 446 đặt thêm điều kiện if để fix lỗi.
- Khi chọn các sản phẩm đã hết hàng trong kho, sẽ hiện lên 1 cửa sổ alert. Để tắt cửa sổ alert ta cũng sẽ sửa trong file product.bwt ở dòng 872 