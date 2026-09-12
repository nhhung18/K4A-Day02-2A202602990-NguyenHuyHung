# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Huy Hùng    
- Mã học viên: 2A202602990
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
+ Check mail
+ Code những phần bị lặp lại, những phần có cấu trúc tương tự nhau
+ Plan cấu trúc để AI code

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (ước lượng, chưa đo thật) |
|---|---|---|---|---|
| 1 | Lặp lại | Code cấu trúc CRUD/module tương tự nhau lặp đi lặp lại | Bản thân và các teammate | Ước lượng 3-5 lần/tuần phải giải thích lại cấu trúc module cho teammate, mỗi lần khoảng 10-15 phút |
| 2 | Lặp lại | Mở nhiều nguồn thông tin khác nhau nhưng chưa đọc kỹ, chuyển app khác lại đọc lại thông tin đấy | Bản thân | Ước lượng 10-15 lần mở app tin tức/ngày, khoảng 30% là đọc trùng tin đã thấy ở app khác |
| 3 | AI có thể tốt hơn | Search, Filter thông tin | Bản thân | Ước lượng mỗi lần search mở 8-10 nguồn, chỉ dùng được 2-3 nguồn |
| 4 | Pain từ người khác | Telesale - gọi điện tư vấn dịch vụ | Doanh nghiệp | Chưa có số, và chưa có nguồn quan sát trực tiếp - phạm vi không khớp với 4 việc gốc, đề nghị bỏ hàng này |
| 5 | Tốn thời gian | Đọc email, phải mở từng cái để phân loại quan trọng/không quan trọng | Bản thân | Ước lượng 15-20 phút/ngày xử lý mail |
| 6 | Chi phí chuyển ngữ cảnh | Đang code dở, bị gián đoạn (check mail/chat nhóm), quay lại mất thời gian nhớ lại đang làm tới đâu | Bản thân | Ước lượng 3-4 lần gián đoạn/ngày, mỗi lần mất 5-10 phút để vào lại việc |
| 7 | Pain từ người khác | Giảng viên/người hướng dẫn phản hồi chậm hoặc không rõ ràng | Bản thân | Ước lượng thời gian chờ phản hồi trung bình 1-2 ngày, khoảng 1/3 lần phải hỏi lại vì chưa rõ |
| 8 | Chờ người khác | Chờ teammate hoàn thành phần của họ mới ghép được, dù không ai làm sai | Bản thân và nhóm | Ước lượng 2-3 giờ/tuần ở trạng thái chờ trước khi tích hợp được |
| 9 | Sai lệch kỳ vọng | Plan structure gửi cho nhóm, nhưng khi code ra thực tế không khớp ý ban đầu, phải sửa lại | Bản thân và teammate | Ước lượng 1-2 lần/đồ án phải sửa lại plan vì teammate hiểu khác ý ban đầu |
| 10 | AI có thể tốt hơn | Viết lại nội dung tổng hợp tiến độ nhóm trước mỗi buổi họp từ các đoạn chat rải rác | Bản thân | Ước lượng 15-20 phút chuẩn bị trước mỗi buổi họp |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: gợi ý painpoint theo 4 lăng kính (lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác) dựa trên 4 việc hằng tuần (check mail, code phần lặp lại/plan structure, search/filter thông tin, làm việc nhóm); sau đó hỏi thêm lăng kính khác ngoài 4 lăng kính gốc.
- Ý dùng được: chi phí chuyển ngữ cảnh khi bị gián đoạn lúc code, chờ teammate dù không ai làm sai, sai lệch kỳ vọng giữa plan và code thực tế, phản hồi chậm từ giảng viên.
- Ý bỏ vì không phải pain thật: telesale doanh nghiệp (lệch phạm vi khỏi công việc cá nhân, không có nguồn quan sát trực tiếp); các lăng kính mở rộng mang tính suy đoán thuần chưa được áp dụng thành problem cụ thể vì chưa có quan sát thật để gán vào.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

