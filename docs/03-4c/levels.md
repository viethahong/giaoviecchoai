# Mức Độ Áp Dụng 4C

4C không phải checklist bắt buộc cho mọi task. Sử dụng theo mức độ quan trọng của task.

---

## Tổng Quan

| Task Type | Context | Commission | Content | Criteria |
|---|---|---|---|---|
| **Hỏi nhanh** | Bỏ qua | 1 câu | Bỏ qua | Bỏ qua |
| **Task thường** | 1-2 câu | Chi tiết | Nếu có thì thêm | 2-3 điểm |
| **Task quan trọng** | 5W1H đầy đủ | 3 tầng đầy đủ | 4 loại đầy đủ | 2 mặt đầy đủ |

---

## Loại 1: Hỏi Nhanh (Quick Query)

**Ví dụ:** Tra cứu thông tin, brainstorm throwaway, hỏi nhanh một khái niệm.

### Khi nào dùng:
- Không cần output chính xác 100%
- Chỉ cần gợi ý ban đầu
- Đang explore ý tưởng

### Prompt mẫu:
```
Hỏi nhanh: có cách nào viết caption cho áo len ngắn gọn không?
```

### Tại sao bỏ qua:
- **Context**: Không cần thiết vì câu hỏi đã đủ rõ
- **Commission**: 1 câu đủ "viết caption cho áo len ngắn gọn"
- **Content**: Không cần vì không có sản phẩm cụ thể
- **Criteria**: Không cần vì chỉ là brainstorm

---

## Loại 2: Task Thường (Regular Task)

**Ví dụ:** Viết email FAQ, caption sản phẩm, bài post ngắn, trả lời khách.

### Khi nào dùng:
- Cần output đúng format
- Có deadline
- Dùng trong công việc thường ngày

### Prompt mẫu (theo 4C):

**Context:**
- Shop bán thời trang online, target 20-30 tuổi
- Sản phẩm: áo sơ mi linen, giá 450k

**Commission:**
- Viết 3 caption Instagram, mỗi caption 80-120 chữ
- Format: hook → mô tả → CTA

**Content:**
- USP: vải linen thoáng mát, ủi nhanh
- Giá: 450k

**Criteria:**
- Phải có: hook, mô tả vải linen, giá, CTA
- Không được: so sánh đối thủ, "sang trọng"

---

## Loại 3: Task Quan Trọng (High-Stakes Task)

**Ví dụ:** Bài content publish, báo cáo gửi manager, chiến dịch marketing, landing page.

### Khi nào dùng:
- Có impact lớn (ảnh hưởng doanh thu, brand)
- Nhiều người đọc/xem
- Cần đúng tiêu chuẩn cao

### Prompt đầy đủ (5W1H):

**Context (5W1H):**
- **Who** (Ai): Shop MIDI, chủ SME
- **What** (Làm gì): Viết bài blog giới thiệu collection mới
- **When** (Khi nào): Pre-launch tuần tới
- **Where** (Ở đâu): Website + social media
- **Why** (Tại sao): Giới thiệu sản phẩm, drive traffic
- **How** (Như thế nào): SEO-friendly, 1000-1500 từ

**Commission (3 tầng):**
1. Tầng 1: Viết bài blog
2. Tầng 2: Có sections rõ ràng, SEO keywords tự nhiên
3. Tầng 3: Kết thúc bằng CTA

**Content (4 loại):**
1. Sản phẩm: tên, giá, mô tả, hình ảnh
2. USP: điểm khác biệt
3. Target audience: pain point, mong muốn
4. Competitors: đối thủ chính (để so sánh)

**Criteria (2 mặt):**
- **Phải có:** title SEO, hook hấp dẫn, mỗi section có key point, CTA cuối bài
- **Không được:** keyword stuffing, so sánh trực tiếp với đối thủ, hứa hẹn không đúng

---

## Decision Tree: Dùng 4C ở mức nào?

```
Task có quan trọng không?
├── KHÔNG (hỏi nhanh, brainstorm) → Chỉ dùng Commission
├── BÌNH THƯỜNG (email, post thường) → Commission + 1-2 C khác
└── RẤT QUAN TRỌNG (publish, báo cáo) → Đủ 4C
```

---

## Tip: Bắt đầu với Commission

Khi không chắc nên viết bao nhiêu context:

1. **Viết Commission trước** — động từ + format + outcome
2. **Hỏi: "AI có đủ thông tin để làm task này không?"**
   - Nếu KHÔNG → thêm Context
   - Nếu CÓ → tiếp tục
3. **Hỏi: "Làm sao biết output tốt?"**
   - Nếu chưa rõ → thêm Criteria
4. **Hỏi: "AI cần nguyên liệu gì?"**
   - Nếu có tài liệu → thêm Content

---

## Ví Dụ Thực Tế: Từ Ít Đến Đủ

### Cấp độ 1 — Hỏi nhanh:
```
Viết caption cho áo sơ mi trắng.
```
→ Chỉ Commission

### Cấp độ 2 — Task thường:
```
Shop MIDI, bán áo sơ mi linen. Viết 3 caption cho áo sơ mi trắng,
80 chữ mỗi cái, có hook và CTA.
```
→ Commission + Context ngắn + Criteria cơ bản

### Cấp độ 3 — Task quan trọng:
```
Context: Shop MIDI, bán áo sơ mi linen cho người đi làm 20-30 tuổi.
USP: vải linen thoáng mát, ủi nhanh, giá 450k.
Competition: Uniqlo, Zara.

Commission: Viết bài blog giới thiệu collection áo sơ mi linen mới.
- SEO keywords: "áo sơ mi linen", "áo sơ mi vải lanh"
- Format: title → intro → 3 sections → CTA
- 1000-1500 từ

Content: Có 5 sản phẩm trong collection, mô tả chi tiết từng sản phẩm.

Criteria:
- Phải có: title có keywords, hook hấp dẫn, mỗi section có key message, CTA cuối
- Không được: keyword stuffing, so sánh trực tiếp với Uniqlo/Zara
- Good sign: khách để lại comment hỏi mua sau khi đọc
- Bad sign: bounce rate cao
```
→ Đủ 4C

---

## Liên quan

- [4C Template](../../templates/4c-template.md)
- [Bài 03 — 4C Framework](./README.md)
