# 5 Tiêu Chí Đánh Giá Tính Khả Thi Cho AI

Dùng để chấm **Tính phù hợp với AI (Khả thi)** của mỗi nỗi đau, thang 1–10. **Điểm cao = dễ triển khai.** Các tiêu chí "phức tạp", "tích hợp", "ngân sách" chấm ngược: càng phức tạp/tốn kém → điểm càng thấp.

## 01 — Dữ liệu sẵn có (CỔNG CHẶN)
*Đánh giá lượng và chất lượng dữ liệu hiện có. AI cần dữ liệu chất lượng và đủ số lượng để học. Không có dữ liệu = không thể triển khai AI.*

| Điểm | Mốc neo |
|------|---------|
| 1–2 | Không có dữ liệu, hoặc chỉ nằm trong đầu nhân viên → **LOẠI / chuyển sang dự án thu thập dữ liệu** |
| 3–4 | Có nhưng rải rác (giấy, tin nhắn Zalo, file Excel mỗi người một kiểu) |
| 5–6 | Số hóa một phần, cần làm sạch 2–4 tuần |
| 7–8 | Số hóa, tập trung (Google Sheets, phần mềm bán hàng, CRM), cần làm sạch nhẹ |
| 9–10 | Dữ liệu sạch, có cấu trúc, truy xuất được qua API/export ngay |

Câu hỏi kiểm tra: Dữ liệu ở đâu? Có bao nhiêu bản ghi / bao nhiêu tháng? Ai sở hữu? Có chứa dữ liệu cá nhân khách hàng không (cần tuân thủ Nghị định 13/2023/NĐ-CP)?

> Với bài toán dùng LLM (chatbot, soạn nội dung, tóm tắt), "dữ liệu" thường là **tài liệu tri thức**: bảng giá, FAQ, chính sách đổi trả, mô tả sản phẩm, kịch bản bán hàng. Nếu những tài liệu này chưa có → viết chúng ra là bước 0.

## 02 — Độ phức tạp kỹ thuật
*Mức độ phức tạp của giải pháp AI cần thiết. Một số vấn đề có thể sử dụng AI có sẵn, trong khi những vấn đề khác cần phát triển tùy chỉnh.*

| Điểm | Mốc neo | Ví dụ |
|------|---------|-------|
| 9–10 | Dùng ngay AI có sẵn qua giao diện chat | ChatGPT/Claude/Gemini soạn content, tóm tắt họp, viết email |
| 7–8 | Công cụ no-code / SaaS có tính năng AI | Chatbot Fanpage/Zalo OA, Make/n8n + AI, Canva AI |
| 5–6 | Cấu hình + prompt engineering + kết nối API đơn giản | Chatbot có knowledge base (RAG), tự động phân loại email |
| 3–4 | Tùy chỉnh đáng kể, cần lập trình viên | Dự báo nhu cầu từ dữ liệu bán hàng, OCR chứng từ riêng |
| 1–2 | Huấn luyện mô hình riêng, nghiên cứu | Thử đồ ảo, computer vision tại cửa hàng |

## 03 — Tích hợp hệ thống
*Khả năng tích hợp giải pháp AI với hệ thống hiện tại. Càng nhiều hệ thống cần tích hợp, độ phức tạp và rủi ro càng cao.*

| Điểm | Mốc neo |
|------|---------|
| 9–10 | Không cần tích hợp (chạy độc lập, copy-paste) |
| 7–8 | 1 hệ thống, có API/tích hợp sẵn (Google Sheets, Fanpage, Zalo OA, Haravan/Sapo/KiotViet) |
| 5–6 | 2–3 hệ thống, có API |
| 3–4 | Hệ thống cũ, không API, phải xuất/nhập file thủ công |
| 1–2 | Nhiều hệ thống lõi (ERP, kế toán, kho) phải đồng bộ thời gian thực |

## 04 — Ngân sách và thời gian
*Chi phí và thời gian cần thiết để triển khai. Bao gồm phần mềm, phần cứng, đào tạo, tư vấn và chi phí vận hành liên tục.*

| Điểm | Chi phí năm đầu (VNĐ) | Thời gian ra kết quả đầu tiên |
|------|-----------------------|-------------------------------|
| 9–10 | < 10 triệu | < 2 tuần |
| 7–8 | 10–50 triệu | 2–6 tuần |
| 5–6 | 50–150 triệu | 1,5–3 tháng |
| 3–4 | 150–500 triệu | 3–6 tháng |
| 1–2 | > 500 triệu | > 6 tháng |

Nhớ cộng đủ: phí phần mềm/API hằng tháng × 12, chi phí thiết lập, giờ công nội bộ, đào tạo, tư vấn, bảo trì.

## 05 — Năng lực nội bộ
*Khả năng của đội ngũ trong việc triển khai và duy trì giải pháp AI. Có cần thuê chuyên gia bên ngoài không?*

| Điểm | Mốc neo |
|------|---------|
| 9–10 | Đội ngũ tự làm và tự duy trì được, đã dùng AI hằng ngày |
| 7–8 | Có 1 "AI champion" nội bộ, cần đào tạo ngắn (1–2 buổi) |
| 5–6 | Cần tư vấn ngoài lúc thiết lập, sau đó tự vận hành |
| 3–4 | Cần đối tác ngoài cả thiết lập lẫn bảo trì |
| 1–2 | Hoàn toàn phụ thuộc bên ngoài, không ai trong công ty hiểu hệ thống |

## Bảng chấm nhanh

| Nỗi đau | 01 Dữ liệu | 02 Kỹ thuật | 03 Tích hợp | 04 Ngân sách/TG | 05 Năng lực | **Khả thi (TB)** | Qua cổng chặn? |
|---------|-----------|-------------|-------------|-----------------|-------------|------------------|----------------|
| | | | | | | | ✅ / ❌ |

**Trọng số gợi ý cho SME:** Dữ liệu 30% · Kỹ thuật 20% · Tích hợp 15% · Ngân sách/Thời gian 20% · Năng lực 15%

## Thang "mức độ AI" — chọn mức thấp nhất giải được bài toán

| Mức | Cách tiếp cận | Chi phí | Khi nào dùng |
|-----|---------------|---------|--------------|
| L1 | Trợ lý AI chung + prompt chuẩn (SOP prompt) | Rất thấp | Soạn thảo, tóm tắt, phân tích, ý tưởng |
| L2 | SaaS có sẵn AI (chatbot, CRM có AI, công cụ content) | Thấp | Tác vụ phổ biến, nhiều nhà cung cấp |
| L3 | Workflow tự động (Make/n8n/Zapier) + API LLM | Trung bình | Nối nhiều bước, nhiều công cụ |
| L4 | AI có tri thức riêng (RAG trên tài liệu doanh nghiệp) | Trung bình–cao | Chatbot tư vấn sâu, trợ lý nội bộ |
| L5 | Mô hình tùy chỉnh / huấn luyện riêng | Cao | Chỉ khi L1–L4 không giải được và giá trị rất lớn |

> Quy tắc của chuyên gia: **80% bài toán AI của SME giải được ở L1–L3.** Nếu đề xuất đầu tiên đã là L5, gần như chắc chắn bài toán đang được định nghĩa quá to.
