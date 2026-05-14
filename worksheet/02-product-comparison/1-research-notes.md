---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để biết khung giờ chính xác)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — file trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu: trong 20 phút thử nghiệm, 2 thành viên cùng test 2 sản phẩm AI với 1 nhiệm vụ chung. File này ghi lại **quan sát thật** (không phải đánh giá tổng kết) — sẽ làm nền cho bảng so sánh ở bước 2.

Lý do làm bước này: slide deck Lab 2 chỉ có sức nặng khi mỗi nhận định dựa trên quan sát cụ thể có ảnh chụp + tên model + thời gian + câu prompt cụ thể. Nếu chỉ "thấy A tốt hơn B" mà không có log → không phòng thủ được khi giảng viên cold-call.

Quy tắc: **không có ảnh chụp / log = không có quan sát**. Mỗi quan sát phải có ảnh tham chiếu hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + câu prompt + tài khoản dùng)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + ghi log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + ghi log
2 phút   — First impressions: ghi 3 quan sát nổi nhất cho mỗi sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên thống nhất các thông số chung. Câu prompt phải **giống y nhau** cho cả 2 sản phẩm — nếu khác sẽ không so sánh được.

- **Nhiệm vụ chung**: Tra cứu quy định quyết toán thuế TNCN 2024 tại Việt Nam cho người có thu nhập từ 2 nơi.
- **Câu prompt chính xác**: "Hướng dẫn chi tiết các bước quyết toán thuế TNCN năm 2024 tại Việt Nam cho cá nhân có thu nhập từ 2 nơi trở lên. Cần dẫn nguồn các thông tư, nghị định và thời hạn nộp hồ sơ cụ thể."
- **Loại tài khoản dùng**:
  - Sản phẩm A: Perplexity AI (Free account)
  - Sản phẩm B: ChatGPT (Plus account - Search mode)
- **Trình duyệt + thời gian test**: Chrome, 18:40 14/05/2026.

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Perplexity AI
**URL**: https://www.perplexity.ai
**Model dưới mui xe**: Default (Sonar/GPT-4o mini)

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

- Trang đầu / màn hình đầu hiển thị gì? Thanh search lớn ở giữa, các tin tức trending bên dưới.
- Có hint / sample prompt sẵn không? Có, các câu hỏi về tin tức thời sự.
- Cần đăng nhập / paywall trước khi dùng không? Không bắt buộc cho lượt search đầu.
- Ảnh đã chụp: `screenshots/product-A-1-entry.png`

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~3 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Có streaming, hiển thị các bước "Searching", "Reading".
- Output dài bao nhiêu (số câu / dòng / từ)? ~400 từ.
- Output có dẫn nguồn không? **Có (Citation cực rõ)**.
- Có hiển thị disclaimer / cảnh báo không (vd: "có thể sai", "kiểm tra lại")? Có.
- Ảnh đã chụp: `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png`

### B.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có.
- Có nút copy / export ra format khác không? Có.
- Có gợi ý câu hỏi tiếp theo không? Có.
- Có lưu lịch sử để truy lại không? Có.
- Có thumb up / thumb down để feedback không? Có.

### B.4 — Quan sát nổi (3 quan sát)

1. **Khả năng dẫn nguồn chính xác**: Trích dẫn đúng Thông tư 80/2021/TT-BTC.
2. **Giao diện tối ưu cho Research**: Các nguồn hiển thị ngay phía trên câu trả lời.
3. **Tốc độ**: Cực nhanh mặc dù phải duyệt qua nhiều trang web tiếng Việt.

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: ChatGPT Search
**URL**: https://chatgpt.com
**Model dưới mui xe**: GPT-4o with Search

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Khung chat quen thuộc, có icon quả địa cầu cho Search.
- Có hint / sample prompt sẵn không? Có các gợi ý "Help me write", "Summarize".
- Cần đăng nhập / paywall trước khi dùng không? Có (yêu cầu login).
- Ảnh đã chụp: `screenshots/product-B-1-entry.png`

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: ~5 giây
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Có icon "Searching".
- Output dài bao nhiêu (số câu / dòng / từ)? ~500 từ.
- Output có dẫn nguồn không? **Có**.
- Có hiển thị disclaimer / cảnh báo không? Có dòng "ChatGPT can make mistakes".
- Ảnh đã chụp: `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

### C.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Có.
- Có nút copy / export ra format khác không? Có.
- Có gợi ý câu hỏi tiếp theo không? Không rõ ràng bằng Perplexity.
- Có lưu lịch sử để truy lại không? Có.
- Có thumb up / thumb down để feedback không? Có.

### C.4 — Quan sát nổi (3 quan sát)

1. **Hành văn mượt mà**: Giải thích các bước quyết toán thuế rất dễ hiểu.
2. **Nguồn dữ liệu**: Chủ yếu lấy từ các báo lớn (VnExpress, Vietnamnet).
3. **Tính hội thoại**: Có thể hỏi nối tiếp cực tốt.

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
   - **ChatGPT**. Vì giao diện chat cực kỳ quen thuộc.

2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
   - **Perplexity**. Vì cách hiển thị nguồn (citation) rất chuyên nghiệp.

3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
   - Tính kinh tế (Pricing) của gói Pro bên nào đáng tiền hơn?

> Đây là first impressions — chưa phải nhận định. Khi sang `2-comparison-table.md` sẽ đối chiếu chéo với số liệu cụ thể.

---

## Bảng kiểm trước khi sang Bước 2

- [ ] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [ ] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
- [ ] Mỗi quan sát có ảnh / log tham chiếu.
- [ ] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
- [ ] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.
