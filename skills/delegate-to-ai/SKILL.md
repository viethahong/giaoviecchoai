---
name: delegate-to-ai
description: Giúp ủy thác công việc cho AI một cách hiệu quả theo framework 4C. Khi user muốn học cách giao việc cho AI đúng cách, hoặc muốn viết prompt tốt hơn.
---

# Skill: Delegate To Ai

Skill này giúp bạn ủy thác công việc cho AI một cách hiệu quả, theo framework 4C.

## Tổng quan

**delegate-to-ai** là skill giúp bạn giao việc cho AI đúng cách — không phải chỉ hỏi "làm giúp tôi X" mà là thiết lập context, commission, content, và criteria để AI làm được việc đúng ý.

**Điều kiện:** AI phải làm việc thuộc phần logic của task (không phải cảm xúc thuần túy).

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Vận hành (email, báo cáo, FAQ) | Task thuần cảm xúc (sáng tác, kết nối) |
| Tổng hợp, phân tích data | Gặp khách hàng trực tiếp |
| Lên ý tưởng, brainstorm | Bán hàng ngay |
| Viết nháp theo format | Nghệ thuật sâu |

## Cách dùng

### Bước 1: Tách task
Tách công việc thành phần logic (AI làm được) và phần cảm xúc (người làm).

### Bước 2: Viết 4C
Dùng [4c-template.md](../../templates/4c-template.md) để viết prompt.

### Bước 3: Gửi cho AI
Gửi prompt theo cấu trúc 4C.

### Bước 4: Đánh giá
Dùng Criteria để chấm output. Điều chỉnh prompt nếu cần.

## Megaprompt

Prompt để dùng với Custom GPT / Claude Project:

[references/prompt.md](references/prompt.md)

## Ví dụ

### Task: Viết email cảm ơn khách VIP

**User hỏi:** "Viết email cảm ơn khách VIP"

**AI phân tích:**
Task này có 2 phần:
- Phần logic: thông tin khách, lịch sử mua hàng, sản phẩm đã mua
- Phần cảm xúc: cảm ơn chân thành, kết nối cảm xúc

→ **Không nên dùng AI toàn bộ** vì cảm xúc không thể thay thế.

**Gợi ý:**
- AI viết nháp email chuẩn format, thông tin đúng
- Người tự viết lại phần cảm ơn, thêm chi tiết cá nhân

## Liên quan

- [4C Framework](../../docs/03-4c/README.md)
- [Template 4C](../../templates/4c-template.md)
- [Skills Index](../)
