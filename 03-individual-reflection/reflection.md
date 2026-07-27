# Phase 7 — Individual Reflection

> Reflection là phần cá nhân. Nội dung dưới đây phản ánh trải nghiệm thật của tôi trong buổi lab hôm nay.

---

## Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra 10 problems từ góc nhìn thực tập sinh: đọc worksheet, tổng hợp ghi chú, viết reflection, tìm info Discord, đọc tài liệu dài, mentor giải thích lại, debug code, chuẩn bị update, bạn hỏi lại deadline, đánh giá trade-off | Nhóm có thêm nhiều candidate từ góc nhìn người học, bổ sung cho góc nhìn TA/coach |
| Pitch Problem Card | Pitch card #1 — "Hiểu yêu cầu bài lab từ worksheet dài" | Bài không được chọn vì impact nhỏ hơn bài TA support, nhưng giúp nhóm thấy pattern "đọc document dài để tìm thông tin" |
| Challenge bài của bạn khác | Hỏi: "Liệu saved replies có đủ cho bài TA support không? Có thật sự cần AI?" | Nhóm phân tích ra 30% FAQ dùng Rule đủ, 70% kỹ thuật mới cần AI → workflow thiết kế tốt hơn |
| Gom trùng / cluster | Gom các bài về "tổng hợp thông tin từ nhiều nguồn" thành cluster | Giúp nhóm thấy pattern chung giữa weekly report, ghi chú, TA support |
| Chọn candidate problem | Đồng ý chọn TA Discord support vì impact lớn nhất (50 ticket/ngày × 3 TAs) | Nhóm thống nhất nhanh, không có disagreement lớn |
| Validation / research | Tìm hiểu Intercom Fin, n8n Discord integration, Stack Overflow for Teams | Nhóm thấy pattern AI draft → human review đã được validate bởi nhiều sản phẩm |
| Workflow nhóm | Đóng góp vào future workflow: đề xuất tách FAQ layer (Rule) và kỹ thuật layer (Workflow) | Workflow cuối có 2 nhánh rõ ràng, tiết kiệm chi phí LLM cho FAQ |
| Problem Statement | Góp ý thêm field "AI intervention point" và "Guardrail Metric" (re-open rate) | PS v1 đầy đủ hơn v0 |
| Rule / Workflow / Agent | Lập luận không chọn Agent vì workflow tuyến tính, cố định, không cần AI tự lập kế hoạch | Nhóm thống nhất chọn Workflow |
| Decision | Đồng ý Go với scope nhỏ; đề xuất pilot 10-15 ticket làm test set | Có exit criteria rõ ràng |

---

## Bảng dùng AI trong lab

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problems theo vai trò thực tập sinh | Giúp nhớ thêm vài pain point mà mình quên (mentor giải thích lại, bạn hỏi lại deadline) | Một số gợi ý quá rộng ("cải thiện toàn bộ quy trình học tập") hoặc không phải pain thật | Bỏ các ý không có workflow thật, chỉ giữ ý có dấu hiệu cụ thể |
| Problem Card | Nhờ AI phản biện Problem Card #1 | Chỉ ra metric "hiểu đúng yêu cầu" khó đo, gợi ý đo bằng "số lần hỏi lại" | AI gợi ý biến thành Agent quá sớm ("bot tự đọc worksheet và push checklist") | Giữ ở mức Workflow, thêm non-AI alternative (cải thiện cấu trúc worksheet) |
| Research | Tìm tool tương tự cho TA support (Intercom, Zendesk, n8n) | Nhanh chóng tìm được 4-5 tool/pattern đã có | Đưa ra claim "giảm 80% thời gian" không có nguồn cụ thể | Chỉ giữ link tool chính thức, bỏ số liệu không verify được |
| Workflow | Nhờ AI chuyển mô tả workflow thành format rõ ràng | Giúp structure các bước, tính thời gian hợp lý | AI gộp bước "đọc context" và "tra cứu tài liệu" thành 1 bước | Tách lại vì bottleneck nằm ở bước đọc context, cần nhìn rõ |
| Problem Statement | Nhờ AI phản biện PS v0 | Chỉ ra boundary chưa rõ ("AI không bịa code" cần cụ thể hơn) | AI đề xuất thêm quá nhiều metric phụ, làm mất focus | Chỉ giữ 4 metric chính (primary, 2 secondary, 1 guardrail) |
| Rule/Workflow/Agent | Hỏi AI so sánh 3 mức cho bài toán TA support | Phân tích rõ vì sao Agent quá rộng cho case tuyến tính | AI ban đầu recommend Agent vì "nhiều nguồn dữ liệu" | Phản biện lại: nhiều nguồn ≠ cần Agent, Workflow tra cả 3 nguồn cùng lúc là đủ |
| Decision | Không dùng AI | — | — | Nhóm tự thảo luận và chốt |

