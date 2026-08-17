# Track 1 - Day 17 — Finding and Validating Pain Points

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202610693
- **Họ tên:** Nguyễn Thị Tuyết Mai
- **Tên nhóm:** FlyIn
- **Thành viên:**
  - Nguyễn Thị Tuyết Mai
  - Lê Thị Linh
- **Case đã chọn:** **Case 3 — AI Support Radar**

---

## 2. Problem Hypothesis Brief

### 2.1. Solution → Capability trung tính

**Chỉ thị giải pháp:**

> AI đọc tín hiệu hành vi học tập và tạo Support Queue cho giảng viên.

**Capability trung tính:**

> Giúp người phụ trách học tập nhận biết và ưu tiên những learner có khả năng đang gặp khó khăn để có thể xem xét hỗ trợ kịp thời.

### 2.2. Change — Chuỗi thay đổi kỳ vọng

```text
AI Support Radar
→ Lab Coach nhận biết learner có dấu hiệu gặp khó khăn
→ Lab Coach xác định ai cần được chú ý trước
→ Lab Coach chủ động kiểm tra/hỗ trợ
→ Learner có cơ hội được hỗ trợ sớm hơn
```

**Các thay đổi được kỳ vọng:**

1. Lab Coach có thêm thông tin để nhận biết learner có khả năng gặp khó khăn.
2. Lab Coach chuyển từ phản ứng khi vấn đề đã rõ sang chủ động kiểm tra learner có dấu hiệu bất thường.
3. Learner có cơ hội được phát hiện và hỗ trợ trước khi vấn đề ảnh hưởng lớn đến tiến độ hoặc kết quả học tập.

**Output:** tín hiệu hoặc danh sách learner có khả năng cần được chú ý.  
**Outcome:** Lab Coach thực sự kiểm tra, ưu tiên và hỗ trợ learner phù hợp.

### 2.3. Actor

| Actor | Họ đang làm gì? | Pain / hậu quả giả định | Lợi ích kỳ vọng |
|---|---|---|---|
| Lab Coach | Theo dõi tiến độ và hỗ trợ nhiều learner | Khó biết learner nào thực sự cần hỗ trợ, nhất là khi learner không chủ động nói | Biết nên chú ý và kiểm tra ai trước |
| Learner | Học bài, làm quiz/assignment và tự xử lý khi bị kẹt | Có thể gặp khó khăn nhưng không chủ động báo hoặc chưa nhận ra mình cần hỗ trợ | Có cơ hội được phát hiện và hỗ trợ sớm |
| Giảng viên | Theo dõi và trực tiếp hỗ trợ learner | Thời gian hỗ trợ có hạn, dễ bỏ sót learner cần giúp | Ưu tiên thời gian cho learner cần hỗ trợ hơn |

**Actor nhóm chọn để điều tra trước:** **Lab Coach**.

**Lý do:** đây là người có job trực tiếp là theo dõi, nhận biết và ưu tiên learner cần hỗ trợ. Nếu Lab Coach đã có thể nhận biết đủ sớm và chính xác bằng cách hiện tại thì capability của AI Support Radar có thể không giải quyết một problem đủ lớn.

### 2.4. Situation & Job

**Mô tả Situation & Job:**

> Khi đang phụ trách một nhóm learner trong quá trình học, Lab Coach đang cố xác định learner nào đang gặp khó khăn và cần được hỗ trợ trước bằng cách quan sát quá trình học, phản hồi của learner, tiến độ, quiz hoặc assignment.

**Giả thuyết JTBD:**

> Khi đang theo dõi nhiều learner cùng lúc, tôi muốn nhận biết learner nào đang gặp khó khăn và cần được chú ý, để có thể ưu tiên kiểm tra và hỗ trợ đúng người trước khi vấn đề trở nên nghiêm trọng hơn.

### 2.5. Hai Pain Hypothesis cạnh tranh

#### Hypothesis A — Visibility Problem

