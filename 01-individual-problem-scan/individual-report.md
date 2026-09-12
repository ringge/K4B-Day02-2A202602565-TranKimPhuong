# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trần Kim Phương
- Mã học viên: 2A202602565
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Lập trình viên trong công ty outsourcing công nghệ
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Họp định kỳ với team để thống nhất các công việc

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Nghe lại bản ghi cuộc họp với team rồi tóm tắt các ý chính | Lập trình viên | Mất 45 phút để nghe lại và tóm tắt xong 1 cuộc họp |
| 2 | Tốn thời gian | Review tài liệu chuyên môn của domain đặc thù như y tế | Lập trình viên | Mất 3 tiếng để học hiểu một tài liệu chuyên môn ngành y tế |
| 3 | Lặp lại | Lướt xem feeds của các KOL trong ngành AI (Tibo, Dario) để cập nhật công nghệ mới | Lập trình viên | Thao tác lặp lại, có những lúc chưa có cập nhật gì nhưng vẫn phải vào kiểm tra mới biết |
| 4 | AI có thể tốt hơn | Đối chiếu log lỗi, mã nguồn và tài liệu để xác định nguyên nhân khi debug | Lập trình viên | Mất khoảng 2 giờ để tìm nguyên nhân và xử lý 1 lỗi có log phức tạp |
| 5 | Pain từ người khác | Hướng dẫn lại quy trình cài đặt và chạy dự án cho thành viên mới | Lập trình viên mới trong nhóm | Cùng một quy trình được hỏi lại khoảng 3 lần/tuần, mỗi lần mất 15 phút để hỗ trợ |
| 6 | Lặp lại | Tổng hợp tiến độ từ ticket và tin nhắn của team để viết cập nhật công việc hằng tuần | Lập trình viên và trưởng nhóm | Thực hiện 1 lần/tuần, mỗi lần mất khoảng 30 phút để tìm và tổng hợp thông tin từ nhiều nguồn |
| 7 | AI có thể tốt hơn | Đọc tài liệu kỹ thuật bằng tiếng Anh và đối chiếu thay đổi giữa các phiên bản thư viện trước khi nâng cấp | Lập trình viên | Khoảng 2 lần/tháng, mỗi lần mất 60 phút để đọc release note, tài liệu migration và xác định phần mã bị ảnh hưởng |
| 8 | Pain từ người khác | Làm rõ ticket lỗi thiếu bước tái hiện, thông tin môi trường hoặc log cần thiết trước khi bắt đầu xử lý | Lập trình viên và người tạo ticket | Khoảng 2 ticket/tuần phải hỏi bổ sung, mỗi ticket mất 20 phút trao đổi trước khi có đủ thông tin để debug |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Xem xét các problems và đánh giá các pain points trong các problems, đưa ra đề xuất điều chỉnh nếu cần
- Ý dùng được: Mất 3 tiếng để hiểu tài liệu chuyên môn
- Ý bỏ vì không phải pain thật: Mỗi ngày đều vào xem feeds

