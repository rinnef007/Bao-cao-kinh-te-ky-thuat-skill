---
description: "Mẫu dự án cụ thể đầy đủ số liệu: Lắp đặt hệ thống ITS (camera AI + VDS) trên đoạn đường cao tốc/quốc lộ quy mô nhỏ – áp dụng BCKTKT"
connections: [mau-thuyet-minh-its, vi-du-tinh-tong-muc-dau-tu-its, dinh-muc-chi-phi]
---

# Mẫu dự án cụ thể: Hệ thống ITS trên đoạn đường cao tốc

**Tên dự án**: Lắp đặt hệ thống giao thông thông minh (ITS) giám sát và đo đếm lưu lượng trên đoạn Km12+500 – Km28+200 tuyến Cao tốc / Quốc lộ [Tên tuyến]  
**Địa điểm**: Đoạn thuộc địa bàn tỉnh [Tên tỉnh]  
**Chủ đầu tư**: Ban Quản lý dự án đường bộ / Sở Giao thông vận tải [Tên tỉnh]  
**Nguồn vốn**: Ngân sách nhà nước (vốn đầu tư công)  
**Tổng mức đầu tư** (không gồm chi phí bồi thường, GPMB, tiền sử dụng đất): **18,5 tỷ đồng** → đủ điều kiện chỉ lập Báo cáo kinh tế kỹ thuật.

---

## 1. Thông tin quy mô chính

| Hạng mục | Số lượng / Thông số | Ghi chú |
|----------|---------------------|---------|
| Camera AI giám sát (PTZ + cố định) | 24 camera | Nhận diện biển số, phát hiện sự cố, đo tốc độ |
| Thiết bị đo lưu lượng & tốc độ (VDS) | 8 điểm | Radar hoặc camera đếm xe |
| Trụ / cột đỡ thiết bị | 20 trụ | Cao 8–12 m, móng bê tông |
| Hệ thống truyền dẫn | Cáp quang + không dây dự phòng | Kết nối về trung tâm điều hành hiện có |
| Phần mềm & tích hợp | 01 gói | Tích hợp AI, lưu trữ, cảnh báo sự cố |
| Chiều dài đoạn tuyến | ≈ 15,7 km | Lắp đặt tại các vị trí trọng yếu |

**Cấp công trình**: Cấp IV (hệ thống kỹ thuật lắp đặt trên hành lang an toàn giao thông hiện hữu).

---

## 1.1. Chỉ tiêu kỹ thuật chi tiết theo từng hạng mục

### A. CCTV / Camera giám sát giao thông (AI)
**Tiêu chuẩn tham chiếu**: TCVN 14464-1:2025, QCVN 05:2024/BCA, QCVN 11:2026/BCA hoặc QCVN 135:2024/BTTTT.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Độ phân giải | ≥ 4MP (khuyến nghị 4K / 8MP) |
| Tầm nhìn đêm | IR ≥ 50–80 m hoặc Full Color |
| Chức năng AI | ANPR (≥ 93% ban ngày / ≥ 80% ban đêm), phân loại phương tiện, phát hiện sự cố |
| Phạm vi giám sát | ≥ 2 làn xe |
| Chuẩn nén | H.265 / H.265+ |
| Chống chịu | IP66/IP67, IK08 hoặc cao hơn |
| An toàn thông tin | Tuân thủ yêu cầu an ninh mạng cơ bản |
| Kết nối | ONVIF Profile S/T/G |

### B. VDS – Hệ thống đo đếm lưu lượng & tốc độ
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015, ISO/TC 204.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Công nghệ | Radar Doppler hoặc camera AI đếm xe |
| Phạm vi | ≥ 2–4 làn |
| Độ chính xác | Đếm xe ≥ 95%; đo tốc độ sai số ≤ ±3–5% |
| Dữ liệu xuất | Lưu lượng theo làn, tốc độ, phân loại xe |

### C. VMS – Biển báo thông tin điện tử
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | Full matrix LED |
| Độ sáng | ≥ 8.000–10.000 cd/m² |
| Khoảng cách nhìn | ≥ 200–300 m |
| Điều khiển | Từ trung tâm TMC; chế độ an toàn khi mất kết nối |

### H. WIM – Hệ thống cân tải trọng xe động
**Tiêu chuẩn tham chiếu**: QCVN 116:2024/BGTVT, ASTM E1318, OIML R134.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | HS WIM hoặc LS WIM |
| Phạm vi tốc độ | 3–120 km/h |
| Độ chính xác | ≥ 93–95% theo quy định |
| Chức năng | Đo tải trọng trục, tổng trọng lượng, phân loại xe, nhận diện biển số |

### I. LCS – Biển kiểm soát làn đường
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | Biển LED matrix |
| Chức năng | Chỉ dẫn làn mở/đóng, cảnh báo sự cố |
| Điều khiển | Từ TMC theo thời gian thực |

### J. Barrier – Cần chắn tự động
| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Thời gian đóng/mở | ≤ 3–5 giây |
| An toàn | Cảm biến chống kẹt, dừng khẩn cấp |

### K. Hệ thống kỹ thuật trong hầm (nếu có)
**Tiêu chuẩn tham chiếu**: TCVN 4527:1988.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Camera | Chống ẩm, khói, độ phân giải cao |
| Cảm biến | Khói, CO, nhiệt độ |
| Thông gió | Quạt điều khiển tự động |

### L. ATM – Hệ thống quản lý giao thông nâng cao
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Chức năng | Thu thập dữ liệu đa nguồn, xử lý real-time, điều khiển thiết bị |
| Tích hợp | API mở với ETC, WIM, hệ thống cấp trên |

**Lưu ý**: Các chỉ tiêu trên là mức tối thiểu khuyến nghị. Khi lập hồ sơ chính thức phải liệt kê đầy đủ QCVN/TCVN áp dụng.

---

## 2. Cơ cấu tổng mức đầu tư (uớc tính)

| Khoản mục | Số tiền (triệu đồng) |
|-----------|----------------------|
| Chi phí xây dựng | 4.200 |
| Chi phí thiết bị | 11.800 |
| Chi phí quản lý dự án | 520 |
| Chi phí tư vấn | 780 |
| Chi phí khác | 300 |
| Dự phòng | 900 |
| **Tổng mức đầu tư** | **18.500** |

---

## 3. Tính chi phí lập Báo cáo kinh tế kỹ thuật

Theo Bảng 2.4 Thông tư 38/2026/TT-BXD – Công trình giao thông:
- Chi phí XD + TB = 16 tỷ → nội suy ≈ **2,82%**
- **Chi phí lập BCKTKT** ≈ **451 triệu đồng** (chưa VAT).

---

## 4. Tiến độ thực hiện dự kiến

| Giai đoạn | Thời gian |
|-----------|-----------|
| Chuẩn bị, khảo sát, lập BCKTKT | 2–3 tháng |
| Thi công lắp đặt | 4–5 tháng |
| Nghiệm thu, bàn giao | 1 tháng |
| **Tổng thời gian** | **7–9 tháng** |

---

## 5. Hiệu quả kỳ vọng

- Giám sát liên tục 24/7, phát hiện sự cố nhanh hơn 30–50%.
- Cung cấp dữ liệu lưu lượng, tốc độ phục vụ quản lý.
- Hỗ trợ giảm tai nạn, ùn tắc.

---

*Mẫu này bổ sung cho `mau-thuyet-minh-its.md` và `vi-du-tinh-tong-muc-dau-tu-its.md`.*
