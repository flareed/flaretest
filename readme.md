# Hướng dẫn sử dụng
## Môi trường và thư viện: 
+ Ngôn ngữ: python 3.12 (nhớ chọn cài pip)
+ Thư viện deepface (pip install deepface)
+ Công cụ sử dụng khi test thử: visual studio code

## Cách hoạt động 
- Sử dụng hàm count_faces_with_timer(directory)
  + Biến directory là đường dẫn tới thư mục chứa các file ảnh (VD: d:\data\images)
- Sau khi hàm chạy xong sẽ thông báo kết quả trên console & sẽ tạo một thư mục có thêm hậu tố "_output" để lưu hình đã được khoanh đỏ phần khuôn mặt (VD: d:\data\images_output)
- Kểt quả trả về trên console:
  + Pos: phát hiện được có mặt người trong ảnh
  + Neg: không phát hiện được có mặt người trong ảnh
