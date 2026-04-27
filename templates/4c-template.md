# Template 4C — Giao Việc Cho AI

Dùng template này để viết prompt theo 4C. Mỗi task có thể cần mức độ khác nhau — xem hướng dẫn trong [docs/03-4c/levels.md](../docs/03-4c/levels.md).

---

## C1. Context — AI phải HIỂU gì?

(Bối cảnh tổng thể)

**Công ty / tổ chức:**
- Tên:
- Ngành:
- Sản phẩm/dịch vụ chính:
- Điểm khác biệt:

**Đối tượng khách hàng:**
- Demographic:
- Pain point chính:
- Cách họ mua hàng:

**Bối cảnh task cụ thể:**
- Đang làm gì (campaign, bài đăng, email...):
- Mục tiêu ngắn hạn:
- Ràng buộc (budget, timeline, kênh...):

---

## C2. Commission — AI phải LÀM gì?

(Phần này viết cuối cùng — sau khi đã rõ Context và Content)

**Output mong đợi:**
- Format (email, caption, bài blog, báo cáo...):
- Độ dài:
- Số lượng bản:

**Action rõ ràng:**
- AI cần tạo gì cụ thể:
- Có cần research thêm không:

---

## C3. Content — AI DÙNG gì để làm?

(Nguyên liệu, dữ liệu, tài liệu AI dùng làm input)

**Thông tin sản phẩm/dịch vụ:**
- Tên, giá, mô tả ngắn:
- USP (điểm bán độc nhất):

**Thông tin khách hàng:**
- Target audience:
- Insight nào quan trọng:

**Tài liệu có sẵn:**
- Website:
- Tài liệu nội bộ:
- Ví dụ output tốt:

---

## C4. Criteria — AI KHÔNG được gì? / Thế nào là LÀM XONG TỐT?

(Ranh giới + tiêu chuẩn đánh giá)

**Phải có (checklist):**
1.
2.
3.

**Không được (禁令):**
1.
2.

**Dấu hiệu output tốt:**
-
-

**Dấu hiệu output cần viết lại:**
-
-

---

## 🔄 Feedback Loop — Sau Khi AI Trả Output

Dùng đoạn prompt sau để AI tự chấm và viết lại:

```
Chấm output trên theo Criteria đã viết ở C4, cho điểm 1-10 từng mục.
Chỉ ra 3 điểm yếu nhất.
Viết lại bản tốt hơn dựa trên những điểm đó.
```

**Khi nào dùng:**
- Output chưa đạt yêu cầu sau lần đầu
- Task quan trọng cần kiểm tra kỹ trước khi dùng
- Muốn hiểu AI đang thiếu gì để cải thiện prompt lần sau

---

*Lưu ý: Bạn KHÔNG cần điền đủ 4 mục cho mọi task. Xem hướng dẫn mức độ áp dụng 4C trong docs/03-4c/levels.md*
