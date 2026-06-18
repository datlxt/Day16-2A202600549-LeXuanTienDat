---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** StudyMate AI — trợ lý ôn thi lấy chính đề thi của sinh viên làm gốc (demo: môn Lập trình Python cơ bản)

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính** → sinh viên đang tự ôn thi môn Lập trình Python cơ bản
- [x] **1 hoàn cảnh / tình huống rõ** → giai đoạn nước rút trước ngày thi, quỹ thời gian ít
- [x] **1 job cốt lõi** → biết mình yếu chủ đề nào và ôn đúng trọng tâm kịp ngày thi
- [x] **1 workflow đủ cụ thể để vẽ ra được** → tải đề → chẩn đoán → bản đồ điểm yếu → lộ trình → luyện → đánh giá sẵn sàng

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** StudyMate AI — hệ thống đọc chính đề thi của sinh viên, tự xác định đáp án từng câu, cho làm thử để chẩn đoán năng lực theo chủ đề, rồi dựng lộ trình ôn bám ngày thi (MVP: Lập trình Python cơ bản).
- **Lát cắt tôi chọn để phân tích hôm nay là:** Một sinh viên ôn thi cuối kỳ môn Python cơ bản, còn ít ngày trước thi, có đề thi/đề ôn nhưng không có đáp án và không biết mình yếu chủ đề nào.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây đúng là lát cắt MVP đã khoanh: 1 môn (Python), 1 nhóm user (sinh viên ôn thi), 1 hoàn cảnh (nước rút), 1 workflow rõ 9 bước. Lát cắt đủ hẹp để vẽ được workflow và chỉ ra AI nên vào đâu, thay vì nói chung chung "AI cho giáo dục".

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Sinh viên ôn thi không biết mình yếu phần nào nên ôn lan man toàn bộ tài liệu trong khi thời gian có hạn → ôn không đúng trọng tâm, vào thi vẫn hổng.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Sinh viên đại học đang tự ôn thi môn Lập trình Python cơ bản (giai đoạn nước rút trước thi).

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Đọc lại slide/giáo trình, làm lại đề cũ thủ công, hỏi ChatGPT/Gemini những câu chung chung, hỏi bạn — đều không cho biết chính xác mình yếu chủ đề nào theo đề thi thật.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Sinh viên đại học học lập trình (demo: Python cơ bản), đặc biệt nhóm gần kỳ thi và không chắc mình nắm vững phần nào.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Giai đoạn nước rút trước thi: nhiều môn cùng lúc, thời gian ít, có đề thi/đề cương nhưng thường không kèm đáp án và không có cách đo nhanh "mình yếu chủ đề nào".

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > ChatGPT (Study Mode), Gemini (Guided Learning), NotebookLM; hoặc tự ôn thủ công (đọc lại tài liệu, làm đề cũ, học nhóm). Các công cụ AI trả lời tốt nhưng **không lấy chính đề thi của sinh viên làm gốc** để chẩn đoán điểm yếu theo chủ đề.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Thị trường AI-in-education tăng nhanh (~5,88 tỉ USD 2024 → 32,27 tỉ USD 2030, CAGR ~31,2% — Grand View Research, ước lượng một hãng). LLM nay đủ giỏi để **tự suy luận đáp án Python cơ bản** và **sinh câu luyện cùng chủ đề/mức tư duy** ở quy mô — điều trước đây cần kho đáp án/người soạn.

### Tóm tắt market context trong 3-4 dòng

> Sinh viên ôn thi lập trình (demo Python) bước vào nước rút với quỹ thời gian ít và nhiều môn. Họ có đề/đề cương nhưng thường không có đáp án, không biết mình yếu đâu nên ôn lan man. Các tool AI phổ thông trả lời tốt nhưng không bám chính đề thi để chẩn đoán điểm yếu và dựng lộ trình theo ngày thi. Thị trường AI-giáo dục đang tăng mạnh và LLM đã đủ giỏi để tự xác định đáp án + sinh câu luyện → đây là thời điểm đáng giải.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Sinh viên đang tự ôn thi môn Python cơ bản — người trực tiếp tải đề lên, làm bài chẩn đoán, luyện theo lộ trình và xem mức sẵn sàng.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Chính sinh viên là người chịu sức ép thi và trực tiếp thực hiện mọi bước trong workflow. Giảng viên/trường chỉ là *influencer/buyer* (trong kịch bản B2B sau này), không phải người ngồi làm bài chẩn đoán và luyện tập — nên job executor là sinh viên.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng AI chấm đề và chỉ ra phần yếu để ôn cho kịp thi.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: "AI", "chấm đề" (đây là cách làm, không phải job)

