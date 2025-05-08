# VNI_air_writing_dataset

**Tác giả:** Trịnh Huỳnh Thịnh Khang
**Tên bộ dữ liệu:** Vni_Air_writing
**Giấy phép:** CC BY-NC-SA 4.0
**Kích thước:** 22760 mẫu
**Mô tả:** Bộ dữ liệu này là về quỹ đạo chữ viết tay trên không đối với tiếng Việt do chính mình tự thực hiện trong thời gian nghiên cứu từ 4/2024 đến 3/2025. Cách viết sẽ là chữ cái trước và dấu câu sau. 

Bạn có thể tải dữ liệu thông qua đoạn code sau:
```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("trnhhunhthnhkhang/vi-air-writing")

print("Path to dataset files:", path)
```

![vni_airwriting](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F15128226%2Fa520158454545012284f06870e67dc81%2Fvni_air.png?generation=1740877182344930&alt=media)

Bộ dữ liệu thô tức file zip VNI_airwriting.zip bao gồm 4 thư mục chính:
- 1_gram: từ đơn một chữ
- 2_grams: từ ghép 2 chữ
- 3_grams: từ ghép 3 chữ
- n_gram: cụm từ ghép từ 4 chữ trở lên

Trong mỗi thư mục con là các thư mục nhỏ đại diện cho các từ và chứa 10 hoặc 50 file csv đại diện cho quỹ đạo của các mẫu.
![tree_folder](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F15128226%2Fcac070ced9188a6cc82048c983afcb55%2Ftree_folder.jpg?generation=1740877375102014&alt=media)

Các file *aggregated_data_x.pkl* (tính tới thời điểm hiện tại) là những file đã được chuẩn hóa và tăng cường đặc trưng, x là số lượng mẫu trong file.
- aggregated_data.pdkl
- aggregated_data_17100.pkl
- aggregated_data_20200.pkl
- aggregated_data_21700.pkl

Bộ dữ liệu này được công bố nhằm mục đích phục vụ cộng đồng và không nhằm mục đích kinh doanh dưới bất kì hình thức nào. Vùi lòng tôn trọng bản quyền và ghi nguồn cụ thể giúp mình nhé.

Nếu có bất kỳ thắc mắc nào có thể liên hệ  mình qua 2 địa chỉ sau:
- **Fanpage Facebook:** Nhật ký học tập của Khang
- **Gmail:** trinhhuynhthinhkhang.work@gmail.com

Cảm ơn mọi người đã quan tâm ạ.
