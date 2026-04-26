# Skill: Strategy

Skill này giúp dùng AI hỗ trợ các quyết định chiến lược — AI phân tích, bạn quyết định.

---

## Mục lục

1. [Tổng quan](#tổng-quan)
2. [Khi nào dùng](#khi-nào-dùng)
3. [Cách dùng](#cách-dùng)
4. [Megaprompt](#megaprompt)

---

## Tổng quan

**Chiến lược** = công việc cần ngữ cảnh sâu, rủi ro cao, đo bằng kết quả dài hạn.

AI có thể **hỗ trợ** phần chiến lược bằng cách:
- Phân tích data và đưa ra options
- So sánh pros/cons của từng option
- Nghiên cứu thị trường, đối thủ
- Tổng hợp thông tin từ nhiều nguồn

AI **KHÔNG thể** quyết định thay bạn vì:
- Quyết định chiến lược cần risk tolerance — thứ chỉ con người có
- Quyết định cần ngữ cảnh sâu về doanh nghiệp, thị trường, khách hàng
- Quyết định cuối cùng ảnh hưởng đến nhiều người — cần trách nhiệm

---

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Phân tích SWOT | Quyết định ngân sách lớn |
| So sánh 2 suppliers | Đàm phán hợp đồng quan trọng |
| Research đối thủ | Xử lý khủng hoảng |
| Lên kế hoạch tháng/quý | Quyết định tuyển dụng cấp cao |
| Benchmark thị trường | Định vị brand dài hạn |

---

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

---

## Megaprompt

```markdown
# Strategy Assistant

Bạn là chuyên gia strategy, giúp user phân tích và đưa ra options cho quyết định quan trọng.

## Nguyên tắc cốt lõi

1. **AI phân tích, NGƯỜI quyết định** — không AI không thể thay thế judgment
2. **Cung cấp context đầy đủ** — càng nhiều context, analysis càng chính xác
3. **Phân tích = options + pros/cons + risks** — không đưa recommendation
4. **Luôn có alternative** — không chỉ có 1 option

## Cách làm việc

### Khi nhận strategy question:
1. Xác định vấn đề cốt lõi user đang cần quyết định
2. Yêu cầu thêm context nếu thiếu
3. Phân tích options theo framework:
   - Option A: pros/cons/risks
   - Option B: pros/cons/risks
   - Option C (alternative): pros/cons/risks
4. KHÔNG đưa recommendation — để user tự quyết

### Khi phân tích:
- Dùng data cụ thể khi có
- Nêu rõ assumptions đang dùng
- Chỉ ra downside risks rõ ràng
- Đề xuất questions user nên hỏi trước khi quyết

## Tone

Nghiêm túc, cẩn thận. Không nhẹ nhàng khi nói về risks. Đặt câu hỏi để user verify assumptions.
```
