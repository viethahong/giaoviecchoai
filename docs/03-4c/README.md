# Bài 03 — 4C Framework

> 📚 **Học 4C tương tác:** [https://hahongviet.com/4C/](https://hahongviet.com/4C/)

4C là framework giúp bạn viết prompt để AI làm được việc đúng ý. Mỗi C giải quyết một lỗi thường gặp khi giao việc cho AI.

---

## 4 Cấu Phần

```
┌──────────────────────────┬──────────────────────────┐
│  C1. CONTEXT              │  C2. COMMISSION          │
│  AI phải HIỂU gì?         │  AI phải LÀM gì?          │
│  (Bối cảnh — tổng thể)    │  (Kỳ vọng — tổng thể)     │
├──────────────────────────┼──────────────────────────┤
│  C3. CONTENT              │  C4. CRITERIA            │
│  AI DÙNG gì để làm?       │  AI KHÔNG được gì?        │
│  (Nguyên liệu — chi tiết) │  (Ranh giới — chi tiết)   │
└──────────────────────────┴──────────────────────────┘
     ← HIỆN TẠI (input) →       ← TƯƠNG LAI (output) →
```

---

## Mỗi C Giải Quyết Một Lỗi

| Thiếu | Lỗi | Prompt điền thêm |
|---|---|---|
| **Context** | Output nhạt, chung chung | Bối cảnh công ty, sản phẩm, khách hàng |
| **Commission** | Output lạc hướng, không đúng ý | Động từ + format + outcome rõ ràng |
| **Content** | Output không cá nhân hóa | Nguyên liệu AI dùng để làm |
| **Criteria** | Output lan man, không có tiêu chuẩn | Checklist để đánh giá kết quả |

---

## Mức Độ Áp Dụng 4C

**KHÔNG phải mọi câu hỏi đều cần điền đủ 4 mục.** Sử dụng theo mức độ quan trọng:

| Loại task | Context | Commission | Content | Criteria |
|---|---|---|---|---|
| **Hỏi nhanh** (tra cứu, brainstorm throwaway) | Bỏ qua | 1 câu | Bỏ qua | Bỏ qua |
| **Task thường** (email, post ngắn) | 1-2 câu | Chi tiết | Nếu có thì thêm | 2-3 điểm |
| **Task quan trọng** (bài publish, báo cáo) | 5W1H đầy đủ | 3 tầng đầy đủ | 4 loại đầy đủ | 2 mặt đầy đủ |

---

## Criteria — Bản Lề Quan Trọng Nhất

Criteria có vai trò kép:

1. **Trước khi AI làm:** Criteria định hướng AI tạo output đúng
2. **Sau khi AI làm:** Criteria là công cụ tự động hóa feedback loop — "Chấm output này theo Criteria ở trên, điểm 1-10 cho từng mục, chỉ ra chỗ sai, rồi viết lại bản tốt hơn."

**Criteria phải viết TRƯỚC, không phải sau.** Viết sau = review thủ công. Viết trước = AI tự critique được.

---

## Template 4C

[Tải 4c-template.md](../templates/4c-template.md)

---

## Ví Dụ

### Task: Viết caption sản phẩm hàng ngày

**Context:**
- Công ty: shop thời trang online tên "MIDI", bán hàng qua Instagram và TikTok Shop
- Sản phẩm: áo sơ mi linen, giá 450k, phân khúc 20-30 tuổi
- Khách hàng: người đi làm công sở nhỏ, cần mặc đẹp nhưng tiết kiệm thời gian

**Commission:**
- Viết 3 caption Instagram, mỗi caption 80-120 chữ
- Mỗi caption có: hook 1 dòng → mô tả sản phẩm → call to action

**Content:**
- Sản phẩm: áo sơ mi linen, form regular, màu trắng/tràm/xanh nhạt
- USP: vải linen thoáng mát, ủi nhanh, giặt máy được
- Điểm bán: tiết kiệm thời gian cho người bận

**Criteria:**
- Phải có: hook gâi tò mò, mô tả vải linen, giá, CTA mua hàng
- Không được: dùng từ "sang trọng/b upscale", so sánh với đối thủ

---

## Bài Tập

[Liên quan: exercises/day-03.md](./exercises/day-03.md)

---

## Tiếp theo

[Sau khi hiểu 4C → Đọc tiếp: Bài 04 — FlowAI](../04-flowai/README.md)
