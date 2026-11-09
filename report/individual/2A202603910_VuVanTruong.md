# Báo cáo cá nhân — 2A202603910_VuVanTruong

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới của bạn, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Văn Trường
- MSSV: 2A202603910
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: AURA
- Link repo nhóm: https://github.com/duongchien147/K5-L3B-DAY02-AURA-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi mở điện thoại buổi sáng và thấy nhiều bài đăng về AI trên X, tôi muốn tổng hợp nhanh các thay đổi quan trọng, để tiết kiệm 20–30 phút đọc lướt và không bỏ sót breakthrough | Chính tôi (1 người) | Mất 20–30 phút/sáng; 7 ngày/tuần ≈ 2,3–3,5 giờ/tuần; chỉ mình tôi gặp; bằng chứng: các bài đã lưu lại trên X (không đo được số bài cụ thể, không có screenshot) |
| 2 | Lặp lại | Khi đã qua ~3-4 tuần kể từ lần khám trước, tôi muốn được nhắc để đặt lịch hẹn mới, để không quên và phải đặt lại muộn | Chính tôi (1 người) | Bỏ lỡ 1 lần, quá lịch hẹn 3 lần trong thời gian qua; phải đợi 1-2 tiếng nếu đi khám, và phải đặt lại lịch hẹn khác ban đầu; bằng chứng: lịch sử khám; chỉ mình tôi chịu ảnh hưởng |
| 3 | Tốn thời gian | Khi đến cuối tháng, tôi muốn tổng hợp và phân loại chi tiêu từ app ngân hàng thành 4 nhóm (nhà/điện, ăn uống, giải trí, linh tinh), để biết tiền đi đâu và phát hiện khoản chi bất thường | Chính tôi (1 người) | Mất ~3 giờ/tháng tổng hợp từ app ngân hàng; phân loại thành 4 nhóm: tiền nhà/điện, tiền ăn uống, tiền sinh hoạt/vui chơi giải trí, linh tinh; chỉ mình tôi chịu ảnh hưởng; bằng chứng: lịch sử giao dịch ngân hàng (không có screenshot tổng hợp) |
| 4 | Pain từ người khác | Khi đang làm task trong nhóm mà yêu cầu bị thay đổi giữa chừng, tôi thấy các thành viên phải dừng và làm lại, để tránh lãng phí thời gian và công sức đã bỏ ra | Các thành viên nhóm (người khác) | Khoảng 3-4 lần trong nhóm project và nhóm lab; những thành viên có task liên quan bị ảnh hưởng; mất khoảng 30 phút - 1 giờ để claim lại và làm lại; bằng chứng: meeting, tin nhắn nhóm; pain chính là thay đổi yêu cầu giữa chừng, không phải phân công ban đầu không rõ |
| 5 | Lặp lại | Khi cần hypertune model để đạt kết quả tốt, tôi muốn giảm số lần phải chỉnh thủ công và chạy train/test, để tiết kiệm thời gian và công sức lặp lại | Chính tôi (1 người) | ~5-6 lần lặp (adjust → train → test) cho mỗi model; mỗi lần chạy mất 4-5 tiếng (computer vision); tổng ~1 tuần/model; chỉ mình tôi chịu ảnh hưởng; bằng chứng: log training trên Kaggle (không có screenshot) |
| 6 | Lặp lại | Khi bắt đầu project mới, tôi muốn setup môi trường nhanh và không bị conflict CUDA/Python, để không mất 30 phút - 1 giờ mỗi project | Chính tôi (1 người) | 1-2 project/tháng; mất 30 phút - 1 giờ setup mỗi project; conflict chủ yếu thư viện CUDA chưa support các thư viện Python mới; không có số lần cụ thể; không còn bằng chứng cụ thể; chỉ mình tôi chịu ảnh hưởng |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cần đọc paper để làm research, tôi muốn trích xuất method/result nhanh, để không mất 5-6 ngày mỗi bài | Chính tôi (1 người) | 3-4 paper/tháng; 1 bài mất 5-6 ngày để đọc; chỉ mình tôi chịu ảnh hưởng; không có bằng chứng cụ thể |

