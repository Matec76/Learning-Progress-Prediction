# [DF26] df dot - Learning Progress Prediction
## 1. Prerequisites

* **Platform:** Google Colab.
* **Hardware Accelerator:** GPU T4.
* **Python:** 3.x (Mặc định của Colab).
* **Dữ liệu:** Cần có tài khoản Google Drive để lưu trữ dataset.

## 2. How to Run

Để tái lập kết quả huấn luyện mô hình, vui lòng làm theo các bước sau:

### Bước 1: Chuẩn bị dữ liệu
1. Tải dữ liệu về máy.
2. Upload thư mục đó lên Google Drive của bạn (ví dụ: tại đường dẫn `MyDrive/DataFlow_TeamX/data`).

### Bước 2: Mở Notebook
Nhấn vào nút **"Open In Colab"** ở trên, hoặc truy cập file:
`notebooks/df_dot-Learning_Progress_Prediction.ipynb`

### Bước 3: Cấu hình GPU T4
Trước khi chạy code, hãy đảm bảo bạn đã bật GPU:
1. Trên menu Colab, chọn **Runtime** > **Change runtime type**.
2. Tại mục **Hardware accelerator**, chọn **T4 GPU**.
3. Nhấn **Save**.

### Bước 4: Chạy Notebook
 Trên menu Colab, chọn **Run all** để chạy tất cả các cell.\
 Note: Thời gian training dự kiến 7 phút.
 
Important: Sửa lại biến `BASE_DIR` trong code nếu bạn lưu data ở thư mục khác.
```python
# Ví dụ trong code:
BASE_DIR = '/content/drive/MyDrive/DataFlow_TeamX/data'