### Bản chốt

**Core JTBD cuối cùng:**  
> Tận dụng quỹ thời gian ôn ít ỏi trước ngày thi để xác định đúng phần kiến thức mình còn yếu và vá chúng, nhằm bước vào phòng thi với mức độ sẵn sàng cao nhất có thể.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Còn ~1 tuần trước thi mà vẫn nguyên chồng tài liệu chưa ôn | Biết ngay mình yếu chủ đề Python nào nhất | Dồn thời gian vào đúng phần đó thay vì đọc lại tất cả | Pain "không biết yếu đâu" → cần **chẩn đoán điểm yếu** |
| JS2 | Làm thử đề và sai mấy câu về vòng lặp / hàm | Được luyện thêm đúng dạng đó tới khi chắc | Không lặp lại lỗi cũ trong phòng thi | Cần **luyện cá nhân hóa theo chủ đề yếu**, không phải học lại từ đầu |
| JS3 | Sát ngày thi, tâm lý lo lắng không biết đã ôn đủ chưa | Có một con số rõ ràng cho biết mình sẵn sàng bao nhiêu % | Biết nên ôn tiếp phần nào hay yên tâm nghỉ ngơi | Cần **chỉ số mức sẵn sàng** để ra quyết định ôn/nghỉ |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| ChatGPT (Study Mode) / Gemini (Guided Learning) | Hỏi đáp khái niệm, giải bài, gợi ý cách học | Phủ rộng, miễn phí, có sẵn tài khoản, dạy kiểu Socratic | Trả lời chung chung; **không bám đề thi thật**; không chẩn đoán điểm yếu theo chủ đề; không có lộ trình bám ngày thi | Thấp (đã có sẵn, dùng quen) |
| NotebookLM | Hỏi đáp bám tài liệu upload, sinh quiz/flashcard | RAG bám đúng tài liệu, context tới 1 triệu token | Bám tài liệu chứ **không lấy đề thi làm gốc để chẩn đoán năng lực** + dựng lộ trình theo ngày thi | Thấp |
| Tự ôn thủ công (đọc lại slide, làm đề cũ, hỏi bạn) | Tự kiểm tra và ôn lại kiến thức | Miễn phí, quen thuộc, chủ động | Tốn thời gian, không biết yếu đâu, dễ ôn lan man, không có chỉ số sẵn sàng | Thấp về tiền nhưng **thói quen mạnh** |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> ChatGPT/Gemini để hỏi đáp + tự ôn thủ công bằng tài liệu và đề cũ — tức là quay lại đúng tình trạng "ôn lan man, không biết yếu đâu".

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định phạm vi cần ôn cho kỳ thi Python | Đề cương, tự suy đoán | Không rõ phạm vi & mức độ yêu cầu thực sự | Med |
| Locate | Tìm đề thi, tài liệu, đáp án | Gom slide/đề cũ, search Google, hỏi bạn | Đề thường **không có đáp án**, tốn công xác minh | High |
| Prepare | Quyết định ôn cái gì trước | Tự đoán / ôn tuần tự từ đầu | Ưu tiên sai, **ôn lan man**, không bám ngày thi | High |
| Confirm | Xác nhận mình hiểu đúng / đáp án đúng | Hỏi bạn, giảng viên, ChatGPT | Mỗi nguồn một kiểu, không chắc đáp án đúng | Med |
| Execute | Thực sự ôn và làm bài | Đọc lại + làm đề cũ | Làm xong không biết đúng/sai theo từng chủ đề | Med |
| Monitor | Theo dõi mình yếu/mạnh ở đâu | Cảm tính | **Không đo được điểm yếu theo chủ đề** | High |
| Modify | Điều chỉnh kế hoạch ôn theo điểm yếu + thời gian còn lại | Hầu như không điều chỉnh | Kế hoạch tĩnh, không xoay theo kết quả thực tế | Med |
| Conclude | Biết mình đã sẵn sàng thi chưa | Cảm giác lo lắng | **Không có chỉ số sẵn sàng** để yên tâm/ưu tiên | High |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Monitor — không biết mình đang yếu chủ đề nào (không có chẩn đoán theo đề thật)  
**Bước đau nhất #2:** Prepare — không biết nên ưu tiên ôn gì trước theo thời gian còn lại (ôn lan man)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Hai bước này chính là gốc của vấn đề "ôn lan man, vào thi vẫn hổng": vì không **Monitor** được điểm yếu nên không **Prepare** được thứ tự ưu tiên. Đây cũng đúng là chỗ các alternative (ChatGPT, NotebookLM, tự ôn) đang fail — họ trả lời/ tổng hợp tốt nhưng không lấy đề thi làm gốc để chẩn đoán + lập lộ trình.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Monitor (chẩn đoán) | Đọc đề thi thật, tự xác định đáp án từng câu, chấm bài làm thử → dựng **bản đồ điểm yếu theo chủ đề** | LLM đủ giỏi suy luận đáp án Python cơ bản + phân loại chủ đề/mức tư duy ở quy mô và tức thì — thứ kho đáp án thủ công không làm kịp | **AI xác định đáp án sai** mà không ai phát hiện → chẩn đoán lệch (giảm rủi ro bằng bước 4 xác nhận + nhãn "đáp án do AI xác định") |
| Prepare → Execute (luyện) | Sắp thứ tự ôn ưu tiên theo điểm yếu + ngày thi; **sinh thêm câu luyện cùng chủ đề/mức tư duy**, có gợi ý khi sai (không lộ đáp án) | AI sinh nội dung luyện gần như vô hạn, cá nhân hóa theo đúng chỗ yếu, chi phí thấp | Câu sinh ra sai/lạc cấp độ; gợi ý vô tình lộ đáp án; lộ trình ưu tiên sai nếu chẩn đoán đầu vào sai |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước **Monitor — chẩn đoán điểm yếu từ chính đề thi thật của sinh viên** (AI đọc đề, tự xác định đáp án, chấm bài thử, dựng bản đồ điểm yếu theo chủ đề). Đây là wedge khác biệt: "lấy đề thi của sinh viên làm gốc".

