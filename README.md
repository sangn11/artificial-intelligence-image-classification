### Phân loại hình ảnh với bộ dữ liệu từ: CIFAR-10
- 1. Load dữ liệu
- 2. Trực quan hóa
- 3. Tiền xử lý
### Ứng dụng mô hình CNN của DeepLearning
Xây dựng mô hình CNN
- 1. Thêm lớp Conv2D thứ hai
- 2. Thêm lớp MaxPooling để giảm kích thước không gian
- 3. Chuyển đổi đầu ra thành một vector 1 chiều
- 4. Thêm lớp Dense với 512 nút và hàm kích hoạt ReLU
- 5. Thêm lớp Dropout nữa
- 6. Lớp đầu ra với 10 nút, mỗi nút tương ứng với một lớp (10 lớp cho CIFAR-10)
### Kết quả
Thực hiện phân loại trên giao diện - Ứng dụng thư viện có sẵn Gradio
![image](https://github.com/user-attachments/assets/b95cd899-c03b-4e41-941e-fc58666feb0f)
