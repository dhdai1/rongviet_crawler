# RongViet Crawler

## Mô tả

Ứng dụng Python này sử dụng Selenium và BeautifulSoup để thu thập nội dung từ các trang GitBook. Nội dung văn bản và hình ảnh được lưu trữ dưới dạng tệp `.txt` trong thư mục tương ứng với từng domain. Công cụ hỗ trợ xử lý ảnh thông qua AWS Bedrock để trích xuất nội dung.

## Cách cài đặt

### 1. Yêu cầu hệ thống
- Python >= 3.8
- Google Chrome phiên bản <114
- ChromeDriver tương thích với phiên bản Chrome

### 2. Cài đặt môi trường

1. Tải Anaconda hoặc Miniconda để quản lý môi trường Python:
   - [Anaconda Download](https://www.anaconda.com/)
   - [Miniconda Download](https://docs.conda.io/en/latest/miniconda.html)

2. Tạo và kích hoạt môi trường Python:
   ```bash
   conda create -n rongviet_crawler python=3.8
   conda activate rongviet_crawler
   ```

3. Cài đặt các thư viện cần thiết:
   ```bash
   pip install requests beautifulsoup4 selenium webdriver-manager tqdm boto3
   ```

4. Đảm bảo Google Chrome trên máy có phiên bản <114 để tương thích với ChromeDriver. Nếu cần, tải phiên bản cũ từ [Google Chrome Archive](https://google-chrome.en.uptodown.com/windows/versions).

---

## Cách sử dụng

### 1. Cập nhật cấu hình
- Mở tệp mã Python và cập nhật các biến:
  - `list_domain`: Danh sách các domain GitBook cần thu thập dữ liệu.

### 2. Chạy ứng dụng
Thực thi mã Python trong từng Code Block:


---

## Kết quả
- Các tệp `.txt` được tạo hoặc ghi đè trong thư mục tương ứng với từng domain GitBook.
- Nội dung văn bản từ trang web và hình ảnh được lưu trữ đầy đủ.

Nếu gặp lỗi, hãy kiểm tra các bước cài đặt hoặc liên hệ với đội hỗ trợ để được giúp đỡ.

