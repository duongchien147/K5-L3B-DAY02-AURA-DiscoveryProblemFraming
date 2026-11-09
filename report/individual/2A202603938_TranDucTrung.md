# Báo cáo cá nhân — 2A202603938_TranDucTrung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Đức Trung
- MSSV: 2A_202603938
- Email trường (không bắt buộc, repo có thể để public): ____________________
- Tên nhóm: ____________________
- Link repo nhóm: ____________________

---

## 2. Scan problem (CP1)


| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi đọc một bài báo khoa học bằng tiếng Anh, tôi muốn nhanh chóng xác định bài toán, phương pháp và kết quả chính, để chọn được tài liệu phù hợp cho đề tài nghiên cứu. | Sinh viên thực hiện nghiên cứu khoa học | Đọc 2 tiếng để hiểu quy trình họ thực hiện. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi đánh giá mô hình AI sau nhiều lần huấn luyện, tôi muốn đối chiếu các chỉ số và cấu hình thí nghiệm, để biết phiên bản nào thực sự cải thiện kết quả. | Sinh viên và nhóm nghiên cứu | Mỗi tuần 1 lần, 20 phút để đối chiếu và so sánh. |
| 3 | Pain từ người khác | Khi thực hiện bài tập lớn theo nhóm, tôi muốn các thành viên nắm rõ nhiệm vụ và thời hạn của mình, để hạn chế bỏ sót hoặc trùng lặp công việc. | Các thành viên nhóm làm bài tập lớn | Mỗi tuần 1 lần, 30 phút |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn thi một môn có nhiều slide, giáo trình và bài tập, tôi muốn hệ thống kiến thức theo từng chủ đề, để không bỏ sót nội dung quan trọng. | Sinh viên đại học | Mỗi tháng 1 lần, mỗi môn 60 phút. |
| 5 | Pain từ người khác | Khi nhóm chuẩn bị nộp bài tập lớn, tôi muốn kiểm tra báo cáo đã đáp ứng đủ yêu cầu của giảng viên, để tránh thiếu nội dung hoặc sai định dạng. | Các thành viên nhóm và người tổng hợp báo cáo | Mỗi tuần 1 lần, 30 phút. |


## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 Mất nhiều thời gian đọc và phân tích bài báo khoa học tiếng Anh | Thời gian đọc một bài báo khoảng 2 tiếng, ảnh hưởng trực tiếp đến tiến độ tìm hiểu tài liệu nghiên cứu. | Chất lượng review khó đo, tốn thời gian ở bước nào nhất. |
| 2 | #2 khó đối chiếu kết quả giữa nhiều lần huấn luyện mô hình AI | Công việc lặp lại hằng tuần, mất khoảng 20 phút mỗi lần và dễ nhầm lẫn giữa các phiên bản thí nghiệm. | Chưa biết việc tự động lập bảng so sánh có thể tiết kiệm bao nhiêu thời gian. |
| 3 | #5 Mất thời gian kiểm tra báo cáo bài tập lớn trước khi nộp | Công việc ảnh hưởng đến chất lượng bài nộp, mất khoảng 30 phút mỗi lần và cần đối chiếu nhiều yêu cầu. | Chưa biết cách nào giúp kiểm tra báo cáo nhanh hơn mà vẫn đảm bảo không bỏ sót lỗi. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đọc một bài báo khoa học bằng tiếng Anh, tôi muốn nhanh chóng xác định bài toán, phương pháp và kết quả chính, để chọn được tài liệu phù hợp cho đề tài nghiên cứu. |
| Actor | Sinh viên thực hiện nghiên cứu khoa học. |
| Thời điểm / bối cảnh | Khi cần tìm hiểu các bài báo khoa học để phục vụ đề tài nghiên cứu. |
| Quy trình hiện tại (3–7 bước) | 1. Tìm kiếm bài báo liên quan. 2. Đọc Abstract và Introduction. 3. Phân tích phương pháp và kiến trúc. 4. Đọc kết quả thực nghiệm. 5. Tổng hợp nội dung quan trọng. |
| Impact (nếu không giải thì sao) | Tốn thời gian đối chiếu, dễ nhầm kết quả giữa các lần chạy và khó tái hiện thí nghiệm. |
| Success metric (baseline → target) | Thời gian làm bảng so sánh: __________ → __________ phút; số lỗi ghép sai config với metrics: __________ → __________ lỗi. |
| Phương án không dùng AI | Quy định tên file thống nhất và dùng Python/pandas để tổng hợp CSV, log theo cấu trúc cố định. |
| Giả thuyết về AI (nếu có) | AI hỗ trợ viết nháp phần nhận xét dựa trên bảng chỉ số đã kiểm tra; con người xác minh trước khi sử dụng. |
| Cảm nhận nhanh | Rule / Workflow. |

Quy trình nháp hiện tại:

