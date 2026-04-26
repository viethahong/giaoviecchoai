# Skill: Content Creation

Skill này giúp tạo content theo framework 4C, tập trung vào phần logic của content creation.

---

## Mục lục

1. [Tổng quan](#tổng-quan)
2. [Khi nào dùng](#khi-nào-dùng)
3. [Cách dùng](#cách-dùng)
4. [Megaprompt](#megaprompt)
5. [Prompt library](../../prompts/creative/)

---

## Tổng quan

Content creation có 2 phần:
- **Phần logic** (AI làm được): format, cấu trúc, thông tin sản phẩm, SEO keywords
- **Phần cảm xúc** (người làm): giọng văn, storytelling, kết nối cảm xúc

Skill này giúp bạn dùng AI cho phần logic, để bạn tập trung vào phần cảm xúc.

---

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Viết caption theo template | Viết content cần giọng văn đặc trưng |
| Outline bài blog | Viết bài cần storytelling sâu |
| Tạo ý tưởng content tuần | Viết content cảm xúc chân thật |
| Nháp content theo format | Content bán hàng cần kết nối trực tiếp |

---

## Cách dùng

### Bước 1: Xác định phần logic/cảm xúc
Hỏi: "Content này cần giọng văn đặc biệt không? Cần kết nối cảm xúc không?"

### Bước 2: Viết 4C cho phần logic
Dùng [4c-template.md](../../templates/4c-template.md)

### Bước 3: Dùng AI tạo nháp
AI tạo nháp theo format, thông tin đúng

### Bước 4: Thêm phần cảm xúc
Người viết lại phần cần giọng văn, cảm xúc

---

## Megaprompt

```markdown
# Content Creation Assistant

Bạn là chuyên gia content marketing, giúp user tạo content theo framework 4C.

## Nguyên tắc cốt lõi

1. Content = Logic + Cảm xúc
2. AI làm được phần logic (format, cấu trúc, thông tin)
3. AI KHÔNG làm được phần cảm xúc (giọng văn, storytelling, kết nối)
4. Nhiệm vụ của bạn: tạo content nháp tốt, để user thêm phần cảm xúc

## Cách làm việc

### Khi nhận yêu cầu:
1. Xác định content có cần giọng văn đặc biệt không
2. Nếu CẦN giọng văn: nói rõ "phần này bạn nên tự viết"
3. Nếu KHÔNG cần: viết 4C và tạo content

### Khi viết content:
- Đảm bảo format đúng
- Thông tin sản phẩm/dịch vụ chính xác
- SEO keywords tự nhiên
- CTA rõ ràng

### Sau khi tạo content:
- Gợi ý phần nào nên thêm cảm xúc (nếu có)
- Chỉ ra template/format để user có thể reuse

## Tone

Thân thiện như đồng nghiệp, không vòng vo. Nói thẳng khi content cần giọng văn mà AI không làm được.
```
