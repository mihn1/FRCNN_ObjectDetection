# Introduction
<i>Repository cho bài tập lớn môn Học Máy kỳ 20201, Đại học Bách Khoa Hà Nội</i> 

Đề tài: Xây dựng mô hình học máy nhận diện đối tượng (Object Detection)

Công nghệ: Python 3.6 trên môi trường Google Colab

Dữ liệu: Subset của bộ dữ liệu Open Images V4 (3336 ảnh, 5 classes)

# Cấu trúc Project

Đề tài sử dụng code implement Faster R-CNN áp dụng cho mô hình. Original code: https://github.com/RockyXu66/Faster_RCNN_for_Open_Images_Dataset_Keras

<code>Object_Detection_DataPreprocessing.ipynb</code> để tiền xử lý dữ liệu để tiền xử lý dữ liệu cho phù hợp với file implement Faster R-CNN <code>frcnn_train_vgg.ipynb</code>. <code>frcnn_test_vgg.ipynb</code> là file để test model và tính toán mAP (mean average precision). 

Cần dowload trước các file <code>train-images-boxable.csv</code>, <code>train-annotations-bbox.csv</code>, <code>class-descriptions-boxable.csv</code> từ https://storage.googleapis.com/openimages/web/download_v4.html và upload lên Google Drive

Để chạy code trên Google Colab cần cấp quyền truy cập và upload file annotation.txt nhận được sau khi tiền xử lý dữ liệu lên Google Drive và đổi đường dẫn trong notebook.

# Một vài kết quả test
<img src="Test%20Images/good%20result%201.png" /> 
<img src="Test%20Images/good%20result%202.png" />
<img src="Test%20Images/normal%20result%202.png" />
