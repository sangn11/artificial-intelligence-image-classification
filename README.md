### Phân loại hình ảnh với bộ dữ liệu từ: CIFAR-10
- Load dữ liệu
- Trực quan hóa
![image](https://github.com/user-attachments/assets/d5fe92a4-3532-4be7-a281-595823c43a03)
- Tiền xử lý
### Ứng dụng mô hình CNN của DeepLearning
Xây dựng mô hình CNN
- Thêm lớp Conv2D thứ hai
- Thêm lớp MaxPooling để giảm kích thước không gian
- Chuyển đổi đầu ra thành một vector 1 chiều
- Thêm lớp Dense với 512 nút và hàm kích hoạt ReLU
- Thêm lớp Dropout nữa
- Lớp đầu ra với 10 nút, mỗi nút tương ứng với một lớp (10 lớp cho CIFAR-10)
### ![image](https://github.com/user-attachments/assets/bec8b215-2b78-4028-848a-54f243790f7a)
### Điểm Acc: 0.8989
### ![image](https://github.com/user-attachments/assets/c1cf8006-7b1c-47fb-a863-2977829e0aa6)
### Thực hiện dự đoán trên tập kiểm tra
### ![image](https://github.com/user-attachments/assets/555725d0-360a-4cf7-8cc4-2ba31c9eef37)
### Kết quả
Thực hiện phân loại trên giao diện - Ứng dụng thư viện có sẵn Gradio
- Load mô hình
- Viết hàm phân loại
- Xây dựng giao diện
- Results:
![image](https://github.com/user-attachments/assets/b95cd899-c03b-4e41-941e-fc58666feb0f)