Lưu ý: việc chọn top 3 dưới đây vẫn dựa trên số liệu ước lượng ở Phase 1, chưa phải số đo thật. Nếu sau khi ghi nhật ký, impact thực tế của hàng nào đó thấp hơn nhiều so với ước lượng, cần xếp lại rank.

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Code cấu trúc CRUD/module tương tự nhau lặp đi lặp lại (hàng 1) | Actor rõ (bản thân + teammate); workflow vẽ được rõ ràng; xảy ra đều đặn (3-5 lần/tuần theo ước lượng); có hướng AI hỗ trợ trực tiếp (sinh code từ mẫu) | Chưa rõ % code thực sự giống nhau đủ để tự động hoá, hay mỗi module vẫn khác nhau nhiều hơn tưởng |
| 2 | Search, filter thông tin kỹ thuật (hàng 3) | Actor rõ (bản thân); bottleneck rõ ở bước đọc lướt lọc nguồn; impact đo được qua số nguồn mở/dùng được | Chưa rõ loại thông tin nào hay cần tra cứu nhất (code, tài liệu, hay bài tập lý thuyết) - cần cụ thể hoá thêm |
| 3 | Tổng hợp tiến độ nhóm trước họp (hàng 10) | Workflow ngắn, dễ vẽ; bottleneck rõ (đọc lướt chat cũ); có thể áp AI trích xuất/tóm tắt trực tiếp | Chưa chắc mình có phải người duy nhất làm việc này trong nhóm, hay mỗi lần một người khác nhau làm |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Code CRUD/module lặp lại

```text
Problem 1 câu: Mỗi khi cần tạo module mới có cấu trúc tương tự module cũ, phải tự mở lại module cũ, copy, sửa thủ công, rồi giải thích lại cấu trúc đó cho teammate.

Actor: Bản thân (người viết code + plan structure) và teammate code theo structure đó.

Thời điểm / bối cảnh: Khi bắt đầu module hoặc tính năng mới trong đồ án, ước lượng 3-5 lần/tuần.

Current workflow 3-7 bước:
1. Nhận yêu cầu module mới (2 phút)
2. Tìm module cũ có cấu trúc gần giống để tham khảo (5 phút)
3. Copy code cũ, đổi tên biến và sửa logic riêng (15 phút)
4. Giải thích lại structure cho teammate nếu họ code phần liên quan (10 phút)
5. Test module mới (10 phút)

Bottleneck: bước 3 (copy và tuỳ chỉnh thủ công) cộng dồn với bước 4 (giải thích lặp lại cho teammate)

Impact: ước lượng 30-40 phút/module, 3-5 lần/tuần, tổng khoảng 2-3 giờ/tuần

Success metric: thời gian từ lúc nhận yêu cầu module mới đến lúc sẵn sàng test giảm xuống dưới 15 phút; số lần phải giải thích lại structure giảm

Non-AI alternative: tự viết template/boilerplate generator bằng script đơn giản, hoặc viết tài liệu structure rõ ràng hơn một lần cho cả nhóm dùng chung

AI hypothesis: AI sinh module mới từ 1 module mẫu cộng với tên/field khác nhau, kèm giải thích ngắn gọn cho teammate

Quick gut:
[x] Workflow
[ ] No AI / process fix
[ ] Rule
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 42 phút

[1 Nhận yêu cầu: 2'] → [2 Tìm module cũ: 5'] → [3 Copy & sửa: 15'] → [4 Giải thích cho teammate: 10'] → [5 Test: 10']
                                                        ^-- bottleneck

FUTURE STATE — 22 phút

[1 Nhận yêu cầu: 2'] → [2 AI sinh module từ mẫu + docs: 5'] → [3 Review & chỉnh sửa: 10'] → [4 Test: 5']
                                                                    ^-- human boundary

Fallback: nếu AI sinh sai cấu trúc hoặc thiếu logic riêng, quay lại làm thủ công từ bước 2 như cũ
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Search, filter thông tin kỹ thuật

```text
Problem 1 câu: Mỗi lần cần tìm thông tin kỹ thuật để làm bài, phải mở nhiều nguồn, đọc lướt từng cái, so sánh chéo mới tìm ra thông tin dùng được.

Actor: Bản thân.

Thời điểm / bối cảnh: Khi gặp vấn đề kỹ thuật cần tra cứu trong lúc code hoặc làm bài, ước lượng vài lần/tuần.

Current workflow 3-7 bước:
1. Xác định câu hỏi cần tìm (2 phút)
2. Search trên Google/Stack Overflow (3 phút)
3. Mở 8-10 tab kết quả (5 phút)
4. Đọc lướt từng tab, loại bỏ nguồn không liên quan (15 phút)
5. So sánh chéo các nguồn còn lại để verify (10 phút)
6. Tổng hợp câu trả lời dùng được (5 phút)

Bottleneck: bước 4 (đọc lướt để lọc), tốn nhiều thời gian nhất trong khi chỉ 2-3 trong 8-10 nguồn thực sự dùng được

Impact: ước lượng 30-40 phút/lần search, vài lần/tuần

