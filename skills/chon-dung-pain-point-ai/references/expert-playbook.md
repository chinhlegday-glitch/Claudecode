# Playbook Hội Đồng Chuyên Gia

Tổng hợp tư duy của 3 nhóm chuyên gia — **AI Automation**, **Đóng gói quy trình**, **Quản trị hiệu suất** — thành các nguyên tắc và công cụ áp dụng trực tiếp khi chọn pain point cho SME.

## 1. Lăng kính AI Automation

**Nguyên tắc:**
1. **Tự động hóa tác vụ, không tự động hóa công việc.** Tách công việc thành tác vụ; AI làm phần lặp lại, con người giữ phần phán đoán và quan hệ.
2. **Mức thấp nhất giải được bài toán thắng** (L1 trước L5). Công cụ có sẵn hôm nay > hệ thống hoàn hảo sau 6 tháng.
3. **Human-in-the-loop trong pilot.** AI soạn — người duyệt — rồi mới nới dần khi độ chính xác ổn định ≥ 95%.
4. **Dữ liệu/tri thức là nhiên liệu.** Một chatbot tệ thường do tài liệu tri thức tệ, không phải do AI tệ.

**Bài kiểm tra "Có phải bài toán AI không?" (4 câu trả lời CÓ trở lên là bài toán tốt):**
- [ ] Tác vụ lặp lại ≥ hằng tuần
- [ ] Có quy luật mà người giỏi có thể giải thích được
- [ ] Đầu vào là văn bản, số liệu, hình ảnh, giọng nói đã số hóa
- [ ] Sai sót có thể được phát hiện và sửa trước khi gây hậu quả lớn
- [ ] Có ví dụ "làm đúng" để AI học theo
- [ ] Kết quả đo được bằng thời gian, tiền, hoặc tỷ lệ

## 2. Lăng kính Đóng gói quy trình

**Nguyên tắc:** *Chuẩn hóa → Đơn giản hóa → Tự động hóa.* Đưa AI vào một quy trình lộn xộn chỉ làm sự lộn xộn chạy nhanh hơn.

**Bản đồ quy trình 1 trang (SIPOC rút gọn)** — làm cho mỗi bài toán Top 3:

| S — Nguồn cung | I — Đầu vào | P — Các bước (5–7 bước) | O — Đầu ra | C — Người nhận |
|----------------|-------------|--------------------------|------------|----------------|
| | | 1. … 2. … 3. … | | |

Sau đó đánh dấu từng bước: **🤖 AI làm** · **👤 Người làm** · **🤝 AI soạn – Người duyệt** · **❌ Bỏ đi (không tạo giá trị)**

**Đóng gói thành tài sản sau pilot:**
- SOP mới (có bước AI) — ai cũng làm theo được
- Thư viện prompt chuẩn (tên, mục đích, prompt, ví dụ đầu ra tốt)
- Checklist kiểm soát chất lượng đầu ra AI
- Video hướng dẫn 5–10 phút cho nhân viên mới

## 3. Lăng kính Quản trị hiệu suất

**Nguyên tắc:**
1. **Không baseline, không dự án.** Đo con số hiện tại ít nhất 1–2 tuần trước khi bật AI.
2. **1 dự án = 1 owner + 1 KPI chính (North Star) + 2–3 KPI phụ + 1 deadline.**
3. **Đo kết quả kinh doanh, không đo "mức độ dùng AI".** "Đã dùng chatbot" không phải KPI; "tỷ lệ chốt đơn inbox tăng từ 18% lên 25%" mới là KPI.
4. **Nhịp review cố định:** check-in 15 phút hằng tuần, đánh giá Go/Fix/Kill tại ngày 30, 60, 90.

**KPI gợi ý theo loại bài toán:**

| Loại bài toán | KPI chính | KPI phụ |
|---------------|-----------|---------|
| Chatbot / CSKH | Thời gian phản hồi TB | % câu hỏi bot tự xử lý, tỷ lệ chốt đơn inbox, CSAT |
| Content / Marketing | Giờ công/bài | Số bài/tuần, tương tác TB, chi phí/lead |
| Dự báo / Tồn kho | % tồn kho chết | Tỷ lệ hết hàng, vòng quay tồn kho |
| Nhập liệu / Đối soát | Giờ công/tháng | Tỷ lệ sai sót, thời gian chốt sổ |
| Sales enablement | Tỷ lệ chốt | Thời gian onboarding sales mới, giá trị đơn TB |

