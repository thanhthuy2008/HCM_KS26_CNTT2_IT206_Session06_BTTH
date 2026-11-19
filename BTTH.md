# BÀI TẬP THỰC HÀNH TỔNG HỢP (BTTH)
## Chủ đề: Ứng dụng AI trong Học tập & Nghiên cứu

### 1. THIẾT KẾ GIẢI PHÁP

**Mục tiêu:** Xây dựng trợ lý AI kết hợp Feynman Prompt và Rubric để hỗ trợ học tập, giải thích kiến thức và tự động chấm bài.

**Input:**
- Chủ đề học tập.
- Nội dung bài làm.
- Đáp án chuẩn.
- Tiêu chí chấm điểm.

**Output:**
- Giải thích kiến thức.
- Bảng điểm.
- Nhận xét và đề xuất cải thiện.

**Quy trình Prompt Chaining:**

1. Kiểm tra dữ liệu đầu vào.
2. Giải thích kiến thức bằng Feynman.
3. Chấm điểm bằng Rubric và tổng hợp kết quả.

### 2. CÁC PROMPT THỰC THI

**Prompt 1 – Kiểm tra dữ liệu:**

Kiểm tra dữ liệu đầu vào, phát hiện thông tin thiếu hoặc sai định dạng. Nếu thiếu chủ đề hoặc bài làm, yêu cầu người dùng bổ sung.

**Prompt 2 – Gia sư Feynman:**

Đóng vai gia sư AI, giải thích chủ đề bằng ngôn ngữ đơn giản, dễ hiểu và có ví dụ thực tế.

**Prompt 3 – Chấm điểm Rubric:**

Đóng vai giám khảo AI, đánh giá bài làm theo từng tiêu chí, tính điểm trên thang 10, chỉ ra lỗi sai và đề xuất cải thiện. Không chấm nếu thiếu dữ liệu cần thiết.

### 3. KẾT QUẢ CHẠY THỬ

**Dữ liệu:** Chủ đề AI; bài làm: AI giúp máy tính mô phỏng trí thông minh con người.

**Kết quả Feynman:**

AI là công nghệ giúp máy tính thực hiện những công việc thông minh như trả lời câu hỏi, nhận diện hình ảnh và phân tích dữ liệu.

**Kết quả Rubric:**

| Tiêu chí | Điểm tối đa | Điểm đạt |
|---|---:|---:|
| Độ chính xác | 4 | 4 |
| Mức độ đầy đủ | 3 | 2 |
| Diễn đạt | 2 | 2 |
| Ví dụ | 1 | 0 |
| **Tổng** | **10** | **8** |
