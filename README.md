# CS188 Project 5: Machine Learning - Nhóm 4

Dự án đã hoàn thiện 100% mã nguồn và đạt điểm tối đa (25/25) trên Autograder.

Phân công mã nguồn trong models.py, losses.py và train.py:
- Nghĩa: Q1 (Perceptron), Q2 (Non-linear Regression)
- Dũng: Q3 (Digit Classification), Q5 (CNN)
- Tuân: Q4 (Language ID), Q6 (Attention), Q7 (Character-GPT)

Các thư viện cần cài:
Numpy, Pytorch, Matplotlib + venv

Cách chạy chấm điểm (Q1 - Q6)
Mở Terminal và chạy lệnh sau để kiểm tra điểm:
python autograder.py
Lưu ý: Khi đồ thị Accuracy/Loss hiện ra, hãy bấm nút X tắt cửa sổ đồ thị để autograder tiếp tục chấm các câu sau.

Cách chạy AI sinh thơ Truyện Kiều (Q7 - Optional)
Mô hình đã được nạp sạch 7565 câu thơ Truyện Kiều chuẩn trong file input.txt. Để xem AI tự động sáng tác, chạy lệnh:
python chargpt.py

tại dòng 87 trong file chargpt.py mọi người sẽ thấy biến context đang được gán là "Trăm năm trong cõi người ta,\nChữ tài chữ mệnh khéo là ghét nhau.\n". Mọi người hoàn toàn có thể thử nghiệm bằng cách đổi biến context thành bất kỳ câu thơ nào khác (ví dụ:
 "Lạ gì bỉ sắc tư phong,
Trời xanh quen thói má hồng đánh ghen."). 
Mỗi từ mồi khác nhau sẽ hướng AI rẽ sang một nhánh xác suất khác và "sáng tác" ra một đoạn thơ hoàn toàn mới.

Chạy giao diện vẽ tương tác nhận diện chữ số (Demo Q3 & Q5): python demo_canvas.py