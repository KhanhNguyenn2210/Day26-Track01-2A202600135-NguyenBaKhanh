---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút (xem deck slide 4 để biết khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu: tìm 1 case bị big tech AI ảnh hưởng + số liệu thật

Mục tiêu: bạn tự chọn 1 sản phẩm hoặc 1 công ty bị ảnh hưởng nặng sau khi big tech AI (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...) ra mắt tính năng tương tự. Tự tìm số liệu cụ thể về case đó từ nguồn công khai. Mỗi số liệu phải có nguồn (URL + tên báo/tổ chức + ngày tháng). Lab 1 là phần cá nhân — mỗi học viên tự chọn case riêng và tự làm phần research trong repo cá nhân.

Lý do làm bước này: phân tích chỉ có sức nặng khi đứng trên số liệu thật. Bạn cần tự tìm ít nhất 8-10 số liệu cụ thể để có nền tảng phản biện cho 4 câu hỏi ở phase 2.

Quy tắc: **không có số liệu = không có nhận định**. Học viên tự tìm số liệu cho case mình chọn. Mỗi nhận định phải có nguồn (URL + ngày).

## Bước 0 — Chọn case (5 phút đầu)

Trước khi tìm số liệu, bạn quyết định case nào:

1. Sản phẩm/công ty bạn chọn là gì?
2. Big tech AI nào ra tính năng tương tự gây ảnh hưởng? (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...)
3. Vì sao bạn chọn case này? (Có số liệu công khai? Có mốc thời gian rõ? Có liên hệ với ngành bạn quan tâm?)

Ghi câu trả lời ngắn vào ô dưới đây trước khi bắt đầu tìm số liệu.

- **Tên case**: Chegg
- **Big tech AI tạo áp lực**: ChatGPT (OpenAI)
- **Lý do chọn**: Đây là case điển hình nhất về việc một sản phẩm "Content-as-a-service" bị sụp đổ nhanh chóng khi AI có khả năng tự tạo nội dung miễn phí. Có đầy đủ số liệu tài chính công khai và phát ngôn từ CEO.

## Quy trình 15 phút

```text
5 phút  — Chọn case + xác định 4 nhóm số liệu cần tìm cho case của mình
8 phút  — Tự tìm số liệu trên các nguồn chính (báo chí công nghệ, báo cáo tài chính, blog chính thức...)
2 phút  — Rà lại bảng số liệu, đánh dấu số chưa kiểm chứng
```

---

## Phần A — Các nhóm số liệu cần tìm

Bạn tự tìm đủ 4 nhóm số liệu dưới đây cho case mình chọn. Tên nhóm giữ nguyên — nội dung cụ thể bạn tự điền theo case.

### Nhóm 1 — Quy mô trước & sau (cổ phiếu, doanh thu, người dùng)

- **S-01: Giá cổ phiếu sụt giảm kỷ lục**
  - Giá trị: Giảm ~48% trong 1 phiên giao dịch.
  - Ngày: 02/05/2023.
  - Nguồn: CNBC, "Chegg shares drop more than 40% after company says ChatGPT is hurting its business". URL: https://www.cnbc.com/2023/05/02/chegg-shares-drop-more-than-40-percent-on-soft-revenue-guidance-after-chatgpt-hit.html
  - Mức tin cậy: ✅ verified

- **S-02: Số lượng người dùng (Subscribers)**
  - Giá trị: Giảm từ 8.2 triệu (Q1 2023) xuống còn ~7.7 triệu (cuối 2023) và tiếp tục giảm xuống ~6.6 triệu (2024).
  - Nguồn: Báo cáo tài chính năm (Annual Report) của Chegg 2023, 2024. URL: https://investor.chegg.com/
  - Mức tin cậy: ✅ verified

- **S-03: Doanh thu (Revenue)**
  - Giá trị: 2023 đạt ~716 triệu USD (giảm 6.6% YoY), dự báo 2024 tiếp tục giảm xuống ~618 triệu USD.
  - Nguồn: MacroTrends & Chegg IR. URL: https://www.macrotrends.net/stocks/charts/CHGG/chegg/revenue
  - Mức tin cậy: ✅ verified

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

- **S-04: Ngày ra mắt ChatGPT**
  - Ngày: 30/11/2022.
  - Nguồn: OpenAI Blog. URL: https://openai.com/blog/chatgpt
  - Mức tin cậy: ✅ verified

- **S-05: Sự kiện "ChatGPT Shock" với Chegg**
  - Ngày: May 2023 (Earnings Call Q1).
  - Nội dung: CEO Dan Rosensweig thừa nhận ChatGPT ảnh hưởng đến tốc độ tăng trưởng người dùng mới.
  - Nguồn: Reuters. URL: https://www.reuters.com/technology/chegg-shares-halve-valuation-after-chatgpt-warning-2023-05-02/
  - Mức tin cậy: ✅ verified

### Nhóm 3 — Phản ứng của case sau khi big tech AI ra mắt

- **S-06: Ra mắt CheggMate**
  - Ngày: 17/04/2023.
  - Nội dung: Hợp tác với OpenAI dùng GPT-4 để xây dựng trợ lý học tập riêng.
  - Nguồn: Chegg Press Release. URL: https://www.chegg.com/press/chegg-announces-cheggmate/
  - Mức tin cậy: ✅ verified

- **S-07: Cắt giảm nhân sự**
  - Giá trị: Sa thải 4% nhân viên (khoảng 80 người) vào tháng 6/2023 và tiếp tục đợt sa thải lớn 23% nhân sự (~441 người) vào tháng 6/2024.
  - Nguồn: TechCrunch. URL: https://techcrunch.com/2024/06/17/edtech-giant-chegg-to-lay-off-23-of-its-workforce/
  - Mức tin cậy: ✅ verified

### Nhóm 4 — Đối thủ AI thay thế

- **S-08: Tăng trưởng của ChatGPT trong giáo dục**
  - Giá trị: 100 triệu người dùng hàng tuần (Weekly Active Users) tính đến tháng 11/2023, trong đó sinh viên là tệp khách hàng lớn.
  - Nguồn: OpenAI DevDay.
  - Mức tin cậy: ✅ verified

- **S-09: Đối thủ AI khác (Perplexity, Claude)**
  - Nội dung: Perplexity AI cung cấp khả năng dẫn nguồn (citation) cực tốt, thay thế trực tiếp tính năng tra cứu bài giải của Chegg.
  - Mức tin cậy: ✅ verified

---

## Phần B — Bảng tổng hợp

| # | Số liệu | Giá trị | Ngày | Nguồn | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Cổ phiếu giảm | -48% | 02/05/2023 | CNBC | ✅ |
| S-02 | Subscribers | 6.6M (2024) | 2024 | IR Page | ✅ |
| S-03 | Doanh thu | 618M USD | 2024 | MacroTrends | ✅ |
| S-04 | ChatGPT launch | 30/11/2022 | 30/11/2022 | OpenAI | ✅ |
| S-05 | CEO admission | ChatGPT impact | 02/05/2023 | Reuters | ✅ |
| S-06 | CheggMate launch| GPT-4 collab | 17/04/2023 | Chegg PR | ✅ |
| S-07 | Layoffs | -23% staff | 17/06/2024 | TechCrunch | ✅ |
| S-08 | ChatGPT WAU | 100M | 11/2023 | OpenAI | ✅ |

Tuỳ case, chọn các chỉ số phù hợp:

- Cổ phiếu / vốn hoá: đỉnh cao + hiện tại (nếu là công ty niêm yết).
- Doanh thu: trước khi big tech AI ra tính năng + sau đó (so sánh quý / năm).
- Người dùng trả tiền / hoạt động: đỉnh + hiện tại.
- Tỷ lệ giảm tổng cộng (%).

Nguồn nên dùng:

- Yahoo Finance, MacroTrends, Google Finance — cho công ty niêm yết.
- Báo cáo quý / 10-K filing (Investor Relations của chính công ty).
- Báo công nghệ: TechCrunch, CNBC, Bloomberg, Reuters, FT.

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

Tìm:

- Tính năng AI cụ thể của big tech (vd: ChatGPT, Gemini Code Assist, Copilot, …).
- Ngày ra mắt + ngày mở rộng người dùng.
- Tốc độ phổ cập của tính năng đó (số người dùng sau 6 tháng, 1 năm).
- Mức độ trùng lặp với sản phẩm của case bạn chọn (tính năng nào trùng?).

Nguồn nên dùng:

- Blog chính thức của big tech (OpenAI blog, Anthropic blog, Google blog, GitHub blog).
- Báo công nghệ.

### Nhóm 3 — Phản ứng của sản phẩm / công ty sau khi big tech AI ra mắt

Tìm:

- Sản phẩm AI / tính năng mới mà công ty đã ra: tên + ngày ra mắt.
- Đối tác AI: dùng model nào dưới mui xe.
- Thời gian từ khi big tech AI ra mắt đến khi công ty này có sản phẩm AI: ___ tháng.
- Đợt sa thải / cắt giảm / tái cơ cấu (nếu có): số người + tỷ lệ + ngày.
- Thông báo delisting / mua bán sáp nhập / đóng cửa (nếu có).

Nguồn nên dùng:

- Báo cáo quý của công ty.
- Báo công nghệ và báo kinh doanh.
- TechCrunch, Bloomberg, CNBC.

### Nhóm 4 — Đối thủ AI thay thế

Tìm:

- Big tech AI thay thế sản phẩm này ở use case cụ thể nào?
- Có đối thủ startup khác cũng đang thay thế không (tên + ngày ra mắt + giá)?
- So sánh giá: sản phẩm gốc vs big tech AI vs startup khác (giá/tháng).

Nguồn nên dùng:

- Trang giá chính thức của từng sản phẩm.
- Báo công nghệ.

---

## Phần B — Bảng tổng hợp số liệu

Sau khi tìm đủ 4 nhóm số liệu, bạn gộp vào bảng dưới đây. Mục tiêu: tối thiểu 8-10 số liệu có nguồn cụ thể.

### Bảng số liệu case [tên case]

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Quy mô đỉnh (cổ phiếu / doanh thu / user) | | / / | | Có / Chưa |
| S-02 | Quy mô hiện tại | | / / | | |
| S-03 | Big tech AI ra tính năng tương tự — ngày | | / / | | |
| S-04 | Sản phẩm AI của công ty ra mắt — ngày + tên | | / / | | |
| S-05 | Khoảng cách thời gian (big tech AI → phản ứng) | ___ tháng | | | |
| S-06 | Đợt sa thải / cắt giảm | ___% | / / | | |
| S-07 | Doanh thu mới nhất (so YoY) | | | | |
| S-08 | Đối thủ AI thay thế — tên + thời điểm | | / / | | |
| S-09 | Giá sản phẩm gốc vs big tech AI | $___ vs $___ | | | |
| S-10 | [Thêm dòng nếu tìm được số đặc biệt] | | | | |

Bổ sung dòng nếu bạn tìm thêm số liệu nào liên quan.

---

## Phần C — Kiểm chứng nguồn

Trước khi chuyển sang phân tích, rà lại từng số liệu:

### Checklist kiểm chứng

- [ ] Mỗi số liệu có URL nguồn cụ thể.
- [ ] URL mở được, không 404.
- [ ] Nội dung URL có khớp với số liệu mình ghi (ít nhất là cùng đơn vị, cùng năm).
- [ ] Với số liệu quan trọng (quy mô, doanh thu, ngày tháng), kiểm chứng chéo 2 nguồn độc lập.
- [ ] Nếu chưa chắc, đánh dấu `[CHƯA KIỂM CHỨNG]` thay vì xoá.

### Quy tắc loại nguồn

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 — Nguồn gốc | Báo cáo tài chính, thông báo chính thức, hồ sơ pháp lý | 10-K filings, SEC filings, blog công ty |
| 2 — Báo lớn | Báo chí công nghệ/kinh doanh uy tín | CNBC, Bloomberg, TechCrunch, Reuters, FT |
| 3 — Báo cáo phân tích | Báo cáo tài chính độc lập | MacroTrends, Yahoo Finance, Google Finance |
| 4 — Tránh dùng | Bài đăng cá nhân, blog không nguồn, mạng xã hội | Reddit posts, Medium articles không có citation |

### Cảnh báo

AI có thể bịa cả nguồn — đặc biệt khi bạn hỏi AI số liệu thay vì tự tìm. Nếu dùng AI để gợi ý nơi tìm, vẫn phải tự mở URL và xác minh.

---

## Phần D — Phát hiện ban đầu

Sau khi có số liệu, ghi nhanh 3-5 phát hiện đáng chú ý nhất. Đây chưa phải nhận định cuối — chỉ là quan sát.

Ví dụ format (không phải case mẫu — bạn viết theo case mình chọn):

- "Doanh thu của [case] giảm ___% trong 18 tháng kể từ khi big tech AI ra tính năng tương tự."
- "[Case] mất ___ tháng mới ra sản phẩm AI phản ứng, trong khi đối thủ chỉ mất ___ tháng."
- "Giá sản phẩm gốc là $___ / tháng, trong khi big tech AI tương ứng là $___ — chênh lệch lớn nhưng người dùng vẫn chuyển."

Phát hiện của bạn:

- [...]
- [...]
- [...]
- [...]
- [...]

---

## Phần E — Câu hỏi mở (cho phân tích Phần 2)

Trước khi chuyển sang `2-analysis.md`, bạn liệt kê các câu hỏi cần đào sâu:

- Câu hỏi 1: [...]
- Câu hỏi 2: [...]
- Câu hỏi 3: [...]
- Câu hỏi 4: [...]

Sau bước này, chuyển sang `2-analysis.md` để vận dụng Lens 1 (Customer Expectations + Four Fits) vào case bạn chọn.
