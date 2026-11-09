# Báo cáo cá nhân — 2A202603907_TrinhHungThinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trịnh Hưng Thịnh
- MSSV: 2A202603907
- Email trường (không bắt buộc, repo có thể để public): 26ai.thinhth@vinuni.edu.vn
- Tên nhóm: AURA
- Link repo nhóm: https://github.com/duongchien147/K5-L3B-DAY02-AURA-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Vào mỗi cuối tuần, cả team tôi sẽ phải viết một báo cáo những gì đã làm trong 1 tuần để gửi lên Lead |Cả team |15 phút mỗi cuối tuần |
| 2 |Lặp lại |Đầu tuần trước khi họp, tôi muốn có đầy đủ các báo cáo của cả team từ cuối tuần trước, báo cáo lên lead |PM |Trước giờ họp 15 phút mỗi đầu tuần |
| 3 |Tốn thời gian |Khi muốn sửa một lỗi của một chuyền sản xuất, mọi người đều phải đi ticket đầy đủ lên một web của cả team, nên tôi cần một tool để có thể tự động cập nhật các ticket đã làm |Cả team |10 phút trước khi xử lí ticket |
| 4 |Tốn thời gian |Khi cần tổng hợp báo cáo từ nhiều thành viên, tôi muốn có một công cụ tự động tổng hợp để tiết kiệm thời gian |PM |Khoảng 20 phút mỗi lần tổng hợp báo cáo |
| 5 |Cần đọc, tổng hợp nhiều thông tin |Khi có quá nhiều ticket cùng gửi đến, tôi muốn biết cái nào có độ ưu tiên cao hơn để có thể hoàn thành trước cho kịp tiến độ sản xuất |Team |Delay đơn hàng của khách vì sửa sai chuyền |
| 6 |Pain từ người khác |Khi các đơn hàng đang rất gấp nhưng chuyền gặp lỗi, cần đi ticket và xử lí rất lâu  |Team sản xuất |Tháng trước trễ 1 đơn vì sai chuyền |
| 7 |Pain từ người khác |Khi các thành viên mới vào team, tôi muốn có tài liệu hướng dẫn rõ ràng để họ không mất thời gian hỏi lại các quy trình cơ bản |Thành viên mới |Mỗi khi có thành viên mới, mất 1–2 ngày để làm quen quy trình |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Khi các thành viên mới vào team, tôi muốn có tài liệu hướng dẫn rõ ràng để họ không mất thời gian hỏi lại các quy trình cơ bản |Thành viên mới mất 1–2 ngày để làm quen quy trình| No AI|
| 2 | Tổng hợp báo cáo từ nhiều thành viên mất thời gian | PM mất 20 phút mỗi lần tổng hợp, dễ sai sót, ảnh hưởng tiến độ | Chưa rõ các công cụ hiện tại đã hỗ trợ tốt chưa |
| 3 | Khi có nhiều ticket, khó xác định ưu tiên xử lý | Ảnh hưởng trực tiếp đến tiến độ sản xuất, có thể gây delay đơn hàng | Chưa rõ tiêu chí ưu tiên đã đủ rõ ràng và tự động hóa được không |

### Problem Card #1