> Khi theo dõi nhiều learner cùng lúc, Lab Coach gặp khó khăn trong việc xác định learner nào đang cần hỗ trợ vì không có đủ tín hiệu rõ ràng và kịp thời, đặc biệt khi learner không chủ động yêu cầu giúp đỡ, dẫn đến một số khó khăn chỉ được phát hiện khi learner đã chậm tiến độ, không hoàn thành bài hoặc kết quả giảm.

#### Hypothesis B — Capacity Problem

> Khi nhiều learner gặp khó khăn cùng lúc, Lab Coach gặp khó khăn trong việc hỗ trợ learner kịp thời vì thời gian và nguồn lực có hạn, dẫn đến một số learner phải chờ hoặc không nhận đủ hỗ trợ dù Lab Coach đã biết họ đang gặp khó khăn.

**Giả thuyết ưu tiên điều tra:** **A — Visibility Problem**.

**Lý do:** solution directive đang ngầm giả định bottleneck nằm ở việc phát hiện và ưu tiên learner. Nếu bottleneck thực tế là thiếu thời gian hoặc nguồn lực hỗ trợ thì solution hiện tại có thể đang giải quyết sai vấn đề.

### 2.6. Evidence Map

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ hoặc bác bỏ |
|---|---|---|
| Situation có thật | Lab Coach thường xuyên phải theo dõi nhiều learner cùng lúc | Lab Coach chỉ phụ trách rất ít learner và nắm rất rõ từng người |
| Pain có ý nghĩa | Có learner gặp khó nhưng Lab Coach chỉ phát hiện sau khi chậm tiến độ, điểm thấp hoặc missing assignment | Lab Coach thường nhận biết đủ sớm và không xem đây là vấn đề đáng kể |
| Workaround tồn tại | Lab Coach phải xem quiz, assignment, hỏi từng người, xem tiến độ hoặc chờ learner chủ động hỏi | Đã có quy trình hiện tại đơn giản, nhanh và đáng tin cậy |
| Consequence tồn tại | Phát hiện muộn khiến learner bị kẹt lâu, miss deadline, kết quả giảm hoặc cần hỗ trợ nhiều hơn | Phát hiện muộn hầu như không tạo hậu quả thực tế |
| Pattern có lặp | Có nhiều case tương tự trong thời gian gần đây | Chỉ là trường hợp hiếm hoặc ngoại lệ |

### 2.7. Problem Hypothesis cuối cùng

> **Khi theo dõi nhiều learner cùng lúc, Lab Coach gặp khó khăn trong việc xác định sớm learner nào đang cần hỗ trợ vì không phải learner nào gặp khó khăn cũng chủ động yêu cầu giúp đỡ và các tín hiệu hiện tại có thể chỉ trở nên rõ ràng khi vấn đề đã xảy ra, dẫn đến nguy cơ learner được phát hiện và hỗ trợ muộn.**

**Điều phải đúng để giả thuyết đứng vững:**

> Phải tồn tại những trường hợp thực tế mà learner gặp khó khăn nhưng Lab Coach không nhận biết đủ sớm; việc phát hiện muộn phải tạo ra hậu quả có ý nghĩa; và cách theo dõi hiện tại chưa giải quyết vấn đề đủ tốt.

**Điều có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**

> Lab Coach thường nhận biết chính xác và đủ sớm learner gặp khó khăn; learner thường chủ động yêu cầu hỗ trợ; phát hiện muộn không tạo hậu quả đáng kể; hoặc bottleneck thực tế là thiếu thời gian hỗ trợ chứ không phải thiếu visibility.

### 2.8. Solution Parking Lot

| Hướng giải quyết có thể có | AI / Không AI |
|---|---|
| AI Support Radar phân tích tín hiệu học tập và flag learner cần chú ý | AI |
| AI Support Prioritizer đề xuất thứ tự learner nên được kiểm tra | AI |
| AI Check-in chủ động hỏi learner khi có dấu hiệu bất thường | AI |
| Weekly learner check-in bằng form ngắn | Không AI |
| Rule-based alert theo deadline, quiz, inactivity | Không AI |

