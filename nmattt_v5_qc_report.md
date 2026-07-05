# Báo cáo rà soát nmattt v5
## Tóm tắt
- Tổng câu hỏi: 1447
- Câu có đáp án hợp lệ: 1447
- Câu còn bị gắn cờ cần rà soát trong file: 0
- Số câu có thay đổi dữ liệu câu hỏi/đáp án/answerText: 615
- Số câu sửa thủ công do OCR làm mất/ghép lựa chọn hoặc đáp án sai: 93
- Phạm vi chỉnh sửa: chỉ thay nội dung JSON `quizData`; phần HTML/CSS/JS giao diện bên ngoài giữ nguyên byte-for-byte.

## Các nhóm lỗi đã xử lý
- Sửa OCR thuật ngữ: `HFTPS` → `HTTPS`, `Publie key` → `Public key`, `IPSee` → `IPSec`, `Disk eneryption/Disl: encryption` → `Disk encryption`, `lỗ hông/lỗ hỗng` → `lỗ hổng`, v.v.
- Tách lại đáp án bị dính note/chữ chương/câu kế tiếp: ví dụ ID 1035, 1085, 1324, 1391.
- Khôi phục các lựa chọn bị OCR nuốt mất: ID 636, 644, 651, 708, 739, 852, 889, 1172, 1298, 1324.
- Sửa các đáp án bị highlight sai do OCR ghép lựa chọn: ID 739, 764, 769/796/920/938 nhóm ISO 27001, 1298.

## Các câu thay đổi thủ công tiêu biểu
- ID 610: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 612: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 618: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 624: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 631: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 636: restore corrupted public-key cryptography question | Đáp án: A, D → Dữ liệu được mã hóa bằng khóa công khai, giải mã bằng khóa bí mật; Từ khóa công khai không thể tìm ra khóa bí mật
- ID 640: canonical SSL port question cleanup | Đáp án: A → 443
- ID 642: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 644: restore hash property question | Đáp án: B → Kháng tiền ảnh
- ID 645: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 649: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 651: restore lost option A and clean botnet OCR | Đáp án: B → Botnet
- ID 659: restore lost option A and clean botnet OCR | Đáp án: B → Botnet
- ID 666: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 667: restore merged multi-answer security definition question | Đáp án: A, B → An toàn thông tin là bảo vệ thông tin và hệ thống thông tin trước tấn công của tin tặc, bao gồm cả những nhóm tin tặc được hậu thuẫn bởi các chính phủ.; An toàn thông tin bao gồm việc đảm bảo hoạt động ổn định của hệ thống thông tin trước khả năng xảy ra sự cố vật lý.
- ID 680: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 681: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 688: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 695: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 700: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 706: canonical SSL port question cleanup | Đáp án: A → 443
- ID 707: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 708: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 716: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 724: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 728: restore merged multi-answer security definition question | Đáp án: A, B → An toàn thông tin là bảo vệ thông tin và hệ thống thông tin trước tấn công của tin tặc, bao gồm cả những nhóm tin tặc được hậu thuẫn bởi các chính phủ.; An toàn thông tin bao gồm việc đảm bảo hoạt động ổn định của hệ thống thông tin trước khả năng xảy ra sự cố vật lý.
- ID 733: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 736: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 739: canonical vulnerability scanner cleanup | Đáp án: C → Công cụ quét lỗ hổng
- ID 744: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 746: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 755: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 761: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 764: canonical anti-spam cleanup | Đáp án: A → Anti-spam
- ID 767: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 768: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 769: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 777: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 778: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 782: canonical SSL port question cleanup | Đáp án: A → 443
- ID 784: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 796: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 798: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 803: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 812: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 815: clean account audit OCR | Đáp án: C → Kiểm toán tài khoản người dùng
- ID 821: canonical SSL port question cleanup | Đáp án: A → 443
- ID 828: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 830: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 831: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 835: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 846: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 852: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 859: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 862: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 872: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 873: restore merged multi-answer security definition question | Đáp án: A, B → An toàn thông tin là bảo vệ thông tin và hệ thống thông tin trước tấn công của tin tặc, bao gồm cả những nhóm tin tặc được hậu thuẫn bởi các chính phủ.; An toàn thông tin bao gồm việc đảm bảo hoạt động ổn định của hệ thống thông tin trước khả năng xảy ra sự cố vật lý.
- ID 874: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 875: canonical SSL port question cleanup | Đáp án: A → 443
- ID 879: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 882: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 886: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 889: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 901: canonical SSL port question cleanup | Đáp án: A → 443
- ID 908: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 916: canonical vulnerability scanner cleanup | Đáp án: C → Công cụ quét lỗ hổng
- ID 917: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 920: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 921: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 924: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 926: canonical data leakage cleanup | Đáp án: B, C, E → Các ứng dụng mạng xã hội trên điện thoại di động; Email; Ứng dụng đọc file PDF
- ID 933: restore merged multi-answer security definition question | Đáp án: A, B → An toàn thông tin là bảo vệ thông tin và hệ thống thông tin trước tấn công của tin tặc, bao gồm cả những nhóm tin tặc được hậu thuẫn bởi các chính phủ.; An toàn thông tin bao gồm việc đảm bảo hoạt động ổn định của hệ thống thông tin trước khả năng xảy ra sự cố vật lý.
- ID 938: restore ISO 27001 duplicate to clean canonical wording | Đáp án: C → ISO 27001 là một tiêu chuẩn xác định các yêu cầu đối với hệ thống quản lý an toàn thông tin
- ID 940: canonical MAC cleanup | Đáp án: A, C → Đảm bảo tính xác thực; Đảm bảo tính toàn vẹn
- ID 943: canonical Trojan horse cleanup | Đáp án: A → Là một chương trình được thiết kế để tấn công hệ thống máy tính trong khi vẫn thực hiện các hành động có vẻ không gây hại
- ID 944: canonical FTPS over SSL cleanup | Đáp án: A → FTPS
- ID 956: canonical PKI encryption key cleanup | Đáp án: B → Public key của An
- ID 959: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số
- ID 964: canonical access sequence cleanup | Đáp án: C → Định danh → Xác thực → Cấp quyền
- ID 965: canonical confidentiality answer cleanup | Đáp án: B → Disk encryption
- ID 1035: split merged option; TCP 443 is HTTPS | Đáp án: C → HTTPS
- ID 1085: split merged MFA authentication options | Đáp án: B → Sử dụng tên người dùng, mật khẩu và thẻ mã thông báo để kết nối với VPN công ty
- ID 1149: clean mojibake PBX question | Đáp án: B → PBX
- ID 1168: split merged choices; cleaned OCR | Đáp án: B → Xu hướng
- ID 1172: split merged choices; 802.1x is network access authentication | Đáp án: C → IEEE 802.1x
- ID 1178: HTTPS OCR repair | Đáp án: D → Sử dụng HTTPS với PKI.
- ID 1182: fixed mixed English/Vietnamese OCR | Đáp án: A → Sử dụng JavaScript cho xác nhận dữ liệu phía server.
- ID 1270: remove OCR tail from ACL question | Đáp án: B → ACL
- ID 1298: restored missing option D and corrected answer | Đáp án: D → Cài đặt chứng chỉ gốc tin cậy trong trình duyệt của máy khách cho tổ chức phát hành chứng chỉ máy chủ mạng nội bộ.
- ID 1324: split merged server-room options from source | Đáp án: F → Giữ nguyên trần thả hiện có
- ID 1391: remove trailing question marker in option D | Đáp án: B, C → Các tập tin có thể được phục hồi.; Các tệp đã xóa chứa tất cả dữ liệu gốc của chúng cho đến khi đĩa cứng chứa đầy dữ liệu khác.
- ID 1425: clean wording and chapter note | Đáp án: D → nslookup
- ID 1448: canonical private key usage cleanup | Đáp án: B, C → Được dùng để giải mã thông điệp nhận được; Được dùng để tạo chữ ký số

