# Báo cáo Kiểm thử Hiệu năng với JMeter

## 1. Thông tin chung
- **Website kiểm thử:** https://www.wikipedia.org
- **Công cụ:** Apache JMeter 5.6.3

## 2. Các kịch bản kiểm thử (Thread Groups)
- **Kịch bản cơ bản:** 10 users, Loop 5.
- **Kịch bản tải nặng:** 50 users, Ramp-up 30s.
- **Kịch bản tùy chỉnh:** 20 users, Duration 60s.

## 3. Kết quả tổng hợp (Summary Report)
- **Tổng số mẫu (Samples):** 120
- **Thời gian phản hồi trung bình (Average):** 569 ms
- **Thông lượng (Throughput):** 4.0/sec
- **Tỉ lệ lỗi (Error %):** 0.00%

## 4. Hình ảnh minh chứng
![Summary Report](summary_report.png)
