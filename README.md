# Computer_vision
Bài tập: So sánh 2 thư viện PIL và CV, liệt kê so sánh trong 1 cell markdown ở file 2.1.2 


```

Tổng quan

- PIL / Pillow
  Thư viện Python thuần, tập trung vào xử lý ảnh cơ bản.

- OpenCV
  Thư viện viết bằng C++, có Python binding, chuyên cho Computer Vision và xử lý ảnh/video hiệu suất cao.

---


Ứng dụng

Dùng PIL / Pillow khi:
- Xử lý ảnh đơn giản cho web
- Cần thư viện nhẹ, dễ học
- Làm watermark, chuyển đổi định dạng ảnh
- Làm việc với ảnh tĩnh
- Tiền xử lý ảnh cho ML (kết hợp NumPy)


Dùng OpenCV khi:
- Làm Computer Vision projects
- Xử lý video, webcam, real-time
- Bài toán detection, recognition, tracking
- Yêu cầu hiệu suất cao
- Pipeline CV kết hợp ML hoặc DL

Vậy nên

- PIL phù hợp cho xử lý ảnh nhẹ và cơ bản
- OpenCV phù hợp cho Computer Vision chuyên sâu
- Trong dự án ML/DL thực tế, thường kết hợp cả hai thư viện
```


