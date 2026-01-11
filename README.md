# ĐỒ ÁN CUỐI KỲ – XỬ LÝ NGÔN NGỮ TỰ NHIÊN (NLP)

##  Tên đề tài
**Dịch Máy Anh → Pháp (EN→FR) sử dụng mô hình Seq2Seq LSTM**

---

## I. Tổng quan
Đây là **đồ án cuối kỳ môn Xử lý ngôn ngữ tự nhiên (NLP)**, tập trung xây dựng mô hình **Machine Translation** dịch câu từ **tiếng Anh sang tiếng Pháp** bằng kiến trúc **Encoder–Decoder (Seq2Seq) sử dụng LSTM**.

Dự án được triển khai bằng **Python và PyTorch**, bao gồm các bước:  
- Chuẩn bị và tiền xử lý dữ liệu song ngữ  
- Huấn luyện mô hình Seq2Seq LSTM  
- Đánh giá chất lượng dịch bằng **BLEU Score** và phân tích lỗi  

---

## II. Công nghệ & Công cụ sử dụng
- **Ngôn ngữ:** Python  
- **Deep Learning:** PyTorch  
- **Xử lý ngôn ngữ:** TorchText, SpaCy, NLTK  
- **Đánh giá & trực quan:** Matplotlib  
- **Cấu hình:** YAML  

---

## III. Nội dung chính của đồ án
1. **Tiền xử lý dữ liệu**
   - Tokenization, xây dựng vocabulary
   - Tạo DataLoader cho huấn luyện và đánh giá

2. **Xây dựng mô hình**
   - Encoder – Decoder LSTM (Seq2Seq)
   - Huấn luyện mô hình với Teacher Forcing

3. **Đánh giá & phân tích**
   - Đánh giá bằng BLEU Score
   - Thực hiện dịch thử và phân tích lỗi dịch

---

## IV. Cấu trúc thư mục
```LSTM-Final-project/
├── data/ # Chuẩn bị & xử lý dữ liệu
├── models/ # Encoder, Decoder, Seq2Seq, training
├── evaluation/ # Inference & BLEU evaluation
├── checkpoints/ # Lưu mô hình tốt nhất
├── notebooks/ # Notebook thử nghiệm & trực quan
├── config/ # File cấu hình tham số
├── report/ # Báo cáo cuối kỳ
├── requirements.txt
├── README.md
└── .gitignore
