# Báo cáo QC v3

- Tổng câu sau QC: 1450
- Câu có đáp án: 1450
- Câu chưa có đáp án: 0
- Số thay đổi/sửa chắc chắn: 25
- Lỗi cấu trúc còn lại: 3

## Kết luận

File v2 chưa chuẩn hoàn toàn. Bản v3 đã sửa các lỗi chắc chắn có thể xử lý từ nội dung hiện có; những item còn thiếu nguồn gốc/lựa chọn đầy đủ được liệt kê ở mục cần đối chiếu thủ công.

## Các thay đổi chính

### 1. ID 450

- Lý do: Sửa trùng nhãn lựa chọn; PGP dùng mô hình web of trust.
- Câu cũ: Giao thức nào sau đây được cho là sử dụng "web tin cậy"?
- Đáp án cũ: A — PGP | IGMP
- Câu mới: Giao thức nào sau đây được cho là sử dụng "web tin cậy"?
- Đáp án mới: A — PGP

### 2. ID 455

- Lý do: Diffie-Hellman cho phép trao đổi/thỏa thuận khóa qua kênh truyền, không cần kênh ngoài băng.
- Câu cũ: Diffie-Hellman cho phép bạn làm gì?
- Đáp án cũ: D —  |  | Trao đổi khóa trong băng tần
- Câu mới: Diffie-Hellman cho phép bạn làm gì?
- Đáp án mới: B — Trao đổi khóa trong băng tần

### 3. ID 623

- Lý do: Tách lựa chọn B bị OCR dính vào A; one-time pad an toàn nhất trên lý thuyết khi dùng đúng.
- Câu cũ: Hệ mã nào sau đây có độ an toàn cao nhất trên lý thuyết
- Đáp án cũ: C — One-time pad
- Câu mới: Hệ mã nào sau đây có độ an toàn cao nhất trên lý thuyết
- Đáp án mới: C — One-time pad

### 4. ID 635

- Lý do: Câu hỏi bị OCR nhét câu dẫn vào lựa chọn A; dấu hiệu đòi tiền giải mã là ransomware.
- Câu cũ: Khi truy cập vào các tài liệu trong một thư mục trên máy tính của bạn, bạn nhận thấy tắt cä các tệp đã bị đỗi tên
thành các tên tệp ngẫu nhiên. Ngoài ra, bạn thấy một tài liệu chứa các hướng dẫn thanh toán để giải mã các tập
- Đáp án cũ: D — Ransomware
- Câu mới: Khi truy cập vào các tài liệu trong một thư mục trên máy tính của bạn, bạn nhận thấy tất cả các tệp đã bị đổi tên thành các tên tệp ngẫu nhiên. Ngoài ra, bạn thấy một tài liệu chứa các hướng dẫn thanh toán để giải mã các tệp tin. Trong trường hợp này bạn đã nhiễm mã độc nào?
- Đáp án mới: D — Ransomware

### 5. ID 637

- Lý do: Tách lựa chọn Black box bị OCR dính vào White box; có thông tin cấu hình là white-box testing.
- Câu cũ: Đâu là kiểu kiểm thử được sử dụng khi người kiểm thử được cung cắp các thông tin cầu hình cũa hệ thống?
- Đáp án cũ: A — White box
0. Black box
- Câu mới: Đâu là kiểu kiểm thử được sử dụng khi người kiểm thử được cung cấp các thông tin cấu hình của hệ thống?
- Đáp án mới: A — White box

### 6. ID 638

- Lý do: Sửa nhãn trùng và OCR H(y); không tìm được hai đầu vào cùng băm là kháng va chạm.
- Câu cũ: Không thể tìm được cặp (x.y) sao cho H(x) = HQ) là tính chất nào của hàm băm
- Đáp án cũ: C — Kháng va chạm
- Câu mới: Không thể tìm được cặp (x, y) sao cho H(x) = H(y) là tính chất nào của hàm băm?
- Đáp án mới: C — Kháng va chạm

### 7. ID 670

