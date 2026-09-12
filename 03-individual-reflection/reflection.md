# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: NGUYỄN HOÀNG CƯỜNG
- Mã học viên: 2A202602473
- Nhóm: B1_Ban2
- Candidate problem nhóm chọn: **#12 — Trả lời câu hỏi tài chính phức tạp từ nhiều bảng và tài liệu**

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể, chỉ ghi phần truy vết được từ artifact) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 8 problems có actor + metric, trải trên báo cáo, support ticket, meeting notes, phê duyệt mua sắm, pháp chế, CSKH, content và nhập hóa đơn. | Vượt yêu cầu tối thiểu 5 problems và dùng nhiều lăng kính. |
| Pitch Problem Card | Chọn Card #1: nhập dữ liệu hóa đơn giấy vào MISA; nêu 300 hóa đơn/tháng, 5 phút nhập/hóa đơn, 12 lỗi/tháng; đề xuất OCR + human review. | Candidate cá nhân được đưa vào bảng hội tụ nhóm thành #13. |
| Challenge bài của bạn khác | **Artifact nguồn không ghi lại câu challenge cụ thể do tôi đặt cho candidate của thành viên khác.** | Không bịa thêm. Nếu đã challenge trong buổi học, cần tự bổ sung đúng câu hỏi/thời điểm để đủ rubric 12đ. |
| Gom trùng / cluster | Ba candidate của tôi xuất hiện trong artifact nhóm: #13 (hóa đơn) vào cluster C, #14 (ticket) vào cluster B, #15 (báo cáo doanh thu) vào cluster A. | Giúp nhóm có candidate ở ba pattern khác nhau để so sánh. |
| Chọn candidate problem | Nhóm score #12 = 34, #7 = 33, #14 = 32 và chốt #12. | #14 của tôi vẫn vào shortlist; nhóm chọn #12 vì evidence/impact và khả năng so sánh Rule/Workflow/Agent tốt hơn. |
| Validation / research | Vai trò trong bảng nhóm được ghi là `facilitator, workflow, research, writer`; artifact nhóm có 3 interview quote, survey n=6, log 15 câu và research Copilot/ChatGPT/RAG. | Có đủ lớp evidence + research để sửa scope về câu hỏi ad-hoc/phức tạp đa nguồn. **Artifact không tách riêng ai thu thập nguồn nào.** |
| Workflow nhóm | Artifact nhóm có current 7 bước và future 6 bước; bottleneck current là tìm + trích số liệu, future boundary là NV review evidence. | Chuyển từ “AI làm tất” sang workflow có human checkpoint và fallback thủ công. **Artifact không ghi riêng ai vẽ phần nào.** |
| Problem Statement | PS v0 → v1 bổ sung baseline 35 phút, accuracy theo giá trị+kỳ+đơn vị, 100% trích nguồn và boundary rõ. | Problem statement chặt hơn, đo được và kiểm soát rủi ro. **Artifact không có attribution cá nhân theo từng field.** |
| Rule / Workflow / Agent | Nhóm so Rule/Workflow/Agent và chọn Workflow; Agent chưa cần ở pilot. | Scope giải pháp vừa đủ: Rule tiền xử lý, LLM+RAG cho bước 2–4, human review ở bước 5. |
| Decision | Nhóm quyết định `Go` với pilot nhỏ, exit nếu accuracy <70% hoặc tổng thời gian không giảm ≥30%. | Decision có điều kiện dừng/rollback thay vì “Go vì AI”. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1–2 câu):**

