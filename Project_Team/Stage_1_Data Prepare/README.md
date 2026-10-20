# Stage 1 — Bản code cơ bản

1. Giải nén toàn bộ thư mục.
2. Mở thư mục Stage1_CoBan trong VS Code/Jupyter.
3. Cài thư viện: `python -m pip install -r requirements.txt`.
4. Mở Stage1.ipynb, chọn Python đã cài thư viện, chạy từ trên xuống.

CSV gốc đã kèm nên không cần tải Kaggle khi chạy. Notebook tự tạo lại hai CSDL và các CSV kết quả. Chạy một notebook tại một thời điểm để tránh khóa Qdrant local.

Chỉ thực hiện Stage 1 cơ bản, không Crawling, không API AI, không huấn luyện mô hình. Kênh liên hệ mô phỏng được ghi rõ theo yêu cầu sinh dữ liệu động. Hai nguồn Kaggle cùng nguồn gốc UCI; notebook chia thời gian để tránh đếm trùng giữa hai bộ.
