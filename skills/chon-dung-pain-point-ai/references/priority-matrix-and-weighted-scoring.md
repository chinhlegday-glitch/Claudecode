# Ma Trận Ưu Tiên & Ma Trận Quyết Định Có Trọng Số

## Phần 1 — Ma trận Tác động × Khả thi (2×2)

Trục dọc: **Tác động** (1–10, từ 10 tiêu chí). Trục ngang: **Khả thi** (1–10, từ 5 tiêu chí AI). Đường chia mặc định ở mức **6** (có thể dùng trung vị của danh sách nếu điểm bị dồn cục).

| Góc | Điều kiện | Tên gọi | Hành động | Phân bổ nguồn lực gợi ý |
|-----|-----------|---------|-----------|-------------------------|
| ① | Tác động ≥ 6, Khả thi ≥ 6 | **Làm ngay (Quick Win)** | Chọn Top 3 từ đây, pilot trong 30 ngày | ~70% |
| ② | Tác động ≥ 6, Khả thi < 6 | **Cược chiến lược** | Tìm điểm nghẽn khả thi (thường là dữ liệu) và gỡ dần; xếp lộ trình 6–12 tháng | ~20% |
| ③ | Tác động < 6, Khả thi ≥ 6 | **Làm nhanh, rẻ** | Giao cá nhân tự dùng tool có sẵn, không lập dự án | ~10% |
| ④ | Tác động < 6, Khả thi < 6 | **Loại bỏ** | Không làm, ghi vào danh sách "KHÔNG làm lúc này" | 0% |

**Cách biến góc ② thành góc ①:** cắt nhỏ bài toán. Ví dụ "Dự đoán hành vi khách hàng cá nhân" (②) → tách thành "Phân nhóm khách theo lịch sử mua (RFM) trên Google Sheets + AI gợi ý kịch bản chăm sóc từng nhóm" (①).

## Phần 2 — Ma trận quyết định có trọng số

Phương pháp này giúp đánh giá khách quan và toàn diện, tránh quyết định dựa trên cảm tính hoặc áp lực từ một bộ phận.

### 5 bước
1. **Xác định các tiêu chí quan trọng** (tác động doanh thu, tiết kiệm chi phí, trải nghiệm khách hàng, dữ liệu sẵn có…)
2. **Gán trọng số cho mỗi tiêu chí** (tổng = 100%) dựa vào ưu tiên của doanh nghiệp
3. **Chấm điểm mỗi bài toán** từ 1–10 cho từng tiêu chí
4. **Tính điểm có trọng số** = Điểm × Trọng số
5. **Chọn bài toán có tổng điểm cao nhất**

### Bộ trọng số mẫu theo giai đoạn doanh nghiệp

| Tiêu chí | Cần dòng tiền nhanh | Cần tối ưu chi phí | Cần tăng trưởng/mở rộng |
|----------|:-:|:-:|:-:|
| Tác động doanh thu | **30%** | 10% | 25% |
| Tiết kiệm chi phí / giờ công | 15% | **30%** | 15% |
| Trải nghiệm khách hàng | 15% | 10% | 15% |
| Phù hợp chiến lược & khả năng mở rộng | 5% | 10% | **20%** |
| Dữ liệu sẵn có | 15% | 15% | 10% |
| Chi phí & thời gian triển khai (dễ = điểm cao) | 15% | 15% | 10% |
| Năng lực nội bộ | 5% | 10% | 5% |
| **Tổng** | **100%** | **100%** | **100%** |

### Hai cách tính "Tổng điểm"

| Cách | Công thức | Thang | Dùng khi |
|------|-----------|-------|----------|
| **A. Nhân (workshop nhanh)** | Tác động × Khả thi | 1–100 | Workshop 2–3 giờ, cần kết quả nhanh. Phạt mạnh bài toán lệch (cao một trục, thấp trục kia) |
| **B. Có trọng số (chuẩn)** | Σ (Điểm tiêu chí × Trọng số) | 1–10 | Quyết định ngân sách, trình ban lãnh đạo |

> Khuyến nghị: dùng A để lọc từ 20 xuống 6–8 ứng viên, dùng B để chọn Top 3 cuối cùng.

