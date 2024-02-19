# Docker và Docker Compose

## Docker

- Docker là một nền tảng phần mềm dùng để xây dựng, chia sẻ, chạy và xác minh ứng dụng ở bất cứ đâu mà không cần quan tâm đến việc quản lý cấu hình môi trường.
    
    1. Xây dựng: đóng gói ứng dụng cùng tất cả các phụ thuộc của nó vào container.
    2. Chia sẻ: dễ dàng chia sẻ ứng dụng được đóng gói trong container đến các bên khác.
    3. Chạy: cung cấp môi trường chạy độc lập cho ứng dụng.
    4. Xác minh: cung cấp công cụ và quy trình để đảm báo tính đúng đắn và hoạt động của ứng dụng.

## Docker Compose

- Một công cụ thuộc hệ sinh thái của Docker, dùng để định nghĩa, quản lý và triển khai các ứng dụng đa container.

    1. Ứng dụng đa container, trong đó mỗi container có thể giữ vai trò là: frontend, backend, cơ sở dữ liệu, máy chủ cache, ...
    2. Định nghĩa một tệp compose.yaml để quản lý tất cả các container và mối quan hệ giữa chúng.
    3. Tạo ra sự đơn giản, linh hoạt và tiện lợi cho các quy trình xây dựng, kiểm thử và triển khai ứng dụng.

# Unix, Linux, BSD, macOS

## Linux

- Hệ điều hành mã nguồn mở dựa trên kernel Linux.
- Phổ biến trong cả môi trường máy tính cá nhân và máy chủ.
- Nhiều phiên bản như là Ubuntu, Fedora, CentOS.

## BSD

- Hệ điều hành mã nguồn mở dựa trên Unix.
- Gồm nhiều nhánh phát triển như FreeBSD, OpenBSD, NetBSD.
- Thường dùng cho máy chủ và môi trường nghiên cứu.

## Unix

- Hệ điều hành gốc, là cơ sở của Linux và BSD.
- Theo tiêu chuẩn POSIX, đa nhiệm, đa người dùng, giao diện dòng lệnh mạnh mẽ.

## macOS

- Hệ điều hành của Apple được thiết kế cho máy tính cá nhân và máy tính xách tay.
- Dựa trên hạt nhân Unix-like, kết hợp giao diện người dùng đồ họa Aqua.
- Phát triển từ hệ điều hành NeXTSTEP và Unix BSD

# Alpine và Ubuntu

## Alpine

- Hệ điều hành Linux nhẹ, nhỏ gọn, được sử dụng chủ yếu cho các container và môi trường cloud.
- Sử dụng musl libc và BusyBox, tiết kiệm tài nguyên hệ thống và có kích thước nhỏ hơn so với Ubuntu.

## Ubuntu

- Hệ điều hành Linux phổ biến, dùng cho máy tính cá nhân và máy chủ.
- Sử dụng glibc và phần mềm tiêu chuẩn của GNU.
- Cung cấp một hệ thống đầy đủ và đa chức năng.

# VNC

- Virtual Network Computing: một công nghệ cho phép người dùng điều khiển và sử dụng máy tính từ xa qua mạng internet.
- Hoạt động trên mô hình client-server. Máy tính muốn điều khiển gọi là VNC server, thiết bị điều khiển là VNC client.
- VNC sử dụng giao thức RFB (Remote Framebuffer Protocol) để truyền dữ liệu.
- Đây là một công nghệ đa nền tảng, có nhiều phiên bản mã nguồn mở, và có khả năng tùy chỉnh và cấu hình linh hoạt.