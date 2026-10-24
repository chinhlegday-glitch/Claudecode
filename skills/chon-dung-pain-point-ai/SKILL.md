---
name: chon-dung-pain-point-ai
description: Chọn đúng pain point (nỗi đau) để ứng dụng AI — giúp doanh nghiệp vừa và nhỏ (SME) liệt kê, chấm điểm, ưu tiên và chọn ra Top 3 bài toán AI giá trị nhất, rồi biến bài toán số 1 thành dự án pilot 30-60-90 ngày có KPI đo được. Đi từ tổng thể đến chi tiết, từ chiến lược đến thực thi.
tags: [ai, automation, pain-point, prioritization, sme, process, performance]
version: 1.0.0
---

# Chọn Đúng Pain Point Để Ứng Dụng AI

> "Đừng hỏi *AI làm được gì?* — hãy hỏi *nỗi đau nào đang làm doanh nghiệp mất tiền nhiều nhất, và AI có giải được nó ngay bây giờ không?*"

Skill này đóng gói phương pháp **Ma trận Tác động × Khả thi** (10 tiêu chí tác động + 5 tiêu chí khả thi AI + ma trận quyết định có trọng số) thành một quy trình 7 bước dùng được ngay cho SME Việt Nam. Mục tiêu: **dồn nguồn lực vào 1–3 dự án AI tạo ra hiệu quả nhanh nhất**, tránh dàn trải, tránh "làm AI cho có", tránh quyết định theo cảm tính hoặc áp lực của một bộ phận.

## Khi nào dùng skill này

- Chủ doanh nghiệp muốn "ứng dụng AI" nhưng chưa biết bắt đầu từ đâu
- Có quá nhiều ý tưởng AI, các phòng ban tranh nhau ưu tiên
- Đã thử vài công cụ AI nhưng không ra kết quả đo được
- Cần lập kế hoạch/ngân sách AI cho quý hoặc năm
- Chuẩn bị workshop "Mapping 3 nỗi đau" với đội ngũ quản lý
- Muốn đánh giá lại danh mục dự án AI đang chạy (dừng / giữ / mở rộng)

## Hội đồng chuyên gia (các lăng kính tư duy)

Skill vận hành như một hội đồng gồm 3 nhóm chuyên gia. Mỗi quyết định phải đi qua cả 3 lăng kính:

| Lăng kính | Câu hỏi cốt lõi | Nguyên tắc vàng |
|-----------|-----------------|-----------------|
| **AI Automation** | Phần nào của quy trình là lặp lại, có quy luật, có dữ liệu? | Tự động hóa *tác vụ*, không tự động hóa *sự hỗn loạn*. Dùng AI có sẵn trước, tùy chỉnh sau. |
| **Đóng gói quy trình** | Quy trình đã chuẩn hóa chưa? Ai làm, làm gì, đầu vào/đầu ra là gì? | Chuẩn hóa → Đơn giản hóa → Tự động hóa. Quy trình chưa viết ra được thì chưa đưa AI vào được. |
| **Quản trị hiệu suất** | Đo bằng chỉ số nào? Baseline hiện tại bao nhiêu? Ai chịu trách nhiệm? | Không có baseline = không chứng minh được ROI. Mỗi dự án AI = 1 owner + 1 KPI chính + 1 deadline. |

**Chi tiết:** `references/expert-playbook.md`

## Quy trình 7 bước (từ tổng thể đến chi tiết)

```
CHIẾN LƯỢC          KHÁM PHÁ           ĐÁNH GIÁ              QUYẾT ĐỊNH          THỰC THI
[B1 Neo mục tiêu] → [B2 Liệt kê] → [B3 Tác động]  →  [B5 Ma trận   ] → [B6 Phân tích sâu] → [B7 Pilot 30-60-90]
                    [   & nhóm  ]   [B4 Khả thi AI]     [& trọng số  ]    [  Top 3        ]    [  + KPI         ]
```

### Bước 1 — Neo vào mục tiêu chiến lược (15 phút)

Trước khi nói về nỗi đau, chốt **1–3 mục tiêu kinh doanh 12 tháng** (ví dụ: tăng doanh thu 30%, giảm chi phí vận hành 15%, mở thêm 2 chi nhánh mà không tăng nhân sự văn phòng). Đây là "la bàn" cho tiêu chí #9 (Phù hợp chiến lược) và cho việc gán trọng số ở Bước 5.

