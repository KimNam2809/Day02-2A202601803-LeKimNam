# Phase 1 — Individual Problem Scan

> Bối cảnh: Tôi là thực tập sinh đang trong chương trình đào tạo AI thực chiến (3 tuần đầu). Buổi sáng thực hành lab, buổi chiều học lý thuyết, sau đó họp với mentor về định hướng triển khai dự án. Công cụ dùng hàng ngày: Discord, Google Docs/Sheets.

---

## Scan rộng — 10 problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Mỗi buổi lab phải đọc worksheet dài (vd: 800+ dòng) để hiểu yêu cầu bài, nhiều khi đọc xong vẫn chưa rõ phải nộp gì, format thế nào | Thực tập sinh (tôi), các bạn cùng nhóm | Mất 20-30 phút đọc hiểu trước khi bắt tay làm; hay phải hỏi lại trên Discord |
| 2 | Lặp lại | Sau mỗi bài lab phải viết báo cáo/reflection theo format gần giống nhau: problem, approach, kết quả, bài học | Thực tập sinh | Lặp lại mỗi ngày, mỗi lần mất 20-40 phút; dễ quên field hoặc viết thiếu |
| 3 | Tốn thời gian | Tổng hợp ghi chú từ nhiều buổi học lý thuyết + meeting mentor để ôn lại kiến thức trước khi làm lab hoặc trước khi bắt đầu dự án | Thực tập sinh | Ghi chú nằm rải rác trên Google Docs, Discord, file cá nhân; mất 30-45 phút để tìm và gom lại |
| 4 | Lặp lại | Tìm lại thông tin đã thảo luận trên Discord (quyết định của mentor, feedback, link tài liệu) nhưng tin nhắn bị trôi | Thực tập sinh, cả nhóm | Xảy ra 3-5 lần/tuần, mỗi lần mất 10-15 phút scroll và search |
| 5 | Tốn thời gian | Đọc tài liệu lý thuyết dài (papers, slides, docs) trước buổi học chiều để chuẩn bị tham gia thảo luận | Thực tập sinh | Tài liệu 10-30 trang, mất 40-60 phút đọc; nhiều khi chưa kịp đọc hết trước buổi học |
| 6 | Pain từ người khác | Mentor phải giải thích lại các khái niệm/quy trình mà thực tập sinh đã được dạy nhưng quên hoặc chưa nắm vững | Mentor, thực tập sinh | Mentor phải lặp lại 2-3 lần cùng một giải thích trong các buổi họp khác nhau |
| 7 | AI có thể tốt hơn | Khi làm lab, gặp lỗi code hoặc không hiểu output nhưng chưa biết nên search gì, hỏi ai, hay đọc doc nào | Thực tập sinh | Mất 15-30 phút debug/tìm hướng xử lý; đôi khi vẫn phải chờ mentor |
| 8 | Lặp lại | Mỗi buổi họp mentor phải chuẩn bị update tiến độ: đã làm gì, đang kẹt gì, kế hoạch tiếp theo — format lặp lại mỗi lần họp | Thực tập sinh | Họp 2-3 lần/tuần, mỗi lần chuẩn bị update mất 10-15 phút |
| 9 | Pain từ người khác | Các bạn cùng nhóm hay hỏi lại nhau trên Discord về deadline, yêu cầu nộp bài, cách tổ chức thư mục repo — dù thông tin đã có trong worksheet | Cả nhóm thực tập | Câu hỏi lặp lại 3-4 lần/tuần trên Discord; ai cũng tốn thời gian trả lời |
| 10 | AI có thể tốt hơn | So sánh và lựa chọn approach/giải pháp khi mentor đưa ra nhiều hướng triển khai dự án — thiếu framework để đánh giá trade-off | Thực tập sinh | Trong buổi họp định hướng dự án, mất thời gian cân nhắc mà không có tiêu chí rõ ràng |

---

