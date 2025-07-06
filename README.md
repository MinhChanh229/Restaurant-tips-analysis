# 🍽️ Restaurant Tips Analysis

Phân tích hành vi tip trong nhà hàng dựa trên các yếu tố như giới tính, thời điểm, thói quen hút thuốc và ngày trong tuần. Dự án sử dụng dữ liệu thực tế từ Mỹ năm 1987 để thực hành phân tích dữ liệu bằng Python và trực quan hóa với Matplotlib.

---

## 📊 Dataset Overview

- 📌 Nguồn: [Tips Dataset on GitHub](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)
- 📦 Số dòng: 244
- 📅 Thu thập: Mỹ, năm 1987
- 🔍 Các cột chính:
  - `total_bill`: Tổng số tiền hóa đơn (USD)
  - `tip`: Số tiền tip (USD)
  - `sex`: Giới tính người thanh toán
  - `smoker`: Người hút thuốc hay không
  - `day`: Ngày trong tuần
  - `time`: Bữa trưa hoặc tối
  - `size`: Quy mô nhóm khách hàng

---

## 🎯 Mục tiêu phân tích

- So sánh hành vi tip giữa người hút thuốc và không hút thuốc
- Phân tích mức tip theo giới tính
- Phân tích mức tip theo thời điểm (Lunch vs Dinner)
- Phân tích ảnh hưởng của ngày trong tuần đến số tiền tip
- Trực quan hóa dữ liệu qua biểu đồ histogram

---

## 🔧 Kỹ thuật sử dụng

- Ngôn ngữ: Python
- Thư viện: `pandas`, `matplotlib`
- Kỹ thuật:
  - Xử lý dữ liệu cơ bản
  - Tính toán thống kê trung tâm (mean, median, min, max)
  - Biểu đồ histogram
  - So sánh phân phối giữa các nhóm

---

## 📈 Kết luận chính

| Câu hỏi                                 | Kết luận                                    |
|-----------------------------------------|---------------------------------------------|
| **Nam giới có tip nhiều hơn không?**     | ✅ Có – tip cao hơn nữ giới xét về giá trị  |
| **Cuối tuần có nhiều tip hơn không?**    | ✅ Có – đặc biệt vào Thứ Bảy và Chủ Nhật     |
| **Bữa tối có nhiều tip hơn không?**      | ✅ Có – Dinner có hóa đơn và tip cao hơn     |

---

## 🧪 Cách chạy mã

1. Clone hoặc tải project:

```bash
git clone https://github.com/your-username/restaurant-tips-analysis.git
cd restaurant-tips-analysis
```
## Cài đặt thư viện cần thiết:
pip install pandas matplotlib
## Chạy file .ipynb hoặc .py:
python tips_analysis.py

## 📁 Cấu trúc thư mục
restaurant-tips-analysis/
│
├── tips_analysis.ipynb      # Notebook phân tích chính
├── tips_analysis.py         # Phiên bản Python script
├── README.md                # Tài liệu mô tả dự án
└── /figures                 # (Tùy chọn) Lưu hình ảnh trực quan hóa