```text
Phần truy vết rõ nhất của tôi là ba candidate #13–#15, đặc biệt Problem Card OCR nhập hóa đơn với metric 300 hóa đơn/tháng, 5 phút nhập/hóa đơn, 4% lỗi và cơ chế validation + human review. Candidate #14 của tôi cũng đi tới shortlist nhóm trước khi nhóm chốt #12.
```

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Không có prompt Phase 1 được lưu trong artifact nguồn. | — | Không đủ bằng chứng để nói AI đã được dùng ở phase này. | Không bổ sung prompt/ý tưởng giả; giữ 8 problem có metric đã ghi. |
| Problem Card | AI được dùng để phản biện rủi ro OCR ở Card #1. | Chỉ ra nhầm chữ số gần giống khi ảnh kém chất lượng. | Nếu chỉ nói “OCR rất chính xác” thì bỏ qua rủi ro tài chính của một chữ số sai. | Thêm validation rule: đối chiếu công thức tiền hàng × VAT và bắt buộc review khi confidence thấp. |
| Workflow | Có thể dùng AI/công cụ vẽ để số hóa flow, nhưng artifact không lưu prompt/tool cụ thể. | Flow before/after giúp nhìn rõ bottleneck, human boundary và fallback. | Workflow ban đầu Card #3 có chênh baseline 210' với tổng bước 185'. | Bản hoàn thiện ghi rõ khoảng chênh 25' chưa được phân loại thay vì tự bịa nguyên nhân. |
| Research | Group artifact có research Copilot for Finance, ChatGPT Data Analysis và RAG/LlamaIndex. | Giúp thấy không cần build Agent ngay; RAG/Workflow phù hợp hơn. | Research không tự chứng minh accuracy với bảng tài chính. | Giữ accuracy là metric cần pilot, không coi RAG là “đã chắc đúng”. |
| Problem Statement | Group artifact ghi rõ “Câu hỏi AI phản biện v0”. | AI giúp chỉ ra Impact 50–60% còn là giả định và accuracy chưa định nghĩa. | Dễ biến mục tiêu thành fact nếu không tách baseline với kỳ vọng. | Chốt baseline 35 phút; định nghĩa accuracy = đúng giá trị + kỳ + đơn vị; đánh dấu phần giảm 50–60% là giả định cần pilot. |
| Rule / Workflow / Agent | Dùng AI ở vai trò phản biện mức giải pháp, không để AI tự quyết định thay nhóm. | Hữu ích khi phân biệt Rule lookup, Workflow tuyến tính và Agent tự lập kế hoạch. | Agent nghe “mạnh” nhưng tăng rủi ro, chi phí và khó debug. | Nhóm hạ mức về Workflow; Agent chỉ là hướng nâng cấp sau. |
| Decision | Không dùng AI để tự chốt `Go`; dùng evidence/metric/boundary trong artifact nhóm. | AI có thể hỗ trợ đặt exit criteria. | Nếu chỉ hỏi AI “có nên làm không” sẽ thành solution-first. | Chốt Go có điều kiện: human review, pilot 10 câu, rollback nếu accuracy <70% hoặc thời gian không giảm ≥30%. |

---

## 3. Reflection câu hỏi mở

> **BẢN NHÁP AI — KHÔNG NỘP NGUYÊN VĂN. Hãy viết lại 8–12 câu bằng trải nghiệm và cách diễn đạt thật của bạn.**

```text
Trong phần scan cá nhân, tôi thấy việc có số đo cụ thể làm một problem thuyết phục hơn rất nhiều so với chỉ nói “mất thời gian”. Ban đầu tôi ưu tiên bài nhập hóa đơn vì workflow rất rõ, tần suất cao và sai một con số có thể ảnh hưởng trực tiếp tới sổ sách. Khi nhìn toàn bộ candidate của nhóm, tôi nhận ra bài dễ tự động hóa nhất chưa chắc là bài nên chọn nếu nhóm muốn kiểm chứng được cả workflow, metric và độ phù hợp của AI. Candidate #12 được chọn chỉ hơn #7 một điểm, nên điều quan trọng với tôi là lý do chọn phải giải thích được chứ không chỉ dựa vào cảm giác. Phần khó nhất của Problem Statement là tách fact khỏi giả định: 35 phút/câu là baseline trong artifact, còn mục tiêu 10–15 phút và accuracy 85% vẫn phải được pilot kiểm chứng. Tôi cũng thấy boundary quan trọng không kém metric, vì với số liệu tài chính AI không nên tự gửi câu trả lời hoặc tự ra quyết định. So sánh Rule/Workflow/Agent giúp tôi hiểu rằng dùng Agent không mặc định tốt hơn; với flow tuần tự và kho tài liệu xác định, Workflow dễ kiểm soát hơn. Điểm tôi muốn giữ trong artifact cuối là mọi số liệu AI đưa ra đều phải có nguồn để người phân tích click vào kiểm tra. Nếu làm lại, tôi sẽ yêu cầu nhóm ghi rõ hơn ai thu thập quote nào, ngày/hình thức phỏng vấn và giữ screenshot survey gốc ngay từ đầu. Tôi cũng sẽ ghi lại câu challenge mình đặt cho candidate của bạn khác để phần đóng góp cá nhân có evidence rõ hơn.
```

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm — **pitch có evidence; challenge bài của bạn khác chưa có log trong file nguồn**
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì — **chỉ tick sau khi tự viết lại đoạn nháp bằng lời của mình**
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

