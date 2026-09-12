# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Lê Đức Tùng
- Mã học viên: 2A202603005
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Đi làm công viêc bán thời gian
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Lên trang công việc tìm yêu cầu từ khách hàng 
  - Phân tích và phân loại bài toán/vấn đề khách hàng đang gặp theo 2 chiều:
    - Technical
    - Nghiệp vụ
  - List ra những vấn đề chưa rõ. Nghĩ kỹ và trao đổi với chat bot AI (GPT, Claude, Gemini) nhưng phần chưa rõ về vấn đề. Kết quả nắm được yêu câu của client. 
  - Xác định công việc có match, nếu match viết proposal
  - Nhận việc, thực hiện và trao đổi với khách hàng về công việc

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Điền bảng điểm danh chấm công | Nhân viên | Nếu quên không điểm danh sẽ mất ngày công, máy chấm gặp trục trặc |
| 2 | Tốn thời gian | ide, docker tải resource, build artifact | Dev, Devops mất thời gian chờ build | Thời gian gap, tốn thêm thời gian để release  |
| 3 | Tốn thời gian| Chạy pipe line unitest, lấy evidence | Dev | Tốn từ 15 phút để chạy toàn bộ unit-test, intergration test, nếu hệ thống càng lớn mà khi chay môi trường dev thì rất tốn ram, và máy yếu sẽ giật lag, có khi mất cả ngày để quay video lấy evidence |
| 4 | Lặp lại | Trong 1 sprint phát triển sản phẩm phần mềm, với một software framework cần build chuẩn theo các layer (rất ceremony, mang tính nghi thức), cần dựng lại folder structure như sprint trước, hay một chức năng core nghiệp vụ chỉ vài dòng nhưng cần dựng rất nhiều code xung quanh | Dev, Tester, team sẽ bị ảnh hưởng tiến độ | Mất thời gian setup, redudance code, complicate up project structure |
| 5 | Tốn thời gian | QA báo bug nhưng Dev không reproceduce được | QA Lead | 12/30 ticket/tháng thiếu request/response hoặc environment; dev mất trung bình 20 phút/ticket để hỏi lại |
| 6 | AI có thể tốt hơn | Team Dev cần release nhanh prototype/ demo cho một số chức năng | Dev | Chỉ mất từ 1 ngày đến 2 ngày để release một demo tính năng nếu dùng AI coding agent |
| 7 | AI có thể tốt hone | Viết email cho các vấn để nội bộ nhân viên trong một công ty | Nhân viên | AI viết mail công sở với văn phong rất chuẩn |
| 8 | AI có thể tốt hơn | Onboarding Dev mới chậm | AI + Tech Lead | AI tạo Q&A assistant từ architecture/docs/code, giảm tải của Lead dành để hỗ trợ thành viên mới | 
| 9 | AI có thể tốt hơn | Tìm documentation khó| AI + Tech Writer | 8 lần/tuần phải hỏi người khác; trung bình 7 phút/lần, đo 10 lần |
| 10 | AI có thể tốt hơn | Phân tích feedback người dùng | AI, PM | 300 feedback/tháng, PM lấy mẫu 50-100 feedback và mất 3 giờ phân tích |

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
| 1 | Dev cần làm các vấn đề lặp lại trong sprint | Tiết kiệm thời gian, Dev chỉ cần quan tâm nhiều thứ giá trị hơn  | Độ chính xác khi dùng AI coding agent |
| 2 | Tìm documentation khó | Tiết kiệm thời gian, Hiệu quả công việc | Vấn để là AI không có biết thuật ngữ, trả lời sai, bịa |
| 3 | Onbarding member mới chậm | Tiết kiệm thời gian, năng suất  | Con người cần tương tác làm quen với mọi người thông qua công việc |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Công việc coding lặp lại