Success metric: giảm số nguồn phải mở trước khi có câu trả lời dùng được; giảm thời gian từ lúc search đến lúc có câu trả lời

Non-AI alternative: lập sẵn danh sách nguồn uy tín hay dùng, hỏi trực tiếp trong nhóm/diễn đàn chuyên biệt thay vì search rộng

AI hypothesis: dùng AI tổng hợp câu trả lời trực tiếp từ nhiều nguồn kèm trích dẫn, để tự verify nhanh hơn thay vì đọc từng tab

Quick gut:
[x] Rule
[ ] No AI / process fix
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 40 phút

[1 Xác định câu hỏi: 2'] → [2 Search: 3'] → [3 Mở 8-10 tab: 5'] → [4 Đọc lọc: 15'] → [5 So sánh: 10'] → [6 Tổng hợp: 5']
                                                                        ^-- bottleneck

FUTURE STATE — 17 phút

[1 Xác định câu hỏi: 2'] → [2 AI tổng hợp trả lời kèm trích dẫn: 5'] → [3 Verify lại nguồn trích dẫn: 10']
                                                                            ^-- human boundary

Fallback: nếu câu trả lời AI không có trích dẫn rõ hoặc thông tin không nhất quán, quay lại search thủ công như cũ
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tổng hợp tiến độ nhóm trước họp

```text
Problem 1 câu: Trước mỗi buổi họp nhóm, phải tự đọc lại lịch sử chat rải rác để nhớ ai làm gì tới đâu rồi viết tóm tắt.

Actor: Bản thân (nếu là người chuẩn bị họp).

Thời điểm / bối cảnh: Trước mỗi buổi họp nhóm, ước lượng 1 lần/tuần.

Current workflow 3-7 bước:
1. Mở lại các đoạn chat từ họp trước đến nay (5 phút)
2. Đọc lướt tìm các cập nhật tiến độ giữa các tin nhắn không liên quan (10 phút)
3. Ghi chú lại ai làm gì, tới đâu (5 phút)
4. Viết tóm tắt hoàn chỉnh để trình bày (5 phút)

Bottleneck: bước 2 (đọc lướt tìm cập nhật tiến độ lẫn trong các tin nhắn không liên quan)

Impact: ước lượng 15-20 phút/tuần, kèm rủi ro bỏ sót thông tin khi họp

Success metric: giảm thời gian chuẩn bị trước họp; giảm số lần thông tin bị thiếu hoặc sai khi trình bày

Non-AI alternative: yêu cầu cả nhóm tự cập nhật tiến độ vào 1 file chung theo mẫu cố định, thay vì báo qua chat rải rác

AI hypothesis: AI đọc lịch sử chat nhóm và tự trích xuất, tóm tắt tiến độ theo từng người

Quick gut:
[x] Rule
[ ] No AI / process fix
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 25 phút

[1 Mở lại chat: 5'] → [2 Đọc lướt tìm cập nhật: 10'] → [3 Ghi chú: 5'] → [4 Viết tóm tắt: 5']
                                ^-- bottleneck

FUTURE STATE — 12 phút

[1 Mở lại chat: 5'] → [2 AI trích xuất & tóm tắt theo người: 3'] → [3 Review & chỉnh sửa: 4']
                                                                        ^-- human boundary

Fallback: nếu AI bỏ sót cập nhật quan trọng hoặc hiểu sai ngữ cảnh, tự đọc lại đoạn chat gốc như cũ
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Code CRUD/module lặp lại
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow 5 bước từ nhận yêu cầu module mới đến test xong, bottleneck rõ ở bước copy/sửa thủ công và giải thích lại cho teammate. Impact ước lượng lớn nhất trong 3 card (2-3 giờ/tuần), và có hướng AI hỗ trợ trực tiếp: sinh module mới từ mẫu có sẵn thay vì copy tay.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Các module trong đồ án có thực sự đủ giống nhau để AI generate tự động tiết kiệm thời gian, hay phần logic riêng của mỗi module lớn đến mức AI generate không giúp được nhiều?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: toàn bộ số liệu (3-5 lần/tuần, 30-40 phút/module) là ước lượng dựa trên suy luận, chưa đo thật; giả định các module đủ giống nhau để tự động hoá cũng chưa được kiểm chứng bằng cách so sánh code thật.
- Tôi sửa gì: ghi nhật ký thực tế ít nhất vài ngày để đo đúng số lần và thời gian; so sánh code của 2-3 module cũ để ước tính % thực sự giống nhau trước khi quyết định đầu tư xây giải pháp.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
