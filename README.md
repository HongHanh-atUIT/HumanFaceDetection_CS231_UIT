Đây là đồ án môn học Nhập môn thị giác máy tính - CS231 tại UIT.
Tác giả: 
23520442 - Phạm Thị Hồng Hạnh.
23520980 - Nguyễn Phương Nam.

I. Data:
- Bộ dữ liệu sử dụng trong bài: https://www.kaggle.com/datasets/sbaghbidi/human-faces-object-detection
- Tuy nhiên, chúng tôi không hài lòng với file csv annotate của tác giả nên đã tự vẽ lại bounding box cho bộ dữ liệu trên.
II. Mô tả các file:
- Face_Detection_HOG_SVM.ipynb: file này là chính, dùng để train model phân loại SVM và thực hiện việc chạy demo quá trình phát hiện khuôn mặt trên 1 bức ảnh nào đó.
- SaveDetection.py: file này dùng để kiểm tra quá trình phát hiện khuôn mặt, lưu kết quả vào các file csv.
- Tunning: file này dùng để tìm tham số cho HOG và SVM.
  