```text
Problem 1 câu:
Mỗi khi vào một phase mới, senior/middle/junior lại phải dựng một project structure mới, dev vào sprint phải làm các thủ tục các chức năng setup không liên quan đến nghiệp vụ, và lặp lại

Actor: Dev chịu trách nhiệm triển khái tính năng

Thời điểm / bối cảnh:
Vào đầu phase và sprint

Current workflow 3-7 bước:
1. Nhận bussiness requirements, technical specification từ cấp trên để triển khai
2. Thực hiên triên khai tính năng theo convention/ project structure / rules của dự án
3. Thực hiện unit test, api integration test, black box test 
4. Nhận phản hồi từ client / PM / QA để chỉnh sửa hoàn thiện tính năng
5. Lặp lại các bước trên cho đến khi đạt yêu cầu chức năng

Bottleneck:

- Bước 2: Cần bỏ thời gian triên khai code theo layer, các quy tắc code,triển khai các đoạn code redundant

Impact:

- Cần nửa ngày của dev, việc test, debug có thể tốn thêm thời gian khi phải chạy qua từng dòng 

Success metric:

- Team dev áp dung prompt, agent skills, và documentation tốt các chức năng giúp AI-Agent hiểu để triển khai giảm rất nhiều thời gian dev phải viết code bằng tay. Thời gian để chức năng nhanh hơn, đẩy nhanh qua trình cho đôi QA kiểm thử 

Non-AI alternative:

- OOP techinique, abstraction trong lập trình, reusable code, tổ chức code tốt, tạo tool gen code lặp đã có săn theo tên

AI hypothesis:

- AI hỗ trợ tạo code theo convetion/ rule và project struture của dự án
- AI có thể hỗ trợ viết code theo tech spec và business requirements

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết

```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 2-4 giờ / task

[1 Nhận requirements] → [2 Setup project structure + boilerplate] → [3 Viết code theo convention] → [4 Chạy test/debug]  <-- bottleneck

FUTURE STATE — 30-90 phút / task

[1 Nhận requirements + tech spec] → [2 AI generate project skeleton + boilerplate theo convention] → [3 Dev review + refine logic] → [4 QA/test validation]  <-- human boundary

Fallback: nếu AI sai thì dev dùng template chuẩn của dự án, so sánh output với codebase mẫu và giữ human review ở phần logic/architecture.
```

---

#### Problem Card #2 — Tìm documentation khó và mất thời gian hỏi lại

```text
Problem 1 câu:
Khi cần triển khai hoặc sửa một tính năng, dev phải mất thời gian dò lại docs, code cũ và hỏi đồng nghiệp vì thông tin phân tán, dẫn đến chậm tiến độ và dễ hiểu sai requirement.

Actor:
Developer / Engineer / Tech lead phụ trách triển khai hoặc hỗ trợ team

Thời điểm / bối cảnh:
Vào lúc bắt đầu task mới, làm maintenance, debug issue, hoặc khi cần hiểu architecture hệ thống cũ.

Current workflow 3-7 bước:
1. Dev nhận task từ PM/QA hoặc phát hiện bug cần xử lý.
2. Tìm trong repo, docs, wiki, ticket và code cũ để hiểu context.
3. Nếu không tìm thấy, gửi câu hỏi cho Tech Lead/đồng nghiệp qua chat/email.
4. Đợi phản hồi hoặc đọc thêm nhiều nguồn thông tin không đồng nhất.
5. Tiếp tục debug/triển khai nhưng vẫn có nguy cơ hiểu sai logic hoặc requirement.

Bottleneck:
- Bước 2-3: Thông tin nằm rải khắp repo/docs/chat và không được tổng hợp theo ngữ cảnh; dev mất 7-10 phút/lần, 8-10 lần/tuần.

Impact:
- Mỗi lần tìm docs mất 5-15 phút; nếu phải hỏi lại, còn tốn thêm 20-30 phút và làm chậm sprint.
- Team mất thời gian lặp lại cùng một câu hỏi, thiếu sự thống nhất trong hiểu biết hệ thống.

Success metric:
- Giảm 50% thời gian tìm hiểu và hỏi lại thông tin trước khi bắt đầu coding.
- Tăng tỷ lệ dev tự giải quyết task trong 1 lần mà không cần hỏi lại.
- Tăng chất lượng onboarding và maintainability cho dự án.

Non-AI alternative:
- Viết wiki chuẩn hóa, tag theo module, tạo docs index, dùng code comments, training onboarding tuần đầu.

AI hypothesis:
- AI có thể tạo bộ “assistant kiến thức dự án” dựa trên repo + docs + kiến trúc để trả lời câu hỏi theo ngữ cảnh, tra cứu nhanh và gợi ý nơi cần xem.
- AI có thể tóm tắt các quyết định kỹ thuật, “what changed”, “where to start”, và answer bằng ngôn ngữ dễ hiểu cho dev mới.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 20-30 phút

[1 Nhận task] → [2 Tìm docs/repo] → [3 Hỏi đồng nghiệp/Tech Lead] → [4 Đợi phản hồi]  <-- bottleneck

FUTURE STATE — 5-10 phút

[1 Nhận task] → [2 AI index & summarize repo/docs] → [3 AI trả lời theo context + gợi ý file/đoạn mã] → [4 Dev review & xác nhận]  <-- human boundary