| Trường | Nội dung |
|---|---|
| Job Story | Khi có thành viên mới gia nhập, tôi muốn có một quy trình cụ thể để có thể huấn luyện người mới|
| Actor | Thành viên mới |
| Thời điểm / bối cảnh | Khi có thành viên mới gia nhập team|
| Quy trình hiện tại (3–7 bước) | 1. Thành viên mới nhận thông báo gia nhập team. 2. Thành viên mới tự tìm hiểu các tài liệu hướng dẫn (nếu có). 3. Thành viên mới hỏi các thành viên cũ về quy trình làm việc. 4. Thành viên mới thực hành các bước cơ bản dưới sự hướng dẫn của thành viên cũ. 5. Thành viên mới tự thực hiện công việc và hỏi lại khi gặp khó khăn. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước làm quen quy trình, mất 1–2 ngày để thành viên mới hiểu và thực hiện đúng các bước |
| Impact (nếu không giải thì sao) | Thành viên mới mất nhiều thời gian làm quen, dễ mắc lỗi do không hiểu quy trình, ảnh hưởng hiệu suất làm việc của cả team. |
| Success metric (baseline → target) | Thời gian làm quen quy trình: 1–2 ngày → dưới 4 giờ |
| Phương án không dùng AI | Cung cấp tài liệu hướng dẫn chi tiết dạng PDF hoặc Google Doc, tổ chức buổi training trực tiếp, xây dựng checklist các bước quy trình cho thành viên mới. |
| Giả thuyết về AI (nếu có) | AI có thể cung cấp chatbot hướng dẫn quy trình, trả lời câu hỏi thường gặp và gợi ý các bước tiếp theo cho thành viên mới. |
| Cảm nhận nhanh | No AI — ưu tiên giải pháp tài liệu hướng dẫn truyền thống, chưa thấy cần AI hoặc workflow tự động ở bước này |

Quy trình nháp hiện tại:

1. Thành viên mới nhận thông báo gia nhập team.
2. Thành viên mới tự tìm hiểu các tài liệu hướng dẫn (nếu có).
3. Thành viên mới hỏi các thành viên cũ về quy trình làm việc.
4. Thành viên mới thực hành các bước cơ bản dưới sự hướng dẫn của thành viên cũ.
5. Thành viên mới tự thực hiện công việc và hỏi lại khi gặp khó khăn.


### Problem Card #2


| Trường | Nội dung |
|---|---|
| Job Story | Khi đến cuối tuần, tôi muốn có một công cụ tự động tổng hợp báo cáo của cả team để tiết kiệm thời gian tổng hợp và gửi lên Lead. |
| Actor | PM (Project Manager) |
| Thời điểm / bối cảnh | Mỗi cuối tuần, trước khi gửi báo cáo lên Lead |
| Quy trình hiện tại (3–7 bước) | 1. Nhắc các thành viên gửi báo cáo cá nhân. 2. Thu thập báo cáo từ email hoặc chat. 3. Đọc từng báo cáo. 4. Tổng hợp nội dung vào một file chung. 5. Kiểm tra lại thông tin. 6. Gửi báo cáo tổng hợp lên Lead. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: Tổng hợp nội dung vào file chung, mất khoảng 15–20 phút. |
| Impact (nếu không giải thì sao) | Mất thời gian, dễ sót thông tin, ảnh hưởng tiến độ báo cáo lên Lead. |
| Success metric (baseline → target) | Thời gian tổng hợp báo cáo: 20 phút → dưới 5 phút. |
| Phương án không dùng AI | Sử dụng template báo cáo thống nhất, nhắc nhở deadline, chia nhóm nhỏ để tổng hợp trước. |
| Giả thuyết về AI (nếu có) | AI có thể tự động thu thập, đọc và tổng hợp báo cáo từ nhiều nguồn thành một file duy nhất. |
| Cảm nhận nhanh | Workflow / Agent |

Quy trình nháp hiện tại:


1. PM nhắc các thành viên gửi báo cáo cá nhân trước thời hạn.
2. Các thành viên gửi báo cáo qua email hoặc nền tảng chat nhóm.
3. PM thu thập tất cả các báo cáo từ các nguồn khác nhau.
4. PM đọc và tổng hợp nội dung các báo cáo vào một file chung.
5. PM kiểm tra lại thông tin tổng hợp để đảm bảo không thiếu sót.
6. PM gửi báo cáo tổng hợp cuối cùng lên Lead.


### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi có nhiều ticket cùng gửi đến, tôi muốn biết cái nào có độ ưu tiên cao hơn để có thể hoàn thành trước cho kịp tiến độ sản xuất |
| Actor | Team members (hoặc PM, tùy theo ai là người gặp khó khăn khi có nhiều ticket cần ưu tiên) |
| Thời điểm / bối cảnh | Khi có nhiều ticket cùng gửi đến trong một khoảng thời gian ngắn, cần xác định ưu tiên xử lý để đảm bảo tiến độ sản xuất |
| Quy trình hiện tại (3–7 bước) | 1. Nhận tất cả các ticket mới gửi đến. 2. Đọc nội dung và thông tin liên quan của từng ticket. 3. Đánh giá mức độ khẩn cấp và ảnh hưởng của từng ticket. 4. Thảo luận với team hoặc PM nếu cần thiết để xác định mức độ ưu tiên. 5. Sắp xếp thứ tự ưu tiên xử lý các ticket. 6. Phân công ticket cho các thành viên phù hợp. 7. Theo dõi tiến độ xử lý và cập nhật trạng thái ticket. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước xác định độ ưu tiên của từng ticket, mất khoảng 10–15 phút mỗi lần có nhiều ticket mới. |
| Impact (nếu không giải thì sao) | Nếu không giải quyết, team sẽ xử lý ticket không hiệu quả, dễ bị chậm tiến độ sản xuất, có thể gây trễ đơn hàng và ảnh hưởng đến khách hàng. |
| Success metric (baseline → target) | Thời gian xác định độ ưu tiên ticket: 15 phút → dưới 5 phút |
| Phương án không dùng AI | Sử dụng checklist đánh giá mức độ ưu tiên dựa trên tiêu chí rõ ràng (ví dụ: deadline, mức độ ảnh hưởng, yêu cầu khách hàng), họp nhóm nhanh để phân loại ticket, hoặc áp dụng quy trình phân loại thủ công theo mẫu có sẵn. |
| Giả thuyết về AI (nếu có) | AI có thể tự động phân tích nội dung và mức độ khẩn cấp của các ticket, từ đó đề xuất thứ tự ưu tiên xử lý dựa trên các tiêu chí như deadline, mức độ ảnh hưởng và lịch sử xử lý. |
| Cảm nhận nhanh | No AI — ưu tiên giải pháp thủ công, chưa thấy cần AI hoặc workflow tự động ở bước này |

Quy trình nháp hiện tại:

1. Nhận tất cả các ticket mới gửi đến.
2. Đọc nội dung và thông tin liên quan của từng ticket.
3. Đánh giá mức độ khẩn cấp và ảnh hưởng của từng ticket.
4. Thảo luận với team hoặc PM nếu cần thiết để xác định mức độ ưu tiên.
5. Sắp xếp thứ tự ưu tiên xử lý các ticket.
6. Phân công ticket cho các thành viên phù hợp.
7. Theo dõi tiến độ xử lý và cập nhật trạng thái ticket.

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                                                     | Đồng ý? | Đã sửa gì                                                                                                 |
| ------------------------------------------------------------------------------------------------------ | ------- | --------------------------------------------------------------------------------------------------------- |
| Actor chưa đủ cụ thể, chưa xác định quy mô team và trách nhiệm thực tế của PM.                         | Có      | Chưa bổ sung quy mô team, vai trò và phạm vi trách nhiệm cụ thể.                                          |
| Quy trình chưa được xác thực, mới chỉ là mô tả giả định.                                               | Có      | Chưa có dữ liệu phỏng vấn hoặc quan sát PM thực tế để xác nhận quy trình.                                 |
| Bottleneck chưa được phân rã thành các thao tác cụ thể.                                                | Có      | Chưa xác định 15–20 phút chủ yếu dành cho copy-paste, chuẩn hóa, loại bỏ trùng lặp hay viết lại nội dung. |
| Metric 20 phút chưa có số liệu đo thực tế; target dưới 5 phút chưa tính thời gian kiểm tra và sửa lỗi. | Có      | Chưa có baseline được đo lường và chưa xác định cách đo chất lượng báo cáo sau tổng hợp.                  |
| Chưa chứng minh template và automation thông thường không giải quyết được vấn đề.                      | Có      | Chưa thử nghiệm template thống nhất và quy tắc tự động trước khi lựa chọn AI.                             |
| Đang nhảy sang AI quá sớm, chưa xác định chính xác công đoạn cần AI.                                   | Có      | Chưa tách riêng bài toán thu thập, xử lý nội dung và tổng hợp để xác định phần thực sự cần AI.            |

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
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
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

-
