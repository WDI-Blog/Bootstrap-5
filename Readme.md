# Bootstrap 5

## Câu lệnh cài đặt bootstrap bằng npm

> https://www.youtube.com/watch?v=I7CfaDYzTVM

- npm init -y
- npm i bootstrap@next
- npm i bootstrap-icons
- npm i popper.js

## Nhúng Bootstrap vào trong dự án

```
Tạo file main.scss sau đó @import file bootstrap.scss vào.

Tiến hành chỉnh sửa file settings.json của extension Watch SASS.Thêm nội dụng sau để thay đổi vị trí thư mục chứa file .css :

"liveSassCompile.settings.formats" : [
  {
    "format" : "compressed",
    "extensionName" : ".css",
    "savePath" : "/css"
  }
],

Nhấn nút Watch Sass để biên dịch

Nhúng file .css vào trong file index.html
```

## Tổng hợp kiến thức

> Học cách cài đặt Bootstrap thông qua npm

#

> Chỉnh sửa giá trị mặc định của Boostrap

#

> Tự tạo ra những giá trị mới kèm class để gọi ra sử dụng khi cần

#

> Ôn tập một chút kiến thức về SASS --> tạo file \_style.scss và dẫn vào trong file chính main.scss để sử dụng.

# Học cách deploy dự án lên trên Netlify

> https://www.youtube.com/watch?v=bjVUqvcCnxM&t=960s

#

> Đưa file dự án lên Github sau đó kết nối tới Netlify.

#

> Thay đổi tên domain cho website bằng cách tạo hai bản ghi

```
Tên @ - Loại A - Dữ liệu 104.198.14.52

Tên www - Loại CNAME - dữ liệu là đường link đến Netlify của website ví dụ :
compassionate-panini-35e65b.netlify.app.
```

> Thiết lập HTTPS ở cùng trang với thiết lập domain.
