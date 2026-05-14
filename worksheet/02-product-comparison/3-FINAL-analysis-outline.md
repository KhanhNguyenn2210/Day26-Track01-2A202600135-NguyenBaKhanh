---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

Mục tiêu: dựng outline đầy đủ cho slide deck Analysis Report ngay trong file markdown — viết hết nội dung 5 mục ở đây trước, sau đó copy sang slide (pptx / Keynote / Google Slides). Không build slide trước khi outline xong.

Lý do làm bước này: dựng thẳng slide từ log dễ bị thiếu mục hoặc bị "đẹp ngoài rỗng trong". Outline markdown ép nhóm trả lời từng câu hỏi trước khi nghĩ về thiết kế slide. Khi giảng viên / nhóm khác hỏi "vì sao bạn xếp Sản phẩm A là Promising?" — câu trả lời đã có sẵn trong outline.

Quy tắc: mỗi nhận định trong outline phải nối được về bằng chứng cụ thể (ảnh / log / số liệu công khai). Nếu một sub-mục để trống → quay lại `1-research-notes.md` đào thêm trước khi sang slide.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để có context
8 phút  — Điền outline 5 mục (S1 → S5)
4 phút  — Riêng cho S5: mở rộng 8 sub-mục (S5.1 → S5.8)
1 phút  — Đối chiếu bảng kiểm trước khi build slide
```

> Sau 15 phút outline + đối chiếu, mới mở pptx / Google Slides / Keynote và copy nội dung sang. Slide deck export thành `analysis-report.pdf` ở cùng folder này.

---

## Thông tin chung của báo cáo

- **Mã thành viên + tên**: [A20-00135 (Nguyễn Bá Khánh)]
- **Ngành chọn**: [A — Tìm kiếm]
- **Nhiệm vụ chung đã test**: Tra cứu quy định quyết toán thuế TNCN 2024 tại Việt Nam cho cá nhân có thu nhập từ 2 nơi.
- **Sản phẩm A** (tên + URL): Perplexity AI - https://www.perplexity.ai
- **Sản phẩm B** (tên + URL): ChatGPT Search - https://chatgpt.com
- **Câu prompt chính xác đã dùng**: "Hướng dẫn chi tiết các bước quyết toán thuế TNCN năm 2024 tại Việt Nam cho cá nhân có thu nhập từ 2 nơi trở lên. Cần dẫn nguồn các thông tư, nghị định và thời hạn nộp hồ sơ cụ thể."

---

## S1 — Product Moment (slide 1-2)

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, điểm gặp đầu (entry point).

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A (Perplexity) | Sản phẩm B (ChatGPT Search) |
|---|---|---|
| Tên + URL | Perplexity AI | ChatGPT |
| Entry point (trang đầu nhìn thấy gì) | Thanh search "Ask anything" | Khung chat với các gợi ý công việc |
| Ý định người dùng (vào để làm gì) | Tìm câu trả lời có dẫn nguồn | Hỏi đáp, hỗ trợ công việc đa năng |
| Surface chính (chat / form / canvas / IDE / khác) | Chat / Answer Engine | Conversational Chat |
| Có cần đăng nhập / paywall ngay không | Không bắt buộc | Yêu cầu login để dùng Search tốt nhất |

### S1.2 — Bằng chứng (ảnh tham chiếu)

- `screenshots/product-A-1-entry.png` — mô tả 1 câu: [...]
- `screenshots/product-B-1-entry.png` — mô tả 1 câu: [...]

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Perplexity tạo ấn tượng tốt hơn cho nhiệm vụ Research nhờ sự tập trung vào thanh search. ChatGPT cho cảm giác đa năng nhưng tốn thêm 1 click để kích hoạt Search mode nếu không tự động.

---

## S2 — Workflow Evidence (slide 3-4)

Mục đích: hiển thị luồng người dùng + 3 friction areas (Lens 3).

### S2.1 — Luồng người dùng (trước / trong / sau khi dùng AI)

```text
TRƯỚC khi gặp AI:
- Người dùng tra cứu Google Search, click vào từng link (Thư viện pháp luật, báo chí) để tổng hợp.

TRONG khi dùng Sản phẩm A (Perplexity):
1. Nhập prompt về thuế TNCN.
2. Theo dõi AI duyệt các nguồn (Browsing).
3. Đọc câu trả lời có dẫn nguồn số hóa (1, 2, 3).

TRONG khi dùng Sản phẩm B (ChatGPT):
1. Nhập prompt.
2. AI hiển thị icon "Searching" và trả lời dạng văn bản mượt mà.
3. Người dùng hỏi thêm về các trường hợp ngoại lệ.