```text
1. Tìm thư mục của các lần chạy          (_____ phút)
2. Mở các file log/CSV                   (_____ phút)
3. Đối chiếu cấu hình và tham số         (_____ phút)
4. Tổng hợp các chỉ số vào một bảng      (_____ phút)
5. So sánh kết quả giữa các lần chạy     (_____ phút)
6. Viết nhận xét cho báo cáo             (_____ phút)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhóm chuẩn bị nộp bài tập lớn, tôi muốn kiểm tra báo cáo đã đáp ứng đủ yêu cầu của giảng viên, để tránh thiếu nội dung hoặc sai định dạng. |
| Actor | Sinh viên phụ trách rà soát, tổng hợp báo cáo nhóm. |
| Thời điểm / bối cảnh | Trước hạn nộp bài tập lớn hoặc khi ghép nội dung các thành viên. |
| Quy trình hiện tại (3–7 bước) | (1) Đọc yêu cầu; (2) lập checklist; (3) mở báo cáo; (4) đối chiếu; (5) ghi lỗi và sửa; (6) kiểm tra lại. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước: __________; thời gian đo được: __________ phút. |
| Impact (nếu không giải thì sao) | Dễ bỏ sót nội dung bắt buộc, phải sửa gấp trước hạn nộp và có nguy cơ mất điểm. |
| Success metric (baseline → target) | Thời gian kiểm tra báo cáo: __________ → __________ phút; số yêu cầu bỏ sót: __________ → __________ mục. |
| Phương án không dùng AI | Dùng checklist dựa trên rubric và phân công thành viên kiểm tra chéo. |
| Giả thuyết về AI (nếu có) | AI hỗ trợ đối chiếu các đề mục với rubric và gợi ý vị trí thiếu; người học tự xác nhận. |
| Cảm nhận nhanh | No AI / Workflow. |

Quy trình nháp hiện tại:

```text
1. Đọc đề bài và rubric                 (_____ phút)
2. Lập danh sách tiêu chí cần kiểm      (_____ phút)
3. Mở báo cáo và rà cấu trúc            (_____ phút)
4. Đối chiếu nội dung với từng yêu cầu  (_____ phút)
5. Ghi lỗi và chỉnh sửa                 (_____ phút)
6. Kiểm tra lại trước khi nộp           (_____ phút)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đọc một bài báo khoa học bằng tiếng Anh, tôi muốn nhanh chóng xác định bài toán, phương pháp và kết quả chính, để chọn được tài liệu phù hợp cho đề tài nghiên cứu. |
| Actor | Sinh viên đang làm nghiên cứu khoa học hoặc đồ án. |
| Thời điểm / bối cảnh | Khi tìm tài liệu liên quan và chuẩn bị phần tổng quan nghiên cứu. |
| Quy trình hiện tại (3–7 bước) | (1) Tìm paper; (2) đọc abstract/introduction; (3) phân tích phương pháp; (4) xem thí nghiệm; (5) tra thuật ngữ; (6) tổng hợp ghi chú. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước: __________; thời gian đo được: __________ phút. |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian tìm tài liệu, dễ bỏ sót công trình phù hợp hoặc hiểu sai phương pháp nghiên cứu. |
| Success metric (baseline → target) | Thời gian đọc và tạo ghi chú cho một paper: __________ → __________ phút; số thông tin sai khi đối chiếu PDF: __________ → __________. |
| Phương án không dùng AI | Sử dụng mẫu ghi chú cố định theo Problem – Method – Dataset – Metrics – Limitations. |
| Giả thuyết về AI (nếu có) | AI hỗ trợ xác định ý chính và vị trí thông tin trong paper; người học kiểm tra lại trực tiếp với PDF. |
| Cảm nhận nhanh | Workflow. |

Quy trình nháp hiện tại:

```text
1. Tìm và chọn bài báo                  (_____ phút)
2. Đọc abstract và introduction         (_____ phút)
3. Phân tích methodology và kiến trúc   (_____ phút)
4. Đọc experiments và kết quả           (_____ phút)
5. Tra thuật ngữ, ghi chú hạn chế       (_____ phút)
6. Tổng hợp và so sánh với đề tài       (_____ phút)
```

### Card muốn pitch nhất

- Card số: __________
- Vì sao: __________
- Câu hỏi muốn nhóm phản biện: __________

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa có số liệu thời gian thực tế nên chưa thể khẳng định bottleneck và baseline của từng card. | __________ | __________ |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ ChatGPT gợi ý 8 vấn đề và cách diễn đạt Job Story. | Giúp phân loại vấn đề theo bốn lăng kính và viết Job Story rõ hơn. | AI không có bằng chứng thực tế và có những vấn đề gần giống nhau. | __________ |
| CP2 Problem Card | Nhờ ChatGPT phác thảo 3 Problem Cards, quy trình và các chỉ số đánh giá. | Hỗ trợ xác định các bước, phương án không dùng AI và giả thuyết về AI. | Các bottleneck và baseline chưa được đo từ trải nghiệm thực tế. | __________ |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**


**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**


**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**


**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**


**6.5. Điều khó nhất khi viết Problem Statement là gì?**


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**


**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.


---

## 7. Tài liệu tham khảo