**Self-check Phase 1:**
- [ x ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ x ] Dùng ít nhất 3/4 lăng kính
- [ x ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Hướng dẫn lại quy trình cài đặt và chạy dự án cho thành viên mới | Xảy ra lặp lại 3 lần/tuần; ảnh hưởng cả người hướng dẫn và thành viên mới; workflow cài đặt có thể mô tả thành các bước rõ ràng | Chưa chắc câu hỏi lặp lại do tài liệu thiếu, môi trường máy khác nhau hay người mới chưa đọc hướng dẫn |
| 2 | Nghe lại bản ghi cuộc họp với team rồi tóm tắt các ý chính | Có actor và đầu ra rõ ràng; mỗi cuộc họp mất 45 phút để xử lý; bottleneck nghe lại và lọc ý chính dễ xác định | Chưa rõ tần suất họp mỗi tuần và mức độ chính xác cần có của bản tóm tắt |
| 3 | Đối chiếu log lỗi, mã nguồn và tài liệu để xác định nguyên nhân khi debug | Impact lớn với khoảng 2 giờ cho một lỗi; workflow debug có thể chia thành 3–7 bước; có nhiều nguồn thông tin cần đối chiếu | Chưa chắc lỗi phức tạp xảy ra thường xuyên đến đâu và bước nào trong quá trình debug tốn thời gian nhất |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Hỗ trợ thành viên mới cài đặt và chạy dự án

```text
Problem 1 câu: Lập trình viên phải lặp lại việc hướng dẫn cài đặt và chạy dự án cho thành viên mới khoảng 3 lần/tuần, mỗi lần mất 15 phút.

Actor: Thành viên mới cần hỗ trợ; lập trình viên trong nhóm là người hướng dẫn.

Thời điểm / bối cảnh: Khi thành viên mới thiết lập môi trường, chạy dự án lần đầu hoặc gặp lỗi cấu hình.

Current workflow 3-7 bước:
1. Thành viên mới đọc tài liệu và thực hiện các bước cài đặt.
2. Thành viên mới gặp lỗi hoặc không biết bước tiếp theo.
3. Thành viên mới nhắn hỏi lập trình viên trong nhóm.
4. Lập trình viên hỏi lại thông tin môi trường, phiên bản và log lỗi.
5. Lập trình viên tìm nguyên nhân, hướng dẫn cách xử lý và xác nhận dự án chạy được.

Bottleneck: Lập trình viên phải thu thập lại ngữ cảnh và tìm hướng dẫn phù hợp cho từng câu hỏi lặp lại.

Impact: 3 lần hỗ trợ/tuần × 15 phút/lần = khoảng 45 phút làm việc của lập trình viên mỗi tuần, chưa tính thời gian chờ của thành viên mới.

Success metric: Giảm thời gian hỗ trợ thủ công từ 45 xuống còn tối đa 15 phút/tuần và giảm câu hỏi lặp lại từ 3 xuống tối đa 1 lần/tuần.

Non-AI alternative: Chuẩn hóa README, checklist onboarding, script kiểm tra môi trường và mục xử lý các lỗi thường gặp.

AI hypothesis: Một workflow AI dùng tài liệu nội bộ đã duyệt để thu thập thông tin môi trường, đối chiếu log lỗi và gợi ý đúng bước xử lý; chuyển cho lập trình viên khi không đủ dữ liệu hoặc độ tin cậy thấp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 15 phút hỗ trợ/lần (ước tính)

[1 Nhận câu hỏi: 1'] → [2 Hỏi và thu thập ngữ cảnh: 3'] → [3 Tìm nguyên nhân: 5'] → [4 Hướng dẫn và xác nhận: 6']
                              ^ bottleneck

FUTURE STATE — tối đa 5 phút hỗ trợ thủ công/lần (mục tiêu)

[1 Người mới gửi log + thông tin môi trường: 1'] → [2 Workflow đối chiếu tài liệu và gợi ý: 2'] → [3 Lập trình viên review ca chưa xử lý được: ≤ 2']
                                                                                           ^ human boundary

Fallback: Nếu gợi ý không giải quyết được lỗi, thiếu nguồn dẫn hoặc độ tin cậy thấp, dừng workflow và chuyển toàn bộ ngữ cảnh cho lập trình viên xử lý theo quy trình hiện tại. AI không tự chạy lệnh hoặc thay đổi môi trường.
```

File đính kèm (nếu vẽ riêng): N/A

---

#### Problem Card #2 — Tóm tắt bản ghi cuộc họp của team

```text
Problem 1 câu: Sau mỗi cuộc họp, lập trình viên mất khoảng 45 phút để nghe lại bản ghi và tóm tắt các ý chính, quyết định và việc cần làm.

Actor: Lập trình viên thực hiện tóm tắt; các thành viên trong team sử dụng bản tóm tắt.

Thời điểm / bối cảnh: Sau cuộc họp có bản ghi, khi team cần lưu lại quyết định, action item, người phụ trách và deadline.

Current workflow 3-7 bước:
1. Mở bản ghi và xác định các đoạn cần nghe lại.
2. Nghe, tua lại và ghi chú nội dung quan trọng.
3. Lọc ra quyết định, action item, người phụ trách và deadline.
4. Sắp xếp ghi chú theo chủ đề và viết bản tóm tắt.
5. Kiểm tra lại với bản ghi rồi chia sẻ cho team.

Bottleneck: Phải nghe và tua lại thủ công để phân biệt nội dung thảo luận với quyết định và action item quan trọng.

Impact: Mất khoảng 45 phút cho mỗi cuộc họp; tổng thời gian theo tuần chưa xác định vì chưa đo tần suất họp.

Success metric: Giảm thời gian tạo một bản tóm tắt từ 45 xuống tối đa 15 phút; trong 4 cuộc họp thử nghiệm, mỗi bản tóm tắt có không quá 1 quyết định hoặc action item phải bổ sung sau khi chia sẻ.

Non-AI alternative: Dùng mẫu meeting note cố định, phân công người ghi chú trực tiếp và đánh dấu timestamp ngay trong cuộc họp.

AI hypothesis: Một workflow AI chuyển bản ghi thành transcript, trích xuất quyết định và action item theo mẫu; lập trình viên kiểm tra với timestamp trước khi chia sẻ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 45 phút/cuộc họp (ước tính theo từng bước)

[1 Mở và tua bản ghi: 2'] → [2 Nghe và ghi chú: 30'] → [3 Lọc ý chính: 5'] → [4 Viết và kiểm tra: 8']
                                      ^ bottleneck

FUTURE STATE — tối đa 15 phút/cuộc họp (mục tiêu)

[1 Tải bản ghi: 1'] → [2 AI tạo transcript + draft: 5'] → [3 Lập trình viên kiểm tra timestamp và sửa: ≤ 9']
                                                                  ^ human boundary

Fallback: Nếu transcript thiếu, sai người nói hoặc không có timestamp để kiểm chứng, không chia sẻ bản AI tạo; lập trình viên quay lại nghe bản ghi và dùng mẫu ghi chú thủ công.
```

File đính kèm: N/A

---

#### Problem Card #3 — Đối chiếu thông tin khi debug lỗi phức tạp

```text
Problem 1 câu: Lập trình viên mất khoảng 2 giờ để đối chiếu log lỗi, mã nguồn và tài liệu nhằm xác định nguyên nhân và xử lý một lỗi phức tạp.

Actor: Lập trình viên phụ trách điều tra và sửa lỗi; team và người dùng bị ảnh hưởng trong thời gian lỗi chưa được xử lý.

Thời điểm / bối cảnh: Khi có lỗi khó tái hiện hoặc stack trace chưa chỉ ra trực tiếp nguyên nhân trong môi trường local, staging hoặc production.

Current workflow 3-7 bước:
1. Thu thập mô tả lỗi và tái hiện lỗi nếu có thể.
2. Lấy log, stack trace, thông tin môi trường và thời điểm xảy ra lỗi.
3. Lần theo stack trace để xác định các phần mã nguồn liên quan.
4. Đối chiếu log, mã nguồn, tài liệu và lịch sử thay đổi để đặt giả thuyết nguyên nhân.
5. Kiểm tra giả thuyết, sửa lỗi và chạy test xác nhận.

Bottleneck: Đối chiếu thủ công nhiều nguồn để nối sự kiện trong log với đoạn mã và thay đổi có khả năng gây lỗi.

Impact: Mất khoảng 2 giờ cho mỗi lỗi phức tạp; impact theo tuần chưa xác định vì chưa đo tần suất loại lỗi này.

Success metric: Giảm thời gian xác định và xử lý một lỗi phức tạp từ 2 giờ xuống tối đa 1 giờ; mọi nguyên nhân do AI gợi ý phải được lập trình viên xác nhận bằng cách tái hiện lỗi hoặc test trước khi merge.

Non-AI alternative: Chuẩn hóa structured logging, bổ sung trace ID, xây runbook và lưu danh mục lỗi cùng cách xử lý đã được xác nhận.

AI hypothesis: Một workflow AI liên kết stack trace với mã nguồn, tìm tài liệu và thay đổi liên quan, sau đó xếp hạng các giả thuyết có dẫn nguồn để lập trình viên kiểm tra.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 120 phút/lỗi (ước tính theo từng bước)

[1 Tái hiện lỗi: 15'] → [2 Thu thập log: 10'] → [3 Lần theo mã nguồn: 20'] → [4 Đối chiếu nhiều nguồn: 50'] → [5 Sửa và test: 25']
                                                                 ^ bottleneck

FUTURE STATE — tối đa 60 phút/lỗi (mục tiêu)

[1 Thu thập dữ liệu lỗi: 10'] → [2 AI liên kết nguồn + xếp hạng giả thuyết: 10'] → [3 Lập trình viên kiểm tra giả thuyết: 20'] → [4 Sửa và chạy test: 20']
                                                                                           ^ human boundary

Fallback: Nếu AI thiếu quyền truy cập, không dẫn được nguồn hoặc giả thuyết không vượt qua test, bỏ gợi ý và quay về workflow debug hiện tại. AI không tự chạy lệnh, sửa mã hoặc merge thay lập trình viên.
```

File đính kèm: N/A

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #2 — Nghe lại bản ghi cuộc họp với team rồi tóm tắt các ý chính
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Sau mỗi cuộc họp, tôi phải mở bản ghi, nghe và tua lại, lọc các quyết định và action item, rồi viết và kiểm tra bản tóm tắt. Workflow hiện tại mất khoảng 45 phút, trong đó bước nghe và ghi chú thủ công là bottleneck lớn nhất; tôi muốn thử workflow AI tạo transcript và bản nháp để giảm thời gian xuống tối đa 15 phút, nhưng lập trình viên vẫn phải kiểm tra với timestamp trước khi chia sẻ. Nếu đạt mục tiêu, mỗi cuộc họp sẽ tiết kiệm khoảng 30 phút mà vẫn giữ human review ở bước cuối.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu transcript nhận sai người nói hoặc bỏ sót một quyết định quan trọng, human review bằng timestamp có đủ để kiểm soát rủi ro không?
2. Tôi cần đo thêm bao nhiêu cuộc họp và tiêu chí chất lượng nào để chứng minh mức giảm từ 45 xuống 15 phút là thực tế?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Chưa có số liệu về số cuộc họp mỗi tuần nên chưa tính được tổng impact; mục tiêu thời gian đã rõ nhưng chất lượng bản tóm tắt cần được đo, đặc biệt với quyết định và action item bị bỏ sót.
- Tôi sửa gì: Thử nghiệm trên 4 cuộc họp, đo thời gian xử lý và số quyết định/action item phải bổ sung sau khi chia sẻ; giữ bước kiểm tra transcript bằng timestamp trước khi gửi cho team.

### Self-check nộp phần 01
- [ x ] Có 5+ problems + top 3 Cards đủ field
- [ x ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ x ] Đã chọn 1 card pitch + câu hỏi challenge
