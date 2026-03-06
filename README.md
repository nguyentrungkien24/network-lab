Thiết Kế Hạ Tầng Mạng Trường Học
Giới thiệu

Dự án này mô phỏng hạ tầng mạng của một trường học bằng phần mềm Cisco Packet Tracer.

Hệ thống mạng được thiết kế để kết nối nhiều tòa nhà và phòng ban trong trường, đồng thời đảm bảo khả năng giao tiếp hiệu quả, tính bảo mật và quản lý tập trung.

Mạng bao gồm các thành phần chính như router, switch, access point không dây, server và các thiết bị người dùng.

Mô hình mạng

Hệ thống mạng bao gồm nhiều khu vực trong trường:

Tòa A

Tòa B

Tòa Hành Chính

Thư Viện

Phòng Quản Trị

Kết nối Internet

Mỗi khu vực được kết nối tới switch trung tâm (core switch), sau đó kết nối với router để truy cập Internet.

Các Access Point WiFi được triển khai ở từng tầng để cho phép các thiết bị như điện thoại và laptop kết nối không dây vào mạng.

Các dịch vụ mạng được triển khai
DHCP (Dynamic Host Configuration Protocol)

Dịch vụ DHCP được sử dụng để tự động cấp phát địa chỉ IP cho các thiết bị trong mạng như:

Máy tính (PC)

Laptop

Điện thoại thông minh

Tablet

Việc sử dụng DHCP giúp giảm cấu hình thủ công và đơn giản hóa việc quản lý mạng.

NAT (Network Address Translation)

NAT được cấu hình trên router để cho phép các thiết bị trong mạng nội bộ sử dụng địa chỉ IP riêng có thể truy cập Internet.

Điều này giúp:

Các thiết bị nội bộ truy cập được ra mạng ngoài

Tăng tính bảo mật cho hệ thống mạng nội bộ

VLAN (Virtual Local Area Network)

VLAN được sử dụng để phân chia mạng logic cho các phòng ban khác nhau trong trường học.

Lợi ích của VLAN:

Giảm broadcast trong mạng

Tăng cường bảo mật

Quản lý mạng dễ dàng hơn

Ví dụ các VLAN trong hệ thống:

VLAN dành cho Ban Giám Hiệu

VLAN dành cho Giáo Viên

VLAN dành cho Học Sinh

VLAN dành cho Quản Trị Hệ Thống

ACL (Access Control List)

ACL được sử dụng để tăng cường bảo mật mạng bằng cách kiểm soát lưu lượng truy cập giữa các VLAN và các khu vực trong mạng.

ACL giúp:

Hạn chế truy cập trái phép

Bảo vệ tài nguyên nội bộ

Kiểm soát giao tiếp giữa các phòng ban

Thiết bị mạng sử dụng

Các thiết bị chính trong hệ thống gồm:

Router Cisco (kết nối Internet)

Switch Cisco Layer 2

Access Point WiFi

Server

Máy tính PC và Laptop

Thiết bị di động

Các thiết bị này được kết nối với nhau để mô phỏng một hệ thống mạng doanh nghiệp thực tế.

Các đặc điểm chính của hệ thống mạng

Kết nối nhiều tòa nhà trong trường

Phân chia mạng bằng VLAN

Cấp phát IP tự động bằng DHCP

Cấu hình NAT để truy cập Internet

Áp dụng ACL để tăng cường bảo mật

Triển khai mạng WiFi cho thiết bị di động

Kết quả học được từ dự án

Thông qua dự án này, tôi đã có thêm kinh nghiệm thực hành về:

Thiết kế mô hình mạng

Cấu hình Router và Switch

Triển khai VLAN

Cấu hình DHCP và NAT

Bảo mật mạng bằng ACL

Xử lý sự cố kết nối mạng
