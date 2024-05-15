Hoàng Tràn Phâu
K56KMT.01
MSSV: K205480106022

Hệ thống hiển thị vị trí dựa trên gg map:
1. Giới Thiệu
Mục tiêu: Cung cấp khả năng định vị và hiển thị vị trí người dùng trên website sử dụng Google Maps API.
2. Cơ Sở Dữ Liệu
Bảng Location:
id (INT),user_id (INT),latitude (DECIMAL),longitude (DECIMAL),address (TEXT),timestamp (TIMESTAMP)
3. Module đọc dữ liệu: Sử dụng Python và FastAPI để tạo một API để lấy dữ liệu từ google map plasform

 MÔ TẢ NGUỒN DỮ LIỆU 
 -Sử dụng Python và FastAPI để tạo một API để lấy dữ liệu từ Google Maps Platform.

 -Google Maps Platform cung cấp các dịch vụ API để làm việc với dữ liệu địa lý, bao gồm lấy vị trí, định vị địa chỉ, tìm đường đi, và nhiều tính năng khác.
 
 -Dữ liệu trả về từ Google Maps API thường là dạng JSON và bao gồm các thông tin như vị trí, địa chỉ, điểm quan trọng, v.v.
5. Giao diện web.
- Xây dựng một ứng dụng web để hiển thị vị trí của người dùng 
- Có thể phát triển thêm các chức năng như chỉ đường phục vụ người dùng
