# Phân loại sản phẩm thời trang

Phân loại sản phẩm thời trang là bài toán thuộc lĩnh vực thị giác máy tính và học máy có giám sát. Mục tiêu của bài toán là tự động phân loại các sản phẩm thời trang dựa trên hình ảnh của chúng thành các danh mục đã được định trước.

1. Dataset:
- Kích thước ảnh: 256 x 256 pixels
- Không gian màu: RGB
- Số lượng lớp: 6 (Hand_bag, Dress, Shoes, Hat, Shirt, Trousers)
- Cách thực hiện: Thu thập ảnh trên Internet (tự động và thủ công). Sau đó, thực hiện các thao tác tiền xử lý (xem xét thủ công, resize, ...)

<img width="731" height="484" alt="image" src="https://github.com/user-attachments/assets/400bf6dc-1240-42bf-9d5e-52ef2b439e50" />

2. Source_code:
- Sử dụng ba phương pháp rút trích đặc trưng bao gồm: Histogram of oriented gradient (HOG), Scale-invariant feature transform (SIFT) + Bag of visual word (BOVW) và Scharr operator kết hợp với ba phương pháp máy học để phân loại bao gồm: K-nearest neighbors (KNN), Support vector machine (SVM) và Random forest (RF).
- Demo: sử dụng Streamlit tạo một web demo đơn giản hiển thị kết quả phân loại hình ảnh mới được nhập vào:

<img width="904" height="400" alt="image" src="https://github.com/user-attachments/assets/fca37b70-8207-49f1-9a26-7c31d7e7697b" />
