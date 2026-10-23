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
**Tiêu chuẩn tham chiếu**: TCVN 14464-1:2025 (Phần 1: Thiết bị giám sát), QCVN 05:2024/BCA, QCVN 11:2026/BCA hoặc QCVN 135:2024/BTTTT (an ninh mạng camera IP).

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Độ phân giải | ≥ 4MP (khuyến nghị 4K / 8MP) |
| Tầm nhìn đêm | IR ≥ 50–80 m hoặc Full Color |
| Chức năng AI | ANPR (nhận diện biển số ≥ 93% ban ngày / ≥ 80% ban đêm), phân loại phương tiện, phát hiện sự cố (xe dừng, ngược chiều, vật rơi, đi sai làn) |
| Phạm vi giám sát | ≥ 2 làn xe |
| Chuẩn nén | H.265 / H.265+ |
| Chống chịu | IP66/IP67, IK08 hoặc cao hơn, nhiệt độ -10°C ~ +50°C |
| An toàn thông tin | Tuân thủ yêu cầu an ninh mạng cơ bản (mật khẩu mạnh, cập nhật firmware, mã hóa kênh) |
| Kết nối | ONVIF Profile S/T/G, PoE hoặc nguồn riêng + UPS |
| Tốc độ khung hình | ≥ 25 fps |
| WDR | ≥ 120 dB (khuyến nghị) |
| Zoom quang (PTZ) | ≥ 20–30x |
| Lưu trữ tại biên | Hỗ trợ SD/edge storage khi mất kết nối |

### B. VDS – Hệ thống đo đếm lưu lượng & tốc độ phương tiện
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015, hướng dẫn Cục Đường bộ / tiêu chuẩn quốc tế ISO/TC 204.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Công nghệ | Radar Doppler, vòng từ, hoặc camera AI đếm xe |
| Phạm vi | ≥ 2–4 làn |
| Độ chính xác | Đếm xe ≥ 95%; đo tốc độ sai số ≤ ±3–5% |
| Dữ liệu xuất | Lưu lượng theo làn, tốc độ trung bình/cao nhất, phân loại xe |
| Môi trường | Hoạt động ổn định trong mưa, sương mù, ban đêm |
| Kết nối | Ethernet, RS485 hoặc không dây; hỗ trợ giao thức mở |

### C. VMS – Biển báo thông tin điện tử
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | Full matrix LED hoặc hybrid |
| Độ sáng | ≥ 8.000–10.000 cd/m² (điều chỉnh tự động) |
| Khoảng cách nhìn | ≥ 200–300 m |
| Nội dung hiển thị | Văn bản, biểu tượng, cảnh báo ùn tắc/sự cố, tốc độ khuyến cáo |
| Chống chịu | IP65 trở lên, chịu gió ≥ 40 m/s |
| Điều khiển | Từ trung tâm (TMC) qua giao thức mở; chế độ an toàn khi mất kết nối |

### H. WIM – Hệ thống cân tải trọng xe động
**Tiêu chuẩn tham chiếu**: QCVN 116:2024/BGTVT, ASTM E1318, OIML R134.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | High-Speed WIM (HS WIM) hoặc Low-Speed WIM (LS WIM) |
| Phạm vi tốc độ | 3–120 km/h |
| Độ chính xác | Đo tải trọng trục / tổng trọng lượng đạt cấp chính xác theo quy định (≥ 93–95%) |
| Chức năng | Đo tải trọng từng trục, cụm trục, tổng trọng lượng xe; phân loại xe; nhận diện biển số; phát hiện quá tải |
| Tích hợp | Camera ANPR, VMS cảnh báo, kết nối dữ liệu về trung tâm |

### I. LCS – Biển kiểm soát làn đường
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | Biển LED matrix hiển thị mũi tên, X, số làn mở/đóng |
| Chức năng | Chỉ dẫn làn mở/đóng, cảnh báo sự cố, hướng dẫn chuyển làn |
| Điều khiển | Từ trung tâm TMC theo thời gian thực; chế độ an toàn mặc định |

### J. Barrier – Cần chắn / Barrier tự động
| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Loại | Barrier tự động điều khiển từ xa |
| Thời gian đóng/mở | ≤ 3–5 giây |
| An toàn | Cảm biến chống kẹt, dừng khẩn cấp, báo hiệu đèn + còi |

