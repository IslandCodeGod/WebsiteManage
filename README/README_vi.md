# Ứng dụng Flask Web - Hệ thống quản trị website doanh nghiệp (phiên bản mã hóa)

## Giới thiệu dự án

Đây là **phiên bản được mã hóa** của hệ thống quản lý trang web doanh nghiệp được phát triển dựa trên khung Flask. Mã lõi đã được PyArmor làm xáo trộn và mã hóa để bảo vệ quyền sở hữu trí tuệ.Hệ thống hỗ trợ đa ngôn ngữ (tiếng Trung và tiếng Anh), xác thực người dùng, quản lý sản phẩm và tin tức, hiển thị thông tin công ty và các chức năng khác.

## Ảnh chụp màn hình ứng dụng

Sau đây là ảnh chụp màn hình giao diện chính của ứng dụng:

### Trang chủ
![首页](screenshots/index.png)

### Nền tảng quản lý
![管理后台](screenshots/admin_dashboard.png)

## Ghi chú phát hành

Phiên bản này là phiên bản mã hóa cơ bản cung cấp các chức năng quản lý trang web công ty hoàn chỉnh.Nếu bạn cần:

- **Phiên bản mã nguồn hoàn chỉnh**: Chứa mã nguồn hoàn chỉnh không được mã hóa để hỗ trợ phát triển thứ cấp
- **Phát triển chức năng tùy chỉnh**: Tùy chỉnh và mở rộng chức năng theo nhu cầu cụ thể của bạn
- **Dịch vụ hỗ trợ kỹ thuật**: Nhận dịch vụ hỗ trợ và bảo trì kỹ thuật chuyên nghiệp

Vui lòng liên hệ với chúng tôi qua thông tin liên hệ bên dưới và chúng tôi sẽ cung cấp cho bạn kế hoạch và báo giá chi tiết.

## Tính năng mã hóa

- **Bảo vệ mã**: Các tệp Python lõi (app.py, init_db.py, models.py) bị xáo trộn và mã hóa
- **Bảo vệ thời gian chạy**: Sử dụng môi trường thời gian chạy PyArmor để ngăn mã bị dịch ngược
- **Đầy đủ chức năng**: Mã được mã hóa duy trì tất cả các chức năng và tính năng ban đầu
- **Hỗ trợ đa ngôn ngữ**: tích hợp chức năng chuyển đổi tiếng Trung và tiếng Anh

## Bao gồm các tập tin

```
/
├── app.py                  # Mục nhập ứng dụng chính được mã hóa
├── init_db.py              # Tập lệnh khởi tạo cơ sở dữ liệu được mã hóa
├── models.py               # Mô hình dữ liệu được mã hóa
├── babel.cfg               # Cấu hình quốc tế hóa Babel
├── pyarmor_runtime_000000/ # Tệp hỗ trợ thời gian chạy PyArmor
├── static/                 # Tệp tài nguyên tĩnh (CSS, JS, hình ảnh)
├── templates/              # Tệp mẫu HTML
├── translations/           # Tập tin dịch đa ngôn ngữ
└── instance/               # Thư mục cơ sở dữ liệu (được tạo tự động trong lần chạy đầu tiên)
```

## Bắt đầu nhanh

### Yêu cầu về môi trường

- Python 3.9 trở lên
- Các gói phụ thuộc đã cài đặt:
- Bình 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Flask-Đăng nhập 0.6.3+
- Bình-Babel 4.0.0+
- Werkzeug 3.0.1+

### Cài đặt phụ thuộc

Nếu các phần phụ thuộc bắt buộc chưa được cài đặt, vui lòng cài đặt chúng trước:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Chạy ứng dụng

1. **Khởi tạo cơ sở dữ liệu**

Trước khi chạy lần đầu tiên, cơ sở dữ liệu cần được khởi tạo:

```bash
   python init_db.py
   ```

2. **Khởi chạy ứng dụng**

```bash
   python app.py
   ```

3. **Truy cập ứng dụng**

Mở trình duyệt và truy cập: http://127.0.0.1:5000

## Hướng dẫn sử dụng

### Truy cập trang web

1. Mở trình duyệt và truy cập http://127.0.0.1:5000
2. Sử dụng nút chuyển đổi ngôn ngữ ở góc trên bên phải để chuyển đổi giữa tiếng Trung và tiếng Anh

### Nền tảng quản lý

1. Truy cập http://127.0.0.1:5000/admin/login
2. Đăng nhập bằng tài khoản quản trị viên (tên người dùng và mật khẩu mặc định: admin/admin123)
3. Sản phẩm, tin tức và thông tin công ty có thể được quản lý trong nền tảng quản lý

## Mô tả chức năng

### Chức năng giao diện người dùng

- **Trang chủ**: Hiển thị thông tin công ty và sản phẩm chính
- **Giới thiệu**: Hiển thị thông tin chi tiết về công ty
- **Hiển thị sản phẩm**: Duyệt qua tất cả danh sách sản phẩm
- **Cập nhật ngành**: Xem tin tức và thông tin mới nhất
- **Chuyển đổi ngôn ngữ**: Hỗ trợ chuyển đổi giữa tiếng Trung và tiếng Anh

### Quản lý các chức năng nền

