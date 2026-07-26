# 🚀 Python Boilerplate

🌐 **Ngôn ngữ / Languages:** [English](../README.md) | **Tiếng Việt**

---

Bộ khung (boilerplate) Python tối giản dành cho việc khởi tạo nhanh các ứng dụng Micro SaaS và API. **Tiết kiệm 10-15 phút mỗi khi tạo project mới.**

---
## 📁 Cấu trúc thư mục

```text
.
├── docs/
│   └── README.vi.md    # Tài liệu hướng dẫn Tiếng Việt
├── .gitignore          # Cấu hình bỏ qua file rác, môi trường ảo (.venv) và secret (.env)
├── .env.example        # Mẫu khai báo các biến môi trường
├── requirements.txt    # Danh sách các thư viện Python cơ bản
├── dev_notes.md        # Ghi chú quy trình phát triển, các lệnh terminal hay dùng
└── README.md           # Tài liệu hướng dẫn chính (Tiếng Anh)
```

### ⚡ Hướng dẫn sử dụng nhanh (Quickstart)
1. Bấm vào nút "Use this template" ở góc trên bên phải của repository này và chọn **"Create a new repository"**..
2. Nhập tên cho repository mới của bạn và bấm **"Create repository"**.
3. Clone repo mới về máy và khởi tạo môi trường ảo:
```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```