---
name: operations
description: Tự động hóa công việc vận hành lặp lại bằng AI. Khi user có task lặp lại, có format chuẩn, muốn làm nhanh hơn.
---

# Skill: Operations

Skill này giúp tự động hóa các công việc vận hành lặp lại hàng ngày bằng AI.

**Operations** là các công việc lặp lại, có quy trình rõ, đo được bằng số lượng.

Đây là nhóm công việc AI làm TỐT NHẤT — vì:
- Lặp lại nhiều → AI học được pattern
- Có format chuẩn → AI trả output đúng format
- Không cần cảm xúc → AI phù hợp 100%

## Khi nào dùng

| Nên dùng | Không nên dùng |
|---|---|
| Trả lời email FAQ | Gửi email cảm ơn khách VIP |
| Viết caption theo template | Viết content cần giọng văn |
| Check chính tả | Viết content sáng tạo |
| Làm báo cáo định kỳ | Phân tích chiến lược |
| Tổng hợp data | Gặp khách hàng |
| Tạo SOP | Xử lý khủng hoảng |


## Cách dùng

### Bước 1: Xác định task có phải operations không
- Lặp lại? Có format chuẩn? Không cần cảm xúc?

### Bước 2: Viết prompt theo 4C
Dùng [4c-template.md](../../templates/4c-template.md)

### Bước 3: Gửi cho AI
AI tạo output theo format chuẩn

### Bước 4: Verify
Kiểm tra output đúng format, đầy đủ thông tin

## Megaprompt

Prompt để dùng với Custom GPT / Claude Project:

[references/prompt.md](references/prompt.md)

## Ví dụ

**Task: Viết email xác nhận đơn hàng cho khách**

**AI phân tích:** Task này là operations thuần — có format chuẩn, lặp lại, không cần cảm xúc. AI làm được 100%.

**Output:**
```
Subject: Xác nhận đơn hàng #DH12345

Chào [Tên khách],

Mình xác nhận đã nhận được đơn hàng #DH12345 với:
- [Sản phẩm 1]: [Số lượng] x [Giá]
- Tổng cộng: [Giá]

Dự kiến giao hàng: [Ngày]

Nếu có câu hỏi gì, reply email này nhé.
[Mình tên], [Địa chỉ shop]
```

## Liên quan

- [4C Framework](../../docs/03-4c/README.md)
- [Template 4C](../../templates/4c-template.md)
- [Skills Index](../)
