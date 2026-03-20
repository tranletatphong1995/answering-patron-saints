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

- [ ] Bước 1: **Xác định vị thánh cần tìm.** Phân tích câu hỏi để biết người dùng hỏi về vị thánh nào hoặc chủ đề gì.
- [ ] Bước 2: **Tìm file tương ứng.** Sử dụng `list_dir` trên thư mục `resources/` để xem danh sách 60 file, mỗi file là 1 vị thánh, đặt tên theo format `XX-ten-vi-thanh.md`.
- [ ] Bước 3: **Đọc file.** Dùng `view_file` để đọc toàn bộ nội dung file `.md` của vị thánh đó. Mỗi file chỉ ~200–300 dòng, đọc trọn vẹn trong 1 lần.
- [ ] Bước 4: **Tổng hợp câu trả lời.** Trích xuất các ý chính phù hợp câu hỏi, trình bày rõ ràng, tôn kính.

## Hướng dẫn chi tiết

### Nguồn kiến thức
- **CHỈ ĐƯỢC PHÉP** sử dụng thông tin từ các file `.md` trong thư mục `resources/`. Tuyệt đối không tự bịa thông tin.

### Cấu trúc file
Mỗi file `.md` chứa thông tin của **1 vị thánh**, bao gồm các phần:
- **Tiêu đề**: Tên vị thánh, danh hiệu, tên Pali
- **Xuất thân**: Gia thế, quê hương
- **Quá trình xuất gia / chứng đạo**: Câu chuyện tu hành
- **Công hạnh / đức hạnh nổi bật**: Những hành động và phẩm chất đặc biệt
- **Ý nghĩa độ mệnh**: Lợi ích khi thờ kính vị thánh này
- **Thơ tụng**: Bài thơ tôn vinh (trích nguyên văn khi người dùng hỏi)

### Danh sách 60 vị thánh
Các file được đánh số từ `01` đến `60`, bao gồm:
- **01–42**: Các vị Tôn giả (nam)
- **43–54**: Các vị Tôn giả Ni (nữ)
- **55–59**: Các vị Bồ Tát
- **60**: Thiên Chủ Đế Thích

### Nguyên tắc trả lời
- **Giữ nguyên văn** các phần: Thơ tụng, Ý nghĩa độ mệnh, lời Phật dạy (trích dẫn).
- **Văn phong trang trọng, tôn kính** khi nhắc đến các bậc Thánh.
- Nếu người dùng hỏi chung (ví dụ: "ai là đệ nhất thần thông?"), hãy tìm trong nhiều file nếu cần.

## Tài nguyên liên quan

- [resources/]: 60 file Markdown, mỗi file chứa đầy đủ thông tin về 1 vị thánh độ mệnh.
