# rongviet_crawler

Bước 1: Tải Anaconda hoặc Miniconda để tạo môi trường Python. Activate môi trường đó

Bước 2: Cài đặt các thư viện cần thiết
Chạy lệnh sau để cài đặt các thư viện Python cần thiết:

pip install requests beautifulsoup4 selenium webdriver-manager tqdm boto3

Bước 2: Cài đặt phiên bản Chrome tương thích với ChromeDriver
Đảm bảo Google Chrome trên máy bạn có phiên bản dưới 114 để tương thích với ChromeDriver.
Nếu cần, tải phiên bản Chrome cũ từ Google Chrome Archive.

Bước 3: Cấu hình AWS để sử dụng Bedrock
Đảm bảo bạn đã cấu hình tài khoản AWS với quyền truy cập Bedrock.
Cài đặt AWS CLI và chạy lệnh sau để cấu hình:
aws configure

Nhập các thông tin sau:
AWS Access Key ID
AWS Secret Access Key
Default region name

Bước 4: Cập nhật các biến cấu hình
Mở tệp mã và cập nhật các biến sau:
list_domain: Danh sách các domain GitBook cần thu thập dữ liệu.

Bước 5: Chạy mã trong Notebook
Kết quả
Các tệp .txt được tạo hoặc ghi đè trong thư mục tương ứng với từng domain GitBook.
Nội dung văn bản từ trang web và hình ảnh sẽ được lưu vào các tệp này.