**Vì sao không phải ở bước khác:**  
> Ở Locate/Confirm/Execute thì các alternative (ChatGPT, tự ôn) đã "đủ tốt" để hỏi đáp và làm bài. Khác biệt thật sự nằm ở chỗ chưa ai làm tốt: **chẩn đoán điểm yếu bám đề thi thật + dựng lộ trình theo ngày thi** — nếu giải được bước này thì các bước sau (luyện, đánh giá sẵn sàng) mới có giá trị.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **sinh viên ôn thi Python** làm tốt hơn việc **biết mình yếu đâu và ôn đúng trọng tâm** ở bước **chẩn đoán điểm yếu từ chính đề thi + lập lộ trình theo ngày thi**, bằng cách **để AI đọc đề thật, tự xác định đáp án, chấm bài thử và dựng bản đồ điểm yếu + lộ trình ưu tiên**, thì họ sẽ chuyển từ **ChatGPT chung chung + tự ôn lan man** sang **StudyMate AI**, vì **tiết kiệm thời gian nước rút và biết chính xác cần ôn gì trước**.

### Tín hiệu sớm nếu hypothesis này đúng

1. Sinh viên upload đề và **hoàn thành trọn bài chẩn đoán** (không bỏ giữa chừng), rồi mở bản đồ điểm yếu.
2. Họ **quay lại luyện đúng các chủ đề yếu** qua nhiều phiên và % sẵn sàng tăng dần — thay vì chỉ xem một lần rồi quay về ChatGPT.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1 — Sinh viên coi "không biết yếu đâu" là pain đủ đau | Có thể họ chấp nhận ôn lan man hoặc chỉ ngại tốn công, không thấy đủ đau để đổi | Mới là quan sát + bối cảnh thị trường, chưa phỏng vấn | Phỏng vấn 5–10 sinh viên về cách ôn hiện tại |
| A2 — AI xác định đáp án Python cơ bản đủ chính xác để chẩn đoán đáng tin | Nếu AI đoán sai đáp án → chẩn đoán lệch → mất niềm tin ngay lập tức | Chưa đo accuracy thực tế | Chấm thử N đề Python, so accuracy của AI với đáp án do người soạn |
| A3 — Sinh viên sẽ rời ChatGPT/tự ôn để dùng StudyMate | Switching cost thấp nhưng ChatGPT free + thói quen rất mạnh | Chưa có | Cho dùng prototype, đo retention & tỉ lệ quay lại |
| A4 — Bản đồ điểm yếu + lộ trình thực sự đổi cách ôn | User có thể xem cho biết rồi vẫn ôn theo cách cũ | Chưa có | Theo dõi hành vi luyện sau khi xem bản đồ (có làm theo lộ trình không) |
| A5 — Sinh viên đủ tin "đáp án do AI xác định" để hành động | Nhãn "AI tự xác định" có thể làm giảm niềm tin, nhất là khi sai vài câu | Chưa có | Hỏi mức độ tin + A/B có/không bước xác nhận (bước 4) |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A2 — độ chính xác đáp án do AI xác định.** Vì toàn bộ giá trị (bản đồ điểm yếu → lộ trình → đánh giá sẵn sàng) đều dựng trên đáp án AI. Nếu AI xác định đáp án sai, chẩn đoán sai theo, và sinh viên mất niềm tin ngay — cả sản phẩm sụp. Đây là tử huyệt cần validate đầu tiên.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| "Core JTBD bản nháp đầu vẫn nhét 'AI/chấm đề' vào — đó là cách làm chứ không phải job" | Core JTBD (Bước 4) | Đã gạch bỏ từ solution, giữ bản chốt solution-free; không sửa thêm |
| "ChatGPT đang free và sinh viên dùng quen — switching cost thấp nhưng quán tính cao, lý do gì đủ mạnh để họ đổi?" | Product hypothesis + A3 | Giữ hypothesis, nhưng nhấn mạnh giá trị "tiết kiệm thời gian nước rút + biết chính xác cần ôn gì"; ưu tiên validate A3 (retention) sớm |
| "Python có câu dính code/edge case, AI tự xác định đáp án rất dễ sai — nếu sai thì cả chẩn đoán sập" | AI leverage point + A2 | Giữ leverage point, nhưng coi bước 4 (xác nhận kết quả bóc đề) là bắt buộc và đo accuracy đáp án AI trước khi tin |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Bàn phản biện **củng cố hướng đi chứ không lật nó**: job executor, core JTBD, leverage point và hypothesis đều đứng vững. Thứ thay đổi không phải nội dung mà là **thứ tự ưu tiên validate**: hai phản biện mạnh nhất (ChatGPT free + quán tính, và rủi ro AI xác định đáp án sai) chỉ thẳng vào **A2** và **A3** — nên mình giữ nguyên bài làm nhưng đặt A2 (độ chính xác đáp án AI) làm việc cần kiểm đầu tiên, A3 (retention so với ChatGPT) ngay sau đó.

