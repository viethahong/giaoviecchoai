# Bài 04 — FlowAI

FlowAI mô tả cách AI xử lý thông tin từ lúc nhận prompt đến lúc trả output. Hiểu FlowAI giúp bạn đặt câu hỏi đúng cho AI.

---

## Cách AI Nhận và Xử Lý Prompt

```
User Prompt
    ↓
[1] Nhận prompt → [2] Tách từ → [3] Tìm xác suất → [4] Ghép từ → [5] Trả output
```

### Bước 1: Nhận prompt
AI nhận toàn bộ text bạn gửi, giữ nguyên thứ tự.

### Bước 2: Tách từ (Tokenize)
Prompt được cắt thành tokens — không phải từ theo nghĩa thông thường mà là chunks của text. "AI" có thể là 1 token, "không" là 1 token, dấu "." là 1 token.

### Bước 3: Tìm xác suất
Với mỗi token tiếp theo, AI tính xác suất "token này xuất hiện sau những token trước đó trong context của nó". Không phải "đoán ngẫu nhiên" mà là "đoán dựa trên pattern đã học".

### Bước 4: Ghép từ (Sampling)
AI chọn token tiếp theo bằng một trong các cách:
- **Greedy**: Chọn token có xác suất cao nhất (thường an toàn, nhưng dễ lặp)
- **Random sampling**: Chọn ngẫu nhiên trong top-N tokens (tạo diversity nhưng có thể lạc)
- **Temperature**: Điều chỉnh độ "ngẫu nhiên" — cao = sáng tạo hơn, thấp = nhất quán hơn

### Bước 5: Trả output
Sau khi đủ độ dài hoặc gặp stop token, AI trả output cho user.

---

## Ảnh Hưởng Của Cách AI Làm Việc

### Điều này có nghĩa gì cho bạn?

**1. AI không "hiểu" — AI "dự đoán"**
Bạn nói "làm một bài content hay" — AI không biết "hay" là gì theo nghĩa cảm nhận. Nó dự đoán token nào có xác suất cao nhất xuất hiện sau "bài content hay".

→ Vì vậy **Criteria rõ ràng** quan trọng hơn adjectives chung chung.

**2. Prompt càng dài = context càng nhiều = output càng đúng ý**
Mỗi token trong prompt là một "manh mối" giúp AI thu hẹp xác suất. Prompt 10 tokens khác prompt 100 tokens rất nhiều.

→ Vì vậy **Context đầy đủ** giúp AI làm đúng hơn.

**3. Cùng prompt ≠ cùng output**
Nếu bạn chạy lại prompt không đổi, output có thể khác — vì sampling có yếu tố ngẫu nhiên.

→ Vì vậy **Temperature setting** quan trọng với task sáng tạo.

---

## Temperature và Khi Nào Dùng

| Temperature | Khi nào dùng | Tác dụng |
|---|---|---|
| **0.0 - 0.3** | Task logic (code, phân tích, báo cáo) | Output nhất quán, đúng ý |
| **0.4 - 0.7** | Task thường (email, post) | Cân bằng giữa đúng ý và mới lạ |
| **0.8 - 1.0** | Brainstorm, ý tưởng | Đa dạng, sáng tạo, có thể "lạc" |
| **>1.0** | Không khuyến khích | Quá ngẫu nhiên, output vô nghĩa |

---

## Context Window — Giới Hạn Của AI

Mỗi AI có giới hạn số tokens có thể xử lý trong một lần (context window). Hiện tại phổ biến:

- Claude: 200K tokens
- GPT-4o: 128K tokens
- Gemini: 1M tokens (nhưng xử lý chậm hơn)

**Khi prompt + output vượt context window:**
- AI sẽ "quên" phần đầu
- Hoặc không xử lý được

**Khi task dài:**
- Chia nhỏ thành nhiều prompt
- Dùng "context summarizing" — sau mỗi 10 lần trao đổi, yêu cầu AI tóm tắt lại toàn bộ context

---

## N × V — Cấu Trúc FlowAI

N × V là cách đọc prompt theo flow:

- **N (Noun)**: Danh từ — AI làm gì? (Content, Strategy, Report...)
- **V (Verb)**: Động từ — AI cần làm gì với danh từ đó? (viết, phân tích, tạo, sửa...)

| N | V | Output |
|---|---|---|
| Content | viết | Bài viết |
| Content | sửa | Bài đã chỉnh |
| Strategy | phân tích | Báo cáo chiến lược |
| Data | tổng hợp | Bảng số liệu |

**Cách đọc:** Khi bạn đọc prompt, hỏi "N là gì, V là gì?" — nếu N+V không rõ ràng, prompt sẽ lạc hướng.

---

## Tiếp theo

[Sau khi hiểu FlowAI → Đọc tiếp: Bài 05 — Chọn AI Cho Từng Việc](../05-ai-tools/README.md)
