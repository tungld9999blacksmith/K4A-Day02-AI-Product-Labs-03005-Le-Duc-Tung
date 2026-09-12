# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Đức Tùng
- Mã học viên: 2A202603005
- Nhóm: D2
- Candidate problem nhóm chọn: Trông trẻ em nằm nôi

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi đề xuất các vấn đề từ trải nghiệm làm việc như coding lặp lại, tìm documentation khó và onboarding dev mới chậm. | Nhóm có thêm các candidate thuộc nhóm vấn đề phát triển phần mềm để so sánh với các ý tưởng đời sống và dữ liệu. |
| Pitch Problem Card | Tôi trình bày các Problem Card, tập trung vào actor, bottleneck, thời gian bị mất và khả năng dùng AI ở từng bước. | Nhóm hiểu rõ hơn điểm nghẽn của từng ý tưởng thay vì chỉ bàn về giải pháp. |
| Challenge bài của bạn khác | Tôi trao đổi và phản biện về độ khó kỹ thuật, độ chính xác, báo động giả và rủi ro khi triển khai các ý tưởng. | Nhóm nhận ra bài toán trông trẻ cần kiểm soát False Positive và không nên bắt đầu ngay bằng streaming realtime. |
| Gom trùng / cluster | Tôi cùng các thành viên so sánh các candidate theo pain, actor, workflow và mức độ phù hợp với AI. | Các ý tưởng được gom thành các cụm để giảm phạm vi tranh luận và dễ chấm điểm hơn. |
| Chọn candidate problem | Tôi tham gia tranh luận giữa trông trẻ em nằm nôi, code CRUD/module và tổng hợp dữ liệu Facebook Ads; tôi ưu tiên phương án có pain sâu, impact rõ và pilot được. | Nhóm thống nhất chọn bài toán trông trẻ em nằm nôi với tổng điểm 34/35. |
| Validation / research | Tôi cùng nhóm thiết kế survey/poll, tổng hợp kết quả 10 người và tìm hiểu các giải pháp CuboAi, Nanit Pro cùng khoảng trống của chúng. | Survey cho thấy 8/10 người xác nhận kiệt sức vì mất ngủ; research giúp nhóm chọn hướng camera/audio AI non-invasive và nhận diện rủi ro báo động giả. |
| Workflow nhóm | Tôi góp ý luồng giám sát, phân tích video/audio, cảnh báo và điểm phụ huynh phải kiểm tra. | Workflow được thu hẹp thành pilot offline trên dữ liệu quay sẵn, có human boundary và fallback rõ ràng. |
| Problem Statement | Tôi góp ý làm rõ actor, bottleneck, impact, metric và boundary để tránh mô tả quá rộng. | Problem Statement v1 xác định người dùng là phụ huynh/người trông trẻ, latency dưới 2 giây và accuracy trên 90%. |
| Rule / Workflow / Agent | Tôi tham gia so sánh Rule, Workflow và Agent, đặt câu hỏi liệu có thật sự cần agent tự lập kế hoạch hay không. | Nhóm chọn Workflow vì dữ liệu video/audio phi cấu trúc nhưng luồng xử lý vẫn tuyến tính, không cần Agent. |
| Decision | Tôi trao đổi về tính khả thi, rủi ro và cách kiểm chứng trước khi nhóm chốt Go. | Nhóm chọn Go với pilot nhỏ trên 1-2 gia đình và đo Accuracy, FPR, Latency trước khi đầu tư sâu hơn. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi cùng team xây dựng, trao đổi và phản biện các ý tưởng, sau đó tham gia lựa chọn bài toán trông trẻ em nằm nôi là phương án khả thi nhất để làm pilot. Dấu tay rõ nhất của tôi là phần survey và research giải pháp, giúp nhóm nhận diện nhu cầu thật, so sánh CuboAi/Nanit Pro và xác định hướng camera/audio AI non-invasive thay vì wearable.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các góc nhìn về problem trong công việc dev. | Giúp mở rộng danh sách candidate nhanh hơn. | Có thể đề xuất các ý tưởng nghe hay nhưng không xuất phát từ pain thật. | Tôi chỉ giữ các vấn đề có trải nghiệm và dấu hiệu cụ thể, còn quyết định cuối do tôi tự chọn. |
| Problem Card | Phản biện actor, bottleneck và metric của các card. | Giúp phát hiện mô tả còn rộng hoặc chưa có điểm nghẽn rõ. | AI không biết đầy đủ bối cảnh team và dễ đưa ra metric chung chung. | Tôi đối chiếu lại với workflow thực tế và số liệu trong scan cá nhân. |
| Workflow | Gợi ý cách tách bước hiện tại, bước AI can thiệp và fallback. | Giúp trình bày luồng trước/sau dễ kiểm tra. | AI có xu hướng đẩy quá nhiều việc sang AI và bỏ qua human boundary. | Tôi giữ phụ huynh là người kiểm tra và xử lý cuối cùng. |
| Research | Hỗ trợ tổng hợp từ khóa và so sánh các giải pháp baby monitor. | Giúp định hướng tìm CuboAi, Nanit Pro và các điểm cần kiểm chứng. | Không được mặc nhiên tin số liệu hoặc kết luận do AI đưa ra nếu thiếu nguồn chính thức. | Tôi kiểm tra lại nguồn, chỉ dùng research để rút ra khoảng trống và bài học cho nhóm. |
| Problem Statement | Gợi ý cách làm rõ actor, impact, metric và boundary. | Giúp phát hiện các field còn thiếu trong bản v0. | Câu trả lời có thể quá chung và chưa phản ánh rủi ro an toàn. | Tôi cùng nhóm sửa thành pilot offline, nêu rõ FPR và trách nhiệm của phụ huynh. |
| Rule / Workflow / Agent | Hỏi AI để so sánh ba mức giải pháp. | Giúp đặt câu hỏi về độ phức tạp và mức cần thiết của Agent. | AI có thể mặc định đề xuất Agent dù bài toán không cần tự lập kế hoạch. | Nhóm tự chốt Workflow vì luồng tuyến tính và không cần agent gọi tool. |
| Decision | Dùng AI như một góc nhìn phản biện về tính khả thi và rủi ro. | Giúp nhóm không bỏ qua false positive, false negative và dữ liệu pilot. | AI không thể thay nhóm quyết định Go vì không biết nguồn lực và người chịu trách nhiệm thực tế. | Tôi dựa trên survey, research và khả năng chạy pilot để ủng hộ quyết định Go có giới hạn. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe các bạn trình bày, tôi nhận ra một ý tưởng tốt không chỉ cần mới mà còn phải có actor, workflow và metric đo được. Tôi đã đóng góp các ý tưởng về coding lặp lại, documentation và onboarding, đồng thời cùng team trao đổi để so sánh chúng với bài toán trông trẻ em nằm nôi. Trong quá trình tranh luận, tôi chú ý đến rủi ro kỹ thuật như độ chính xác, báo động giả và khả năng triển khai realtime. Tôi thay đổi góc nhìn từ việc ưu tiên một bài toán quen thuộc với dev sang ủng hộ bài toán có pain xã hội sâu hơn và impact rõ hơn. Tôi cùng nhóm thực hiện survey 10 người, trong đó 8 người xác nhận bị kiệt sức vì mất ngủ, nên nhận định về nhu cầu không chỉ dựa trên cảm tính. Tôi cũng tìm kiếm và so sánh CuboAi với Nanit Pro để xem thị trường đã giải quyết phần nào và còn khoảng trống nào. Research cho thấy hướng camera/audio AI non-invasive phù hợp hơn wearable, nhưng nhóm vẫn phải kiểm soát false positive và không hứa hẹn AI thay thế hoàn toàn người chăm trẻ. Từ các trao đổi đó, tôi đồng ý chọn Workflow thay vì Rule hoặc Agent vì dữ liệu cần AI xử lý nhưng luồng nghiệp vụ vẫn tuyến tính. Dấu tay của tôi trong artifact cuối là phần survey, research và các lập luận về tính khả thi của pilot offline. Nếu làm lại, tôi sẽ hỏi sâu hơn về nhóm người dùng khảo sát và mức chấp nhận báo động giả trước khi chốt Go.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
