# HOCSAU

## Bài Lab: Deep Learning với PyTorch

### Công nghệ sử dụng
- **PyTorch**: Thư viện chính cho deep learning, được sử dụng để tạo và thao tác với tensors, tính toán gradient, và xây dựng mô hình học máy.
- **NumPy**: Thư viện cho tính toán số học, được sử dụng để tạo mảng và xử lý dữ liệu số.
- **Pandas**: Thư viện cho phân tích dữ liệu, được sử dụng để đọc và xử lý tập dữ liệu Iris từ file CSV.
- **Matplotlib**: Thư viện vẽ đồ thị, được import nhưng không sử dụng trực tiếp trong notebook này.
- **Scikit-learn**: Thư viện học máy, được sử dụng cho LabelEncoder và train_test_split để chuẩn bị dữ liệu.

### Cách hoạt động
Notebook này giới thiệu các khái niệm cơ bản của PyTorch thông qua các phần sau:

1. **PyTorch Basic**: Kiểm tra tính khả dụng của CUDA và import PyTorch.
2. **Dataset với PyTorch**: Đọc tập dữ liệu Iris từ file CSV, tiền xử lý dữ liệu (mã hóa nhãn, chia train/test), và chuyển đổi sang tensors của PyTorch.
3. **Tính toán Gradient**: Sử dụng autograd của PyTorch để tính đạo hàm của các hàm số đơn giản.
4. **Bài tập về nhà (BTVN)**:
   - BTVN 1: Tính đạo hàm của đa thức tại một điểm cụ thể.
   - BTVN 2: Áp dụng Gradient Descent để tối ưu hóa hàm số.
   - BTVN 3: Xây dựng mô hình Linear Regression đơn giản và huấn luyện bằng Gradient Descent.
   - BTVN 4: Giải thích sự khác biệt giữa `torch.from_numpy` và `torch.tensor`.
   - BTVN 5: Tạo các loại tensor khác nhau (empty, zeros, ones, random) và reshape chúng.

Mỗi phần bao gồm code mẫu và giải thích, với các bài tập thực hành để củng cố kiến thức.

### Kết quả
- **Kiểm tra CUDA**: Xác nhận GPU khả dụng (hoặc không).
- **Xử lý dữ liệu Iris**: Hiển thị shape của dữ liệu, phân phối nhãn, và chuyển đổi thành tensors.
- **Tính Gradient**: Tính đạo hàm của các hàm số, ví dụ: đạo hàm của 5x^5 + 6x^3 - 3x + 1 tại x=2.
- **Gradient Descent**: Cập nhật giá trị x qua 10 vòng lặp, hiển thị sự thay đổi của x và gradient.
- **Linear Regression**: Huấn luyện mô hình với 100 epochs, hiển thị loss giảm dần và các tham số w, b hội tụ về giá trị thực (khoảng 3 và 5).
- **Tensor Operations**: Tạo và hiển thị các tensor với các giá trị khác nhau, và reshape chúng.

Các kết quả được in ra trực tiếp trong notebook, bao gồm giá trị tensors, gradients, và loss qua các epochs.

### Giao diện web xuất kết quả
Không có yêu cầu giao diện web trong bài lab này. Kết quả được hiển thị trực tiếp trong Jupyter Notebook.