---

## 3. Conversation Guide phiên bản cuối

### 3.1. Big 3 — Ba điều quan trọng nhất cần học

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| **1. Lab Coach có thực sự phát hiện learner gặp khó khăn muộn không?** | Một sự kiện gần đây có trình tự rõ: learner gặp khó → Lab Coach chưa biết → xuất hiện tín hiệu muộn → Lab Coach mới phát hiện | Lab Coach thường nhận biết learner gặp khó đủ sớm và không có case đáng kể bị bỏ sót |
| **2. Việc phát hiện muộn có tạo hậu quả đủ lớn để đáng giải quyết không?** | Learner bị kẹt lâu, miss deadline, giảm kết quả, mất động lực hoặc cần nhiều hỗ trợ hơn sau đó | Phát hiện muộn chỉ gây bất tiện nhỏ, không ảnh hưởng đáng kể đến learner hoặc Lab Coach |
| **3. Bottleneck thật sự là thiếu visibility hay thiếu capacity?** ⭐ | Lab Coach kể được case họ không biết learner đang gặp khó cho đến khi có tín hiệu muộn | Lab Coach thực ra biết ai đang gặp khó nhưng không có thời gian hoặc nguồn lực để hỗ trợ — khi đó nhóm cần đổi hướng |

> **Câu hỏi “đáng sợ” của nhóm là Big 3 số 3**, vì nếu bottleneck là capacity chứ không phải visibility thì Problem Hypothesis A sẽ yếu đi đáng kể.

### 3.2. Tiêu chí tuyển người

> Chúng tôi cần nói chuyện với **Lab Coach đã trực tiếp theo dõi và hỗ trợ nhiều learner trong một lớp/cohort** trong vòng **30 ngày gần đây**; đồng thời ưu tiên thêm learner đã từng gặp khó khăn trong quá trình học trong vòng **7 ngày gần đây**.

### 3.3. Recruitment check

**Với Lab Coach:**

> Trong 30 ngày gần đây, bạn có trực tiếp theo dõi tiến độ hoặc hỗ trợ nhiều learner trong cùng một lớp/cohort không?

**Với learner:**

> Trong 7 ngày gần đây, bạn có lần nào bị kẹt khi học hoặc làm bài nhưng chưa hỏi Lab Giảng viên ngay không?

> Recruitment check chỉ dùng để xác nhận đúng đối tượng phỏng vấn, không tính là evidence chính.

### 3.4. Lời mở đầu

> Cảm ơn bạn đã dành thời gian. Nhóm mình đang tìm hiểu cách learner được theo dõi và hỗ trợ trong quá trình học. Mình muốn nghe về những tình huống thực tế bạn đã trải qua gần đây, không có câu trả lời đúng hay sai. Mình sẽ chủ yếu hỏi về những gì đã thực sự xảy ra và cách bạn xử lý lúc đó.

### 3.5. Story opener

**Với Lab Coach:**

> Kể mình nghe về lần gần nhất bạn phát hiện một learner đang gặp khó khăn muộn hơn bạn mong muốn?

**Với learner:**

> Kể mình nghe về lần gần nhất bạn bị kẹt khi học nhưng chưa hỏi Lab Coach hoặc mentor ngay?

### 3.6. Big 3 Questions — Lab Coach

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| Lab Coach có phát hiện learner muộn không? | **Lần gần nhất bạn nhận ra một learner đang gặp khó khăn là khi nào? Bạn nhận ra bằng cách nào?** |
| Pain có đủ ý nghĩa không? | **Từ lúc learner bắt đầu gặp khó đến lúc bạn nhận ra, chuyện gì đã xảy ra và việc đó kéo theo hậu quả gì?** |
| Visibility hay Capacity? ⭐ | **Trong tình huống đó, điều khó hơn với bạn là không biết learner đang cần hỗ trợ, hay là đã biết nhưng chưa có thời gian/nguồn lực để hỗ trợ? Bạn có thể kể cụ thể không?** |

