# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thu Hằng
- Mã học viên:2A202602463
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Nhân viên IT trong một công ty vận hành hệ thống thu phí. Mỗi cuối ngày, bạn phải làm Báo cáo hoạt động hàng ngày gửi cho quản lý.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
- Kiểm tra tình trạng và dữ liệu hình ảnh từ hệ thống camera tại các tuyến/trạm.
- Theo dõi và ghi nhận các sự cố phát sinh trong quá trình vận hành.
- Kiểm tra, theo dõi số lượng nhân sự đang vận hành tại các tuyến.
- Thu thập và đối chiếu số liệu vận hành từ BE tại các trạm thu phí.
- Tổng hợp các thông tin và số liệu thành Báo cáo hoạt động hàng ngày để gửi cho quản lý vào cuối ngày.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| #  | Lăng kính| Problem quan sát được| Ai chịu ảnh hưởng?| Dấu hiệu thật (số + bằng chứng)|
| -- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| 1 | Lặp lại| Mỗi cuối ngày phải thu thập số liệu vận hành từ BE tại nhiều trạm để làm báo cáo| Nhân viên IT| Thực hiện 1 lần/ngày, khoảng 10 trạm, mất khoảng 15 phút/lần|
| 2 | Tốn thời gian| Phải đối chiếu số liệu BE với file báo cáo trước khi tổng hợp để tránh sai lệch | Nhân viên IT| Mất khoảng 15 phút/ngày, trung bình kiểm tra 30–40 dòng số liệu|
| 3 | Lặp lại| Phải kiểm tra tình trạng camera theo các khung giờ được phân công/random| Nhân viên IT/vận hành| Khoảng 4 lần/ngày, mỗi lần 5–7 phút, theo dõi khoảng 20 camera/trạm|
| 4 | Tốn thời gian| Khi phát hiện camera hoặc dữ liệu bất thường, phải kiểm tra lại thông tin trước khi ghi nhận sự cố| Nhân viên IT| Giả lập 20–30 trường hợp/ngày, mỗi trường hợp mất 5–10 phút để xác minh|
| 5  lại thủ công| Nhân viên IT + quản lý| Khoảng 3–5 sự cố/ngày, thông tin được ghi nhận từ 2–3 nguồn khác nhau|
| 6 | Lặp lại| Phải tổng hợp tình hình nhân sự vận hành tại các tuyến vào báo cáo cuối ngày | Nhân viên IT + quản lý vận hành | Thực hiện 1 lần/ngày, theo dõi khoảng 5–10 tuyến, mất khoảng 10 phút|
| 7 | Tốn thời gian| Phải chuyển các số liệu và thông tin đã thu thập sang mẫu Báo cáo hoạt động hàng ngày| Nhân viên IT| Mất khoảng 10 phút/ngày, phần lớn thao tác là copy/paste và format|
| 8 | AI có thể tốt hơn| Từ nhiều dữ liệu sự cố và vận hành, việc xác định điểm bất thường hoặc thông tin cần chú ý chưa được tự động tổng hợp| Nhân viên IT + quản lý| Mỗi ngày có khoảng 3–5 sự cố/thông tin cần xem xét, mất khoảng 10 phút để tổng hợp và xác định điểm đáng chú ý |
| 9 | Pain từ người khác| Quản lý đôi khi phải hỏi lại thông tin chi tiết của sự cố hoặc số liệu trong báo cáo| Quản lý + nhân viên IT| Giả lập 1–2 lần hỏi lại/tuần, thường liên quan đến thời gian, nguyên nhân hoặc trạng thái sự cố|
| 10 | Lặp lại / Tốn thời gian | Toàn bộ quy trình tổng hợp Báo cáo hoạt động hàng ngày phải thực hiện thủ công dù cấu trúc báo cáo gần như giống nhau mỗi ngày | Nhân viên IT | Thực hiện 5 ngày/tuần, tổng thời gian khoảng 60 phút/ngày, tương đương 5 giờ/tuần |