- Lý do: Loại lựa chọn A rỗng do OCR; mã hóa khóa công khai dùng public key để mã hóa và private key để giải mã, không suy ra private key từ public key.
- Câu cũ: Trong mã hóa dữ liệu sử dụng mật mã khóa công khai, phát biểu nào sau đây là ĐÚNG: (chọn 2 đáp
- Đáp án cũ: A, D —  | Dữ liệu được mã hóa bằng khóa công khai, giải mã bằng khóa bí mật | Từ khóa công khai không thể tìm ra khóa bí mật
- Câu mới: Trong mã hóa dữ liệu sử dụng mật mã khóa công khai, phát biểu nào sau đây là ĐÚNG: (chọn 2 đáp
- Đáp án mới: A, D — Dữ liệu được mã hóa bằng khóa công khai, giải mã bằng khóa bí mật | Từ khóa công khai không thể tìm ra khóa bí mật

### 8. ID 701

- Lý do: Sửa hai lựa chọn trùng nhãn E; hai phát biểu chắc đúng là bí mật thuộc CIA và chỉ cung cấp cho người có thẩm quyền.
- Câu cũ: Những phát biểu nào sau đây là đúng? (chọn 2 đáp án)
- Đáp án cũ: E — Để đảm bảo tính bí mật thì cần nghiêm cắm việc tạo bản sao của thông tỉn. | Để đảm bảo tính bí mật thì chỉ eung cấp thông tin cho người có thẩm quyền tiếp cận.
- Câu mới: Những phát biểu nào sau đây là đúng? (chọn 2 đáp án)
- Đáp án mới: A, F — Tính bí mật là một trong những tính chất an toàn của thông tin. | Để đảm bảo tính bí mật thì chỉ cung cấp thông tin cho người có thẩm quyền tiếp cận.

### 9. ID 722

- Lý do: NIDS phân tích lưu lượng mạng để phát hiện; ngăn chặn là IPS, còn hoạt động trên máy cá nhân là HIDS/HIPS.
- Câu cũ: Phát biểu nào sau đây đúng với NIDS?.
- Đáp án cũ: A — Các lưu lượng mạng được phân tích để tìm ra các gói tin độc hại
8. Các gói tin độc hại bị ngăn chặn
- Câu mới: Phát biểu nào sau đây đúng với NIDS?
- Đáp án mới: A — Các lưu lượng mạng được phân tích để tìm ra các gói tin độc hại

### 10. ID 741

- Lý do: Cắt bỏ OCR của câu sau bị dính vào lựa chọn D; MD5 là hàm băm dùng kiểm tra toàn vẹn trong ngữ cảnh câu hỏi.
- Câu cũ: Công nghệ nào sau đây đầm bảo tính toàn vẹn cho dữ liệu?
- Đáp án cũ: D — MD5 „ n
âu 46 Những phát biểu nào sau đây là ĐỨNG? (chọn 2 đáp án -. sn
em A. Một h chức chỉ có thể đẾ: chứng nhận đạt chuẩn ISO 27001 khi đáp ứng tất cả các yêu câu
- Câu mới: Công nghệ nào sau đây đầm bảo tính toàn vẹn cho dữ liệu?
- Đáp án mới: D — MD5

### 11. ID 765

- Lý do: Câu hỏi bị gộp vào lựa chọn A; chuyển vùng DNS bất thường liên quan DNS poisoning/zone transfer abuse theo lựa chọn có sẵn.
- Câu cũ: Bạn theo dõi và kiểm tra lưu lượng mạng hàng tuần để đảm bảo rằng mạng đang được sử
đựng đúng cách. Khi làm như vậy, bạn nhận thấy lưu lượng truy cập đến cẵng 'TCP 53 trên
máy chủ của mình từ một địa ehï IP không xác định. Sau khi xem lại nhật ký máy chủ của
- Đáp án cũ: C — DNS poisoning
- Câu mới: Bạn theo dõi và kiểm tra lưu lượng mạng hàng tuần để đảm bảo rằng mạng đang được sử dụng đúng cách. Khi làm như vậy, bạn nhận thấy lưu lượng truy cập đến cổng TCP 53 trên máy chủ của mình từ một địa chỉ IP không xác định. Sau khi xem lại nhật ký máy chủ, bạn nhận thấy nhiều lần thất bại trong việc thực hiện chuyển vùng đến máy chủ của mình. Đây là dấu hiệu của kiểu tấn công nào?
- Đáp án mới: C — DNS poisoning

### 12. ID 876

- Lý do: Tách câu hỏi về khóa riêng bị OCR gộp vào cùng item.
- Câu cũ: Phần mềm nào sau đây giúp chống lại việc thu thập thông tin cá nhân cũa người dùng?
- Đáp án cũ: C — Antispyware
- Câu mới: Phần mềm nào sau đây giúp chống lại việc thu thập thông tin cá nhân của người dùng?
- Đáp án mới: C — Antispyware

### 13. ID 1448

- Lý do: Tách từ item OCR bị gộp: Khóa riêng dùng để giải mã thông điệp nhận được và tạo chữ ký số; xác minh chữ ký dùng khóa công khai.
- Câu mới: Phát biểu nào sau đây đúng với khóa riêng của người dùng? (Chọn 2 đáp án)
- Đáp án mới: B, C — Được dùng để giải mã thông điệp nhận được | Được dùng để tạo chữ ký số

### 14. ID 900

- Lý do: Tách câu Michelangelo bị OCR gộp vào item ransomware.
- Câu cũ: Khi truy cạ
4 cä các tập đã bị đãi ta don rong một thư mục trên máy tính của bạn, bạn nhận thấy tắt
các hướng dẫn thanh toán để các tên tệp ngẫu nhiên. Ngoài ra, bạn thấy một tài liệu chứa
độc nào? oắn đề giải mã các tệp tin. Trong trường hợp này bạn đã nhiễm mã
- Đáp án cũ: D — Ransomware
Cua E. Worm
âu 20 uy phát hiện vào năm 1991, virus Michelangelo được cho là đã được kích hoạt để ghi đè
\ 10 scetor đĩa cứng đầu tiên với dữ liệu null mỗi năm vào ngày 6 tháng 3, đúng vào
ngày sinh nhật của nghệ sĩ người Ý. Miehelangelo thuộc loại virus nào? | Logic bomb
- Câu mới: Khi truy cập các tệp trong một thư mục trên máy tính của bạn, bạn nhận thấy tất cả các tệp đã bị đổi tên thành các tên tệp ngẫu nhiên. Ngoài ra, bạn thấy một tài liệu chứa các hướng dẫn thanh toán để giải mã các tệp tin. Trong trường hợp này bạn đã nhiễm mã độc nào?
- Đáp án mới: D — Ransomware

### 15. ID 1449

- Lý do: Tách từ item OCR bị gộp: Payload kích hoạt theo ngày/điều kiện là logic bomb.
- Câu mới: Được phát hiện vào năm 1991, virus Michelangelo được cho là đã được kích hoạt để ghi đè lên 100 sector đĩa cứng đầu tiên với dữ liệu null mỗi năm vào ngày 6 tháng 3, đúng vào ngày sinh nhật của nghệ sĩ người Ý. Michelangelo thuộc loại virus nào?
- Đáp án mới: D — Logic bomb

### 16. ID 969

- Lý do: Sửa hai lựa chọn trùng nhãn E; chọn hai phát biểu chắc đúng.
- Câu cũ: Những phát biểu nào sau đây là đúng? (chọn 2 đáp án)
- Đáp án cũ: A, E — Tính bí mật là một trong những tính chất an toàn của thông tin. | Để đâm bảo tính bí mật thì cằn nghiêm cấm việc tạo bản sao của thông. th | Để đảm bảo tính bí mật thì chỉ cung cấp thông tỉn cho người có thẳm quyền tiếp cận
- Câu mới: Những phát biểu nào sau đây là đúng? (chọn 2 đáp án)
- Đáp án mới: A, F — Tính bí mật là một trong những tính chất an toàn của thông tin. | Để đảm bảo tính bí mật thì chỉ cung cấp thông tin cho người có thẩm quyền tiếp cận.

### 17. ID 1175

- Lý do: Tách phần câu hỏi bị OCR thành lựa chọn C; IIS site isolation dùng application pool riêng.
- Câu cũ: 28. công ty của bạn sử dụng Microsoft IIS để lưu trữ nhiều trang web intranet trên một cụm hai nút. Allsites lưu trữ cấu hình và nội dung của họ trên ổ
- Đáp án cũ: C — và các tập tin đăng nhập được lưu trữ trên ổ D:. Allsites chia sẻ một Hồ bơi ứng dụng phổ biến. Giám đốc CNTT đã yêu cầu bạn đảm bảo rằng một trang web đơn bị tấn công sẽ không ảnh hưởng xấu đến các trang web khác đang chạy. Bạn nên làm gì? | cấu hình mỗi trang web để sử dụng hồ bơi ứng dụng riêng của mình.
- Câu mới: 28. Công ty của bạn sử dụng Microsoft IIS để lưu trữ nhiều trang web intranet trên một cụm hai nút. Tất cả các site lưu trữ cấu hình và nội dung trên ổ C: và các tập tin đăng nhập được lưu trữ trên ổ D:. Tất cả site chia sẻ một application pool phổ biến. Giám đốc CNTT yêu cầu bạn đảm bảo rằng một trang web đơn bị tấn công sẽ không ảnh hưởng xấu đến các trang web khác đang chạy. Bạn nên làm gì?
- Đáp án mới: C — Cấu hình mỗi trang web để sử dụng application pool riêng của mình.

### 18. ID 1214

- Lý do: EFS yêu cầu NTFS; câu hỏi bị OCR cắt ở ổ D:.
- Câu cũ: 27. bạn cố gắng mã hóa một thư mục trên ổ
- Đáp án cũ: A — vấn đề chuyển đổi d:/FS: NTFS lệnh.
- Câu mới: 27. Bạn cố gắng mã hóa một thư mục trên ổ D: sử dụng EFS, nhưng tùy chọn mã hóa không có sẵn. Bạn nên làm gì?
- Đáp án mới: A — Chạy lệnh convert d: /FS:NTFS.

### 19. ID 1231

- Lý do: Xóa chữ CHAPTER 8 bị dính vào lựa chọn Pulping; các phương pháp tiêu hủy/sanitization gồm đốt, shredding, degaussing, pulping.
- Câu cũ: 51. phương pháp hủy diệt dữ liệu và Media sanitization là gì? (Chọn tất cả những áp dụng.)
- Đáp án cũ: A, C, D, E — đốt cháy | Shredding | Mất Degaussing | Pulping CHAPTER 8
- Câu mới: 51. phương pháp hủy diệt dữ liệu và Media sanitization là gì? (Chọn tất cả những áp dụng.)
- Đáp án mới: A, C, D, E — Đốt cháy | Shredding | Degaussing | Pulping

### 20. ID 1329

- Lý do: Tách câu phân tích rủi ro bị OCR gộp vào cùng item; bảo vệ cửa sổ dùng cảm biến mạch kín và camera quan sát.
- Câu cũ: 22. Bạn đang xem xét các tùy chọn để bảo vệ các cửa sổ trong cơ sở của bạn. Điều nào sau đây bạn có thể xem xét?
- Đáp án cũ: C, D — Cảm biến mạch kín | Huy hiệu ID | Thời gian ngừng hoạt động của máy chủ vì mất điện | Dữ liệu hóa đơn của khách hàng bị phá hủy vì hỏa hoạn
- Câu mới: 22. Bạn đang xem xét các tùy chọn để bảo vệ các cửa sổ trong cơ sở của bạn. Điều nào sau đây bạn có thể xem xét? (Chọn hai.)
- Đáp án mới: C, E — Cảm biến mạch kín | Camera quan sát

### 21. ID 1450

- Lý do: Tách từ item OCR bị gộp: Tách câu phân tích rủi ro bị gộp từ item 1329.
- Câu mới: Câu 1. Bạn đang tiến hành phân tích rủi ro cho một công ty môi giới chứng khoán ở Miami, Florida. Những yếu tố nào nên được xem xét? (Chọn hai.)
- Đáp án mới: C, D — Thời gian ngừng hoạt động của máy chủ vì mất điện | Dữ liệu hóa đơn của khách hàng bị phá hủy vì hỏa hoạn

### 22. ID 754

- Lý do: Tách lựa chọn Trojan/Logic Bomb bị OCR dính vào lựa chọn khác.
- Câu cũ: Mã độc nào sau đây có khả năng tự nhân bản (chọn 2 đáp án)
- Đáp án cũ: A, C — Virus
| B. Trojan | Worm
- Câu mới: Mã độc nào sau đây có khả năng tự nhân bản (chọn 2 đáp án)
- Đáp án mới: A, C — Virus | Worm

### 23. ID 854

- Lý do: Tách lựa chọn Worm/Logic Bomb bị OCR dính vào lựa chọn khác.
- Câu cũ: Mã độc nào sau đây có khả năng tự nhân bản (chọn 2 đáp án)
- Đáp án cũ: A, C — Virus < | Worm < :
: D. Logic Bomb
- Câu mới: Mã độc nào sau đây có khả năng tự nhân bản (chọn 2 đáp án)
- Đáp án mới: A, C — Virus | Worm

### 24. ID 676

- Lý do: Sửa OCR FTPS/TLS và câu hỏi FTP qua SSL.
- Câu cũ: Công ty muốn sử dụng một máy chủ FTP và muốn đảm bão an toàn cho các luông dữ Hiệu F LẺ sử: ¬
dụng SSL. Lựa chọn nào sau đây nên được sử dụng:
- Đáp án cũ: A — FTPS
- Câu mới: Công ty muốn sử dụng một máy chủ FTP và muốn đảm bảo an toàn cho các luồng dữ liệu FTP sử dụng SSL. Lựa chọn nào sau đây nên được sử dụng?
- Đáp án mới: A — FTPS

### 25. ID 828

- Lý do: Sửa lựa chọn TTPS thành FTPS trong ngữ cảnh FTP dùng SSL.
- Câu cũ: Công ty muốn sử dụng một máy chủ FTP và muốn đảm bảo an toàn cho các luồng dữ liệu
FTP sử dụng SSL. Lựa chọn nào sau đây nên được sử dụng: _.
- Đáp án cũ: A — FTPS
- Câu mới: Công ty muốn sử dụng một máy chủ FTP và muốn đảm bảo an toàn cho các luồng dữ liệu
FTP sử dụng SSL. Lựa chọn nào sau đây nên được sử dụng: _.
- Đáp án mới: A — FTPS

## Item còn cần đối chiếu thủ công

- ID 1232: Item bị gộp 2 câu, chỉ còn 2 lựa chọn đều nhãn C; thiếu bảng luật/tùy chọn gốc nên chưa thể khôi phục chuẩn.
- ID 1234: Item bị gộp câu hỏi VPN concentrator với đáp án LAN B; thiếu lựa chọn gốc nên chưa thể khôi phục chuẩn.

## Lỗi cấu trúc còn lại sau QC

- ID 807: duplicate labels; labels=['A', 'B', 'C', 'B']; answer=['A']; answerText=['Theo dại lạ hấp kiểm thử thụ động;']
- ID 1232: duplicate labels; labels=['C', 'C']; answer=['C']; answerText=['LAN users can connect to external web servers. External users can use RDP to connect to LAN computers. 8. Công cụ nào sẽ cho phép bạn chụp và xem lưu lượng mạng?', 'Protocol analyzer']
- ID 1234: duplicate labels; labels=['B', 'B']; answer=['B']; answerText=['Bạn nên đặt bộ tập trung VPN ở đâu?', 'LAN B']
