# Hướng dẫn cách chạy

# Tải file rar image

link tải: https://drive.google.com/file/d/1pU0A1w4APTVBRbkam8jnmiD-ERKqwP24/view?usp=sharing

# Tải file rar web_Local_Decte_Face_Friend

link tải: https://drive.google.com/file/d/1RJpRRLf07yzhOQjHHO51K2ks13z89cfk/view?usp=sharing

# Giải nén 2 file rar

Sau khi giải nén bạn vào file web_Local_Decte_Face_Friend sẽ thấy file face_recognition_sface_2021dec.onnx copy file này ra ngoài

Lưu ý: phải có file này mới chạy được file training.py

# Bước 1: chạy cắt ảnh từ video

Gõ lệnh run: python GetImageFromVideo.py

# Bước 2: train ảnh

Gõ lệnh run: python Training.py

Sau khi chạy xong copy file svc.pkl vào thư mục web_Local_Decte_Face_Friend

# Bước 3: Chạy nhận diện

Truy cập vào thư mục web_Local_Decte_Face_Friend mới có thể dùng lệnh chạy

Chạy local: python NhanDangKhuonMat.py

Chạy web: python web.py
