# Portfolio năng lực số - Nguyễn Phương Danh

Bộ website tĩnh đã hoàn thiện để đăng lên **GitHub Pages**. Website gồm:

- `index.html`: Trang Giới thiệu
- `projects.html`: Trang Dự án
- `project-1.html` đến `project-6.html`: Chi tiết 6 bài tập
- `summary.html`: Trang Tổng kết
- `reports/`: 6 báo cáo PDF
- `assets/`: giao diện, JavaScript và ảnh minh họa

## Cách xem ngay trên máy tính

Nhấp đúp vào file `index.html`. Website có thể mở trực tiếp mà không cần cài đặt phần mềm.

## Cách đăng lên GitHub Pages - không cần sửa code

### 1. Tạo tài khoản và repository

1. Đăng nhập GitHub.
2. Bấm dấu **+** ở góc trên bên phải → **New repository**.
3. Đặt tên repository, ví dụ: `portfolio-nguyen-phuong-danh`.
4. Chọn **Public**.
5. Bấm **Create repository**.

### 2. Tải toàn bộ website lên

1. Trong repository, chọn **Add file → Upload files**.
2. Giải nén file ZIP của website trước.
3. Kéo **toàn bộ nội dung bên trong thư mục** lên GitHub, gồm `index.html`, các trang HTML, `assets`, `reports`, `README.md`...
4. Không tải nguyên một thư mục bọc bên ngoài; `index.html` phải xuất hiện ngay ở trang chính của repository.
5. Bấm **Commit changes**.

### 3. Bật GitHub Pages

1. Vào **Settings** của repository.
2. Chọn **Pages** ở thanh bên trái.
3. Tại **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Bấm **Save**.
5. Chờ khoảng 1-5 phút và tải lại trang Settings → Pages.

Đường dẫn thường có dạng:

`https://TEN_TAI_KHOAN.github.io/portfolio-nguyen-phuong-danh/`

### 4. Kiểm tra trước khi nộp

- Mở đường dẫn bằng cửa sổ ẩn danh.
- Kiểm tra menu Trang chủ - Dự án - Tổng kết.
- Mở lần lượt 6 trang bài tập.
- Thử nút **Mở báo cáo PDF**.
- Kiểm tra trên điện thoại.

## Cách cập nhật nội dung sau này

Cách đơn giản nhất trên GitHub:

1. Mở file HTML cần sửa.
2. Bấm biểu tượng bút chì **Edit this file**.
3. Sửa phần chữ cần thiết.
4. Bấm **Commit changes**.
5. GitHub Pages tự cập nhật sau ít phút.

## Các thông tin có thể thay đổi nhanh

- Tên, lớp, mã sinh viên: tìm trong `index.html`.
- Phần tự đánh giá: sửa trong `summary.html`.
- Nội dung từng dự án: sửa trong `project-1.html` ... `project-6.html`.
- Ảnh: thay file trong `assets/images/screenshots/` nhưng giữ nguyên tên file để khỏi sửa HTML.
- PDF: thay file trong `reports/` nhưng giữ nguyên tên file.

## Lưu ý về quyền riêng tư

Repository GitHub Pages miễn phí thường để **Public**. Website hiện có tên, lớp và mã sinh viên theo báo cáo. Có thể xóa mã sinh viên khỏi `index.html` nếu không muốn công khai rộng rãi, nhưng nên giữ nếu giảng viên yêu cầu.

## Lỗi thường gặp

- **Trang báo 404:** kiểm tra `index.html` có nằm ở thư mục gốc repository không.
- **Mất ảnh hoặc CSS:** phải tải cả thư mục `assets` lên và không đổi cấu trúc thư mục.
- **PDF không mở:** phải tải cả thư mục `reports` lên.
- **Đã sửa nhưng website chưa đổi:** chờ 1-5 phút, tải lại bằng `Ctrl + F5`.
