# Hand Gesture CNN Game Control

## 📋 Mô tả đồ án

Dự án này sử dụng phương pháp nhận dạng cử chỉ tay bằng Convolutional Neural Network (CNN) để xây dựng hệ thống giao diện điều khiển trò chơi không chạm. Người dùng có thể điều khiển trò chơi chỉ bằng cử chỉ tay mà không cần chạm vào thiết bị.

## 🎯 Mục tiêu

- Phát triển mô hình CNN có khả năng nhận dạng chính xác các cử chỉ tay
- Tích hợp mô hình vào hệ thống điều khiển trò chơi real-time
- Tạo trải nghiệm người dùng mới mẻ và tiện lợi

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ**: Python
- **Framework ML**: TensorFlow/Keras hoặc PyTorch
- **Thư viện xử lý ảnh**: OpenCV
- **Dataset**: Hand Gesture Detection System từ Kaggle

## 📊 Dataset

Sử dụng dataset từ Kaggle: [Hand Gesture Detection System](https://www.kaggle.com/datasets/marusagar/hand-gesture-detection-system)

Dataset bao gồm các ảnh cử chỉ tay với nhiều lớp khác nhau để huấn luyện mô hình.

## 🚀 Cài đặt và chạy

### Yêu cầu hệ thống
- Python 3.8+
- Webcam hoặc camera
- GPU (khuyến nghị cho training)

### Cài đặt dependencies
```bash
pip install -r requirements.txt
```

### Huấn luyện mô hình
```bash
python train.py
```

### Chạy hệ thống điều khiển
```bash
python game_control.py
```

## 📁 Cấu trúc dự án

```
hand-gesture-cnn-game-control/
├── data/                    # Dataset và dữ liệu
├── models/                  # Mô hình đã huấn luyện
├── src/                     # Source code
│   ├── preprocessing.py     # Tiền xử lý dữ liệu
│   ├── model.py            # Kiến trúc CNN
│   ├── train.py            # Script huấn luyện
│   └── game_control.py     # Hệ thống điều khiển
├── notebooks/              # Jupyter notebooks cho experimentation
├── requirements.txt        # Dependencies
├── checklist.md           # Checklist thực hiện dự án
└── README.md              # Tài liệu này
```

## 📈 Kết quả dự kiến

- Độ chính xác nhận dạng cử chỉ > 90%
- Độ trễ phản hồi < 100ms
- Hỗ trợ 5-10 cử chỉ cơ bản cho điều khiển trò chơi

## 👨‍💻 Tác giả

**mson0714** - Đồ án chuyên ngành

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Đồ án này được thực hiện trong khuôn khổ học tập và nghiên cứu khoa học.*