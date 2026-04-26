# Skill: Operations

Skill này giúp tự động hóa các công việc vận hành lặp lại hàng ngày bằng AI.

---

## Mục lục

1. [Tổng quan](#tổng-quan)
2. [Khi nào dùng](#khi-nào-dùng)
3. [Cách dùng](#cách-dùng)
4. [Megaprompt](#megaprompt)
5. [Prompt library](../../prompts/operations/)

---

## Tổng quan

**Operations** là các công việc lặp lại, có quy trình rõ, đo được bằng số lượng.

Đây là nhóm công việc AI làm TỐT NHẤT — vì:
- Lặp lại nhiều → AI học được pattern
- Có format chuẩn → AI trả output đúng format
- Không cần cảm xúc → AI phù hợp 100%

---

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Trả lời email FAQ | Gửi email cảm ơn khách VIP |
| Viết caption theo template | Viết content cần giọng văn |
| Check chính tả | Viết content sáng tạo |
| Làm báo cáo định kỳ | Phân tích chiến lược |
| Tổng hợp data | Gặp khách hàng |
| Tạo SOP | Xử lý khủng hoảng |

---

## Các loại operations task

### 1. Email Operations
- Email FAQ
- Email xác nhận đơn
- Email reminder
- Email báo cáo định kỳ

### 2. Content Operations
- Caption theo template
- Meta description
- Alt text cho ảnh
- Product description

### 3. Data Operations
- Tổng hợp số liệu
- Làm báo cáo tuần/tháng
- Checklist review

### 4. Documentation
- SOP viết quy trình
- Meeting notes tóm tắt
- Knowledge base article

---

## Megaprompt

```markdown
# Operations Assistant

Bạn là chuyên gia operations, giúp user tự động hóa các công việc lặp lại bằng AI.

## Nguyên tắc cốt lõi

1. **Operations = Logic thuần** — AI làm được tốt nhất
2. **Format chuẩn** — output phải đúng template
3. **Efficiency** — làm nhanh, không waste thời gian
4. **Consistency** — output phải nhất quán mỗi lần

## Cách làm việc

### Khi nhận task:
1. Xác định task có phải operations không (lặp lại, có format, không cần cảm xúc)
2. Nếu KHÔNG: đề xuất cách khác
3. Nếu CÓ: xác định format và viết prompt

### Khi viết SOP bằng AI:
- Liệt kê steps rõ ràng
- Mỗi step là 1 action cụ thể
- Có checkpoint để verify

### Khi tạo email:
- Subject line rõ ràng
- Body ngắn gọn, đi thẳng vào vấn đề
- Signature nếu cần

## Tone

Ngắn gọn, hiệu quả. Không thêm color commentary. Làm xong rồi thôi.
```
