# Bài 1 - Ngày 17 — Tìm và Xác Thực Vấn Đề

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202610693
- **Họ tên:** Nguyễn Thị Tuyết Mai
- **Tên nhóm:** FlyIn
- **Thành viên:**
  - Nguyễn Thị Tuyết Mai
  - Lê Thị Linh
- **Case đã chọn:** Case 3 — AI Support Radar

---

## 2. Problem Hypothesis Brief

### 2.1. Solution

**Solution directive:**

> AI đọc tín hiệu hành vi học tập và tạo Support Queue cho giảng viên.

**Capability trung tính:**

> Giúp người phụ trách học tập nhận biết và ưu tiên những learner có khả năng đang gặp khó khăn để có thể xem xét hỗ trợ kịp thời.

---

### 2.2. Expected Change

Chuỗi thay đổi được kỳ vọng:

```text
AI Support Radar
→ Lab Coach nhận biết learner có dấu hiệu gặp khó khăn
→ Lab Coach xác định ai cần được chú ý trước
→ Lab Coach chủ động kiểm tra/hỗ trợ
→ Learner có cơ hội được hỗ trợ sớm hơn
````

Các thay đổi chính:

1. Lab Coach có thêm thông tin để nhận biết learner có khả năng gặp khó khăn.
2. Lab Coach chuyển từ phản ứng khi vấn đề đã rõ sang chủ động kiểm tra learner có dấu hiệu bất thường.
3. Learner có cơ hội được phát hiện và hỗ trợ trước khi vấn đề ảnh hưởng lớn đến tiến độ hoặc kết quả học tập.

**Output:** tín hiệu/danh sách learner có khả năng cần được chú ý.

**Outcome:** Lab Coach thực sự kiểm tra hoặc hỗ trợ learner phù hợp.

---

### 2.3. Actors

| Actor        | Họ đang làm gì?                          | Pain/Hậu quả giả định                  | Lợi ích kỳ vọng                 |
| ------------ | ---------------------------------------- | -------------------------------------- | ------------------------------- |
| Lab Coach  | Theo dõi tiến độ và hỗ trợ nhiều learner | Khó biết learner nào đang cần hỗ trợ   | Biết nên chú ý ai trước         |
| Learner      | Học bài, làm quiz/assignment             | Có thể bị kẹt nhưng không chủ động báo | Có cơ hội được hỗ trợ sớm       |
| Giảng viên | Theo dõi và hỗ trợ learner               | Thời gian hỗ trợ có hạn                | Ưu tiên đúng learner cần hỗ trợ |

**Actor nhóm chọn điều tra trước:** Lab Coach.

**Lý do:** đây là người có trách nhiệm trực tiếp trong việc nhận biết và ưu tiên learner cần hỗ trợ. Nếu Lab Coach đã nhận biết đủ sớm và chính xác bằng cách hiện tại thì capability của AI Support Radar có thể không giải quyết một vấn đề thực sự quan trọng.

---

### 2.4. Situation & Job

**Situation:**

> Khi đang phụ trách một nhóm learner trong quá trình học, Lab Coach đang cố xác định learner nào đang gặp khó khăn và cần được hỗ trợ trước bằng cách quan sát quá trình học, phản hồi của learner, tiến độ, quiz hoặc assignment.

**JTBD:**

> Khi đang theo dõi nhiều learner cùng lúc, tôi muốn nhận biết learner nào đang gặp khó khăn và cần được chú ý, để có thể ưu tiên kiểm tra và hỗ trợ đúng người trước khi vấn đề trở nên nghiêm trọng hơn.

---

### 2.5. Pain Hypotheses

#### Hypothesis A — Visibility Problem

> Khi theo dõi nhiều learner cùng lúc, Lab Coach gặp khó khăn trong việc xác định learner nào đang cần hỗ trợ vì không có đủ tín hiệu rõ ràng và kịp thời, đặc biệt khi learner không chủ động yêu cầu giúp đỡ, dẫn đến một số khó khăn chỉ được phát hiện khi learner đã chậm tiến độ, không hoàn thành bài hoặc kết quả giảm.

#### Hypothesis B — Capacity Problem

> Khi nhiều learner gặp khó khăn cùng lúc, Lab Coach gặp khó khăn trong việc hỗ trợ learner kịp thời vì thời gian và nguồn lực có hạn, dẫn đến một số learner phải chờ hoặc không nhận đủ hỗ trợ dù Lab Coach đã biết họ đang gặp khó khăn.

**Giả thuyết ưu tiên điều tra:** Hypothesis A — Visibility Problem.

**Lý do:** AI Support Radar đang ngầm giả định rằng bottleneck nằm ở việc phát hiện và ưu tiên learner. Nếu bottleneck thực tế là thiếu thời gian hoặc nguồn lực hỗ trợ thì solution hiện tại có thể đang giải quyết sai vấn đề.

---

### 2.6. Evidence cần kiểm tra

| Cần kiểm tra        | Evidence làm nhóm tin hơn                                                 | Evidence làm nhóm nghi ngờ/bác bỏ             |
| ------------------- | ------------------------------------------------------------------------- | --------------------------------------------- |
| Situation có thật   | Lab Coach thường xuyên phải theo dõi nhiều learner                       | Lab Coach chỉ phụ trách rất ít learner       |
| Pain có ý nghĩa     | Có learner bị phát hiện muộn sau khi chậm tiến độ/điểm thấp               | Lab Coach thường phát hiện sớm               |
| Workaround tồn tại  | Lab Coach phải xem quiz, assignment, hỏi từng người hoặc chờ learner hỏi | Đã có quy trình hiện tại đơn giản và hiệu quả |
| Consequence tồn tại | Learner bị kẹt lâu, miss deadline hoặc cần hỗ trợ nhiều hơn               | Phát hiện muộn gần như không tạo hậu quả      |
| Pattern có lặp      | Có nhiều case tương tự                                                    | Chỉ là trường hợp hiếm                        |

---

### 2.7. Problem Hypothesis cuối cùng

> Khi theo dõi nhiều learner cùng lúc, Lab Coach gặp khó khăn trong việc xác định sớm learner nào đang cần hỗ trợ vì không phải learner nào gặp khó khăn cũng chủ động yêu cầu giúp đỡ và các tín hiệu hiện tại có thể chỉ trở nên rõ ràng khi vấn đề đã xảy ra, dẫn đến nguy cơ learner được phát hiện và hỗ trợ muộn.

**Điều phải đúng để giả thuyết đứng vững:**

> Phải tồn tại những trường hợp thực tế mà learner gặp khó khăn nhưng Lab Coach không nhận biết đủ sớm; việc phát hiện muộn phải tạo ra hậu quả có ý nghĩa; và cách theo dõi hiện tại chưa giải quyết vấn đề đủ tốt.

**Điều có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**

> Lab Coach thường nhận biết chính xác và đủ sớm learner gặp khó khăn; learner thường chủ động yêu cầu hỗ trợ; phát hiện muộn không tạo hậu quả đáng kể; hoặc bottleneck thực tế là thiếu thời gian hỗ trợ chứ không phải thiếu visibility.

---

### 2.8. Solution Parking Lot

| Hướng giải quyết                                                      | Loại     |
| --------------------------------------------------------------------- | -------- |
| AI Support Radar phân tích tín hiệu học tập và flag learner cần chú ý | AI       |
| AI Support Prioritizer đề xuất thứ tự learner cần kiểm tra            | AI       |
| AI Check-in chủ động hỏi learner có dấu hiệu bất thường               | AI       |
| Weekly learner check-in bằng form ngắn                                | Không AI |
| Rule-based alert theo deadline, quiz, inactivity                      | Không AI |

---

## 3. Conversation Guide phiên bản cuối

### Mục tiêu

Tìm bằng chứng về việc Lab Coach có thực sự khó phát hiện learner gặp khó khăn đủ sớm hay không, đồng thời phân biệt giữa:

* Visibility Problem
* Capacity Problem

Không pitch AI Support Radar trong quá trình phỏng vấn.

### Đối tượng phỏng vấn

* 2 learners
* 1 Lab Coach

---

### Guide cho Lab Coach

#### Câu 1 — Sự kiện gần nhất

> Gần đây nhất có trường hợp nào bạn phát hiện một learner đang gặp khó khăn muộn hơn bạn mong muốn không? Bạn có thể kể lại chuyện đó từ đầu không?

Câu đào sâu:

* Lúc đầu chuyện gì xảy ra?
* Khi nào bạn bắt đầu nhận ra learner đang gặp vấn đề?
* Bạn nhận ra bằng dấu hiệu nào?
* Trước đó learner có chủ động nói với bạn không?

#### Câu 2 — Cách làm hiện tại

> Bình thường bạn làm thế nào để biết learner nào đang cần hỗ trợ?

Câu đào sâu:

* Bạn thường nhìn vào những thông tin nào?
* Bạn có phải chủ động kiểm tra từng learner không?
* Việc này mất khoảng bao nhiêu thời gian?
* Có trường hợp nào dễ bị bỏ sót không?

#### Câu 3 — Visibility hay Capacity

> Khi nhiều learner cùng gặp vấn đề, điều khó nhất với bạn là biết ai đang cần giúp hay là không đủ thời gian để hỗ trợ tất cả?

Câu đào sâu:

* Bạn quyết định ưu tiên ai trước như thế nào?
* Có lúc nào bạn biết learner đang cần giúp nhưng chưa thể hỗ trợ không?
* Có lúc nào bạn chỉ phát hiện vấn đề sau deadline hoặc sau khi điểm giảm không?

---

### Guide cho Learner

#### Câu 1

> Trong 7 ngày gần đây, có lần nào bạn bị kẹt khi học nhưng không hỏi Lab Coach hoặc mentor ngay không?

Câu đào sâu:

* Bạn đang làm gì lúc đó?
* Bạn bị kẹt ở đâu?
* Bạn đã thử tự giải quyết như thế nào?

#### Câu 2

> Tại sao lúc đó bạn không hỏi Lab Coach ngay?

Câu đào sâu:

* Bạn nghĩ mình có thể tự giải quyết được không?
* Bạn có ngại hỏi không?
* Bạn có biết chính xác mình cần hỏi gì không?

#### Câu 3

> Lab Coach cuối cùng có biết bạn đang gặp khó khăn không? Nếu có thì họ biết bằng cách nào?

Câu đào sâu:

* Họ biết sau bao lâu?
* Điều gì khiến họ nhận ra?
* Trước khi họ phát hiện, đã có dấu hiệu nào không?
* Việc được phát hiện muộn có ảnh hưởng gì không?

---

## 4. Practice Reflection

> Phần này cập nhật sau khi nhóm luyện phỏng vấn.

### 4.1. Câu hỏi nào hiệu quả nhất?

> [Điền sau buổi luyện]

Ví dụ:

> Câu “Gần đây nhất có trường hợp nào bạn phát hiện một learner gặp khó khăn muộn hơn mong muốn không?” hiệu quả vì buộc người trả lời kể lại một sự kiện thật thay vì đưa ra ý kiến chung chung.

### 4.2. Câu hỏi nào có tính dẫn dắt?

> [Điền sau buổi luyện]

Ví dụ:

> Câu “Có phải learner không chủ động hỏi nên bạn không biết họ gặp khó không?” mang tính dẫn dắt vì đã gợi sẵn nguyên nhân.

**Cách sửa:**

> “Lúc đó điều gì khiến bạn chưa nhận ra learner đang gặp khó khăn?”

### 4.3. Nhóm đã chỉnh Conversation Guide như thế nào?

> [Điền sau buổi luyện]

Ví dụ:

> Nhóm giảm các câu hỏi giả định về AI, tăng câu hỏi yêu cầu người được phỏng vấn kể lại sự kiện gần nhất và bổ sung câu hỏi phân biệt giữa thiếu visibility và thiếu capacity.

---

## 5. AI Support Log

### AI đã hỗ trợ gì?

AI được sử dụng để:

* phân rã solution directive thành chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence;
* đề xuất hai pain hypothesis cạnh tranh;
* hỗ trợ viết Problem Hypothesis;
* đề xuất các loại evidence cần tìm;
* hỗ trợ xây dựng bản nháp Conversation Guide;
* rà soát các câu hỏi có nguy cơ dẫn dắt người được phỏng vấn.

### Điểm AI còn sai hoặc hời hợt

Một số gợi ý ban đầu của AI có xu hướng:

* mặc định rằng Lab Coach chắc chắn đang phát hiện learner quá muộn;
* xem learner không chủ động hỏi là nguyên nhân chính khi chưa có evidence;
* nghiêng quá nhanh về AI Support Radar như một solution phù hợp;
* đưa ra các ví dụ phỏng vấn giả định có thể dễ bị nhầm với evidence thật.

### Nhóm đã tự sửa như thế nào?

Nhóm:

* giữ toàn bộ nội dung Chặng 1 ở mức hypothesis;
* bổ sung Hypothesis B về Capacity Problem để tránh confirmation bias;
* xác định rõ evidence có thể bác bỏ giả thuyết;
* không sử dụng các đoạn hội thoại giả định làm evidence;
* chỉnh Conversation Guide theo hướng hỏi về sự kiện và hành vi đã xảy ra thay vì hỏi ý kiến về solution;
* giữ các hướng giải pháp trong Solution Parking Lot và chưa quyết định sử dụng AI trước khi hoàn thành problem validation.

```

Còn `interview/notes.md` nên chứa **ghi chú của buổi phỏng vấn thật**: thời gian, loại người được phỏng vấn, câu chuyện họ kể, hành vi/workaround/consequence và các evidence nổi bật. `recording.m4a` là file ghi âm buổi phỏng vấn nếu người tham gia đã đồng ý cho ghi âm.
```
