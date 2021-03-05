## Tiêu đề : xây dựng một trang collection mới

## Giới thiệu : 
- Dựa vào trang collection mẫu là https://juno.vn/collections/happy-sale tạo 1 trang template collection tương tự.

## Chi tiết

- Tạo các file mới là : collection.salepage.bwt ở templates và salepage-collection.css, product_grid_office_1.bwt, product_grid_office_1_css.css ở snippets 

- Hoàn thành dựng layout và reponsive.
- Chưa hoàn thành : các hàm chức năng.


- Hiện vẫn đang chưa tìm được cách filter products và nút mở rộng.

Ý tưởng cho các chức năng 
- Filter : lấy tên tag hay type cần filter và id collection sau đó gọi api theo collection và type, dùng javascript để ghi đè HTML.
- show more : lấy danh sách sản phẩm theo collection và filter và phân trang. mỗi lần click sẽ gọi api của trang tiếp theo.