### Version cuối cùng tôi nộp

**Job executor:**  
> Sinh viên đang tự ôn thi môn Lập trình Python cơ bản (giai đoạn nước rút trước thi).

**Core JTBD:**  
> Tận dụng quỹ thời gian ôn ít ỏi trước ngày thi để xác định đúng phần kiến thức mình còn yếu và vá chúng, nhằm bước vào phòng thi với mức độ sẵn sàng cao nhất có thể.

**2 bước đau nhất trong workflow:**  
> (1) **Monitor** — không biết mình yếu chủ đề nào; (2) **Prepare** — không biết nên ưu tiên ôn gì trước theo thời gian còn lại.

**AI leverage point chính:**  
> Chẩn đoán điểm yếu từ chính đề thi thật: AI đọc đề, tự xác định đáp án, chấm bài thử và dựng bản đồ điểm yếu theo chủ đề → từ đó lập lộ trình ôn ưu tiên.

**Product hypothesis:**  
> Nếu giúp sinh viên ôn thi Python biết chính xác mình yếu đâu và ôn đúng trọng tâm — bằng cách để AI chẩn đoán từ đề thật + lập lộ trình theo ngày thi — họ sẽ chuyển từ "ChatGPT chung chung + tự ôn lan man" sang StudyMate AI, vì tiết kiệm thời gian nước rút và biết phải ôn gì trước.

**Assumption cần validate đầu tiên:**  
> A2 — độ chính xác của đáp án do AI tự xác định cho đề Python (chấm thử N đề, so với đáp án người soạn).

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