### Xử lý khi hòa điểm (theo thứ tự)
1. Bài toán ra kết quả đo được nhanh hơn
2. Bài toán có điểm Dữ liệu cao hơn
3. Bài toán có khả năng mở rộng (#07) cao hơn
4. Bài toán có owner nhiệt tình hơn

## Phần 3 — Ví dụ đầy đủ: Cửa hàng thời trang (doanh thu ~15 tỷ/năm, 25 nhân sự, bán online + 2 cửa hàng)

Mục tiêu 12 tháng: tăng doanh thu online 40%, giảm tồn kho chết 30%.

### Bước 3–4: Chấm Tác động và Khả thi

| # | Bài toán AI | Tác động | Khả thi | A = T×K | Góc |
|---|-------------|:-:|:-:|:-:|:-:|
| 1 | Chatbot hỗ trợ đơn hàng cơ bản (giá, size, ship, đổi trả) trên Fanpage/Zalo | 8 | 8 | **64** | ① |
| 2 | Dự báo xu hướng sản phẩm bán chạy (từ dữ liệu bán + trend TikTok) | 9 | 6 | **54** | ① |
| 3 | Tự động phân loại & viết mô tả sản phẩm trên website | 6 | 9 | **54** | ① |
| 4 | Tự động trả lời email thông thường | 3 | 9 | 27 | ③ |
| 5 | Phân tích cảm xúc từ đánh giá | 4 | 8 | 32 | ③ |
| 6 | Hệ thống thử đồ ảo cho khách hàng | 8 | 2 | 16 | ② |
| 7 | Dự đoán hành vi khách hàng cá nhân | 8 | 3 | 24 | ② |
| 8 | Nhận diện khách hàng tại cửa hàng | 3 | 2 | 6 | ④ |
| 9 | Robot tư vấn trong cửa hàng | 2 | 1 | 2 | ④ |

### Bước 5: Ma trận có trọng số cho 3 ứng viên góc ① (bộ trọng số "Cần dòng tiền nhanh")

| Tiêu chí | Trọng số | Chatbot đơn hàng | Dự báo xu hướng | Mô tả SP tự động |
|----------|:-:|:-:|:-:|:-:|
| Tác động doanh thu | 30% | 8 → 2,40 | 9 → 2,70 | 5 → 1,50 |
| Tiết kiệm chi phí | 15% | 8 → 1,20 | 6 → 0,90 | 8 → 1,20 |
| Trải nghiệm khách hàng | 15% | 9 → 1,35 | 5 → 0,75 | 6 → 0,90 |
| Chiến lược & mở rộng | 5% | 7 → 0,35 | 9 → 0,45 | 6 → 0,30 |
| Dữ liệu sẵn có | 15% | 8 → 1,20 | 6 → 0,90 | 9 → 1,35 |
| Chi phí & thời gian | 15% | 8 → 1,20 | 5 → 0,75 | 9 → 1,35 |
| Năng lực nội bộ | 5% | 7 → 0,35 | 4 → 0,20 | 9 → 0,45 |
| **Tổng** | **100%** | **8,05** 🥇 | **6,65** 🥉 | **7,05** 🥈 |

**Kết luận:**
- **#1 Chatbot đơn hàng (8,05)** — pilot ngay tháng 1 (L2–L4: chatbot Fanpage/Zalo OA có knowledge base). Baseline: thời gian phản hồi TB 45 phút, 15% tin nhắn ngoài giờ bị bỏ lỡ.
- **#2 Mô tả sản phẩm tự động (7,05)** — tác động vừa phải nhưng gần như miễn phí, ra kết quả trong 1 tuần → giao nhân viên content làm theo SOP prompt, không cần lập dự án riêng.
- **#3 Dự báo xu hướng (6,65)** — tác động cao nhất nhưng bị kéo xuống bởi dữ liệu, chi phí và năng lực. Đây là bài học quan trọng: *điểm Tác động cao không đủ để thắng*. Bắt đầu bằng bản đơn giản (AI phân tích file Excel bán hàng 12 tháng + danh sách trend hằng tuần → gợi ý nhập hàng), song song chuẩn hóa dữ liệu SKU để nâng điểm Khả thi cho quý sau.
- **KHÔNG làm lúc này:** thử đồ ảo, robot tư vấn, nhận diện khách tại cửa hàng, dự đoán hành vi cá nhân (chờ đủ dữ liệu CRM).
