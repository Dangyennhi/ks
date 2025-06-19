1.🔐 Giới thiệu: Ứng dụng Web Ký Số RSA
Ứng dụng ký số web RSA cung cấp giao diện đơn giản để người dùng:

Chọn file dữ liệu (văn bản hoặc hình ảnh)

Nhập cặp khóa riêng/tư

Thực hiện ký số và xác thực chữ ký

Sử dụng thuật toán RSA với các bước rõ ràng:

Ký số: Băm nội dung → mã hóa bằng khóa riêng → tạo chữ ký số

Xác minh: Băm lại nội dung → giải mã chữ ký bằng khóa công khai → đối chiếu

2.✅ Chức năng chính
Ký số tệp tin: Đọc nội dung file, tạo hàm băm SHA-256 và mã hóa bằng khóa riêng để tạo chữ ký.

Xác minh chữ ký: Tải file và chữ ký lên, nhập khóa công khai để kiểm tra chữ ký.

Hiển thị kết quả: Kết quả ký và xác thực sẽ hiển thị trực tiếp trên giao diện.

3.🛠️ Công nghệ sử dụng

  Thành phần	Công nghệ
  
  Ngôn ngữ chính	Python
  
  Framework Backend	Flask
  
  Mã hóa	PyCryptodome (RSA + SHA-256)
  
  Giao diện	HTML, CSS, JavaScript
  4. Giao diện 
  ![image](https://github.com/user-attachments/assets/a220643e-e5a3-4055-b789-90e408cbeba9)
  Giao diện xác thực ký số 
