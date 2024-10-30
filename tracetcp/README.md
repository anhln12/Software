Hướng dẫn dùng lệnh tracetcp trên window

* Khái niệm

Tracert là gì ?

Tracert là công cụ dòng lệnh nền tảng Windows dùng để xác định đường đi từ nguồn tới đích của một gói Giao thức mạng Internet (IP – Internet Protocol). Tracert tìm đường tới đích bằng cách gửi các thông báo Echo Request (yêu cầu báo hiệu lại) Internet Control Message Protocol (ICMP) tới từng đích. Sau mỗi lần gặp một đích, giá trị Time to Live (TTL), tức thời gian cần để gửi đi sẽ được tăng lên cho tới khi gặp đúng đích cần đến. Đường đi được xác định từ quá trình này.

* Download thư viện

WinPcap
tracetcp_v1.0.3.zip 

Để sử dụng lệnh bạn vào cmd di chuyển đến thư mục chưa file tracetcp.exe vừa giải nén :
```
cd C:\Users\Administrator\Downloads\tracetcp_v1.0.3\tracetcp_v1.0.3
```
chạy tiếp lệnh :

```
tracetcp.exe xxx.xxx.vn:22
```