Hỏi thêm: ngân sách AI tối đa cho 90 ngày đầu? Ai là người ra quyết định cuối? Ai có thể làm "AI champion" nội bộ?

### Bước 2 — Liệt kê & nhóm các nỗi đau (45–60 phút)

1. Brainstorm với đại diện **mọi phòng ban**: Marketing, Bán hàng, Vận hành, Tài chính, Nhân sự, CSKH (và Kho/Mua hàng nếu có).
2. Mỗi nỗi đau viết theo công thức: **"[Ai] mất [bao nhiêu thời gian/tiền] mỗi [tuần/tháng] vì [vấn đề cụ thể]"**
   - ❌ "CSKH quá tải"
   - ✅ "2 nhân viên CSKH mất ~6h/ngày trả lời lặp lại 20 câu hỏi về giá, size, ship qua Zalo/Fanpage; 15% tin nhắn sau 22h không được trả lời → mất đơn"
3. Gom nhóm theo lĩnh vực, gộp các nỗi đau trùng, tách nỗi đau quá to thành các vấn đề nhỏ có thể giải quyết độc lập.
4. Mục tiêu: 10–25 nỗi đau cụ thể. Gợi ý theo ngành: `references/sme-pain-point-library.md`

### Bước 3 — Chấm điểm TÁC ĐỘNG (Mức độ nghiêm trọng, 1–10)

Chấm theo **10 tiêu chí đánh giá tác động** (chi tiết thang điểm có mốc neo 1/5/10 trong `references/impact-criteria.md`):

| # | Tiêu chí | Câu hỏi nhanh |
|---|----------|---------------|
| 01 | Tác động tài chính | Mất bao nhiêu tiền/tháng (doanh thu mất + chi phí phát sinh)? |
| 02 | Tần suất xảy ra | Bao lâu xảy ra một lần? Hằng ngày hay hằng quý? |
| 03 | Phạm vi ảnh hưởng | Bao nhiêu người/bộ phận/khách hàng bị ảnh hưởng? |
| 04 | Tác động đến khách hàng | Có làm khách không hài lòng, rời bỏ, đánh giá xấu? |
| 05 | Thời gian & nguồn lực tiêu tốn | Bao nhiêu giờ công bị "đốt" vào việc này? |
| 06 | Tính cấp bách | Cần giải quyết ngay hay có thể chờ? Có deadline/áp lực thị trường? |
| 07 | Khả năng mở rộng giải pháp | Giải pháp có tái sử dụng cho vấn đề/bộ phận khác không? |
| 08 | Tác động đến hiệu suất làm việc | Ảnh hưởng năng suất, động lực, sự hài lòng của nhân viên? |
| 09 | Phù hợp với chiến lược | Có hỗ trợ mục tiêu chiến lược dài hạn (Bước 1) không? |
| 10 | Rủi ro nếu không giải quyết | Rủi ro pháp lý, tài chính, danh tiếng, vận hành? |