> Gợi ý tự soi:
> - Tuần trước, công việc mất nhiều thời gian nhất là tổng hợp Báo cáo hoạt động hàng ngày vào cuối ngày vì phải lấy dữ liệu từ nhiều nguồn, đối chiếu và format lại báo cáo.
> - Việc thường bị trì hoãn là tổng hợp báo cáo khi trong ngày có nhiều sự cố phát sinh hoặc phải chờ đủ dữ liệu từ các trạm.
> - Người quản lý có thể hỏi lại các thông tin như số liệu cụ thể của trạm, thời điểm xảy ra sự cố, nguyên nhân và trạng thái xử lý.
> - Workflow được nhận thấy là chậm là quy trình thu thập → đối chiếu → tổng hợp dữ liệu từ nhiều nguồn trước khi hoàn thành Báo cáo hoạt động hàng ngày.

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi:
  "Dựa trên công việc của một nhân viên IT phụ trách theo dõi dữ liệu vận hành, camera, sự cố, nhân sự tại các tuyến và tổng hợp Báo cáo hoạt động hàng ngày cuối ngày, hãy giúp tôi brainstorm 10 vấn đề có thể quan sát được. Với mỗi vấn đề, hãy xác định actor, tần suất/thời gian và dấu hiệu có thể đo được. Không đề xuất giải pháp AI ngay."

- Ý dùng được:
  - Tổng hợp báo cáo cuối ngày từ nhiều nguồn dữ liệu.
  - Đối chiếu số liệu trước khi đưa vào báo cáo.
  - Tổng hợp thông tin sự cố phát sinh trong ngày.
  - Kiểm tra camera lặp lại nhiều lần trong ngày.
  - Theo dõi và tổng hợp tình hình nhân sự tại các tuyến.
  - Chuyển dữ liệu sang mẫu báo cáo và format thủ công.

- Ý bỏ vì không phải pain thật:
  - Ý tưởng xây một Agent tự động quản lý toàn bộ hoạt động vận hành.
  - Ý tưởng để AI tự đưa ra quyết định xử lý sự cố.
  - Các vấn đề quá rộng như "AI giúp phòng IT làm việc hiệu quả hơn".
  - Các ý chỉ mô tả mong muốn về công nghệ nhưng chưa xác định được actor, workflow hoặc dấu hiệu đo lường.

**Self-check Phase 1:**

- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Toàn bộ quy trình tổng hợp Báo cáo hoạt động hàng ngày phải thực hiện thủ công dù cấu trúc báo cáo gần như giống nhau mỗi ngày |Workflow rõ từ thu thập dữ liệu → đối chiếu → tổng hợp → viết → gửi; thực hiện hằng ngày và có baseline khoảng 60 phút/ngày; impact dễ quy đổi thành thời gian/tuần/tháng |Chưa chắc bottleneck lớn nhất nằm ở lấy dữ liệu, đối chiếu hay viết báo cáo; cần đo từng bước |
| 2 |Phải đối chiếu số liệu BE với file báo cáo trước khi tổng hợp để tránh sai lệch |Actor rõ là nhân viên IT; workflow ngắn và dễ vẽ; có thể đo thời gian và số lượng dữ liệu phải kiểm tra | Chưa rõ bao nhiêu lỗi/sai lệch thực tế được phát hiện; có thể Rule/validation đã giải quyết được mà chưa cần AI|
| 3 |Khi phát hiện camera hoặc dữ liệu bất thường, phải kiểm tra lại thông tin trước khi ghi nhận sự cố |Xảy ra trong quá trình vận hành; có workflow rõ từ phát hiện → xác minh → ghi nhận → báo cáo; có tiềm năng so sánh Rule với AI |Chưa chắc AI thực sự tốt hơn rule; cần xác định loại bất thường và tỷ lệ false alarm |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu: Nhân viên IT mất khoảng 60 phút mỗi ngày để thu thập, đối chiếu và tổng hợp dữ liệu vận hành từ nhiều nguồn thành Báo cáo hoạt động hàng ngày.

Actor: Nhân viên IT phụ trách tổng hợp và gửi báo cáo vận hành cuối ngày.

Thời điểm / bối cảnh: Cuối mỗi ngày làm việc, sau khi đã có dữ liệu từ BE, camera, sự cố và tình hình nhân sự tại các tuyến.

Current workflow 3-7 bước:
1. Thu thập số liệu vận hành từ BE tại các trạm.
2. Kiểm tra dữ liệu hình ảnh/tình trạng camera.
3. Tổng hợp thông tin sự cố trong ngày.
4. Kiểm tra thông tin nhân sự vận hành tại các tuyến.
5. Đối chiếu và tổng hợp các dữ liệu.
6. Điền và format Báo cáo hoạt động hàng ngày.
7. Review và gửi báo cáo cho quản lý.

Bottleneck: Bước 5 — đối chiếu và tổng hợp dữ liệu từ nhiều nguồn.

Impact: Mất khoảng 60 phút mỗi ngày cho một báo cáo; workflow lặp lại hằng ngày và có nguy cơ chậm báo cáo hoặc phải kiểm tra lại thông tin.

