Dưới đây là phiên bản được thiết kế lại của file **README** với bố cục rõ ràng và chuyên nghiệp hơn:  

---

# **MEDICINE PILL IMAGE RECOGNITION**  

### **1. Giới thiệu**  
**Medicine Pill Image Recognition** là ứng dụng trí tuệ nhân tạo hỗ trợ nhận diện thuốc từ hình ảnh và trích xuất thông tin từ đơn thuốc bằng công nghệ thị giác máy tính và nhận diện ký tự quang học (OCR).  

**Mục tiêu chính**:  
- Tự động nhận diện thuốc dựa trên hình ảnh.  
- Trích xuất thông tin văn bản từ đơn thuốc.  
- Đối chiếu thông tin thuốc với đơn thuốc để giảm thiểu sai sót.  

---

### **2. Thành viên nhóm thực hiện**  
- **Lâm Hưng Nguyên** - 2250968  
- **Lê Cảnh Nhật** - 22521016  

---

### **3. Cài đặt môi trường**  

#### **Bước 1: Tải mã nguồn**  
Sao chép hoặc tải mã nguồn từ kho lưu trữ.  

```bash
git clone <repository_link>
cd path/to/source
```

#### **Bước 2: Tạo môi trường ảo**  
```bash
python -m venv venv
```

#### **Bước 3: Kích hoạt môi trường ảo**  
- Trên Windows:  
```bash
.\venv\Scripts\activate
```
- Trên Linux/MacOS:  
```bash
source venv/bin/activate
```

#### **Bước 4: Cài đặt các thư viện cần thiết**  
```bash
pip install -r requirements.txt
```

#### **Bước 5: Chạy ứng dụng**  
```bash
streamlit run app.py
```

---

### **4. Dataset**  
**Link Dataset**:  
[VAIP Dataset on Kaggle](https://www.kaggle.com/datasets/kusnguyen/vaipe-dataset)  

Dataset bao gồm:  
- 7429 ảnh trong tập huấn luyện.  
- 1040 ảnh trong tập validation.  
- 1033 ảnh trong tập kiểm thử.  

---

### **5. Hướng dẫn sử dụng ứng dụng**  

1. **Tải lên hình ảnh**:  
   - **Pill Image**: Ảnh viên thuốc (JPG, PNG).  
   - **Prescription Image**: Ảnh đơn thuốc (JPG, PNG).  

2. **Nhấn nút "Show Results"** để xem kết quả nhận diện.  

3. **Các kết quả hiển thị**:  
   - **Pill Detection Results**: Thông tin loại thuốc và độ chính xác nhận diện.  
   - **OCR Results**: Trích xuất tên thuốc và liều lượng từ đơn thuốc.  
   - **Final Results**: Đối chiếu thông tin giữa đơn thuốc và thuốc thực tế.  

4. **Tải xuống kết quả**:  
   - Cho phép tải ảnh có đánh dấu nhận diện và dữ liệu bảng tổng hợp kết quả.  

---

**© 2024 MEDICINE PILL IMAGE RECOGNITION. All Rights Reserved.**  