## 4. Công thức ROI cho SME

```
Lợi ích/tháng = (Giờ công tiết kiệm × Chi phí giờ công)
              + (Doanh thu tăng thêm × Biên lợi nhuận gộp)
              + Chi phí sai sót/thất thoát giảm được

Chi phí/tháng = Phí công cụ/API + (Chi phí thiết lập ÷ 12) + Giờ công vận hành × Chi phí giờ công

ROI (%)       = (Lợi ích/tháng − Chi phí/tháng) ÷ Chi phí/tháng × 100
Hoàn vốn      = Chi phí thiết lập ÷ (Lợi ích/tháng − Chi phí vận hành/tháng)
```

**Ví dụ — Chatbot đơn hàng cửa hàng thời trang:**
- Giờ công tiết kiệm: 2 nhân viên × 4h/ngày × 26 ngày = 208h × 40.000đ = **8,3 triệu**
- Đơn tăng thêm (inbox ngoài giờ): 60 đơn × 450.000đ × 40% biên = **10,8 triệu**
- Lợi ích ≈ **19,1 triệu/tháng**
- Chi phí: công cụ 1,5 triệu/tháng + thiết lập 12 triệu (÷12 = 1 triệu) + vận hành 10h × 40.000đ = 0,4 triệu → **2,9 triệu/tháng**
- ROI ≈ **559%**, hoàn vốn chi phí thiết lập < 1 tháng

**Ngưỡng ra quyết định:** ROI ≥ 200% và hoàn vốn ≤ 6 tháng = đáng làm cho SME.

## 5. 10 sai lầm thường gặp (và cách tránh)

| # | Sai lầm | Cách tránh |
|---|---------|-----------|
| 1 | Bắt đầu từ công cụ ("mình mua chatbot đi") | Bắt đầu từ nỗi đau có con số |
| 2 | Chọn bài toán "oai" nhất thay vì giá trị nhất | Tin vào ma trận có trọng số, không tin cảm tính |
| 3 | Chỉ một người (thường là chủ) chấm điểm | Chấm độc lập theo nhóm, lấy trung bình |
| 4 | Bỏ qua cổng chặn dữ liệu | Dữ liệu ≤ 2 điểm → loại khỏi danh sách hiện tại |
| 5 | Tự động hóa quy trình chưa chuẩn | Viết SOP trước, AI sau |
| 6 | Không đo baseline | Đo 1–2 tuần trước khi bật AI |
| 7 | Làm 5 dự án AI cùng lúc | SME < 20 người: 1 dự án; 20–200 người: tối đa 3 |
| 8 | Không có owner cụ thể | Mỗi dự án đúng 1 người chịu trách nhiệm |
| 9 | Để AI trả lời khách hàng không kiểm soát ngay từ đầu | Human-in-the-loop trong 30 ngày đầu |
| 10 | Không đóng gói lại sau pilot | Pilot thành công → SOP + thư viện prompt + đào tạo |

## 6. Câu hỏi khai vấn (dùng khi phỏng vấn chủ doanh nghiệp/trưởng phòng)

1. Việc gì anh/chị hoặc nhân viên làm đi làm lại mỗi ngày mà ghét nhất?
2. Nếu ngày mai mất người làm việc X, chuyện gì xảy ra?
3. Khách hàng phàn nàn nhiều nhất về điều gì?
4. Ở đâu tiền đang "rò rỉ" mà anh/chị biết nhưng chưa có thời gian xử lý?
5. Báo cáo nào anh/chị muốn có mỗi sáng mà hiện không có?
6. Quyết định nào anh/chị đang đưa ra theo cảm tính mà lẽ ra nên dựa trên số liệu?
7. Nếu có thêm 1 nhân viên miễn phí làm việc 24/7, anh/chị giao cho họ việc gì đầu tiên?
