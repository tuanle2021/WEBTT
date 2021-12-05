Yêu cầu công nghệ để chạy thử Web server
Cài đặt NodeJs
Cài đặt MongoDB Local(Có thể cài đặt thêm MongoDBCompass một GUI giúp tương tác với data) hoặc sử dụng MongoDB Atlas
Tạo database WEBCTT2(Xem trong file ./source/user-guest/code/config/key.config.js để biết thêm chi tiết)
Tạo các collection có tên trùng với tên file trong thư mục ./source/database
Import *.json tương ứng vào các collection vừa tạo
Đi tới đường dẫn ./source/user-guest/code và gõ lệnh npm install(Tự động cài đặt các package cần thiết để chạy server)
Đi tới đường dẫn ./source/admin/ vã gõ lệnh npm install(Tự động cài đặt các package cần theiest để chạy server)
Khởi chạy server trang web
Khởi chạy server cho trang web của Guest và Người dùng
Đi tới đường dẫn ./source/user-guest/code
Chạy lệnh npm start
Lúc này sẽ có một thông báo xuất hiện trên console cho biết số port mà server đang lắng nghe người dùng connect (cụ thể là port 8000 và có thể được đổi lại trong file app.js)
Mở trình duyệt và truy cập vào đường dẫn http://localhost:8000
Khởi chạy server cho trang web của admin và quản lý rạp chiếu
Đi tới đường dẫn ./source/admin/
Chạy lệnh npm start
Lúc này sẽ có một thông báo xuất hiện trên console cho biết số port mà server đang lắng nghe người dùng connect (cụ thể là port 8001 và có thể được đổi lại trong file app.js)
Mở một trình duyệt khác với trình duyệt đã sử dụng cho server Người dùng(vd: Microsofe Edge and Goolge Chorme) và truy cập vào đường dẫn http://localhost:8001/admin/login