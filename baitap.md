1.Backend/Server hoạt động như thế nào?

- Cung cấp cho client 1 mã cookie để phân biện người dùng
- Lưu trữ thông tin đăng nhập vào section và lưu trữ ở RAM server
- Lưu trữ dữ liệu lên hệ thống database
  => Nhận request từ phía client, xử lí logic và trả dữ liệu cho người dùng
  2.Http protocol
- Là cách thức website truyền tải trên internet
- HTTP là 1 giao thức cho phép tìm nạp tài nguyên
  3.Mô hình client-server
- Là một kiến trúc phần mềm mạng, trong đó Server cung cấp dịch vụ hoặc tài nguyên cho Client
  Các thành phần chính:
  Client (Máy khách): Là máy tính hoặc thiết bị sử dụng dịch vụ hoặc tài nguyên từ máy chủ. Các máy khách thường yêu cầu thông tin hoặc tài nguyên từ máy chủ bằng cách gửi các yêu cầu thông qua mạng. Ví dụ, một trình duyệt web trên máy tính cá nhân là một client khi nó gửi yêu cầu để tải một trang web từ máy chủ web.
  Server (Máy chủ): Là máy tính hoặc thiết bị cung cấp dịch vụ hoặc tài nguyên cho các máy khách. Máy chủ lắng nghe các yêu cầu từ các máy khách và phản hồi bằng cách cung cấp dữ liệu hoặc thực hiện các chức năng được yêu cầu. Ví dụ, một máy chủ web chứa các trang web và phản hồi với dữ liệu HTML khi nhận yêu cầu từ các trình duyệt web.
  Network (Mạng): Là phương tiện truyền thông cho các máy khách và máy chủ để giao tiếp với nhau.
  Protocol (Giao thức): Là các quy tắc và quy định được sử dụng để truyền thông giữa máy khách và máy chủ. Các giao thức thông dụng trong mô hình client-server: HTTP (cho truy cập web)
  4.Server side rendering
- SSR là quá trình tạo ra và gửi các trang web hoặc ứng dụng từ phía máy chủ trước khi chúng được gửi đến máy khách (trình duyệt). Điều này đảm bảo rằng người dùng nhận được nội dung trang web nhanh chóng và giúp cải thiện SEO bởi vì các công cụ tìm kiếm có thể dễ dàng lập chỉ mục nội dung
  5.API là viết tắt của "Application Programming Interface", đó là một tập hợp các quy tắc và công cụ cho phép các ứng dụng và dịch vụ khác nhau tương tác và giao tiếp với nhau. Các loại API bao gồm Web APIs (dành cho việc tương tác qua internet), Library APIs (tập hợp các hàm và phương thức cho phát triển ứng dụng), và Operating System APIs (để tương tác với hệ điều hành). API giúp giảm thời gian và công sức cần thiết để phát triển phần mềm và tạo ra các ứng dụng phức tạp bằng cách kết hợp các chức năng từ các nguồn khác nhau.