Fallback: Nếu AI không chắc, trả về nguồn tham khảo, file cần xem và câu hỏi gợi ý để dev kiểm tra lại; Tech Lead chỉ review khi có edge case/decision quan trọng.
```

---

#### Problem Card #3 — Onboarding member mới chậm và phụ thuộc nhiều vào Tech Lead

```text
Problem 1 câu:
Khi team có thành viên mới, Lead phải mất thời gian giải thích architecture, quy trình và dự án; dev mới phải tự mò làm quen, làm chậm tiến độ và tăng tải cho người có kinh nghiệm.

Actor:
Dev mới / Team Lead / Mentor / PM

Thời điểm / bối cảnh:
Khi tuyển thành viên mới, bắt đầu sprint hoặc khi có task cần hiểu hệ thống từ đầu.

Current workflow 3-7 bước:
1. Dev mới nhận task/được assign vào dự án.
2. Đọc docs, repo và codebase ban đầu nhưng thiếu định hướng rõ ràng.
3. Gửi câu hỏi cho Lead/mentor về architecture, quy tắc triển khai, nơi bắt đầu.
4. Lead trả lời từng câu hỏi hoặc demo bằng tay.
5. Dev mới mất thời gian làm quen và bắt đầu đóng góp chậm hơn kỳ vọng.

Bottleneck:
- Bước 3-4: Tech Lead phải lặp lại giải thích giống nhau cho nhiều người và nhiều câu hỏi nhỏ; dẫn đến việc hỗ trợ không scalable.

Impact:
- Dev mới cần nhiều ngày hoặc hàng tuần để nắm đủ context; thời gian đến mức có thể đóng góp thực sự bị kéo dài.
- Lead bị giảm thời gian cho việc phát triển và review kỹ thuật, đồng thời tăng nguy cơ kiến thức bị “rỉ ra” theo từng cá nhân.

Success metric:
- Giảm thời gian onboarding từ nhiều ngày xuống 1-2 ngày cho các task cơ bản.
- Giảm số câu hỏi phải hỏi trực tiếp của new joiner xuống dưới mức mục tiêu.
- Tăng tỷ lệ member mới tự giải quyết được task đầu trong tuần đầu.

Non-AI alternative:
- Tạo onboarding checklist, architecture guide, “start here” documentation, pair programming, mentorship sessions.

AI hypothesis:
- AI có thể tạo nhanh một Q&A assistant và summary dự án từ docs + code để trả lời câu hỏi onboarding theo ngữ cảnh.
- AI giúp tóm tắt architecture, flow main modules, các quy tắc coding và task mẫu để Dev mới tự học mà không cần chờ Lead đáp lại từng câu hỏi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 2-5 ngày

[1 Dev mới vào dự án] → [2 Đọc docs/repo] → [3 Gửi nhiều câu hỏi cho Lead] → [4 Lead trả lời lặp lại]  <-- bottleneck

FUTURE STATE — 0.5-1 ngày

[1 Dev mới vào dự án] → [2 AI tổng hợp repo + docs + architecture] → [3 AI trả lời câu hỏi onboarding + hướng dẫn task mẫu] → [4 Lead review final concept & mentor chỉ khi cần]  <-- human boundary

Fallback: Nếu AI thiếu thông tin hoặc có nhầm lẫn, Lead cung cấp “golden source” như architecture doc, coding convention, và một task mẫu chuẩn để AI dùng làm reference.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #2 — Tìm documentation khó và mất thời gian hỏi lại
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là card có workflow rõ nhất: dev nhận task → tìm docs/repo → hỏi lại Lead → mất thời gian chờ phản hồi. Bài này có số đo cụ thể, như 5-15 phút mỗi lần, 8-10 lần/tuần, và có thể đo được hiệu quả sau khi dùng AI assistant: giảm 50% thời gian tìm hiểu và hỏi lại. Impact không chỉ là thời gian mà còn là tăng năng suất và giảm lệ thuộc vào người khác trong team.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Ai assistant trong trường hợp này có đủ thông tin từ repo/docs để trả lời đúng không, hay vẫn cần người thật để validate? Nếu AI trả lời sai hoặc thiếu context, team sẽ chịu thêm rủi ro gì và cách kiểm soát như thế nào?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
```text
AI có thể trả lời sai hoặc “bịa” vì không hiểu thuật ngữ domain hay thiếu context của repo cũ. Một số câu hỏi cần kiến thức miền và context từ chat cũ, không phải chỉ dựa trên code.
```
- Tôi sửa gì:
```text
Tôi thêm phần “fallback” trong workflow: AI trả lời có nguồn tham khảo, gợi ý file cần xem, và chỉ để Tech Lead review ở những trường hợp edge case hoặc quyết định thiết kế. Tôi cũng nhấn rõ đây là công cụ hỗ trợ tri thức, không thay thế người review.
```

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
