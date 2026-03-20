---
name: answering-patron-saints
description: Skill dùng để trả lời các câu hỏi về kiến thức, sự tích, hạnh nguyện và ý nghĩa độ mệnh của 60 vị thánh độ mệnh dựa trên tài liệu được cung cấp.
---

# Trả Lời Kiến Thức Về 60 Vị Thánh Độ Mệnh

## Khi nào nên dùng skill này

- Khi người dùng muốn biết thông tin về một vị thánh độ mệnh cụ thể (ví dụ: Tôn giả Xá Lợi Phất, Mục Kiền Liên,...).
- Khi người dùng hỏi về ý nghĩa độ mệnh của các vị thánh.
- Khi người dùng thắc mắc về các câu chuyện, sự tích, hoặc thơ tụng liên quan đến 60 vị thánh này.
- Khi người dùng nhắc đến: `thánh độ mệnh`, `vị thánh độ mệnh`, hoặc tên của các vị A La Hán, Bồ Tát trong danh sách 60 vị.

## Quy trình làm việc

- [ ] Bước 1: **Xác định thông tin cần tìm kiếm.** Phân tích câu hỏi của người dùng để biết họ đang hỏi về vị thánh nào hoặc chủ đề gì (sự tích, ý nghĩa độ mệnh, thơ tụng).
- [ ] Bước 2: **Đọc tài liệu.** Sử dụng tool `grep_search` hoặc `view_file` để tìm kiếm và đọc thông tin từ file `resources/knowledge.md` nằm trong thư mục của skill này.
- [ ] Bước 3: **Tổng hợp câu trả lời.** Dựa trên thông tin nguyên gốc trong tài liệu, trích xuất các ý chính để trả lời câu hỏi của người dùng một cách chính xác, đầy đủ và súc tích.
- [ ] Bước 4: **Trình bày.** Format câu trả lời rõ ràng (sử dụng bullet points, in đậm chú thích) và đảm bảo văn phong trang trọng, tôn kính khi nhắc đến các bậc Thánh.

## Hướng dẫn chi tiết

- **Nguồn kiến thức duy nhất:** Bạn CHỈ ĐƯỢC PHÉP sử dụng thông tin từ file `.agent/skills/answering-patron-saints/resources/knowledge.md` để trả lời các câu hỏi về 60 vị thánh độ mệnh. Tuyệt đối không tự bịa thông tin hoặc lấy từ các nguồn không chính thống khác.
- **Cách tìm kiếm:** File `knowledge.md` chứa thông tin của cả 60 vị thánh, được phân chia bằng các header `## [Số thứ tự]. [Tên vị thánh]`. Hãy dùng công cụ tìm kiếm (`grep_search`) theo tên vị thánh để tìm đoạn văn bản có chứa thông tin đó, sau đó dùng lệnh `view_file` ở các dòng xung quanh để đọc toàn bộ phần cần thiết.
- **Cấu trúc thông tin của mỗi vị thánh:** Thông thường mỗi vị thánh sẽ có các phần: Tiêu đề, Xuất thân, Quá trình chứng đạo / hạnh nguyện, Ý nghĩa độ mệnh, và Thơ tụng. Hãy khoanh vùng thông tin cần thiết tùy theo câu hỏi của người dùng.
- **Giữ nguyên văn những nội dung quan trọng:** Đối với **Thơ tụng** hoặc **Ý nghĩa độ mệnh**, hãy trích dẫn nguyên văn để giữ đúng ý nghĩa tâm linh và sự tôn kính.

## Tài nguyên liên quan

- [resources/knowledge.md]: Chứa toàn bộ nội dung chi tiết về 60 vị thánh độ mệnh được trích xuất từ các file Word gốc do người dùng cung cấp.
