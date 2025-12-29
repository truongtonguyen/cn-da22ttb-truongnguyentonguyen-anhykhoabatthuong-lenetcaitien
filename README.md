# cn-da22ttb-truongnguyentonguyen-anhykhoabatthuong-lenetcaitien

### Giới thiệu đề tài
Phát hiện ảnh y khoa bất thường là một trong những hướng nghiên cứu quan trọng trong lĩnh vực trí tuệ nhân tạo, đặc biệt là học sâu (Deep Learning).	Đề tài tập trung vào việc nghiên cứu, triển khai và cải tiến mô hình LeNet – một kiến trúc mạng nơ-ron tích chập (CNN) cổ điển – để phát hiện ảnh y khoa có dấu hiệu bất thường.

### Bộ dữ liệu
Tên dataset: Brain Tumor MRI Dataset

Nguồn: Kaggle Datasets

### Kiến trúc mô hình
Lenet-5:

- 3 lớp Convolution
- 2 lớp Average Pooling
- 2 lớp Fully Connected 
- Activation: Tanh

### Công nghệ sử dụng
- PyTorch
- Kaggle Notebooks

### Các bước thực hiện
- Thu thập dữ liệu
- Chuẩn bị dữ liệu
- Xây dựng mô hình
- Huấn luyện mô hình
- So sánh và đánh giá
- Thử nghiệm

### Các cải tiến
- Dùng ReLU thay cho Tanh để tăng tốc độ hội tụ và giảm vanishing gradient.
- Dùng Max Pooling thay cho Average Pooling để bảo toàn các đặc trưng nổi bật nhất.
- Thêm Batch Normalization sau các lớp tích chập để ổn định và tăng tốc huấn luyện.
- Thêm Dropout vào các lớp Fully Connected để chống overfitting.
- Kỹ thuật hỗ trợ: Tăng cường Dữ liệu. 

======
Trương Nguyễn Tố Nguyên
truongtonhu12@gmail.com
0911048533