SAU khi dùng AI:
- Copy hướng dẫn và danh sách thông tư để chuẩn bị hồ sơ quyết toán.
```

### S2.2 — 3 Friction Areas (Lens 3)

| Friction | Sản phẩm A | Sản phẩm B |
|---|---|---|
| **Physical load** | Thấp (1 click xem nguồn) | Trung bình (icon nhỏ khó click) |
| **Cognitive burden** | Trung bình (cần verify nguồn) | Thấp (giải thích rất dễ hiểu) |
| **User workarounds** | Prompt thêm để lấy bảng biểu | Prompt thêm để yêu cầu trích luật |

### S2.3 — Bằng chứng

- `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png`
- `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

### S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn? Tại sao? (3-4 câu)

Perplexity giảm physical load tốt hơn cho khâu xác thực dữ liệu. ChatGPT giảm cognitive burden tốt hơn nhờ cách hành văn thân thiện. Với dự án Thuế, Perplexity đang có lợi thế hơn ở khâu "Verification".

---

## S3 — Output & Trust (slide 5-6)

Mục đích: đánh giá chất lượng output + 6 tín hiệu đáng tin.

### S3.1 — Chất lượng output

- **Sản phẩm A**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, đầy đủ các bước.
  - Output có **bịa thông tin** không? Không phát hiện, dẫn nguồn chính xác.
  - Output có **đầy đủ** hay nửa vời? Đầy đủ, có cả thời hạn nộp.
- **Sản phẩm B**:
  - Output có **trả lời đúng câu hỏi** chính không? Có.
  - Output có **bịa thông tin** không? Không.
  - Output có **đầy đủ** hay nửa vời? Khá đầy đủ, nhưng thiếu chi tiết về các mẫu tờ khai cụ thể.

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu | Sản phẩm A | Sản phẩm B |
|---|---|---|
| 1. Dẫn nguồn | Có (Tuyệt vời) | Có (Khá) |
| 2. Disclaimer khi không chắc | Có | Có |
| 3. Fallback / dừng lại khi out-of-scope | Có | Một phần |
| 4. Consistency | Cao | Khá |
| 5. User control | Đầy đủ | Đầy đủ |
| 6. Explanation | Có | Một phần |

### S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn? Vì sao? (3-4 câu)

Perplexity tạo trust mạnh hơn nhờ hệ thống citation minh bạch. Với các tác vụ liên quan đến pháp luật/thuế, việc kiểm chứng nguồn là quan trọng nhất, và Perplexity đã biến điều này thành lợi thế cạnh tranh cốt lõi.

---

## S4 — Business Signal (slide 7)

Mục đích: định vị 2 sản phẩm trên Cost-Capability-Speed + pricing pattern.

### S4.1 — Định vị tam giác (cho mỗi sản phẩm)

- **Sản phẩm A**: [mạnh-đắt] — model dưới mui xe: Sonar/GPT-4o — lý do định vị 1 câu: Ưu tiên Capability và Reliability cho Research.
- **Sản phẩm B**: [cân bằng] — model dưới mui xe: GPT-4o — lý do định vị 1 câu: Hướng tới trải nghiệm người dùng toàn diện.

### S4.2 — Pricing pattern

| Yếu tố | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Mô hình giá | Freemium | Freemium |
| Giá entry (free tier giới hạn gì) | Free (Giới hạn Pro Search) | Free (Giới hạn GPT-4o quota) |
| Giá trả phí (gói chính + giá) | $20/tháng | $20/tháng |
| Paywall xuất hiện | Khi dùng tính năng Pro | Khi hết quota model mạnh nhất |

### S4.3 — Nhận định: chiến lược kinh doanh của 2 sản phẩm khác nhau thế nào? (2-3 câu)

Perplexity tập trung vào Niche người dùng chuyên sâu (Pro-sumer). ChatGPT tập trung vào Mass market bằng cách hạ thấp rào cản sử dụng.

---

## S5 — Product Judgment (slide 8-12 — phần đậm nhất)

Mục đích: ra verdict + vận dụng 4 Lens + Spark/Loop/System + Niche/Feature Map + liên hệ Lab 1.

S5 mở rộng thành 8 sub-mục — bắt buộc xong **S5.1, S5.6, S5.7, S5.8**. Nhóm khá phải hoàn thành cả 8 sub-mục. Nhóm Đạt có thể ghi "không có nguồn công khai" cho 1-2 số liệu ở S5.2-S5.5 nhưng phải ghi rõ.

### S5.1 — Verdict (BẮT BUỘC)

- **Sản phẩm A**: **Promising** — Lý do: Có moat cực mạnh về sự tin tưởng trong ngách search học thuật/nghiên cứu.
- **Sản phẩm B**: **Strong** — Lý do: Vị thế dẫn đầu thị trường và khả năng đa nhiệm không đối thủ.

### S5.2 — User base + tăng trưởng