**Nếu có dùng AI để gợi ý thêm:** Không dùng AI ở bước scan; các problem đều từ trải nghiệm thật. AI chỉ dùng ở CP2 để phản biện Problem Card, không gợi ý thêm problem.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #5 Hypertuning model | Pain không chỉ là thời gian chạy (~1 tuần/model, 20-30 giờ) mà còn là sự tốn kém tài nguyên compute (đốt quota GPU Kaggle) và sự cồng kềnh khi phải setup search space thủ công cho từng kiến trúc model (ResNet, ViT, v.v.) | Nỗi lo về việc AI có thể hiểu ngữ cảnh code tốt đến đâu để sinh search space tối ưu; LLM có thể hallucinate ra hyperparameter không hợp lệ |
| 2 | #1 Tổng hợp AI news từ X | Pain lặp lại hàng ngày (20-30 phút/sáng × 7 ngày), bottleneck cụ thể, dễ kiểm chứng | Chưa chắc AI tóm tắt có đủ chính xác và không bỏ sót breakthrough |
| 3 | #3 Tổng hợp chi tiêu cuối tháng | Pain rõ ràng (~3 giờ/tháng), bottleneck cụ thể (phân loại thủ công), workflow before/after dễ vẽ | Chưa chắc app ngân hàng có API để tự động lấy dữ liệu |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần hypertune model để đạt kết quả tốt, tôi muốn giảm số lần phải chỉnh thủ công và chạy train/test, để tiết kiệm thời gian và công sức lặp lại |
| Actor | ML Engineers / AI Researchers làm việc trong môi trường giới hạn tài nguyên (Kaggle/Colab) |
| Thời điểm / bối cảnh | Khi train model CV, cần tune hyperparameter để đạt kết quả tốt |
| Quy trình hiện tại (3–7 bước) | 1. Chỉnh hyperparameter → 2. Chạy train → 3. Chạy test/eval → 4. So sánh kết quả → 5. Lặp lại (5-6 lần) |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-3: mỗi lần chạy train/test mất 4-5 tiếng; tổng ~1 tuần/model. Ngoài ra còn tốn thời gian setup thủ công không gian tìm kiếm (search space) cho từng kiến trúc model (ResNet, ViT, v.v.) |
| Impact (nếu không giải thì sao) | Lãng phí ~1 tuần/model (~20-30 giờ) và đốt cháy quota GPU trên Kaggle vào những trial có khả năng thất bại cao ngay từ những epoch đầu |
| Success metric (baseline → target) | Baseline: ~1 tuần/model (5-6 lần × 4-5 giờ) → Target: < 1 ngày/model |
| Phương án không dùng AI | Dùng Optuna/Ray Tune/Hyperopt (Tự động hóa tốt nhưng vẫn yêu cầu con người phải hiểu sâu để viết code cấu hình search space thủ công; không có khả năng suy luận dựa trên ngữ cảnh code/kiến trúc model) |
| Giả thuyết về AI (LLM Agent) | AI (LLM) đọc code để tự động sinh search space phù hợp, đồng thời phân tích biểu đồ loss (Time-series/CV) để quyết định dừng sớm (pruning) các trial tệ chỉ sau vài epoch, hoạt động như một "Senior ML Engineer" thực thụ |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
[Chỉnh hyperparam] → [Train 4-5h] → [Test/Eval] → [So sánh] → (lặp 5-6 lần) → [Chọn best]
        ↑___________________________________________________________|
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi mở điện thoại buổi sáng và thấy nhiều bài đăng về AI trên X, tôi muốn tổng hợp nhanh các thay đổi quan trọng, để tiết kiệm 20-30 phút đọc lướt và không bỏ sót breakthrough |
| Actor | Sinh viên theo dõi AI (chính tôi) |
| Thời điểm / bối cảnh | Buổi sáng, mở điện thoại, lướt feed X |
| Quy trình hiện tại (3–7 bước) | 1. Mở app X → 2. Lướt feed → 3. Đọc bài đăng → 4. Lưu bài quan trọng → 5. Tổng hợp trong đầu |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-3: lướt và đọc mất 20-30 phút/sáng |
| Impact (nếu không giải thì sao) | Mất 20-30 phút/sáng × 7 ngày = 2,3-3,5 giờ/tuần; có thể bỏ sót breakthrough quan trọng |
| Success metric (baseline → target) | Baseline: 20-30 phút/sáng → Target: < 5 phút/sáng |
| Phương án không dùng AI | Dùng RSS feed, curated list tài khoản, newsletter AI (The Batch, TLDR AI) |
| Giả thuyết về AI (nếu có) | AI tóm tắt bài đăng và lọc bài quan trọng theo lĩnh vực quan tâm |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
[Mở X] → [Lướt feed 20-30p] → [Đọc bài] → [Lưu bài quan trọng] → [Tổng hợp trong đầu]
              ↑ (bottleneck)
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến cuối tháng, tôi muốn tổng hợp và phân loại chi tiêu từ app ngân hàng thành 4 nhóm, để biết tiền đi đâu và phát hiện khoản chi bất thường |
| Actor | Sinh viên quản lý chi tiêu (chính tôi) |
| Thời điểm / bối cảnh | Cuối mỗi tháng, khi cần tổng kết chi tiêu |
| Quy trình hiện tại (3–7 bước) | 1. Mở app ngân hàng → 2. Xem giao dịch → 3. Phân loại vào 4 nhóm (nhà/điện, ăn uống, giải trí, linh tinh) → 4. Tổng hợp → 5. Phân tích |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-4: phân loại và tổng hợp mất ~3 giờ/tháng |
| Impact (nếu không giải thì sao) | Mất ~3 giờ/tháng cho việc tổng hợp chi tiêu; có thể bỏ sót khoản chi bất thường |
| Success metric (baseline → target) | Baseline: ~3 giờ/tháng → Target: < 15 phút/tháng |
| Phương án không dùng AI | Dùng app quản lý chi tiêu (Money Lover, Spendee) hoặc Excel template với công thức tự động |
| Giả thuyết về AI (nếu có) | AI tự động phân loại giao dịch từ sao kê ngân hàng vào 4 nhóm |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
[Mở app NH] → [Xem GD] → [Phân loại 4 nhóm ~3h] → [Tổng hợp] → [Phân tích]
                          ↑ (bottleneck)