Success metric: Giảm thời gian hoàn thành Báo cáo hoạt động hàng ngày từ khoảng 60 phút xuống còn tối đa 20–25 phút, đồng thời không làm tăng số lỗi hoặc số lần quản lý phải hỏi lại thông tin.

Non-AI alternative: Chuẩn hóa template báo cáo, tạo checklist và dùng Rule/script để tự động tổng hợp những dữ liệu có cấu trúc.

AI hypothesis: AI có thể hỗ trợ tổng hợp thông tin từ nhiều nguồn và tạo bản draft Báo cáo hoạt động hàng ngày để nhân viên IT kiểm tra, chỉnh sửa trước khi gửi.

Quick gut:
[X] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — khoảng 60 phút

[1. Thu thập BE: 15']
        ↓
[2. Check camera: 7']
        ↓
[3. Tổng hợp sự cố: 10']
        ↓
[4. Check nhân sự: 5']
        ↓
[5. Đối chiếu + tổng hợp: 15']  <-- BOTTLENECK
        ↓
[6. Format report: 5']
        ↓
[7. Review + gửi: 3']


FUTURE STATE — mục tiêu 20–25 phút

[1. Auto collect data: 3']       ← Rule/Script
        ↓
[2. Rule validation: 3']         ← Rule
        ↓
[3. AI summarize + draft: 4']   ← AI
        ↓
[4. Human review + edit: 10']   ← HUMAN BOUNDARY
        ↓
[5. Gửi report: 2']


Fallback:
Nếu AI tổng hợp sai hoặc bỏ sót thông tin → nhân viên IT kiểm tra dữ liệu nguồn và chỉnh sửa hoặc tự viết phần đó.

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---
#### Problem Card #2 — Đối chiếu số liệu BE với dữ liệu báo cáo

```text
Problem 1 câu:
Nhân viên IT phải kiểm tra và đối chiếu số liệu BE với dữ liệu trong file báo cáo trước khi tổng hợp Báo cáo hoạt động hàng ngày, gây mất thời gian cho một công việc lặp lại hằng ngày.

Actor:
Nhân viên IT phụ trách kiểm tra và tổng hợp báo cáo vận hành.

Thời điểm / bối cảnh:
Cuối mỗi ngày, trước khi hoàn thiện Báo cáo hoạt động hàng ngày.

Current workflow 3-7 bước:

1. Lấy số liệu từ BE tại các trạm.
2. Mở file dữ liệu/báo cáo cần đối chiếu.
3. So sánh các trường dữ liệu tương ứng.
4. Xác định các số liệu không khớp.
5. Kiểm tra lại dữ liệu từ nguồn.
6. Xác nhận hoặc điều chỉnh số liệu.
7. Đưa dữ liệu đã kiểm tra vào báo cáo.

Bottleneck:
Bước 3-5 — so sánh và xác minh các số liệu không khớp.

Impact:
Mất khoảng 15 phút mỗi ngày để đối chiếu khoảng 30–40 dòng dữ liệu. Đây là công việc lặp lại và có thể làm chậm thời gian hoàn thành báo cáo cuối ngày.

Success metric:
Giảm thời gian đối chiếu từ khoảng 15 phút xuống dưới 5 phút, đồng thời không làm tăng số trường hợp bỏ sót sai lệch dữ liệu.

Non-AI alternative:
Sử dụng công thức Excel, conditional formatting hoặc Rule để tự động so sánh dữ liệu và đánh dấu các trường không khớp.

AI hypothesis:
AI có thể hỗ trợ phân tích các trường dữ liệu bất thường và giải thích những điểm cần nhân viên IT kiểm tra thêm.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — khoảng 15 phút

[Lấy BE data: 3']
→ [Mở file báo cáo: 2']
→ [So sánh dữ liệu: 5']  <-- bottleneck
→ [Kiểm tra sai lệch: 3']
→ [Xác nhận/sửa: 2']

FUTURE STATE — khoảng 5 phút

[BE data + Report data]
→ [Rule tự động đối chiếu: 1']
→ [Chỉ hiển thị dữ liệu bất thường: 1']
→ [Human kiểm tra: 3']  <-- human boundary

Fallback:
Nếu Rule phát hiện sai lệch không chính xác hoặc thiếu dữ liệu → nhân viên IT kiểm tra trực tiếp dữ liệu nguồn và xác nhận thủ công.
```

---

#### Problem Card #3 — Xác minh camera hoặc dữ liệu bất thường

```text
Problem 1 câu:
Nhân viên IT phải kiểm tra thủ công các trường hợp camera hoặc dữ liệu có dấu hiệu bất thường trước khi ghi nhận và báo cáo sự cố.

Actor:
Nhân viên IT/vận hành phụ trách theo dõi hệ thống camera.

Thời điểm / bối cảnh:
Trong các lần kiểm tra camera hằng ngày hoặc khi phát hiện dấu hiệu bất thường.

Current workflow 3-7 bước:

1. Thực hiện kiểm tra camera.
2. Phát hiện camera hoặc dữ liệu có dấu hiệu bất thường.
3. Kiểm tra lại trạng thái và hình ảnh.
4. Xác minh có phải sự cố thực tế hay không.
5. Ghi nhận sự cố.
6. Theo dõi tình trạng xử lý.
7. Tổng hợp thông tin vào báo cáo cuối ngày.

Bottleneck:
Bước 3-4 — kiểm tra và xác minh các trường hợp bất thường.

Impact:
Giả lập khoảng 2–3 trường hợp cần xác minh mỗi ngày, mỗi trường hợp mất khoảng 5–10 phút. Việc kiểm tra thủ công làm tăng thời gian theo dõi và tổng hợp sự cố.

Success metric:
Giảm thời gian xác minh mỗi trường hợp xuống dưới 3 phút mà không làm tăng số trường hợp báo lỗi sai.

Non-AI alternative:
Sử dụng Rule dựa trên trạng thái camera, mất kết nối hoặc các ngưỡng được xác định trước để lọc các trường hợp cần kiểm tra.

AI hypothesis:
AI có thể hỗ trợ phân loại hoặc ưu tiên các trường hợp bất thường để nhân viên IT tập trung kiểm tra những trường hợp có khả năng là sự cố thực tế.

Quick gut:
[ ] No AI / process fix
[x] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — khoảng 20 phút/ngày

[Check camera]
→ [Phát hiện bất thường]
→ [Kiểm tra lại: 5–10'/case]  <-- bottleneck
→ [Xác minh]
→ [Ghi nhận sự cố]
→ [Báo cáo]

FUTURE STATE — mục tiêu dưới 10 phút/ngày

[Camera monitoring]
→ [Rule lọc bất thường]
→ [AI hỗ trợ phân loại/ưu tiên]
→ [Human verification]  <-- human boundary
→ [Ghi nhận + báo cáo]

Fallback:
Nếu hệ thống đánh dấu sai hoặc bỏ sót trường hợp bất thường → nhân viên IT kiểm tra trực tiếp camera và ghi nhận thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Tổng hợp Báo cáo hoạt động hàng ngày từ nhiều nguồn dữ liệu.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi chọn Card #1 vì đây là workflow lặp lại hằng ngày, có actor rõ và có thể mô tả từ bước thu thập dữ liệu đến review và gửi báo cáo. Theo baseline giả lập, quy trình mất khoảng 60 phút mỗi ngày và bottleneck nằm ở bước đối chiếu, tổng hợp thông tin từ nhiều nguồn trước khi viết báo cáo. Problem này cũng có thể so sánh rõ giữa No AI, Rule, Workflow và Agent để tìm ra mức tự động hóa phù hợp.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Bottleneck thực sự nằm ở việc thu thập dữ liệu, đối chiếu dữ liệu hay viết báo cáo? Nếu chỉ dùng Rule/automation để lấy và kiểm tra dữ liệu thì phần nào còn thực sự cần AI?

Workflow này có cần Agent không, hay một Workflow tuyến tính với Rule + AI draft + human review đã đủ?
```

**AI phản biện Card (nếu có):**

* Điểm yếu AI chỉ ra:

  * Problem "tự động hóa báo cáo" ban đầu còn quá rộng và dễ trở thành solution-first.
  * Cần tách rõ các bước trong workflow để xác định chính xác bottleneck.
  * Không nên mặc định dùng Agent khi quy trình có các bước cố định.
  * Cần có metric cụ thể để chứng minh vấn đề và đo hiệu quả sau cải thiện.

* Tôi sửa gì:

  * Thu hẹp problem thành quy trình tổng hợp Báo cáo hoạt động hàng ngày từ nhiều nguồn dữ liệu.
  * Tách workflow thành các bước thu thập, kiểm tra, đối chiếu, tổng hợp, review và gửi.
  * Xác định bước đối chiếu/tổng hợp là bottleneck cần tiếp tục kiểm chứng.
  * Đưa Rule và Workflow vào phương án so sánh thay vì mặc định chọn Agent.

### Self-check nộp phần 01

* [x] Có 5+ problems + top 3 Cards đủ field
* [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
* [x] Đã chọn 1 card pitch + câu hỏi challenge