**Điểm Tác động** = trung bình có trọng số của 10 tiêu chí (mặc định trọng số bằng nhau; SME thường tăng trọng số #01, #05, #06).

### Bước 4 — Chấm điểm KHẢ THI cho AI (Tính phù hợp với AI, 1–10)

Chấm theo **5 tiêu chí đánh giá tính khả thi** (chi tiết `references/ai-feasibility-criteria.md`). *Lưu ý: điểm cao = DỄ triển khai.*

| # | Tiêu chí | 10 điểm khi… | 1 điểm khi… |
|---|----------|--------------|-------------|
| 01 | Dữ liệu sẵn có | Dữ liệu số hóa, đủ, sạch, truy cập được ngay | Không có dữ liệu → **không thể triển khai AI** |
| 02 | Độ phức tạp kỹ thuật | Dùng AI có sẵn (ChatGPT/Claude/Gemini, chatbot no-code) | Phải phát triển/huấn luyện mô hình riêng |
| 03 | Tích hợp hệ thống | Chạy độc lập hoặc nối 1 hệ thống có sẵn API | Phải tích hợp nhiều hệ thống cũ, không API |
| 04 | Ngân sách & thời gian | < 10 triệu VNĐ, chạy được trong < 4 tuần | > 500 triệu VNĐ, > 6 tháng |
| 05 | Năng lực nội bộ | Đội ngũ tự làm & tự duy trì được | Phải thuê chuyên gia ngoài toàn bộ |

**Cổng chặn (knock-out):** Nếu tiêu chí 01 (Dữ liệu) ≤ 2 → loại khỏi danh sách hiện tại, chuyển sang "dự án thu thập dữ liệu" trước.

### Bước 5 — Ma trận ưu tiên & điểm có trọng số

**5a. Vẽ ma trận 2×2** (trục dọc = Tác động 1–10, trục ngang = Khả thi 1–10, đường chia ở mức 6):

```
 Tác động
   10 ┌──────────────────────┬──────────────────────┐
      │  ② CƯỢC CHIẾN LƯỢC   │  ① LÀM NGAY          │
      │  Tác động cao,        │  Tác động cao,        │
      │  Khả thi thấp         │  Khả thi cao          │
      │  → Chuẩn bị dữ liệu,  │  → QUICK WIN: chọn    │
      │    lên lộ trình Q2-Q3 │    Top 3 từ đây       │
    6 ├──────────────────────┼──────────────────────┤
      │  ④ LOẠI BỎ            │  ③ LÀM NHANH, RẺ      │
      │  Tác động thấp,       │  Tác động thấp,       │
      │  Khả thi thấp         │  Khả thi cao          │
      │  → Không làm          │  → Dùng tool có sẵn,  │
      │                       │    giao cá nhân tự làm│
    1 └──────────────────────┴──────────────────────┘
      1                      6                     10  Khả thi
```

**5b. Tổng điểm (cột "Tổng điểm" trong template):**
- **Cách nhanh (workshop):** `Tổng điểm = Tác động × Khả thi` (thang 1–100). ≥ 49 (tức ≥ 7×7) = ứng viên mạnh.
- **Cách chuẩn (ma trận quyết định có trọng số):**
  1. Xác định các tiêu chí quan trọng (tác động doanh thu, tiết kiệm chi phí, trải nghiệm khách hàng, dữ liệu sẵn có…)
  2. Gán trọng số cho mỗi tiêu chí (**tổng = 100%**) theo ưu tiên doanh nghiệp
  3. Chấm điểm mỗi bài toán 1–10 cho từng tiêu chí
  4. Điểm có trọng số = Điểm × Trọng số
  5. Chọn bài toán có tổng điểm cao nhất

Bộ trọng số mẫu cho SME, ví dụ tính toán đầy đủ và cách xử lý hòa điểm: `references/priority-matrix-and-weighted-scoring.md`

### Bước 6 — Chọn Top 3 & phân tích sâu

Chọn 3 nỗi đau điểm cao nhất (ưu tiên góc ①). Với mỗi nỗi đau, trả lời 4 câu hỏi:

1. **Dữ liệu cần thiết để giải quyết** — dữ liệu gì, đang nằm ở đâu, ai sở hữu, chất lượng ra sao?
2. **Giải pháp AI tiềm năng** — công cụ/cách tiếp cận cụ thể (ưu tiên có sẵn → no-code → tùy chỉnh)
3. **Lợi ích kỳ vọng khi giải quyết** — quy ra VNĐ/tháng và giờ công/tháng, có baseline
4. **Rủi ro và thách thức** — dữ liệu, con người, pháp lý (Nghị định 13/2023 về bảo vệ dữ liệu cá nhân), chất lượng đầu ra AI

**Kiểm tra chéo trước khi chốt (sanity check):**
- [ ] Quy trình hiện tại đã viết ra được thành các bước rõ ràng chưa? (Nếu chưa → chuẩn hóa trước)
- [ ] Có 1 người chịu trách nhiệm (owner) cụ thể chưa?
- [ ] Đã đo được baseline (con số hiện tại) chưa?
- [ ] Pilot có thể ra kết quả đo được trong ≤ 30 ngày không?
- [ ] Nếu AI sai, hậu quả có kiểm soát được không? (có người duyệt cuối — human-in-the-loop)

Template: `templates/pain-point-mapping-template.md`

### Bước 7 — Biến bài toán #1 thành dự án pilot 30-60-90 ngày

| Giai đoạn | Mục tiêu | Đầu ra |
|-----------|----------|--------|
| **Ngày 0–30: Chứng minh** | Pilot nhỏ, 1 quy trình, 1 nhóm người dùng | Bản đồ quy trình (SOP), baseline, prototype chạy thật, KPI tuần 1–4 |
| **Ngày 31–60: Ổn định** | Sửa lỗi, chuẩn hóa prompt/quy trình, đào tạo | SOP mới có AI, checklist kiểm soát chất lượng, ROI thực tế |
| **Ngày 61–90: Nhân rộng** | Mở rộng sang bộ phận/quy trình tương tự (tiêu chí #07) | Quyết định Go / Fix / Kill, kế hoạch bài toán #2 |

Mỗi dự án có **Project Charter 1 trang**: `templates/ai-project-charter-template.md`

**Quy tắc Go / Fix / Kill tại ngày 30:**
- **GO** — đạt ≥ 70% KPI mục tiêu → sang giai đoạn ổn định
- **FIX** — đạt 30–70% → điều chỉnh 1 lần, đánh giá lại sau 2 tuần
- **KILL** — đạt < 30% hoặc phát sinh rủi ro không kiểm soát → dừng, rút bài học, chuyển nguồn lực sang bài toán #2

## Ví dụ nhanh: Cửa hàng thời trang

| Góc phần tư | Bài toán AI |
|-------------|-------------|
| ① Tác động cao, Khả thi cao | Dự báo xu hướng sản phẩm bán chạy · Tự động phân loại sản phẩm trên website · Chatbot hỗ trợ đơn hàng cơ bản |
| ② Tác động cao, Khả thi thấp | Hệ thống thử đồ ảo cho khách hàng · Dự đoán hành vi khách hàng cá nhân |
| ③ Tác động thấp, Khả thi cao | Tự động trả lời email thông thường · Phân tích cảm xúc từ đánh giá |
| ④ Tác động thấp, Khả thi thấp | Nhận diện khách hàng tại cửa hàng · Robot tư vấn trong cửa hàng |

Bảng chấm điểm đầy đủ cho ví dụ này: `references/priority-matrix-and-weighted-scoring.md`

## Định dạng đầu ra

Khi chạy skill, luôn trả về theo cấu trúc:

1. **Tóm tắt điều hành** (3–5 dòng): Top 3 bài toán, bài toán #1, lợi ích kỳ vọng (VNĐ/tháng), chi phí ước tính, thời gian ra kết quả
2. **Bảng Mapping nỗi đau** (đủ cột: Nỗi đau · Mô tả · Bộ phận · Tác động · Khả thi AI · Tổng điểm · Góc phần tư)
3. **Ma trận 2×2** (dạng ASCII hoặc bảng)
4. **Phân tích sâu Top 3** (4 câu hỏi của Bước 6)
5. **Project Charter cho bài toán #1** + lộ trình 30-60-90
6. **Danh sách "KHÔNG làm lúc này"** (góc ③④ và lý do) — để đội ngũ không phân tán
7. **Bước tiếp theo trong 7 ngày** (tối đa 5 hành động, mỗi hành động có người phụ trách)

## Nguyên tắc bắt buộc

- **Nỗi đau trước, công nghệ sau.** Không bắt đầu bằng "mình có nên dùng chatbot không?"
- **Định lượng mọi thứ.** Mỗi nỗi đau phải có ít nhất 1 con số (giờ, VNĐ, %, số đơn).
- **Ít mà chất.** Tối đa 1 dự án AI chạy song song cho doanh nghiệp < 20 người; tối đa 3 cho doanh nghiệp 20–200 người.
- **Chấm điểm theo nhóm, không theo một người.** Mỗi người chấm độc lập rồi lấy trung bình; chênh lệch > 3 điểm thì thảo luận lại.
- **Dữ liệu là cổng chặn.** Không có dữ liệu = không có AI.
- **Con người duyệt cuối** với mọi đầu ra AI chạm tới khách hàng, tiền, hoặc pháp lý trong giai đoạn pilot.

## Tài nguyên

**References:**
- `references/impact-criteria.md` — 10 tiêu chí tác động + thang điểm có mốc neo
- `references/ai-feasibility-criteria.md` — 5 tiêu chí khả thi AI + thang điểm + cổng chặn
- `references/priority-matrix-and-weighted-scoring.md` — ma trận 2×2, bộ trọng số mẫu, ví dụ tính toán
- `references/sme-pain-point-library.md` — thư viện nỗi đau phổ biến của SME theo phòng ban + giải pháp AI gợi ý
- `references/expert-playbook.md` — tư duy 3 nhóm chuyên gia, công thức ROI, sai lầm thường gặp

**Templates:**
- `templates/pain-point-mapping-template.md` — template workshop "Mapping 3 nỗi đau" (điền được ngay)
- `templates/ai-project-charter-template.md` — Project Charter 1 trang + KPI tracker 30-60-90