```

### Card muốn pitch nhất

- Card số: #5
- Vì sao: Vấn đề rất thực tế với dân làm AI, có metric rõ ràng (từ 1 tuần xuống 1 ngày), và giải pháp AI Agent giải quyết được điểm yếu của các thư viện truyền thống (Optuna) — không chỉ tìm số mà còn đọc code, sinh search space và pruning sớm.
- Câu hỏi muốn nhóm phản biện: "Làm sao để AI Agent có thể đọc hiểu code của các framework khác nhau (PyTorch, TensorFlow) để sinh search space chính xác?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chi phí gọi LLM API mỗi lần tune có thể rất cao (nhiều iteration × nhiều trial) | Đồng ý | Dùng local model nhỏ (ví dụ: Llama 3 8B quantized) cho bước sinh search space; chỉ gọi API mạnh cho phân tích loss curve quan trọng |
| Độ trễ: LLM suy luận chậm, có thể làm chậm toàn bộ pipeline tuning | Đồng ý | Tách bước sinh search space (chạy 1 lần trước khi tune) khỏi bước pruning (chạy real-time); cache kết quả LLM |
| LLM có thể hallucinate ra hyperparameter không hợp lệ (ví dụ: learning rate = 0.99) | Đồng ý | Thêm lớp rule-based validation để kiểm tra output của LLM trước khi đưa vào Optuna; reject các giá trị ngoài range hợp lý |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch card #10 (Hypertuning model), #11 (tổng hợp AI news từ X), #12 (tổng hợp chi tiêu cuối tháng); card #10 muốn pitch nhất | Bảng pitch 15 card trong `group_report.md` mục 2.1 (dòng 10–12) |
| Phản biện bài của bạn khác | Hỏi Trần Đức Trung về candidate #4 (đọc paper): "Đọc Abstract và Conclusion thường chỉ mất 5–10 phút, tại sao mất tới 2 tiếng nếu chỉ ở bước sàng lọc?" ; hỏi Lưu Nguyễn Chí Đức candidate #15: "Bước nghẽn thật sự là do phải dò 5–7 website hay do đọc JD để đối chiếu CV?" | Ghi trong cột "Câu hỏi phản biện nhận được" của các dòng pitch tương ứng |
| Nhận phản biện | Câu hỏi nhận được: "Các framework như Optuna/Ray Tune đã hỗ trợ tự động tìm kiếm và pruning rất tốt, AI (LLM) sinh search space có nguy cơ hallucinate không?" (Đức Trung); "Ai ngoài bạn chịu ảnh hưởng trực tiếp?" (Chí Đức) | Tôi đã sửa: thêm rule-based validation để kiểm tra output LLM trước khi đưa vào Optuna; thu hẹp impact card #11 về bản thân |
| Gom cluster / cây OST | Góp ý gom candidate #10, #11, #12 vào Cluster C (tối ưu tác vụ kỹ thuật lặp lại) | Bảng cluster mục 2.2, Opportunity C trong cây OST mục 2.3 |
| Chọn candidate problem | Phản biện candidate #10 vì over-engineering và khó kiểm chứng trong lab; đồng thuận chọn candidate #2 | Mục 2.4: candidate #10 bị loại với lý do "đòi hỏi GPU, khó phỏng vấn đối tượng rộng"; xử lý bất đồng ghi rõ |
| Kiểm chứng / research | Hỗ trợ Trần Đức Trung research 6 công cụ giải pháp (Google Drive Search, Notion Wiki, Gemini Notebook, Glean, Slack Enterprise Search, Conclude) | Bảng research `group_report.md` mục 3.3 (6 dòng, link mở được) |
| Quy trình nhóm | Rà soát quy trình hiện tại/tương lai và bảng before/after do Chí Đức vẽ; góp ý thêm rủi ro mới phát sinh | `group_report.md` mục 4.1–4.3 |
| Problem Statement | Rà soát PS v0; điền PS v1 trường AI intervention point, mức chọn, rủi do & người kiểm tra | `group_report.md` mục 5 và 7 |
| Mức can thiệp AI | Điền ma trận, so sánh 4 mức, AI Canvas, 2 câu PAIR, PS v1, 5 tiêu chí eval | `group_report.md` mục 6.1–6.4 và 7 |
| Quyết định | Tham gia chấm 4 rủi ro và kết luận Go (pilot nhỏ nhất) + ngưỡng dừng | `group_report.md` mục 8.1–8.2 |



---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Không dùng AI để scan; tự viết 7 problem từ trải nghiệm thật | — | — | Giữ nguyên các dấu hiệu thật (thời gian, tần suất) dù chưa có screenshot; không thêm problem giải pháp trá hình |
| CP2 Problem Card | Dùng AI đóng vai PM hoài nghi phản biện 3 card (điểm yếu: chi phí LLM API, độ trễ, hallucinate hyperparameter) | AI chỉ ra đúng 3 rủi ro sát thủ cho card #1, giúp tôi thêm lớp rule-based validation và tách bước sinh search space | AI ban đầu đề xuất cả "Agent tự động tune end-to-end" — over-engineering, không vừa sức lab | Tôi sửa: Agent chỉ đọc code sinh search space + pruning sớm; không để AI tự chốt hyperparameter; thêm Optuna làm engine thực thi |
| CP4 Research | AI gợi ý danh sách công cụ giải pháp đã có (6 công cụ) | AI tổng hợp nhanh các tool enterprise search (Glean, Slack Enterprise Search, Conclude) để so sánh khoảng trống | AI có xu hướng gợi ý tool đắt/enterprise không phù hợp nhóm sinh viên; một số link cần tự mở lại để kiểm | Tôi lọc lại theo tiêu chí "nhẹ, miễn phí, phù hợp SV VN dùng Zalo/Drive"; chỉ giữ tool có link mở được và đúng nội dung |
| CP5 Quy trình | Nhờ AI chuyển mô tả quy trình sang Mermaid và phản biện PS v0 | AI gợi ý thêm tiêu chí "không dùng nhầm bản cũ" vào metric | AI gộp bước 2–4 thành một bước, làm mất bottleneck tìm kiếm rải rác | Tôi tách lại các bước và giữ bottleneck 15 phút chờ người đã gửi; sửa metric theo phản biện nhưng giữ baseline 45 phút |
| CP5–6 Problem Statement | Nhờ AI chỉ ra lỗ hổng PS v0 (metric chưa đo chất lượng, phụ thuộc gắn nhãn) | AI đặt câu hỏi đúng: "Success metric mới chỉ đo thời gian, chưa đo đúng bản mới nhất" | AI đề xuất thêm trường "AI confidence score" không cần thiết cho bài toán | Tôi thêm tiêu chí "không dùng nhầm bản cũ" và "100% kiểm tra nguồn", bỏ trường confidence |
| CP6 Mức can thiệp / quyết định | AI hỗ trợ so sánh 4 mức và gợi ý eval criteria | AI gợi ý tiêu chí "khả năng quay về" (fallback) — tôi thấy rất hữu ích | AI ban đầu gợi ý chọn Agent vì "nghe ấn tượng hơn"; không giải thích vì sao Workflow không đủ | Tôi giữ Workflow, viết rõ lý do không chọn Agent (over-engineering, boundary AI chỉ đọc); thêm ngưỡng dừng đo được |



---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi học được rằng cùng một pain "thông tin phân tán" có thể được nhìn từ nhiều actor khác nhau: Minh Chiến nhìn từ góc nhóm trưởng (theo dõi tiến độ), Hưng Thịnh từ góc PM sản xuất (tổng hợp báo cáo, ticket), Chí Đức từ góc thành viên (bàn giao task). Nhờ vậy tôi hiểu candidate #2 không chỉ là "tìm file" mà là "phối hợp nhóm đồ án" tổng thể. Tôi cũng nhận ra candidate #10 (hypertuning) của tôi bị phản biện đúng: nó thú vị kỹ thuật nhưng khó kiểm chứng trong 4 tiếng lab và khó phỏng vấn đối tượng rộng — bài học "vừa sức lab" quan trọng hơn "ngầu".

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, ngay ở candidate #2: một số thành viên đề xuất "xây chatbot AI tra cứu tài liệu trên Zalo" trước khi hiểu pain. Nhóm nhận ra khi vẽ cây OST — ý đó là solution đội lốt opportunity, nên gạch bỏ khỏi tầng opportunity. Tương tự candidate #10 của tôi cũng bị nghi ngờ là "nghĩ giải pháp trước": tôi pitching "LLM Agent đọc code sinh search space" trước khi kiểm chứng pain có thật với người khác. Nhóm xử lý bằng tiêu chí "Vừa sức lab" và "Khả năng kiểm chứng với người dùng thật" để loại candidate #10, đồng thời ép tôi phải chứng minh pain hypertuning bằng log training thật.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Ban đầu tôi pitching candidate #10 và nghĩ AI Agent có thể tự tune end-to-end. Đức Trung phản biện: "Optuna/Ray Tune đã hỗ trợ tự động tìm kiếm và pruning rất tốt, AI sinh search space có nguy cơ hallucinate ra hyperparameter không hợp lệ không?" Tôi đồng ý và sửa Problem Card: AI chỉ đọc code sinh search space + pruning sớm, còn engine thực thi là Optuna; thêm lớp rule-based validation để reject hyperparameter ngoài range. Đây là lần tôi đổi từ "Agent tự làm hết" sang "Agent hỗ trợ một bước cụ thể".

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Có. Survey chỉ 8 người và 3/8 nói "template là đủ" — tín hiệu phản bác nhỏ nhưng quan trọng, buộc nhóm phải giải thích vì sao No AI không đủ (thông tin đã phân tán từ trước, nhóm SV không tuân thủ quy ước). Research 6 công cụ cũng làm tôi bất ngờ: Glean/Slack Enterprise Search đã làm AI search xuyên kênh từ lâu, nhưng enterprise-grade và đắt; nhóm SV VN dùng Zalo/Drive nên khoảng trống vẫn còn. Điều này củng cố quyết định Go (pilot nhỏ nhất) thay vì tự xây agent.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là giữ Problem Statement không chứa giải pháp. Khi viết v0 tôi dễ viết "AI tìm kiếm ngữ nghĩa" vào phần Quy trình/Bottleneck. Khó thứ hai là Success Metric phải có baseline, target và cách đo: baseline "45 phút/lần" là ước tính từ một lần tìm gần nhất, chưa kiểm chứng bằng phỏng vấn — tôi phải thừa nhận đây là điểm yếu. Khó thứ ba là boundary: phải ghi rõ AI không được làm gì (không sửa/xóa/gửi, không trả lời khi không có nguồn) và ai kiểm tra (HITL).

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ phản biện candidate #2 mạnh hơn ở feasibility: mọi người có thật sự gắn nhãn tin nhắn/quyết định không, hay chỉ là kỳ vọng? Tôi cũng sẽ yêu cầu nhóm kiểm chứng baseline 45 phút bằng phỏng vấn trước khi viết metric, thay vì dùng số ước tính. Ngoài ra tôi sẽ phản biện candidate #13 (kiểm tra file nộp lab) kỹ hơn: nó bị loại vì Rule đã đủ, nhưng nếu đo tần suất "sát giờ nộp" thì impact có thể lớn hơn nhóm nghĩ. Cuối cùng, tôi sẽ viết reflection sớm hơn thay vì để trống đến cuối.

**6.7. Hiểu bài:** Nhóm chọn bài toán thông tin, tài liệu và quyết định bị phân tán trên Zalo/Drive/Sheets trong nhóm đồ án sinh viên. Quy trình hiện tại mất 45 phút/lần tìm vì phải lục từng nơi và chờ người đã gửi trả lời. Metric muốn giảm xuống dưới 5 phút/lần và không dùng nhầm bản cũ. Boundary rõ: AI chỉ đọc, không sửa/xóa/gửi, không trả lời khi không có nguồn; người hỏi phải kiểm tra nguồn trước khi dùng (HITL). Nhóm chọn mức can thiệp Workflow: Rule gom link chạy nền + AI tìm kiếm ngữ nghĩa trả lời kèm nguồn, vì No AI phụ thuộc kỷ luật con người và Agent là over-engineering. Quyết định Go (pilot nhỏ nhất) với ngưỡng dừng: nếu sau 2 tuần thời gian tìm không xuống dưới 15 phút/lần hoặc hơn 50% câu hỏi AI không tìm được nguồn thì quay về cách cũ.



---

## 7. Tài liệu tham khảo

- Group report `report/team/group_report.md` mục 3.3 (bảng research 6 công cụ).
- Google Drive Search — https://support.google.com/drive/answer/2375114
- Notion Wiki — https://www.notion.com/help/wikis-and-verified-pages
- Gemini Notebook (NotebookLM) — https://support.google.com/gemininotebook/answer/16215270
- Glean — https://www.glean.com
- Slack Enterprise Search — https://slack.com/intl/zh-cn/features/enterprise-search
- Conclude — https://conclude.app
- Frameworks: Lean UX (Jeff Gothelf), Google PAIR, The Mom Test (Rob Fitzpatrick), Opportunity Solution Tree (Teresa Torres), Assumption Map (David Bland), Prediction Machines (Agrawal, Gans, Goldfarb), Building Effective Agents (Anthropic).