### 3.7. Big 3 Questions — Learner

| Điều cần học | Câu hỏi sẽ dùng |
|---|---|
| Learner có gặp khó mà Lab Coach chưa biết không? | **Lần gần nhất bạn bị kẹt, bạn đã làm gì trước khi tìm đến Lab Giảng viên?** |
| Vì sao visibility gap có thể xuất hiện? | **Điều gì khiến bạn chưa hỏi Lab Giảng viên ngay lúc đó?** |
| Consequence có thật không? | **Lab Giảng viên cuối cùng có biết bạn đang gặp khó không? Nếu có, họ biết bằng cách nào và lúc đó đã xảy ra điều gì?** |

### 3.8. Probe bank

Chỉ dùng khi cần đào sâu câu chuyện:

- “Lúc đó chuyện gì xảy ra tiếp theo?”
- “Bạn đã làm gì?”
- “Vì sao bạn chọn cách đó?”
- “Phần nào khó nhất?”
- “Bạn đã thử cách nào khác chưa?”
- “Việc đó kéo theo hậu quả gì?”
- “Khoảng bao lâu thì chuyện đó được giải quyết?”
- “Ai là người nhận ra vấn đề đầu tiên?”
- “Lần gần nhất trước đó là khi nào?”
- “Bạn có thể kể một ví dụ cụ thể không?”

### 3.9. Ba phản xạ khi data bắt đầu lệch

| User đưa ra | Phản xạ | Cách quay lại evidence |
|---|---|---|
| Lời khen hoặc nhận xét về ý tưởng | **Deflect** | “Cảm ơn bạn. Quay lại tình huống vừa rồi, lúc đó bạn đã làm gì tiếp?” |
| Câu chung chung hoặc lời hứa tương lai | **Anchor** | “Lần gần nhất chuyện đó thực sự xảy ra là khi nào?” |
| Ý tưởng hoặc feature request | **Dig** | “Điều đó giúp bạn làm được gì? Hiện tại bạn đang xử lý việc đó như thế nào?” |

### 3.10. Tự rà soát guide

- [x] Không nhắc đến AI Support Radar trong lời mở đầu hay câu hỏi chính.
- [x] Không hỏi “Bạn có thích/ muốn dùng feature này không?”.
- [x] Story opener được neo vào **lần gần nhất**.
- [x] Ba câu hỏi chính nối trực tiếp với Big 3.
- [x] Có câu hỏi có thể làm giả thuyết yếu đi: **Visibility hay Capacity?**
- [x] Probe bank tập trung vào hành vi, workaround và consequence đã xảy ra.
- [x] Recruitment check xác nhận interviewee thực sự từng trải qua situation.

### 3.11. Phân công phỏng vấn

| Thành viên | Đối tượng | Vai trò |
|---|---|---|
| [Thành viên 1] | Lab Coach | Interviewer chính |
| [Thành viên 2] | Learner 1 | Interviewer + ghi chú |
| [Thành viên 3] | Learner 2 | Interviewer + ghi chú |

---

## 4. Practice Reflection

> Phần này phản ánh việc luyện guide trước khi phỏng vấn thật; không sử dụng hội thoại giả định làm evidence về user.

### 4.1. Câu hỏi hiệu quả nhất

> **“Trong tình huống đó, điều khó hơn với bạn là không biết learner đang cần hỗ trợ, hay là đã biết nhưng chưa có thời gian/nguồn lực để hỗ trợ? Bạn có thể kể cụ thể không?”**

Câu hỏi này hiệu quả vì nó buộc nhóm kiểm tra trực tiếp hai cách giải thích cạnh tranh — **Visibility Problem** và **Capacity Problem** — thay vì chỉ tìm bằng chứng ủng hộ giả thuyết ban đầu.

