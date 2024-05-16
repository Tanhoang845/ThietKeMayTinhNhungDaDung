# ThietKeMayTinhNhungDaDung
Thiết kế phần cứng máy tính nhúng đa dụng sử dụng chip Quectel SC20 và LAN9512.

Để kế thừa các ưu điểm của các SBC phổ biến có trên thị trường như Beagle
Bon và Raspberry Pi, khắc phục được những nhược điểm khó bảo trì sửa chữa,
thiếu ổn định khi sử dụng Phần cứng chuyên biệt (HAT).Tôi đề xuất một bản thiết
kế sử dụng Dòng chip Quectel SC20 và chip LAN9512 với tính sẵn sàng và ổn
định cao, dễ dàng triển khai trên môi trường thực tế với các chức năng sau:
* Cung cấp tất cả các tính năng cần thiết trên mạch;
* Làm việc với dải điện áp đầu vào rộng (5 - 37V);
* Cung cấp khả năng làm việc với các chân GPIO cấp thấp cũng như các cổng
I/O cấp cao;
* Kết nối được các chuẩn kết nối tầm ngắn (Wifi, Bluetooh), và các chuẩn kết
nối tầm xa (3G/4G);
* Định vị bằng nhiều hệ thống dẫn đường toàn cầu (GNSS).
* Phát triển phần mềm sử dụng bộ phát triển phần mềm cấp cao (Android SDK);
* Cung cấp màn hình hiển thị độ phân giải SD 720p, cảm ứng đa điểm chạm.
* Cung cấp 02 cổng giao tiếp chuẩn USB 2.0;
* Cung cấp kết nối phần cứng mạng có dây theo chuẩn Mạng cục bộ (Ethernet).
