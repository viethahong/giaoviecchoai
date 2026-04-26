---
name: strategy
description: Phân tích chiến lược với AI — AI phân tích options, user quyết định. Khi user cần so sánh suppliers, phân tích SWOT, lên kế hoạch.
---

# Skill: Strategy

Skill này giúp dùng AI hỗ trợ các quyết định chiến lược — AI phân tích, bạn quyết định.

**Chiến lược** = công việc cần ngữ cảnh sâu, rủi ro cao, đo bằng kết quả dài hạn.

AI có thể **hỗ trợ** phần chiến lược bằng cách:
- Phân tích data và đưa ra options
- So sánh pros/cons của từng option
- Nghiên cứu thị trường, đối thủ

AI **KHÔNG thể** quyết định thay bạn vì:
- Quyết định chiến lược cần risk tolerance — thứ chỉ con người có
- Quyết định cần ngữ cảnh sâu về doanh nghiệp, thị trường, khách hàng

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Phân tích SWOT | Quyết định ngân sách lớn |
| So sánh 2 suppliers | Đàm phán hợp đồng quan trọng |
| Research đối thủ | Xử lý khủng hoảng |
| Lên kế hoạch tháng/quý | Quyết định tuyển dụng cấp cao |
| Benchmark thị trường | Định vị brand dài hạn |


## Cách dùng

### Bước 1: Xác định vấn đề
Rõ ràng: "Mình đang cần quyết định X. Đang cân nhắc Y và Z."

### Bước 2: Cung cấp context
- Thông tin doanh nghiệp
- Ràng buộc (budget, timeline)
- Mục tiêu ngắn/dài hạn

### Bước 3: Yêu cầu AI phân tích
Không hỏi "mình nên làm gì?" mà hỏi "hãy phân tích pros/cons của..."

### Bước 4: Tự quyết định
AI cung cấp analysis, bạn quyết định dựa trên risk tolerance riêng.

## Megaprompt

Prompt để dùng với Custom GPT / Claude Project:

[references/prompt.md](references/prompt.md)

## Ví dụ

**Task: "Mình nên chọn supplier A hay B?"**

**AI phân tích:**
Cần thêm context:
- Sản phẩm gì? (quần áo, food, cosmetics?)
- Budget cho supplier per tháng?
- Volume mong đợi?
- Priority là giá, chất lượng, hay lead time?

[Sau khi có context đủ]

**Output:** Phân tích options theo format:
| | Supplier A | Supplier B |
|---|---|---|
| Pros | ... | ... |
| Cons | ... | ... |
| Risk | ... | ... |
| Lead time | ... | ... |
| MOQ | ... | ... |

**Câu hỏi bạn nên tự hỏi:**
- Bạn đang ở giai đoạn nào của business?
- Nếu fail với supplier này, hậu quả là gì?

## Liên quan

- [Học 4C tương tác](https://hahongviet.com/4C/)
- [4C Framework (docs)](../../docs/03-4c/README.md)
- [Skills Index](../)