### K. Hệ thống kỹ thuật trong hầm (nếu có)
**Tiêu chuẩn tham chiếu**: TCVN 4527:1988, quy định an toàn hầm, PCCC.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Camera giám sát | Camera cố định + PTZ, chống ẩm, khói |
| Cảm biến | Khói, CO, nhiệt độ, lưu lượng không khí |
| Thông gió | Quạt thông gió điều khiển tự động |
| Chiếu sáng | Chiếu sáng thích ứng, đèn sự cố |

### L. ATM – Hệ thống quản lý giao thông nâng cao
**Tiêu chuẩn tham chiếu**: TCVN 10850:2015.

| Chỉ tiêu | Yêu cầu kỹ thuật tối thiểu |
|----------|----------------------------|
| Chức năng chính | Thu thập dữ liệu đa nguồn, xử lý real-time, điều khiển thiết bị (VMS, LCS, Barrier) |
| Tích hợp | API mở với các hệ thống khác (ETC, WIM, hệ thống cấp trên) |
| Giao diện vận hành | Dashboard thời gian thực, bản đồ số, cảnh báo tự động |

**Lưu ý quan trọng**:
- Các chỉ tiêu trên là mức **tối thiểu khuyến nghị** dựa trên tiêu chuẩn hiện hành.
- Khi lập hồ sơ chính thức phải liệt kê đầy đủ QCVN/TCVN áp dụng.
- Đối với WIM: phải tuân thủ QCVN 116:2024/BGTVT.
- An ninh mạng camera phải được xem xét kỹ.

---

## 2. Cơ cấu tổng mức đầu tư (uớc tính)

| Khoản mục | Số tiền (triệu đồng) |
|-----------|----------------------|
| Chi phí xây dựng (móng trụ, lắp đặt, điện, bảo vệ) | 4.200 |
| Chi phí thiết bị (camera AI, VDS, truyền dẫn, phần mềm) | 11.800 |
| Chi phí quản lý dự án | 520 |
| Chi phí tư vấn (lập BCKTKT + thiết kế BVTC + khảo sát) | 780 |
| Chi phí khác | 300 |
| Dự phòng | 900 |
| **Tổng mức đầu tư** | **18.500** |

**Chi phí xây dựng + thiết bị** = 16.000 triệu đồng.

---

## 3. Tính chi phí lập Báo cáo kinh tế kỹ thuật

Theo Bảng 2.4 Thông tư 38/2026/TT-BXD – Công trình giao thông:
- Mốc 15 tỷ: 2,9%
- Mốc 20 tỷ: 2,7%
- Chi phí XD + TB = 16 tỷ → nội suy ≈ **2,82%**

**Chi phí lập BCKTKT** ≈ 2,82% × 16 tỷ = **≈ 451 triệu đồng** (chưa VAT).

---

## 4. Tiến độ thực hiện dự kiến

| Giai đoạn | Thời gian |
|-----------|-----------|
| Chuẩn bị, khảo sát, lập BCKTKT & thiết kế | 2–3 tháng |
| Thi công lắp đặt | 4–5 tháng |
| Kiểm tra, nghiệm thu, bàn giao vận hành | 1 tháng |
| **Tổng thời gian** | **7–9 tháng** |

---

## 5. Hiệu quả kỳ vọng

- Giám sát liên tục 24/7, phát hiện sự cố nhanh hơn 30–50%.
- Cung cấp dữ liệu lưu lượng, tốc độ phục vụ quản lý và dự báo.
- Hỗ trợ giảm tai nạn, ùn tắc trên đoạn tuyến.
- Kết nối dữ liệu với trung tâm điều hành cấp trên / ETC / WIM (nếu có).

---

## 6. Các điểm cần lưu ý khi áp dụng mẫu này

- Số liệu trên là **uớc tính minh họa**.
- Phải điều chỉnh theo đơn giá, định mức, khối lượng khảo sát thực tế.
- Đồng bộ thuyết minh – thiết kế bản vẽ thi công – dự toán.
- Kiểm tra lại hạn mức ≤ 40 tỷ (không gồm đất) trước khi trình.

**Cách sử dụng**: Copy cấu trúc này vào thuyết minh chính, điền thông tin tuyến cụ thể, và tính toán lại chi phí bằng phần mềm dự toán.

---

*Mẫu này bổ sung cho `mau-thuyet-minh-its.md` và `vi-du-tinh-tong-muc-dau-tu-its.md`.*
