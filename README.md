HỆ THỐNG NHẬN DIỆN LÁ CÂY SỬ DỤNG YOLOv8 VÀ FLASK

📌 Giới thiệu
Đây là hệ thống nhận diện và phân loại lá cây theo thời gian thực bằng cách sử dụng mô hình học sâu YOLOv8 kết hợp với giao diện web xây dựng bằng Flask.

Người dùng có thể sử dụng webcam để quét lá cây, hệ thống sẽ hiển thị loại lá được nhận dạng cùng với độ tin cậy (confidence).

🧠 Công nghệ sử dụng
- [x] Python 3.10+
- [x] YOLOv8 (Ultralytics)
- [x] Flask (Web framework)
- [x] OpenCV (Xử lý ảnh)
- [x] Roboflow (Gán nhãn dữ liệu)
- [x] Jinja2 + HTML (Giao diện)

🗂️ Cấu trúc thư mục
├── app.py # File Flask chính
├── weights/
│ └── best.pt # Mô hình YOLOv8 đã huấn luyện
├── templates/
│ └── index.html # Giao diện người dùng
├── static/ # (Tùy chọn) lưu ảnh kết quả
├── data.yaml # Thông tin cấu hình lớp
├── requirements.txt # Các thư viện cần cài đặt
└── README.md


⚙️ Hướng dẫn cài đặt
git clone https://github.com/your-username/leaf-detection-yolov8.git
cd leaf-detection-yolov8
Tạo môi trường ảo (tuỳ chọn)

python -m venv venv
source venv/bin/activate  # hoặc venv\Scripts\activate trên Windows
Cài đặt thư viện

pip install -r requirements.txt
Chạy ứng dụng

python app.py
Mở trình duyệt và truy cập

http://localhost:5000/
📸 Kết quả
![nhandienlachuoi](https://github.com/user-attachments/assets/c0736e59-f551-4dbc-bf0c-6824e8db46c1)
![nhandienlaphuong](https://github.com/user-attachments/assets/6bd05a96-514f-435d-9206-7b8cb154c220)

📚 Tài liệu tham khảo
https://docs.ultralytics.com/
https://flask.palletsprojects.com/
https://roboflow.com/
https://docs.opencv.org/

👨‍💻 Thông tin sinh viên
Họ và tên: Thiều Khánh Phú
MSSV: 1571020200
Lớp: CNTT 15-03
Giảng viên hướng dẫn: ThS. Lê Trung Hiếu

👨‍💻 Thông tin sinh viên
Họ và tên: Thiều Khánh Phú
MSSV: 1571020200
Lớp: CNTT 15-03
Giảng viên hướng dẫn: ThS. Lê Trung Hiếu