- **Sản phẩm A**: ~50 triệu MAU (tháng 3/2024). Nguồn: Reuters.
- **Sản phẩm B**: ~200 triệu MAU (tháng 8/2024). Nguồn: OpenAI Official.

### S5.3 — Doanh thu / pricing power

- **Sản phẩm A**: ARR dự báo ~$20M - $30M (2024). Nguồn: Forbes. Chiến lược: Freemium tập trung vào Pro users.
- **Sản phẩm B**: ARR dự báo >$3.4B (2024). Nguồn: Bloomberg. Chiến lược: Đa dạng hóa nguồn thu từ API, Plus, Team và Enterprise.

### S5.4 — Moat phân tích (5 loại)

| Moat | Sản phẩm A (Perplexity) | Sản phẩm B (ChatGPT) |
|---|---|---|
| Data (proprietary data flywheel) | Trung bình (dựa vào web indexing) | Mạnh (dữ liệu tương tác khổng lồ) |
| Network effects | Yếu | Trung bình (hệ sinh thái GPTs) |
| Switching cost | Trung bình (lịch sử thread) | Cao (Personalization, History) |
| Brand | Mạnh (ngách Search) | Rất mạnh (AI synonym) |
| Distribution | Trung bình (Web/App) | Rất mạnh (Tích hợp Apple/Microsoft) |

### S5.5 — Data flywheel + feedback loop

- **Sản phẩm A**: Loop dựa trên việc người dùng click và đánh giá nguồn. Càng nhiều người dùng -> Web indexing càng tối ưu cho câu hỏi thực tế.
- **Sản phẩm B**: Loop cực mạnh. Mỗi lượt chat giúp model hiểu ngữ cảnh và nhu cầu người dùng tốt hơn -> Model đời sau thông minh hơn.

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

- **Sản phẩm A**:
  - Niche cụ thể: Chuyên gia, sinh viên nghiên cứu, người làm luật/thuế.
  - AI Feature Map:
    - User Value: Cao — Giảm thời gian tổng hợp nguồn.
    - User Alignment: Cao — Giao diện search kết hợp citation.
    - Business Value: Cao — Khả năng upsell gói Pro cho DN.
- **Sản phẩm B**:
  - Niche cụ thể: Người dùng phổ thông, content creator, lập trình viên.
  - AI Feature Map:
    - User Value: Cao — Trợ lý toàn năng.
    - User Alignment: Cao — Chat mượt mà.
    - Business Value: Rất cao — Platform hóa dịch vụ AI.

### S5.7 — Spark → Loop → System (BẮT BUỘC)

- **Sản phẩm A**: [Loop] — Lý do: Đã có vòng lặp giữ chân người dùng qua lịch sử research. — Dự báo 12 tháng tới: Sẽ tích hợp sâu hơn vào các công cụ viết lách.
- **Sản phẩm B**: [System] — Lý do: Đã trở thành một hệ sinh thái với Store, API. — Dự báo 12 tháng tới: Sẽ thay thế phần lớn Google Search truyền thống.

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

- Sản phẩm A có rủi ro disruption tương tự case nào của nhóm? Case Google Search (với Big Tech AI là ChatGPT).
- Sản phẩm B có rủi ro disruption tương tự case nào của nhóm? Case các công ty phần mềm truyền thống (như Chegg, Jasper).
- Bài học rút từ Lab 1 áp dụng được cho 2 sản phẩm này thế nào? (2-3 câu): Luôn phải xây dựng Moat vượt ra ngoài nội dung thô. ChatGPT đang làm điều này bằng System, Perplexity bằng Trust.

---

## Bảng kiểm trước khi build slide

- [ ] S1 → S4 đã điền đầy đủ.
- [ ] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành (4 sub-mục bắt buộc).
- [ ] S5.2 → S5.5 đã hoàn thành (hoặc đã ghi rõ "không có nguồn công khai" cho ô trống).
- [ ] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [ ] Verdict ở S5.1 nhất quán với phân tích moat ở S5.4 và giai đoạn ở S5.7.
- [ ] 2 thành viên cùng đồng ý với toàn bộ outline.

---

## Sau khi xong outline

1. Mở pptx / Keynote / Google Slides / Figma.
2. Tạo 12-15 slide bám theo cấu trúc S1 → S5 ở trên (mỗi mục 1-3 slide).
3. **Mỗi slide có ít nhất 1 ảnh tham chiếu** (từ `screenshots/`).
4. Export PDF → lưu thành `analysis-report.pdf` trong cùng folder này.
5. Nếu dùng Google Slides công khai, lưu link vào `analysis-report-link.md` (tuỳ chọn).
6. 2 thành viên cùng copy `analysis-report.pdf` + `group-members.md` về repo cá nhân của mình.

> Tham khảo `prompts/08-analysis-report.md` nếu cần AI hỗ trợ build slide từ outline này.
