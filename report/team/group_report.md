# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: AURA
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi thực hiện đồ án nhóm, các thành viên gặp khó khăn và mất nhiều thời gian khi tìm lại tài liệu, quyết định và thông tin quan trọng bị phân tán trên nhiều kênh (Zalo, Google Drive, Google Sheets).
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Dương Minh Chiến | Khi thực hiện đồ án nhóm, tôi muốn theo dõi tiến độ công việc của từng người, để kịp thời phát hiện task trễ hạn | Chiến (Lead) và 4 thành viên đồ án | Kiểm tra nhiều kênh (Zalo, Sheets) và phải đi hỏi từng người (15–25'/lần) | "Nếu nhóm chỉ cần quy định 1 bảng Kanban/Trello cố định và cam kết cập nhật hằng ngày lúc 18h thì đã giải quyết được chưa, tại sao vẫn cần AI?" *(Chí Đức hỏi)* |
| 2 | Dương Minh Chiến | Khi cần tìm lại tài liệu hoặc quyết định đã trao đổi, tôi muốn tìm nhanh chóng, để tiếp tục công việc mà không phải hỏi lại | Cả nhóm đồ án (5 người) | Tìm lại tin nhắn trên Zalo, Drive và hỏi người gửi nếu không thấy (5–10'/lần) | "Bottleneck thật sự là do công cụ tìm kiếm kém, hay do quy ước đặt tên thư mục trên Google Drive của nhóm chưa thống nhất ngay từ đầu?" *(Hưng Thịnh hỏi)* |
| 3 | Dương Minh Chiến | Khi cần tổ chức họp nhóm, tôi muốn tìm được khung giờ phù hợp với các thành viên, để tiết kiệm thời gian thống nhất lịch | Cả nhóm đồ án (5 người) | Chờ phản hồi và đối chiếu lịch bận của từng người qua tin nhắn (10–15'/lần) | "Dùng Google Calendar chia sẻ lịch rảnh hoặc Google Form chọn khung giờ thì có giải quyết được không, có cần dùng AI không?" *(Văn Trường hỏi)* |
| 4 | Trần Đức Trung | Khi đọc bài báo khoa học tiếng Anh, tôi muốn nhanh chóng xác định bài toán và kết quả chính, để chọn tài liệu phù hợp | Sinh viên làm NCKH / đồ án | Đọc và phân tích toàn văn bài báo để lọc ý (khoảng 2 tiếng/bài) | "Đọc Abstract và Conclusion thường chỉ mất 5–10 phút để biết bài toán có hợp không, tại sao lại mất tới 2 tiếng nếu chỉ ở bước sàng lọc tài liệu?" *(Văn Trường hỏi)* |
| 5 | Trần Đức Trung | Khi nhóm chuẩn bị nộp bài tập lớn, tôi muốn kiểm tra báo cáo đã đủ yêu cầu của giảng viên, để tránh thiếu sót hoặc sai định dạng | Người rà soát báo cáo nhóm | Đối chiếu từng mục trong báo cáo với rubric và rubric dài (30'/lần) | "Nếu dùng một checklist mẫu in sẵn đối chiếu chéo giữa 2 thành viên trước hạn nộp thì mất bao nhiêu phút, đã thử cách này chưa?" *(Hưng Thịnh hỏi)* |
| 6 | Trần Đức Trung | Khi đánh giá mô hình AI sau nhiều lần train, tôi muốn đối chiếu các chỉ số và cấu hình thí nghiệm, để biết phiên bản nào thực sự cải thiện | Sinh viên / nhóm nghiên cứu AI | Thu thập log/CSV từ nhiều thư mục để ghép vào một bảng đối chiếu (20'/lần) | "Các công cụ tracking có sẵn như MLflow, WandB hoặc TensorBoard đã có sẵn bảng đối chiếu run, tại sao không dùng mà phải tự làm?" *(Minh Chiến hỏi)* |
| 7 | Trịnh Hưng Thịnh | Khi có thành viên mới vào team, tôi muốn có quy trình cụ thể để đào tạo, để họ không mất thời gian hỏi lại quy trình cơ bản | Thành viên mới, người hướng dẫn | Thành viên mới tự mò tài liệu và hỏi lại thành viên cũ nhiều lần (mất 1–2 ngày) | "Tần suất có thành viên mới vào team là bao lâu một lần? Nếu một học kỳ chỉ có 1–2 lần thì impact có đủ lớn để giải quyết bằng công nghệ không?" *(Đức Trung hỏi)* |
| 8 | Trịnh Hưng Thịnh | Khi đến cuối tuần, tôi muốn tự động tổng hợp báo cáo của cả team, để tiết kiệm thời gian gửi lên Lead | PM / Leader | Đọc và tổng hợp nội dung báo cáo từ nhiều tin nhắn chat/email vào 1 file (15–20'/tuần) | "Việc tổng hợp mất 20 phút mỗi tuần là do đọc và tóm tắt chậm, hay do các thành viên nộp báo cáo muộn và thiếu format chuẩn?" *(Minh Chiến hỏi)* |
| 9 | Trịnh Hưng Thịnh | Khi có nhiều ticket gửi đến cùng lúc, tôi muốn biết ticket nào ưu tiên cao hơn, để hoàn thành kịp tiến độ sản xuất | Thành viên xử lý ticket, PM | Phải đọc từng ticket và đánh giá mức độ khẩn cấp thủ công (10–15'/lần) | "Tiêu chí ưu tiên ticket có thể viết thành rule cứng (như deadline + severity) được không, hay bắt buộc phải có AI phán đoán?" *(Chí Đức hỏi)* |
| 10 | Vũ Văn Trường | Khi hypertune model để đạt kết quả tốt, tôi muốn giảm số lần chỉnh thủ công và train/test, để tiết kiệm thời gian và tài nguyên GPU | Kỹ sư AI / Sinh viên làm CV | Chờ mỗi lần train/test 4–5 tiếng, phải lặp lại 5–6 lần (tốn ~1 tuần/model, đốt quota GPU) | "Các framework như Optuna/Ray Tune đã hỗ trợ tự động tìm kiếm và pruning rất tốt, AI (LLM) tham gia vào sinh search space có nguy cơ hallucinate ra hyperparameter không hợp lệ không?" *(Đức Trung hỏi)* |
| 11 | Vũ Văn Trường | Khi mở điện thoại buổi sáng thấy nhiều tin AI trên X, tôi muốn tổng hợp nhanh thay đổi quan trọng, để tiết kiệm thời gian đọc lướt | Người theo dõi tin AI | Phải lướt và đọc thủ công hàng chục bài post trên feed (20–30'/ngày) | "Ai ngoài bạn chịu ảnh hưởng trực tiếp từ việc này? Nếu không đọc news mỗi sáng thì có gây hậu quả đo đạc được (impact) ngay không?" *(Chí Đức hỏi)* |
| 12 | Vũ Văn Trường | Khi đến cuối tháng, tôi muốn tổng hợp và phân loại chi tiêu từ app ngân hàng thành 4 nhóm, để biết tiền đi đâu và phát hiện khoản bất thường | Sinh viên quản lý chi tiêu (cá nhân) | Mở app ngân hàng, tải giao dịch và phân loại thủ công vào 4 nhóm (~3 giờ/tháng) | "Các app ngân hàng hoặc app quản lý chi tiêu như Money Lover đã có biểu đồ tự động phân loại danh mục chi tiêu, sao không dùng giải pháp đó?" *(Minh Chiến hỏi)* |
| 13 | Lưu Nguyễn Chí Đức | Khi vừa làm xong lab và sắp tới hạn nộp, tôi muốn biết chính xác phải nộp file gì và đặt tên thế nào, để không mất điểm vì sai quy trình | Học viên làm lab (AI20K) | Đưa file vào đúng thư mục và tự kiểm tra đối chiếu lại từng file sát giờ nộp (15'/lần nộp) | "Khâu nộp bài chỉ diễn ra sát hạn nộp mỗi tuần 1 lần, một script bash/powershell kiểm tra tên file và thư mục có thể giải quyết 100% không, có cần đến AI không?" *(Minh Chiến hỏi)* |
| 14 | Lưu Nguyễn Chí Đức | Khi nhóm làm nhiều task song song và có task phụ thuộc nhau, tôi muốn biết task nào đã xong để bắt đầu phần tiếp theo, tránh phải nhắn hỏi mỗi ngày | Thành viên nhóm dự án (4 người) | Chờ người trước phản hồi và giải thích bàn giao (mất 40+ phút/lần, có khi chờ cả ngày) | "Nếu nhóm quy định rõ definition-of-done và gửi pull request/commit tag lên GitHub để tự thông báo thì đã giải quyết được việc chờ chưa?" *(Hưng Thịnh hỏi)* |
| 15 | Lưu Nguyễn Chí Đức | Khi tìm việc trên nhiều trang tuyển dụng, tôi muốn biết nhanh tin nào hợp CV, để dành thời gian ứng tuyển vào đúng việc | Sinh viên tìm việc làm | Dò tin trên 5–7 trang và đọc chi tiết từng JD để đối chiếu với CV (35–60'/tin) | "Bước nghẽn thật sự là do bạn phải vào 5–7 website dò tin thủ công, hay do việc đọc chi tiết từng JD để đối chiếu với CV?" *(Văn Trường hỏi)* |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A (Quản lý thông tin & Phối hợp nhóm đồ án) | #1, #2, #3, #7, #8, #9, #14 | Thông tin, tiến độ, báo cáo và tài liệu bị phân tán trên nhiều kênh rời rạc (Zalo, Drive, Sheets), phụ thuộc giao tiếp thủ công làm mất thời gian tìm kiếm và theo dõi. |
| B (Hỗ trợ học tập, nghiên cứu & Nộp bài) | #4, #5, #13, #15 | Tốn nhiều thời gian đọc lướt, tổng hợp và đối chiếu tài liệu dài (paper, rubric đồ án, quy định nộp bài lab, JD tuyển dụng) với các tiêu chí/yêu cầu đặt ra. |
| C (Tối ưu hóa quy trình kỹ thuật AI / Vận hành) | #6, #10, #11, #12 | Các tác vụ kỹ thuật lặp lại cần xử lý nhiều dữ liệu hoặc tiêu tốn tài nguyên tính toán (hypertune model, phân loại ticket sản xuất, theo dõi log thí nghiệm, tổng hợp news). |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian lãng phí vào các tác vụ tìm kiếm, xác nhận thông tin và phối hợp trong nhóm làm đồ án từ 60 phút/tuần xuống dưới 15 phút/tuần
├── Opportunity A: Thông tin, quyết định quan trọng và tài liệu bị trôi và phân tán rải rác trên Zalo, Drive, Sheets
├── Opportunity B: Mất thời gian hỏi từng thành viên để cập nhật tiến độ công việc và trạng thái task
└── Opportunity C: Khó đối chiếu và phát hiện các task phụ thuộc nhau bị tắc nghẽn trước hạn nộp
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ *"Xây dựng Chatbot AI tra cứu tài liệu trên Zalo"* (Đây là solution cụ thể, đưa giải pháp công nghệ vào trước khi hiểu sâu vấn đề)
- ✗ *"Tạo Dashboard Notion/Trello tự động đồng bộ"* (Đây là công cụ/tính năng, không phải nhu cầu hay pain gốc của người dùng)
- ✗ *"AI Agent tự động nhắc việc và tag tên thành viên"* (Đây là ý tưởng giải pháp đội lốt opportunity)

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #2 Thông tin & tài liệu bị phân tán trên nhiều kênh (Chiến) | 5 | 5 | 5 | 4 | 5 | 5 | 5 | **34** |
| #13 Kiểm tra file và cấu trúc trước khi nộp bài lab (Đức) | 5 | 5 | 4 | 4 | 5 | 3 | 5 | **31** |
| #10 Tự động hóa hypertuning mô hình AI (Trường) | 4 | 4 | 4 | 4 | 3 | 4 | 4 | **27** |

**Candidate được chọn:**
Candidate #2 — Khó tìm lại tài liệu, quyết định và nội dung trao đổi bị phân tán trên nhiều nền tảng (Zalo, Google Drive, Google Sheets) trong nhóm đồ án.

**Vì sao chọn:**
1. **Pain có thật và thường trực:** Xảy ra hàng tuần trong suốt 8 tuần làm đồ án của sinh viên; cả 5 thành viên nhóm đều là actor trực tiếp, dễ dàng lấy dữ liệu chứng minh.
2. **Vừa sức và khả thi cao trong lab:** Nhóm có thể phỏng vấn ngay các nhóm sinh viên khác trong lớp tại CP4 để kiểm chứng giả định mà không phụ thuộc hạ tầng phức tạp.
3. **Phổ so sánh 4 mức rất rõ ràng:**
   - *No AI:* Thống nhất quy ước đặt tên file, cấu trúc thư mục Drive và ghim tin nhắn (pin note).
   - *Rule:* Webhook tự động gom link tài liệu gửi vào Zalo về một Google Sheets.
   - *Workflow:* RAG search tra cứu tài liệu ngữ nghĩa.
   - *Agent:* Tự động tổng hợp và trả lời câu hỏi phức tạp xuyên kênh.

**Vì sao loại các candidate còn lại:**
- **Loại Candidate #13 (Kiểm tra file nộp lab):** Mức can thiệp đơn giản nhất là *Rule* (script PowerShell/Bash kiểm tra tên file và thư mục) đã có thể giải quyết triệt để 90–100%. Nếu dùng AI sẽ là over-engineering; hơn nữa tần suất phát sinh thấp (chỉ vài phút cuối tuần).
- **Loại Candidate #10 (Hypertuning model AI):** Đòi hỏi tài nguyên tính toán GPU lớn, thời gian train kéo dài nhiều giờ khiến việc kiểm chứng và đo đạc trong khuôn khổ buổi lab không khả thi; rủi ro ảo giác (hallucination) tham số lớn.

**Xử lý bất đồng (nếu có):**
Ban đầu có thành viên muốn chọn Candidate #10 vì hứng thú với khía cạnh kỹ thuật mô hình AI. Tuy nhiên, sau khi đối chiếu với tiêu chí "Vừa sức trong 4 tiếng lab" và "Khả năng kiểm chứng thực tế với người dùng thật", nhóm đã phản biện rằng Candidate #10 khó phỏng vấn được đối tượng rộng trong lớp và dễ rơi vào bẫy "nghĩ giải pháp trước khi hiểu vấn đề". Cả nhóm đã đồng thuận 100% chọn Candidate #2.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | PM, Team Leader hoặc thành viên nhóm thường xuyên phải tham gia tổng hợp báo cáo công việc. | Value | 5 | 1 | Có |
| 2 | Việc thu thập báo cáo từ nhiều nguồn hoặc báo cáo không thống nhất định dạng gây khó khăn cho quá trình tổng hợp. | Value | 5 | 1 | Có |
| 3 | Các nhóm thường gặp tình trạng thiếu thông tin hoặc thành viên gửi báo cáo trễ. | Value | 5 | 1 | Có |
| 4 | Việc tổng hợp báo cáo thủ công gây ảnh hưởng đáng kể đến công việc của người phụ trách. | Value | 5 | 1 | Có |
| 5 | Người phụ trách có nhu cầu ưu tiên cải thiện công đoạn thu thập hoặc tổng hợp báo cáo vào file chung. | Value | 4 | 1 | Có |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Drive Search | https://support.google.com/drive/answer/2375114 | Tìm lại tài liệu, báo cáo và Google Sheets đã lưu trên Drive. | Có sẵn, dễ sử dụng; hỗ trợ tìm theo tên, nội dung, loại file và thời gian chỉnh sửa. | Không tìm được nội dung trao đổi trên Zalo; tài liệu phân tán hoặc đặt tên không thống nhất vẫn khó tìm. | Nên thử chuẩn hóa tên file và cấu trúc thư mục Drive trước khi sử dụng AI. |
| Notion Wiki | https://www.notion.com/help/wikis-and-verified-pages | Tập trung các quyết định, biên bản họp và đường dẫn tài liệu của nhóm vào một nơi. | Dễ tổ chức thông tin theo từng dự án; hỗ trợ tìm kiếm và cập nhật nội dung chung. | Thành viên phải chủ động cập nhật; thông tin trên Zalo và Drive không tự động được tập hợp đầy đủ. | Cần thống nhất nơi lưu trữ thông tin quan trọng và quy định người chịu trách nhiệm cập nhật. |
| Gemini Notebook (NotebookLM) | https://support.google.com/gemininotebook/answer/16215270 | Tìm kiếm, tổng hợp và trả lời câu hỏi từ các tài liệu Google Docs, Sheets, PDF đã đưa vào notebook. | Hỗ trợ hỏi đáp bằng ngôn ngữ tự nhiên, tổng hợp nhiều tài liệu và trích dẫn nguồn để kiểm tra. | Cần lựa chọn nguồn tài liệu; không tự động bao phủ toàn bộ tin nhắn Zalo; câu trả lời AI vẫn cần kiểm chứng. | Có thể thử nghiệm AI trên một tập tài liệu nhỏ và so sánh thời gian, độ chính xác với cách tìm kiếm thủ công. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