## Top 3 Problem Cards

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Đọc worksheet dài để hiểu yêu cầu bài lab (#1) | Workflow rõ (đọc → phân tích → tìm deliverable), xảy ra hàng ngày, có bottleneck cụ thể (parse yêu cầu), ảnh hưởng tất cả thực tập sinh | "Hiểu đúng yêu cầu" đo bằng gì? Có thể đo bằng số lần hỏi lại không? |
| 2 | Tổng hợp ghi chú từ nhiều buổi học/meeting (#3) | Tốn thời gian rõ, ghi chú phân tán nhiều nơi, workflow lặp lại mỗi tuần, impact đo được bằng thời gian | Liệu chỉ cần tổ chức tốt hơn (folder/naming) là đủ, không cần AI? |
| 3 | Viết báo cáo/reflection sau mỗi bài lab (#2) | Lặp lại mỗi ngày, format khá cố định, bottleneck ở bước viết narrative/bài học | Chất lượng reflection có bị giảm nếu AI giúp draft không? |

---

## Problem Card #1 — Hiểu yêu cầu bài lab từ worksheet dài

**Problem 1 câu:**
Mỗi buổi lab, thực tập sinh mất 20-30 phút đọc worksheet dài (800+ dòng) để hiểu cần nộp gì, format thế nào, và phần nào là yêu cầu bắt buộc — nhưng đọc xong vẫn hay bỏ sót hoặc phải hỏi lại trên Discord.

**Actor:**
Thực tập sinh trong chương trình đào tạo AI thực chiến, phải hoàn thành lab mỗi buổi sáng.

**Thời điểm / bối cảnh:**
Đầu mỗi buổi lab (sáng), khi nhận worksheet mới. Phải hiểu yêu cầu nhanh để bắt đầu làm trong thời gian giới hạn.

**Current workflow 3-7 bước:**
1. Mở file worksheet (markdown dài 500-800+ dòng)
2. Đọc lướt toàn bộ để nắm cấu trúc
3. Đọc kỹ từng phase để hiểu yêu cầu chi tiết
4. Tìm phần deliverable / output cần nộp (rải rác trong nhiều section)
5. Ghi ra checklist cá nhân những gì cần làm
6. Bắt đầu làm, nhưng giữa chừng phải quay lại đọc worksheet khi không chắc
7. Hỏi trên Discord nếu vẫn không rõ

**Bottleneck:**
Bước 3-4 — Đọc kỹ và tìm deliverable mất nhiều thời gian nhất (15-20 phút) vì yêu cầu nằm rải rác, xen lẫn hướng dẫn, ví dụ, template và tiêu chí đánh giá.

**Impact:**
20-30 phút/buổi lab × 5 buổi/tuần = 100-150 phút/tuần chỉ để đọc hiểu yêu cầu. Nếu hiểu sai, phải làm lại hoặc nộp thiếu → mất thêm thời gian. Cả nhóm cùng bị, nhân lên 10-20 thực tập sinh thì tổng thời gian đáng kể.

**Success metric:**
Giảm thời gian từ mở worksheet đến bắt tay làm từ 25 phút xuống dưới 10 phút; giảm số câu hỏi "phải nộp gì" trên Discord xuống 0-1 câu/buổi.

**Non-AI alternative:**
- Tổ chức lại worksheet: tách phần TL;DR / checklist nộp bài lên đầu file.
- Dùng template checklist cố định cho mỗi lab.
- Instructor highlight rõ deliverable trong buổi briefing.

**AI hypothesis:**
AI có thể đọc worksheet và tóm tắt: (1) danh sách deliverable cần nộp, (2) format yêu cầu, (3) tiêu chí đánh giá, (4) timeline — giúp thực tập sinh nắm nhanh yêu cầu trước khi đọc chi tiết.

**Quick gut:**
[x] Workflow

### Draft current workflow — Card #1

```text
CURRENT STATE — 25 phút

[1 Mở worksheet: 1']
→ [2 Đọc lướt cấu trúc: 3']
→ [3 Đọc kỹ từng phase: 10']      <-- tốn thời gian
→ [4 Tìm deliverable rải rác: 7']  <-- bottleneck
→ [5 Ghi checklist cá nhân: 2']
→ [6 Làm lab, quay lại đọc: +5-10' giữa chừng]
→ [7 Hỏi Discord nếu chưa rõ: +5']
```

### Draft future workflow — Card #1

```text
FUTURE STATE — 8 phút

[1 Paste worksheet vào AI: 1']
→ [2 AI tóm tắt deliverable + format + tiêu chí: 1']  -- Workflow step
→ [3 Thực tập sinh đọc tóm tắt + đối chiếu: 5']       -- Human boundary
→ [4 Bắt tay làm lab: 1']

Fallback: AI tóm tắt thiếu/sai → thực tập sinh quay lại đọc worksheet gốc ở phần cụ thể.
```

---

## Problem Card #2 — Tổng hợp ghi chú từ nhiều buổi học/meeting

**Problem 1 câu:**
Thực tập sinh phải tìm và gom ghi chú rải rác từ Google Docs, Discord, file cá nhân để ôn lại trước khi làm lab hoặc họp mentor, mất 30-45 phút mỗi lần và hay bỏ sót ý quan trọng.

**Actor:**
Thực tập sinh cần ôn lại kiến thức trước buổi lab hoặc trước buổi họp định hướng dự án.

**Thời điểm / bối cảnh:**
Trước mỗi buổi lab (để áp dụng lý thuyết đã học) hoặc trước buổi họp mentor (để chuẩn bị context).

**Current workflow 3-7 bước:**
1. Nhớ lại "mình đã ghi chú ở đâu" (Google Docs? Discord? file local?)
2. Mở từng nguồn và search từ khóa
3. Copy-paste các đoạn liên quan vào một file tạm
4. Sắp xếp lại theo chủ đề / timeline
5. Đọc lại toàn bộ để nắm context

**Bottleneck:**
Bước 1-3 — Tìm và gom ghi chú từ nhiều nguồn mất 20-30 phút vì không có hệ thống đặt tên/phân loại nhất quán.

**Impact:**
30-45 phút/lần × 2-3 lần/tuần = 60-135 phút/tuần. Nếu không ôn kịp, chất lượng tham gia buổi lab/meeting giảm.

**Success metric:**
Giảm thời gian tổng hợp từ 35 phút xuống dưới 10 phút; không bỏ sót ý quan trọng từ các buổi trước.

**Non-AI alternative:**
- Quy ước tập trung ghi chú vào một nơi duy nhất (1 Google Doc master).
- Đặt tên file theo convention: ngày-chủ đề.
- Viết recap 3 bullet cuối mỗi buổi.

**AI hypothesis:**
AI tổng hợp nhiều nguồn ghi chú thành summary theo chủ đề, highlight ý chính và action item. Thực tập sinh review summary thay vì đọc lại toàn bộ raw notes.

**Quick gut:**
[x] Workflow

### Draft current workflow — Card #2

```text
CURRENT STATE — 35 phút

[1 Nhớ lại ghi chú ở đâu: 3']
→ [2 Mở Google Docs, search: 8']
→ [3 Mở Discord, search tin cũ: 8']   <-- bottleneck
→ [4 Copy-paste vào file tạm: 6']
→ [5 Sắp xếp theo chủ đề: 5']
→ [6 Đọc lại để nắm context: 5']
```

### Draft future workflow — Card #2

```text
FUTURE STATE — 10 phút

[1 Gom links/paste raw notes vào AI: 2']
→ [2 AI summary theo chủ đề + highlight action: 1']   -- Workflow step
→ [3 Thực tập sinh review summary: 5']                 -- Human boundary
→ [4 Bổ sung ý mình nhớ thêm: 2']

Fallback: AI summary bỏ sót → thực tập sinh đọc lại raw notes ở phần cụ thể.
```

---

## Problem Card #3 — Viết báo cáo/reflection sau mỗi bài lab

**Problem 1 câu:**
Sau mỗi bài lab, thực tập sinh phải viết báo cáo/reflection theo format lặp lại (problem, approach, kết quả, bài học), mất 20-40 phút mỗi lần và hay bị blank page ở phần viết bài học/reflection.

**Actor:**
Thực tập sinh phải nộp bài sau mỗi buổi lab.

**Thời điểm / bối cảnh:**
Cuối mỗi buổi lab hoặc cuối ngày, trước deadline nộp bài.

**Current workflow 3-7 bước:**
1. Mở template báo cáo
2. Điền thông tin cơ bản (tên bài, ngày, nhóm)
3. Viết lại problem/yêu cầu bài
4. Viết approach / cách giải quyết
5. Ghi kết quả / output
6. Viết reflection / bài học rút ra    <-- bottleneck
7. Review format và nộp

**Bottleneck:**
Bước 6 — Viết reflection/bài học mất 10-15 phút vì khó diễn đạt cụ thể, dễ bị chung chung, hay bị blank page.

**Impact:**
20-40 phút/buổi × 5 buổi/tuần = 100-200 phút/tuần chỉ cho viết báo cáo. Chất lượng reflection thường không đều.

**Success metric:**
Giảm tổng thời gian viết báo cáo từ 30 phút xuống 15 phút; reflection có ít nhất 2 insight cụ thể thay vì câu chung chung.

**Non-AI alternative:**
- Template có sẵn câu hỏi gợi ý cho reflection (vd: "Bước nào khó nhất?", "Nếu làm lại sẽ đổi gì?").
- Ghi reflection ngay trong lúc làm lab thay vì đợi cuối buổi.

**AI hypothesis:**
AI đọc nội dung bài lab + output của thực tập sinh, gợi ý draft reflection với các câu hỏi cụ thể. Thực tập sinh edit lại bằng trải nghiệm thật của mình.

**Quick gut:**
[ ] Rule — template gợi ý có thể đủ
[x] Workflow — nếu muốn AI gợi ý cụ thể hơn dựa trên nội dung bài

### Draft current workflow — Card #3

```text
CURRENT STATE — 30 phút

[1 Mở template: 1']
→ [2 Điền thông tin cơ bản: 2']
→ [3 Viết problem/yêu cầu: 3']
→ [4 Viết approach: 5']
→ [5 Ghi kết quả: 4']
→ [6 Viết reflection/bài học: 12']   <-- bottleneck, blank page
→ [7 Review + nộp: 3']
```

### Draft future workflow — Card #3

```text
FUTURE STATE — 15 phút

[1 Paste nội dung lab + output vào AI: 2']
→ [2 AI gợi ý draft reflection + câu hỏi cụ thể: 1']  -- Workflow step
→ [3 Thực tập sinh sửa lại bằng trải nghiệm thật: 8']  -- Human boundary
→ [4 Điền các field còn lại + review: 3']
→ [5 Nộp: 1']

Fallback: AI gợi ý quá chung chung → thực tập sinh tự viết, dùng template câu hỏi gợi ý.
```

---

## Card muốn pitch nhất

```text
Card #1 — Hiểu yêu cầu bài lab từ worksheet dài
```

Vì sao:

```text
- Xảy ra mỗi ngày với tất cả thực tập sinh, impact lớn nhất về tổng thời gian.
- Workflow rõ ràng, bottleneck cụ thể (parse deliverable từ document dài).
- Có thể vẽ before/after rõ, metric đo được (thời gian + số câu hỏi lại).
- Có non-AI alternative tốt (cải thiện cấu trúc worksheet) nên có thể so sánh Rule/Workflow/Agent.
- Cả nhóm đều trải nghiệm nên dễ validate và dễ pitch.
```

Câu hỏi tôi muốn nhóm challenge:

```text
- Liệu cải thiện cấu trúc worksheet (thêm TL;DR, checklist đầu file) đã đủ chưa, hay thật sự cần AI?
- Nếu AI tóm tắt sai một deliverable quan trọng, hậu quả là gì và ai phát hiện?
- Bài toán này có quá đơn giản (chỉ cần Rule: checklist cố định) hay thật sự cần Workflow?
```