### 4.2. Câu hỏi có tính dẫn dắt và cách sửa

**Phiên bản dễ dẫn dắt:**

> “Có phải learner không chủ động hỏi nên bạn không biết họ đang gặp khó không?”

Câu này đã gợi sẵn nguyên nhân và dễ khiến interviewee đồng ý với giả định của nhóm.

**Cách sửa:**

> “Lúc đó điều gì khiến bạn chưa nhận ra learner đang gặp khó khăn?”

Phiên bản mới mở hơn và cho phép interviewee đưa ra nguyên nhân khác với giả thuyết của nhóm.

### 4.3. Nhóm đã chỉnh Conversation Guide như thế nào?

Nhóm đã:

1. Bỏ các câu hỏi hỏi trực tiếp về AI hoặc mức độ yêu thích solution.
2. Neo story opener vào **một sự kiện gần nhất** thay vì hỏi chung chung.
3. Chuyển các câu hỏi từ “Bạn có thường...?” sang “Lần gần nhất...?” để lấy hành vi quá khứ.
4. Bổ sung câu hỏi phân biệt **Visibility** và **Capacity** nhằm giảm confirmation bias.
5. Bổ sung probe về workaround, thời gian, hậu quả và mức độ lặp lại để đánh giá pain có thực sự đáng giải hay không.

---

## 5. AI Support Log

### 5.1. AI đã hỗ trợ gì?

AI được sử dụng để:

- phân rã solution directive theo chuỗi **Solution → Change → Actor → Situation & Job → Pain → Evidence**;
- đề xuất hai pain hypothesis cạnh tranh;
- hỗ trợ cấu trúc Evidence Map và Big 3;
- hỗ trợ viết bản nháp Conversation Guide;
- rà soát các câu hỏi có nguy cơ pitch solution hoặc dẫn dắt interviewee;
- đề xuất cách chuyển câu hỏi chung chung thành câu hỏi về hành vi và sự kiện đã xảy ra.

### 5.2. Điểm AI còn sai hoặc hời hợt

Một số gợi ý ban đầu của AI có xu hướng:

- mặc định rằng Lab Coach chắc chắn đang phát hiện learner quá muộn;
- xem việc learner không chủ động hỏi là nguyên nhân chính khi chưa có evidence;
- nghiêng quá nhanh về AI Support Radar như solution phù hợp;
- tạo ví dụ hội thoại giả định dễ bị nhầm với evidence thật;
- chưa tách rõ **visibility problem** và **capacity problem** ngay từ đầu.

### 5.3. Nhóm đã tự sửa như thế nào?

Nhóm đã:

- giữ toàn bộ Chặng 1 ở mức **hypothesis**, không ghi như fact về user;
- bổ sung **Capacity Problem** làm cách giải thích cạnh tranh;
- xác định rõ evidence nào có thể làm nhóm bác bỏ giả thuyết;
- không dùng hội thoại mô phỏng làm evidence;
- chỉnh Conversation Guide để hỏi về sự kiện, hành vi và consequence thực tế;
- chưa quyết định dùng AI trước khi hoàn thành problem validation;
- giữ nhiều hướng giải pháp trong **Solution Parking Lot**, bao gồm cả phương án không sử dụng AI.

---

## 6. Interview Artifacts

```text
.
├── README.md
└── interview/
    ├── notes.md
    └── recording.m4a
```

- `interview/notes.md`: ghi chú phỏng vấn thực tế, gồm sự kiện, hành vi, workaround, consequence và evidence đáng chú ý.
- `interview/recording_link.md`: bản ghi âm buổi phỏng vấn khi đã được người tham gia đồng ý.

> **Lưu ý:** README này chỉ chứa hypothesis, guide và reflection của nhóm. Evidence dùng để xác thực hoặc bác bỏ Problem Hypothesis phải đến từ phỏng vấn thực tế và được ghi lại trong `interview/notes.md`.
