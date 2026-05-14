---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** — cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng. Sau bước này, nhóm có "khung xương" của slide deck.

Lý do làm bước này: nhảy thẳng từ log sang slide deck dễ bị bỏ sót mục. Bảng so sánh ép nhóm trả lời từng mục cho cả 2 sản phẩm song song — phát hiện ngay nếu mục nào còn thiếu bằng chứng.

Quy tắc: mỗi ô của bảng dài tối đa 2 câu. Nếu ô nào để trống → quay lại `1-research-notes.md` đào thêm trước khi sang Bước 3.

## Quy trình 5 phút

```text
3 phút  — Điền bảng so sánh 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô nào còn thiếu bằng chứng
1 phút  — Quyết định: cần test thêm hay đủ để sang slide?
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A (Perplexity) | Sản phẩm B (ChatGPT Search) |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính (chat / form / canvas / IDE)</sup> | Entry point là thanh search lớn. Moment "Aha" khi thấy các nguồn dẫn link ngay lập tức và chính xác. | Entry point là khung chat quen thuộc. Moment "Aha" khi AI giải thích các bước quyết toán thuế bằng ngôn ngữ đời thường. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính (số click, tab, copy-paste, load mental)</sup> | Tối ưu cho việc verify và đào sâu với Related questions. Ít click để kiểm chứng nguồn. | Tối ưu cho việc hỏi đáp nối tiếp (Conversational). Load mental thấp nhờ hành văn tự nhiên. |
| **S3 — Output &amp; Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control cho người dùng</sup> | Độ tin cậy cao nhờ trích dẫn văn bản luật gốc rõ ràng. Citation hiển thị nổi bật. | Độ tin cậy khá, nhưng cảm giác thiên về tóm tắt báo chí. Citation icon nhỏ khó nhìn. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + định vị Cost-Capability-Speed (rẻ-nhanh hay mạnh-đắt)</sup> | Định vị mạnh về Capability & Speed cho Research. Có gói Pro cho người dùng chuyên nghiệp. | Định vị cân bằng, hướng tới sự phổ biến và đa dụng. Gói Plus có giá trị cộng thêm lớn. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng: Strong / Promising / Weak / At Risk + lý do</sup> | **Promising** - Công cụ search tốt nhất cho chuyên gia cần độ chính xác cao. | **Strong** - Sản phẩm search toàn diện cho người dùng phổ thông. |

---

## Phần B — Đối chiếu 3 friction areas (nén từ Lens 3)

Đây là cột trụ của mục S2 trong slide deck. Mỗi friction area trả lời 1 câu so sánh:

- **Physical load** (số click / tab / lần copy-paste): Perplexity ít click hơn để xem nguồn; ChatGPT cần click vào icon nhỏ.
- **Cognitive burden** (cần học prompt engineering / có hint sẵn / có nhớ ngữ cảnh giữa lượt chat):
  - Perplexity có hint tốt cho research; ChatGPT nhớ ngữ cảnh chat tốt hơn.
- **User workarounds** (nhóm phải tự làm gì để bù yếu điểm — vd: prompt lại 3 lần, copy sang công cụ khác):
  - Với Perplexity, đôi khi phải prompt thêm để output bớt khô khan. Với ChatGPT, phải prompt yêu cầu dẫn nguồn luật cụ thể.

---

## Phần C — Đối chiếu 6 trust signals (nén cho mục S3)

Đánh dấu mỗi sản phẩm có / không / một phần:

| Tín hiệu đáng tin | Sản phẩm A (Perplexity) | Sản phẩm B (ChatGPT) |
|---|---|---|
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung | Có (Rất tốt) | Có (Khá) |
| 2. Disclaimer khi không chắc ("không tìm được", "có thể sai") | Có | Có |
| 3. Fallback / dừng lại khi out-of-scope | Có | Một phần |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | Cao | Khá |
| 5. User control — sửa lại, dừng, regenerate, undo | Đầy đủ | Đầy đủ |
| 6. Explanation — giải thích "tại sao AI nói thế" (nếu có) | Một phần | Một phần |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed (cho mục S4)

Mỗi sản phẩm chọn **1** trong 3 góc tam giác (vẽ hình tay nếu cần — sẽ dán vào slide S4):

- **Sản phẩm A nghiêng về**: [mạnh-đắt] — lý do 1 câu: Tập trung vào chất lượng output và độ chính xác cho Pro users.
- **Sản phẩm B nghiêng về**: [cân bằng] — lý do 1 câu: Kết hợp tốt giữa khả năng search và sức mạnh hội thoại của LLM.

---

## Phần E — Verdict sơ bộ (cho mục S5.1)

Đặt verdict 1 dòng cho mỗi sản phẩm (sẽ tinh chỉnh lại ở Bước 3 sau khi vận dụng 4 Lens + Spark/Loop/System):

- **Sản phẩm A — verdict sơ bộ**: [Promising]
  - Lý do 1 câu: Đang làm rất tốt việc giải quyết nỗi lo tin cậy trong AI search.
- **Sản phẩm B — verdict sơ bộ**: [Strong]
  - Lý do 1 câu: Tận dụng được hệ sinh thái người dùng khổng lồ hiện có.

---

## Bảng kiểm trước khi sang Bước 3

- [ ] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [ ] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [ ] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [ ] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [ ] Còn ô nào thiếu bằng chứng → đã đánh dấu để Phase 3 đào thêm.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ (với S5 mở rộng 8 sub-mục) trước khi build slide.
