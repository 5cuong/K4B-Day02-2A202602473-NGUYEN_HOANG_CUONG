# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Hoàng Cường
- Mã học viên: 2A202602473
- Vai trò / bối cảnh: Học viên Day 02, thực hiện problem scan từ các workflow nghiệp vụ văn phòng/tài chính/hỗ trợ vận hành đã quan sát.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): tổng hợp báo cáo/số liệu; xử lý hoặc theo dõi tác vụ lặp lại; đọc và đối chiếu tài liệu; phối hợp với các bên liên quan; rà soát kết quả trước khi gửi.


---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                                                                                                                                                                                                                                                                                                                                                                                                            | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng)                                                                                                                                                                                                                                              |
|---|------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Tốn thời gian,AI có thể làm tốt hơn, Pain từ người khác,(có thể: Lặp lại)    | Tốn thời gian Tổng hợp báo cáo doanh thu tuần thủ công bởi Trưởng nhóm Sale đo bằng số giờ làm việc mỗi thứ Hai.<br/>AI có thể làm thay:AI/Automation có thể tự động gom dữ liệu từ 4 file Excel và xuất báo cáo sau 5 giây.Lăng kính. Pain từ người khác: Giám đốc Kinh doanh phải đợi báo cáo muộn, không kịp ra quyết định đầu tuần. Lăng kính: Pain từ người khác: Giám đốc Kinh doanh phải đợi báo cáo muộn, không kịp ra quyết định đầu tuần. |Trưởng nhóm Sale, Giám đốc Kinh doanh | • Mất 3.5 tiếng liên tục vào mỗi sáng thứ Hai (kết quả bấm giờ 3 tuần liên tiếp).• Dữ liệu phân mảnh từ 4 nguồn file Excel khác nhau do các nhóm gửi về muộn.• Bằng chứng: Lịch sử gửi mail báo cáo muộn của Sale và timestamp hoàn thành file tổng hợp luôn sau 11h30 trưa. |
| 2 | Lặp lại, Tốn thời gian, AI có thể làm tốt hơn, Pain từ người khác.           | Phân loại và gán thẻ ticket hỗ trợ kỹ thuật bởi Nhân sự trực tổng đài đo bằng số lượng ticket xử lý mỗi ngày.Tốn 2 phút/ticket, tích tụ thành 4-5 tiếng/ngày chỉ để phân loại.Thao tác đọc - chọn danh mục lặp đi lặp lại 120-150 lần/ngày.AI (NLP) có thể đọc hiểu nội dung ticket và tự động gán thẻ chính xác 95% ngay lập tức.Khách hàng phải chờ đợi lâu hơn; Đội Support Line 2 nhận ticket sai phòng ban do lỗi phân loại tay.                                                                                                                                                                                                                                                                                                                                    |Đội ngũ Support Line 1, Khách hàng | Tần suất 120-150 ticket/ngày, mỗi ticket mất 2 phút chỉ để đọc và chọn danh mục thủ công (Theo log hệ thống Jira tuần qua),                                                                                                                                                  |
| 3 | Tốn thời gian, AI có thể làm tốt hơn, Pain từ người khác, Lặp lại            | Tóm tắt biên bản cuộc họp họp giao ban bởi Trợ lý dự án đo bằng thời gian hoàn thành sau cuộc họp.  Mất thêm 1.5 tiếng sau cuộc họp kéo dài 2 tiếng để hoàn thành biên bản.Diễn ra hằng ngày sau mỗi buổi họp giao ban.AI có thể chuyển giọng nói thành văn bản (Speech-to-Text) và tóm tắt hành động (Action items) trong 1 phút.12 thành viên nhận được biên bản quá muộn (lúc 19h), làm chậm tiến độ thực thi công việc của ngày hôm đó.                                                                                                                                                                                                                                                                                                                                             |Toàn bộ thành viên dự án (12 người) | Cuộc họp kéo dài 2 tiếng/ngày, trợ lý mất thêm 1.5 tiếng để nghe lại ghi âm và viết tóm tắt (Dựa trên timestamp gửi email biên bản lúc 19h).                                                                                                                                 |
| 4 | Tốn thời gian,AI có thể làm tốt hơn, Pain từ người khác,(có thể: Lặp lại)    | Xét duyệt yêu cầu mua sắm thiết bị chậm trễ bởi Trưởng phòng Tài chính đo bằng ngày chờ đợi phê duyệt. Quy trình thủ công khiến ticket bị ngâm, kéo dài 4 ngày chờ đợi.Quy trình ký duyệt duyệt qua nhiều cấp diễn ra mỗi khi có nhân sự mới hoặc dự án mới.AI có thể tự động kiểm tra hạn mức ngân sách và duyệt tự động các case chuẩn dưới một số tiền nhất định.5 nhân sự Đội Design/IT phải dừng dự án, ngồi không chờ phần mềm, gây lãng phí nguồn lực công ty.                                                                                                                                                                                                                                                                                                                                          |Nhân viên cấp dưới (Đội Design/IT) | Đội Design có 5 người phải dừng dự án 4 ngày để đợi duyệt mua bản quyền phần mềm (Mã ticket mua sắm: #REQ-8829).                                                                                                                                                             |
| 5 | Lặp lại, Tốn thời gian, AI có thể làm tốt hơn, Pain từ người khác.           | Soát lỗi chính tả và format hợp đồng bởi Chuyên viên Pháp chế đo bằng số lỗi sót lại trên mỗi bản thảo. Mất 45 phút cho mỗi bản hợp đồng dài 20 trang.Kiểm tra thủ công từng câu chữ, dấu chấm phẩy 15 lần/tuần.AI (LLM) có thể quét lỗi chính tả, rà soát điều khoản ẩn và đối chiếu format chuẩn trong 10 giây.Đội Kinh doanh bị chậm trễ gửi hợp đồng cho đối tác; Kinh doanh/Pháp chế đổ lỗi cho nhau khi sót lỗi nghiêm trọng.                                                                                                                                                                                                                                                                                                                                         |Đội Pháp chế, Đội Kinh doanh | Trung bình 45 phút/hợp đồng 20 trang, kiểm tra 15 hợp đồng/tuần, phát hiện sót 3 lỗi nghiêm trọng ở bản in cuối (Quote chỉnh sửa nội bộ số #LEGAL-02).                                                                                                                       |
| 6 | Lặp lại, Tốn thời gian, AI có thể làm tốt hơn, Pain từ người khác.           | Gửi email nhắc nhở gia hạn hợp đồng cho khách hàng bởi Nhân viên CSKH đo bằng tỷ lệ khách hàng phản hồi.Tốn 10 phút/email, tổng cộng mất gần 7 tiếng/tuần chỉ để soạn và gửi email.Thao tác lọc danh sách và copy-paste văn bản lặp lại 40 lần/tuần.AI kết hợp Automation có thể tự động gửi email cá nhân hóa dựa trên trigger ngày hết hạn trong CRM.Khách hàng nhận email chậm nên quên gia hạn; Công ty bị sụt giảm doanh thu giữ chân khách hàng (Retention rate).                                                                                                                                                                                                                                                                                                                                         |Đội CSKH (Account Executive) | Phải lọc tay và gửi 40 email nhắc nhở/tuần, mất 10 phút/email soạn thảo và kiểm tra ngày hết hạn (Báo cáo hiệu suất tháng 8 phòng CSKH).                                                                                                                                     |
| 7 | AI có thể tốt hơn, tốn thời gian, lặp lại, Pain từ người khác                | Sáng tạo ý tưởng nội dung (Brainstorm) đăng bài bởi Content Marketer đo bằng số lượng bài viết được duyệt/tuần.Tiêu tốn trọn vẹn 8 tiếng (1 ngày làm việc) của cả đội nhóm 3 người.Diễn ra định kỳ vào mỗi thứ Sáu hằng tuần để chuẩn bị cho tuần tới.AI có thể gợi ý 50 tiêu đề/ý tưởng dựa trên xu hướng thị trường chỉ với 1 câu lệnh (Prompt).Cả đội Marketing rơi vào trạng thái "bí ý tưởng" gây stress; Quản lý duyệt bài mệt mỏi vì chất lượng ý tưởng thấp (bị loại 60%).                                                                                                                                                                                                                                                                                                                                  |Đội ngũ Marketing | Đội Marketing gồm 3 người mất trọn vẹn 1 ngày thứ Sáu (8 tiếng) chỉ để nghĩ ra 10 tiêu đề bài viết, trong đó 6 bài bị loại (Biên bản họp tuần phòng Mar).                                                                                                                    |
| 8 | Pain từ người khác                                                           | Nhập dữ liệu hóa đơn giấy vào phần mềm kế toán bởi Kế toán viên đo bằng tỷ lệ sai sót dữ liệu đầu vào.                                                                                                                                                                                                                                                                                                                                           |Kế toán trưởng, Cơ quan thuế | Tần suất 300 hóa đơn/tháng, nhập tay mất 5 phút/tờ, tháng trước phát hiện nhập sai số tiền ở 12 hóa đơn dẫn đến lệch sổ sách (Log chỉnh sửa hệ thống MISA tháng trước).                                                                                                      |
| 9 |                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                  | |                                                                                                                                                                                                                                                                              |
| 10 |                                                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                  | |                                                                                                                                                                                                                                                                              |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Nhập dữ liệu hóa đơn giấy vào phần mềm kế toán thủ công bởi Kế toán viên đo bằng tỷ lệ sai sót dữ liệu đầu vào. |• Actor cụ thể, workflow rõ ràng 5 bước.• Bottleneck nhập tay dữ liệu có impact cực kỳ lớn (ảnh hưởng trực tiếp đến thuế/sổ sách).• Dễ dàng đo lường bằng tỷ lệ sai lỗi và thời gian xử lý. |Độ chính xác của AI OCR khi gặp các hóa đơn bị mờ, nhòe hoặc định dạng bảng quá phức tạp. |
| 2 |Phân loại và gán thẻ ticket hỗ trợ kỹ thuật thủ công bởi Nhân sự trực tổng đài đo bằng số lượng ticket xử lý mỗi ngày. |• Tần suất lặp lại rất cao (120-150 lần/ngày).• Bottleneck phân loại tay làm chậm toàn bộ luồng xử lý phía sau.• Giải pháp AI phân loại văn bản (Text Classification) có độ chín công nghệ rất cao. |Khả năng phân loại đúng các ticket sử dụng từ lóng, teencode hoặc viết không dấu của khách hàng. |
| 3 |Tổng hợp báo cáo doanh thu tuần thủ công bởi Trưởng nhóm Sale đo bằng số giờ làm việc mỗi thứ Hai. |• Rõ thời điểm (Sáng thứ Hai), rõ actor (Trưởng nhóm Sale).• Giải phóng 3.5 tiếng/tuần cho nhân sự cấp quản lý tập trung thúc đẩy doanh số.• Impact đo được trực tiếp bằng thời gian hoàn thành. |Việc format dữ liệu từ các nhóm gửi về không đồng nhất (thiếu cột, sai định dạng ngày tháng) có thể làm gãy pipeline tự động. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu: Kế toán viên mất quá nhiều thời gian (25 tiếng/tháng) nhập tay 300 hóa đơn giấy vào phần mềm MISA, dẫn đến tỷ lệ sai sót thông tin chiếm 4% (12 hóa đơn/tháng) gây lệch sổ sách kế toán.

Actor:Kế toán viên tài vụ

Thời điểm / bối cảnh:Định kỳ cuối ngày hoặc khi nhận được hóa đơn từ các bộ phận thu mua gửi về.

Current workflow 5 bước:
1. Nhận hóa đơn giấy/file PDF từ các phòng ban. (2')
2. Đọc và kiểm tra tính hợp lệ của hóa đơn bằng mắt. (1')
3. Nhập tay thủ công từng trường thông tin (Mã số thuế, Tiền hàng, VAT, Tổng tiền) vào MISA. (5')
4. Kiểm tra lại số liệu giữa hóa đơn gốc và phần mềm. (1')
5. Bấm lưu và lưu trữ chứng từ gốc vào file cứng. (1')

Bottleneck:Bước 3 — Nhập tay thủ công từng trường thông tin vào phần mềm.

Impact:Mất 1,500 phút (25 tiếng)/tháng của 1 kế toán viên. Sai sót 12 hóa đơn/tháng làm mất thêm 6 tiếng để đối soát chéo và sửa đổi với cơ quan thuế.

Success metric: 
- Thời gian nhập dữ liệu giảm từ 5 phút xuống dưới 1 phút/hóa đơn.
- Tỷ lệ sai sót thông tin đầu vào giảm từ 4% xuống dưới 0.5%.

Non-AI alternative: Thuê thêm thực tập sinh kế toán để nhập liệu (Tốn chi phí quản lý, không giải quyết được bài toán sai số do con người).

AI hypothesis: Sử dụng công nghệ AI OCR (như Llama-3-Vision hoặc OpenAI GPT-4o mini) để đọc hiểu ảnh chụp/file PDF hóa đơn, trích xuất cấu trúc JSON (MST, Tiền hàng, VAT) và dùng API đẩy trực tiếp vào phần mềm kế toán.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 10 phút

[1 Nhận HD: 2'] → [2 Kiểm tra: 1'] → [3 Nhập tay MISA: 5'] <-- bottleneck → [4 Check lại: 1'] → [5 Lưu: 1']

FUTURE STATE — 3 phút

[1 Quét/Up ảnh HD lên hệ thống: 0.5'] → [2 AI OCR tự động trích xuất & điền nháp vào MISA: 0.5'] → [3 Kế toán review & duyệt: 1'] <-- human boundary → [4 Hệ thống tự động lưu: 1']

Fallback: nếu AI sai hoặc không đọc được (độ tự tin < 85%), hệ thống sẽ bôi đỏ trường dữ liệu nghi ngờ và chuyển sang giao diện nhập tay truyền thống cho Kế toán viên sửa.

```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu: Nhân sự trực tổng đài (Line 1) mất 4-5 tiếng/ngày để đọc và gán thẻ phân loại thủ công 150 ticket hỗ trợ, làm tăng thời gian chờ của khách hàng và gửi sai phòng ban xử lý do yếu tố cảm tính.

Actor: Nhân sự trực tổng đài Line 1

Thời điểm / bối cảnh: Ngay khi khách hàng gửi yêu cầu hỗ trợ (gặp lỗi phần mềm, lỗi phần cứng, yêu cầu đổi trả) lên hệ thống Jira/Zendesk.

Current workflow 4 bước:
1. Tiếp nhận ticket mới đổ về hàng chờ tập trung. (0.5')
2. Đọc nội dung mô tả lỗi của khách hàng để hiểu vấn đề. (1.5')
3. Chọn danh mục (Category) và gán thẻ (Tag) thủ công phù hợp. (2')
4. Chuyển ticket về hàng chờ của đội kỹ thuật chuyên môn (Line 2). (0.5')

Bottleneck: Bước 3 — Đọc hiểu và chọn danh mục/gán thẻ thủ công.

Impact: Khách hàng phải chờ trung bình 15-20 phút mới được phân loại xong ticket. Tỷ lệ phân loại sai phòng ban đạt 8%, khiến ticket bị chuyển qua lại giữa các đội kỹ thuật, kéo dài thời gian xử lý tổng thể.

Success metric:
- Thời gian phân loại ticket giảm từ 4 phút xuống dưới 10 giây/ticket.
- Tỷ lệ gán sai thẻ/sai phòng ban giảm từ 8% xuống dưới 2%.

Non-AI alternative: Viết bộ quy tắc từ khóa cố định (Nếu chứa từ "mạng" -> gán IT). Nhược điểm: Khách hàng viết sai chính tả, dùng từ đồng nghĩa hoặc mô tả quá dài dòng khiến bộ rule bị lỗi.

AI hypothesis: Tích hợp mô hình ngôn ngữ nhỏ (SLM) tinh chỉnh (Fine-tune) trên tập dữ liệu ticket lịch sử để phân loại văn bản (Text Classification), tự động gắn tag và định tuyến (Routing) ticket ngay khi khách hàng nhấn submit.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết

```

**Draft workflow Card #2:**

```text
CURRENT STATE — 4.5 phút

[1 Nhận ticket: 0.5'] → [2 Đọc lỗi: 1.5'] → [3 Phân loại & Gán tag tay: 2'] <-- bottleneck → [4 Chuyển đội Line 2: 0.5']

FUTURE STATE — 0.2 phút (12 giây)

[1 Khách gửi ticket] → [2 AI tự động đọc, gán tag & định tuyến thẳng sang Line 2: 0.2'] <-- automation → [3 Kỹ thuật viên Line 2 tiếp nhận xử lý] <-- human boundary

Fallback: Nếu AI phân loại với độ tự tin (Confidence score) < 80%, ticket sẽ được đưa vào hàng chờ "Chờ phân loại thủ công" để nhân sự Line 1 xử lý tay như cũ.

```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu: Trưởng nhóm Sale mất 3.5 tiếng vào mỗi sáng thứ Hai để tổng hợp dữ liệu doanh thu từ 4 file Excel phân mảnh, làm chậm tiến độ họp giao ban đầu tuần của Giám đốc Kinh doanh.

Actor: Trưởng nhóm Sale

Thời điểm / bối cảnh: Từ 8h00 đến 11h30 sáng thứ Hai hằng tuần trước khi diễn ra cuộc họp giao ban công ty.

Current workflow 5 bước:
1. Tải 4 file Excel báo cáo riêng lẻ từ các nhóm trưởng gửi về. (15')
2. Định dạng lại dữ liệu (chuẩn hóa ngày tháng, loại bỏ dòng trống, kiểm tra lỗi công thức). (45')
3. Sao chép và gộp dữ liệu vào một file Master chung. (30')
4. Vẽ biểu đồ xu hướng và viết nhận xét/đánh giá ngắn bằng chữ. (90')
5. Gửi email file báo cáo tổng hợp cho Giám đốc Kinh doanh. (5')

Bottleneck: Bước 4 — Phân tích số liệu, vẽ biểu đồ và viết nhận xét nhận diện nguyên nhân tăng/giảm doanh số.

Impact: Chiếm trọn sáng thứ Hai của cấp quản lý (3.5 tiếng). Giám đốc nhận báo cáo muộn nên cuộc họp giao ban bị lùi xuống buổi chiều, làm chậm việc ra các quyết định kinh doanh quan trọng.

Success metric:
- Thời gian tổng hợp và viết nhận xét giảm từ 3.5 tiếng xuống dưới 15 phút.
- Báo cáo được gửi trước 9h00 sáng thứ Hai định kỳ.

Non-AI alternative: Xây dựng hệ thống dashboard tự động bằng Power BI / Google Looker Studio. Nhược điểm: Chỉ giải quyết được phần gom số liệu và vẽ biểu đồ, không tự viết được phần nhận xét, phân tích định tính (Tại sao nhóm A giảm doanh số? Xu hướng tuần tới là gì?).

AI hypothesis: Sử dụng Python Script chạy tự động (ETL) để gom dữ liệu 4 file Excel thành 1 file Master, sau đó dùng LLM (thông qua API) đọc bảng số liệu tổng hợp để tự động viết phần nhận xét, đánh giá sâu và xuất ra file báo cáo hoàn chỉnh.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[X] Agent
[ ] Chưa biết

```

**Draft workflow Card #3:**

```text
CURRENT STATE — 185 phút (3 tiếng 5 phút)

[1 Tải file: 15'] → [2 Format lại: 45'] → [3 Gộp file Master: 30'] → [4 Vẽ biểu đồ & Viết nhận xét: 90'] <-- bottleneck → [5 Gửi mail: 5']

FUTURE STATE — 15 phút

[1 Hệ thống tự động gom dữ liệu & vẽ biểu đồ: 2'] → [2 AI Agent phân tích số liệu & viết dự thảo nhận xét: 3'] → [3 Trưởng nhóm Sale review, sửa đổi & duyệt: 10'] <-- human boundary → [4 Hệ thống tự động gửi mail: 0']

Fallback: Nếu dữ liệu đầu vào bị gãy định dạng khiến AI không phân tích được, hệ thống sẽ gửi cảnh báo qua Slack/Email cho Trưởng nhóm Sale để kiểm tra lại file Excel nguồn, đồng thời giữ nguyên phần dashboard số liệu trực quan để họp giao ban trước.

```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1: Nhập dữ liệu hóa đơn giấy vào phần mềm kế toán bằng AI OCR.

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là quy trình có workflow cực kỳ rõ ràng, mang tính lặp đi lặp lại cao với tần suất 300 lần/tháng và bottleneck nằm hoàn toàn ở khâu nhập liệu thủ công. Bằng cách áp dụng AI OCR, chúng ta có thể giảm thời gian xử lý từ 5 phút xuống dưới 1 phút/hóa đơn, giải phóng 25 tiếng làm việc/tháng cho nhân sự tài chính. Quan trọng nhất, dự án này triệt tiêu hoàn toàn rủi ro sai sót dữ liệu đầu vào (hiện đang là 4%) - một nỗi đau cực kỳ lớn gây lệch sổ sách kế toán và rủi ro phạt thuế cho doanh nghiệp.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Làm sao để hệ thống AI OCR xử lý chuẩn xác đối với các hóa đơn giấy bị mờ mực, nhăn rách khi quét, hoặc các hóa đơn có kết cấu bảng biểu (table) phức tạp, nhiều danh mục hàng hóa kéo dài nhiều trang mà không làm xáo trộn dữ liệu đầu vào của phần mềm MISA?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Các mô hình vision/OCR hiện tại có thể đọc sai các chữ số có nét giống nhau (ví dụ: số 3 và số 8, số 0 và số 6) nếu chất lượng ảnh chụp kém, dẫn đến sai lệch nghiêm trọng về số tiền thuế hoặc mã số thuế.
- Tôi sửa gì:Thiết lập một bộ Validation Rules (quy tắc kiểm tra chéo) bằng mã code cứng: Hệ thống sẽ tự động tính toán lại công thức: Tổng tiền hàng * % Thuế suất VAT = Tiền thuế. Nếu kết quả AI trích xuất không khớp với công thức toán học này, hệ thống sẽ ngay lập tức gắn cờ đỏ bắt buộc con người (Kế toán viên) phải kiểm tra và sửa đổi bằng tay ở bước Review.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