---

## Reflection câu hỏi mở

- **Tôi học được gì khi nghe top 3 problems của các bạn khác?**
  Mỗi người nhìn từ góc nhìn khác nhau: người thấy pain ở phía học viên, người thấy pain ở phía TA, người thấy pain ở phía mentor. Khi gom lại mới thấy bài toán TA support có impact rộng nhất vì ảnh hưởng cả TA lẫn học viên.

- **Nhóm có lúc nào bị solution-first không?**
  Có. Lúc đầu có bạn muốn "xây Discord bot + AI agent" trước khi phân tích workflow rõ. Phải quay lại vẽ workflow hiện tại trước mới thấy bottleneck nằm ở đâu, và thấy rằng Workflow đủ, không cần Agent.

- **Tôi có thay đổi ý kiến sau khi bị challenge không?**
  Có. Ban đầu tôi nghĩ bài "đọc worksheet" có impact lớn, nhưng sau khi nghe challenge "chỉ ảnh hưởng cá nhân, trong khi TA support ảnh hưởng 50 học viên/ngày" thì đồng ý chuyển sang bài TA support.

- **Tôi đóng góp gì thật sự vào artifact cuối?**
  Đóng góp chính: (1) đề xuất tách FAQ/kỹ thuật thành 2 layer, (2) research n8n + Intercom pattern, (3) lập luận không chọn Agent. Các phần này có trong group report cuối.

- **Điều khó nhất khi viết Problem Statement là gì?**
  Viết boundary rõ ràng. "AI không bịa code" nghe đúng nhưng khó enforce. Cuối cùng nhóm cụ thể hóa: "AI chỉ trích dẫn code/giải pháp từ tài liệu nguồn trong vector DB, không generate code mới ngoài nguồn."

- **Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**
  Tôi sẽ challenge kỹ hơn về metric Draft Acceptance Rate > 85%. Con số 85% đến từ đâu? Có nên pilot trước rồi mới set target không? Nếu chỉ đạt 60% thì sao — có nên dừng hay retune?

---

## Bài học rút ra

- Problem tốt không phải problem nghe "AI" nhất, mà là problem có workflow và metric rõ. Bài TA support mạnh vì đo được thời gian, đếm được ticket, theo dõi được re-open rate.
- Vẽ workflow trước khi chọn AI giúp thấy phần nào Rule đủ (FAQ), phần nào cần AI (kỹ thuật). Không phải mọi bước đều cần AI.
- Agent không phải đích đến mặc định. Trong case này, Workflow hợp lý hơn vì workflow tuyến tính và có TA review. Agent chỉ cần khi AI phải tự lập kế hoạch động.
- Research giúp tránh "nghĩ trong chân không". Pattern AI draft → human review đã được validate bởi Intercom, Fellow, Zendesk. Không cần phát minh lại.
- AI hữu ích nhất khi dùng để phản biện (chỉ ra điểm yếu PS, so sánh Rule/Workflow/Agent). AI nguy hiểm nhất khi dùng để chốt quyết định (recommend Agent quá sớm, đưa metric không có nguồn).

Nếu làm lại:

```text
Tôi sẽ:
1. Validate metric baseline kỹ hơn: đo thực tế 18 phút/ticket trên 20+ ticket thay vì ước lượng từ 2-3 TA.
2. Challenge con số 85% Draft Acceptance Rate — nên pilot trước rồi mới set target.
3. Dành thêm thời gian cho validation phase: hỏi thêm học viên về trải nghiệm chờ đợi (không chỉ TA).
```

---

## Tự kiểm cuối bài

- [x] [12đ cá nhân] Cá nhân có 5+ problems (10 problems) và top 3 Problem Cards.
- [x] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [x] [15đ nhóm] Nhóm có workflow trước/sau.
- [x] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [x] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [x] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

*Individual Reflection — Day 02 Lab*
