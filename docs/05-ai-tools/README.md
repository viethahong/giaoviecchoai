# Bài 05 — Chọn AI Cho Từng Việc

Không phải mọi AI đều giỏi mọi việc. Chọn đúng AI giúp tiết kiệm thời gian và cải thiện kết quả.

---

## Nguyên Tắc Chọn AI

**Đừng chọn tool — chọn output.**

Hỏi trước: "Mình cần output gì?" rồi mới hỏi "AI nào cho output đó tốt nhất?"

---

## Phân Loại AI Theo Nhiệm Vụ

### 1. AI cho vận hành (Operations AI)

**Phù hợp:** Email, báo cáo, tổng hợp data, FAQ, checklist, SOP

| AI | Điểm mạnh | Điểm yếu |
|---|---|---|
| **Claude** | Viết rõ ràng, logic, dài hạn được | Không realtime |
| **ChatGPT** | Nhanh, tiện, nhiều plugin | Context ngắn hơn |
| **Gemini 2.0 Flash** | Miễn phí, nhanh, search web | Style hơi "ổn định quá" |
| **DeepSeek** | Miễn phí, tốt với task logic | Dữ liệu lưu trữ ở TQ |

**Khi nào dùng:** Task lặp lại, cần đúng format, không cần sáng tạo.

### 2. AI cho sáng tạo (Creative AI)

**Phù hợp:** Ý tưởng, concept, brainstorm, viết nháp đầu

| AI | Điểm mạnh | Điểm yếu |
|---|---|---|
| **Claude** | Ý tưởng sâu, nuance tốt | Chậm |
| **ChatGPT (GPT-4o)** | Sáng tạo, đa dạng | Có thể "bình thường" |
| **Grok (xAI)** | Hiểu xu hướng mạng xã hội, hài hước | Dữ liệu training giới hạn |

**Khi nào dùng:** Khi bạn cần ý tưởng mới, cần góc nhìn khác.

### 3. AI cho nghiên cứu (Research AI)

**Phù hợp:** Phân tích thị trường, benchmark, tìm insight

| AI | Điểm mạnh | Điểm yếu |
|---|---|---|
| **Perplexity** | Trích nguồn, realtime | Chiều sâu hạn chế |
| **Gemini** | Search web tốt, multi-modal | Style hơi bảng tính |
| **Claude** | Phân tích sâu, suy luận tốt | Cần prompt tốt |
| **Grok** | Realtime X (Twitter), xu hướng thị trường VN | Cần tài khoản Premium |

**Khi nào dùng:** Khi cần thông tin thị trường, đối thủ, xu hướng.

### 4. AI cho thiết kế (Design AI)

**Phù hợp:** Wireframe, landing page, design system

| AI | Điểm mạnh | Điểm yếu |
|---|---|---|
| **Claude (Artifacts)** | Code HTML/CSS nhanh | Không phải designer thật |
| **Figma AI** | Tích hợp design | Cần Figma |
| **Galileo AI** | Wireframe nhanh | Chỉ wireframe |

**Khi nào dùng:** Khi cần prototype nhanh, không có designer.

---

## Context Window — Giới Hạn Cần Biết (2025)

| Model | Context Window | Ghi chú |
|---|---|---|
| Claude 3.7 Sonnet | 200K tokens | Tốt cho tài liệu dài |
| GPT-4o | 128K tokens | Phổ biến nhất |
| Gemini 2.0 Flash | 1M tokens | Nhanh, phù hợp file lớn |
| DeepSeek | 128K tokens | Miễn phí, tốt cho task logic |

**Khi prompt + output vượt context window:**
- AI sẽ "quên" phần đầu
- Chia nhỏ thành nhiều prompt
- Dùng "context summarizing" sau mỗi 10 trao đổi dài

---

## Bảng Quyết Định

| Task của bạn | AI khuyên dùng | Lý do |
|---|---|---|
| Viết email marketing | Claude / ChatGPT | Cần đúng tone, có logic |
| Brainstorm ý tưởng chiến dịch | Claude | Sâu, nuance tốt |
| Research đối thủ nhanh | Perplexity | Trích nguồn realtime |
| Làm landing page prototype | Claude (Artifacts) | Code nhanh |
| Viết content dài (blog) | Claude | Nhất quán hơn |
| Tổng hợp data report | ChatGPT / Claude | Nhanh, đúng format |
| Viết script video | ChatGPT / Claude | Cần dialogue flow |

---

## Nguyên Tắc Quan Trọng

**1. Không lock vào 1 AI duy nhất**
Mỗi AI có thế mạnh riêng. Người dùng AI giỏi không ngại chuyển tool.

**2. Đừng tin 100% vào AI**
Kiểm tra facts, số liệu, thông tin thị trường với nguồn khác.

**3. Context quan trọng hơn tool**
Prompt tốt với Claude yếu hơn prompt tệ với GPT-4. Đừng đổ lỗi cho tool.

**4. Test và so sánh**
Với task quan trọng, chạy cùng 1 prompt trên 2-3 AI và so sánh kết quả.

---

## Bài Tập

Chọn 3 task từ ma trận của bạn. Với mỗi task, xác định:

1. Nhóm task (vận hành / sáng tạo / nghiên cứu / thiết kế)
2. AI bạn sẽ dùng và tại sao
3. Output mỗi AI từ cùng 1 prompt đơn giản

---

## Bài Tập

[Liên quan: exercises/day-05.md](../../exercises/day-05.md)

---

## Tiếp theo

[Sau khi chọn được AI → Đọc tiếp: Bài 06 — Tư Duy Vòng Lặp](../06-loop-thinking/README.md)
