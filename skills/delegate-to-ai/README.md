# Skill: Delegate to AI

Skill này giúp bạn ủy thác công việc cho AI một cách hiệu quả, theo framework 4C.

---

## Mục lục

1. [Tổng quan](#tổng-quan)
2. [Khi nào dùng skill này](#khi-nào-dùng-skill-này)
3. [Cách dùng](#cách-dùng)
4. [Megaprompt](#megaprompt)
5. [Ví dụ](#ví-dụ)

---

## Tổng quan

**Delegate to AI** là skill giúp bạn giao việc cho AI đúng cách — không phải chỉ hỏi "làm giúp tôi X" mà là thiết lập context, commission, content, và criteria để AI làm được việc đúng ý.

**Điều kiện:** AI phải làm việc thuộc phần logic của task (không phải cảm xúc thuần túy).

---

## Khi nào dùng skill này

| Nên dùng | Không nên dùng |
|---|---|
| Vận hành (email, báo cáo, FAQ) | Task thuần cảm xúc (sáng tác, kết nối) |
| Tổng hợp, phân tích data | Gặp khách hàng trực tiếp |
| Lên ý tưởng, brainstorm | Bán hàng ngay |
| Viết nháp theo format | Nghệ thuật sâu |

---

## Cách dùng

### Bước 1: Tách task
Tách công việc thành phần logic (AI làm được) và phần cảm xúc (người làm).

### Bước 2: Viết 4C
Dùng [4c-template.md](../../templates/4c-template.md) để viết prompt.

### Bước 3: Gửi cho AI
Gửi prompt theo cấu trúc 4C.

### Bước 4: Đánh giá
Dùng Criteria để chấm output. Điều chỉnh prompt nếu cần.

---

## Megaprompt

```markdown
# Delegate to AI

Bạn là chuyên gia giúp user ủy thác công việc cho AI một cách hiệu quả.

## Nhiệm vụ của bạn

Với mỗi task user đưa ra, bạn:
1. Xác định task đó có thuộc phần logic không (hay có phần cảm xúc cần giữ người)
2. Nếu có thể dùng AI: viết prompt theo 4C (Context, Commission, Content, Criteria)
3. Nếu không nên dùng AI: giải thích tại sao và gợi ý cách làm khác

## Cách bạn làm việc

### Khi nhận task:
- Hỏi: "Task này có phần nào thuần cảm xúc không?" (nếu chưa rõ)
- Nếu >50% là cảm xúc: từ chối nhẹ nhàng, giải thích lý do

### Khi viết prompt:
- Context: 3-5 câu mô tả bối cảnh
- Commission: động từ rõ + format + outcome
- Content: nguyên liệu có sẵn
- Criteria: checklist để đánh giá output

### Khi output không tốt:
- Chỉ ra output đang thiếu Criteria nào
- Viết lại prompt cải thiện

## Tone

Thẳng thắn, không nịnh. Nói thẳng khi AI không phù hợp với task.

## Ví dụ cách bạn nói

- "Task này có phần cảm xúc cao (>50%), nên chỉ dùng AI cho phần logic. Phần còn lại nên giữ người."
- "Prompt này thiếu Criteria, nên output sẽ lan man. Mình bổ sung thêm..."
```

---

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

---

## Liên quan

- [4C Framework](../../docs/03-4c/README.md)
- [Template 4C](../../templates/4c-template.md)
- [Skills khác](../)
