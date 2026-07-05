# FIX_NOTE

Bản này được dựng lại từ `nmattt-main.zip` gốc.

Nguyên tắc sửa:

- Giữ nguyên câu hỏi và lựa chọn theo nguồn nhiều nhất có thể.
- Không dịch lại câu hỏi sang văn phong mới.
- Chỉ sửa lỗi chính tả/OCR rõ ràng, ví dụ `SQL Injecttion` → `SQL Injection`, lựa chọn bị OCR nuốt vào câu hỏi.
- Xóa nhiễu đáp án như `-> sai`, `BẢNG ĐÁP ÁN`, `Đã chọn`, ghi chú audit.
- Không hiển thị `Thông tin kiểm tra`, `đáp án nguồn`, hoặc ghi chú rà soát trong màn làm test.
- Câu thiếu hình/OCR quá hỏng sẽ không bị đoán bừa; xem mục D trong `fix_full_original_questions.md`.

Thống kê:

- Tổng câu: 1437
- Có đáp án sau khi sửa: 1405
- Chưa đủ chắc để chấm: 32
- Sửa đáp án chắc chắn: 89
- Bổ sung/sửa đáp án từ nhóm chưa biết: 349
- Sửa OCR thủ công: 8
- Chưa tự động sửa: 32