## Kiểm tra sau khi xuất file
- Answer label hợp lệ / không trỏ vào lựa chọn thiếu: Đạt
- Các pattern lỗi nặng còn sót trong HTML:  Câu
- UI ngoài JSON giữ nguyên: Đạt

## Bổ sung sau kiểm tra ký tự lạ
- Sửa thêm 9 câu có ký tự OCR sót hoặc đáp án bị sai/mất lựa chọn: 354, 355, 698, 720, 819, 849, 861, 941, 952
- Ký tự OCR lạ còn lại theo bộ lọc: Không phát hiện

## Bổ sung rà soát nhóm OCR nặng
- Sửa thêm 48 lượt ở các nhóm còn dễ gây hiểu sai: phishing, anti-spyware, HIDS, ACL, mã hóa đối xứng, MD5/toàn vẹn, phát biểu về bí mật/ATTT.
- ID đã chỉnh: 605, 661, 701, 793, 897, 969, 756, 884, 621, 788, 665, 861, 628, 668, 709, 825, 617, 689, 781, 864, 885, 947, 646, 692, 742, 783, 837, 867, 935, 630, 674, 718, 752, 792, 845, 907, 648, 809, 1047, 653, 757, 818, 881, 904, 972, 808, 824, 832
- Lựa chọn còn nghi bị dính nhãn A./B./C.: Không phát hiện
- Ký tự OCR lạ còn lại: Không phát hiện

## Bổ sung dọn note và chính tả OCR còn sót
- Sửa thêm 21 lượt ở các nhóm Michelangelo, vét cạn mật khẩu, NIDS, ví dụ tính bí mật và các câu có note nội bộ.
- ID đã chỉnh: 673, 775, 814, 948, 339, 616, 686, 730, 787, 805, 841, 963, 643, 848, 939, 633, 747, 855, 914, 592, 1128
- Note/pattern nặng còn lại: Không phát hiện
- Ký tự OCR lạ còn lại: Không phát hiện