- **Quản lý sản phẩm**: Thêm, sửa, xóa sản phẩm
- **Quản lý tin tức**: Đăng, sửa, xóa tin
- **Thông tin công ty**: Cập nhật thông tin cơ bản về công ty
- **Xác thực người dùng**: hệ thống đăng nhập an toàn

## Hướng dẫn chụp ảnh màn hình

Để có được hiệu ứng hiển thị README tốt nhất, nên tạo và thêm ảnh chụp màn hình theo hướng dẫn sau:

1. **Tạo thư mục ảnh chụp màn hình**: Tạo thư mục `screenshots/` trong thư mục `dist/`
2. **Kích thước ảnh chụp màn hình**: Sử dụng ảnh chụp màn hình có độ phân giải 1920x1080 hoặc 1366x768 để đảm bảo hiển thị rõ ràng nội dung
3. **Nội dung ảnh chụp màn hình**:
- Trang chủ: Hiển thị giao diện trang chủ hoàn chỉnh, bao gồm thanh điều hướng và vùng nội dung chính
- Chuyển đổi ngôn ngữ: Hiển thị hiệu ứng so sánh của việc chuyển đổi giữa tiếng Trung và tiếng Anh (có thể sử dụng ảnh chụp màn hình chia đôi)
- Trưng bày sản phẩm: hiển thị danh sách sản phẩm và chi tiết từng sản phẩm
- Trang tin tức: hiển thị danh sách tin tức và chi tiết tin tức
- Quản lý backend: hiển thị bảng điều khiển và giao diện chức năng sau khi quản trị viên đăng nhập
4. **Định dạng ảnh chụp màn hình**: Sử dụng định dạng PNG để có chất lượng tốt nhất
5. **Đặt tên tệp**: Lưu ảnh chụp màn hình theo tên tệp được chỉ định trong README (index.png, ngôn ngữ_switch.png, v.v.)

## Ghi chú

1. **Tính toàn vẹn của tệp**: Vui lòng đảm bảo rằng tất cả các tệp đã được tải xuống chính xác, đặc biệt là thư mục `pyarmor_runtime_000000` và nội dung của nó

2. **Tệp cơ sở dữ liệu**:
- File cơ sở dữ liệu sẽ được tạo tự động trong thư mục `instance`
- Nếu bạn cần sao lưu dữ liệu, vui lòng sao lưu file `instance/site.db` thường xuyên

3. **Hỗ trợ đa ngôn ngữ**:
- Tất cả file dịch đều nằm trong thư mục `translation`
- Để thêm ngôn ngữ dịch mới, vui lòng tham khảo tài liệu dự án gốc

4. **Môi trường hoạt động**:
- Đảm bảo phiên bản Python không thấp hơn 3.9
- Đảm bảo tất cả các phụ thuộc cần thiết đã được cài đặt

5. **Mẹo an toàn**:
- Khi triển khai vào môi trường sản xuất, vui lòng thay đổi mật khẩu quản trị viên mặc định.
- Cân nhắc sử dụng máy chủ WSGI (chẳng hạn như Gunicorn) thay vì máy chủ phát triển
- Cấu hình các quy tắc tường lửa thích hợp

## Đề xuất triển khai

### Môi trường phát triển

Sử dụng máy chủ phát triển tích hợp Flask (hiển thị trong phần khởi động nhanh ở trên).

### Môi trường sản xuất

1. **Sử dụng máy chủ WSGI**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Sử dụng proxy ngược**:
- Định cấu hình Nginx hoặc Apache làm proxy ngược
- Thiết lập chứng chỉ SSL để kích hoạt HTTPS

3. **Tối ưu hóa cơ sở dữ liệu**:
- Cân nhắc sử dụng PostgreSQL hoặc MySQL thay vì SQLite
- Cấu hình cơ chế sao lưu thường xuyên

## Khắc phục sự cố

### Câu hỏi thường gặp

1. **Không thể khởi động ứng dụng**:
- Kiểm tra phiên bản Python có đáp ứng yêu cầu không
- Xác nhận rằng tất cả các gói phụ thuộc đã được cài đặt chính xác
- Kiểm tra xem thư mục `pyarmor_runtime_000000` có tồn tại và đầy đủ không

2. **Chuyển đổi ngôn ngữ không hoạt động**:
- Xác nhận rằng thư mục `translation` và nội dung của nó đã hoàn tất
- Kiểm tra xem cài đặt Cookies của trình duyệt có được phép không

3. **Lỗi kết nối cơ sở dữ liệu**:
- Xác nhận rằng thư mục `instance` tồn tại và có quyền ghi
- Thử chạy lại `init_db.py` để khởi tạo cơ sở dữ liệu

### Xem nhật ký

Khi ứng dụng khởi động, thông tin nhật ký sẽ được xuất ra trên bảng điều khiển. Nếu gặp sự cố, bạn có thể kiểm tra các nhật ký này để biết thêm thông tin.

## Giấy phép

[MIT License](LICENSE)

## Thông tin liên hệ

Nếu bạn có bất kỳ thắc mắc, góp ý hoặc cần phát triển phiên bản đầy đủ/chức năng tùy chỉnh, vui lòng liên hệ qua các phương pháp sau:

- **Email**: austinlive666@gmail.com (được khuyến nghị)
- **Bất hòa**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Cảm ơn bạn đã sử dụng dự án này!