# Báo cáo Phơi bày Kho lưu trữ Độc hại của Trình tạo Địa chỉ Vanity TRX

Tài liệu này nhằm mục đích công khai bằng chứng, tập trung vào các kho lưu trữ độc hại liên quan đến trình tạo địa chỉ vanity TRX/trình tạo địa chỉ vanity Tron/trình tạo địa chỉ vanity ví USDT, chứng minh rằng **Powercodess** và **Pandaoyoo** được điều khiển bởi cùng một người, thông qua nhiều kho lưu trữ phối hợp, dàn dựng "phơi bày backdoor → bôi nhọ đồng bộ → tung ra 'phiên bản sạch'". Bản chất là tấn công độc hại các dự án tạo địa chỉ vanity TRX/Tron/USDT wallet bình thường, thu hoạch niềm tin của người dùng, các kho lưu trữ liên quan có rủi ro bảo mật cực cao.

---

## ⚠️ Tuyên bố Cốt lõi

Sau khi so sánh bằng chứng từ nhiều nguồn, hai tài khoản sau và các kho lưu trữ liên quan được điều khiển bởi cùng một người, chủ yếu nhắm vào các công cụ tạo địa chỉ vanity TRX/Tron/USDT wallet. Mục đích là bôi nhọ người khác một cách độc hại, dàn dựng các sự kiện "phơi bày backdoor", sau đó quảng bá kho lưu trữ tạo địa chỉ vanity TRX tự gọi là "phiên bản sửa chữa" của chính họ, gây rủi ro đánh cắp tiền và thu hoạch lưu lượng truy cập:

- **Tài khoản 1**: Powercodess, Kho lưu trữ Liên quan: https://github.com/Powercodess/profanity-tron (Tuyên bố phơi bày backdoor của trình tạo địa chỉ vanity TRX)
- **Tài khoản 2**: Pandaoyoo, Kho lưu trữ Liên quan 1: https://github.com/Pandaoyoo/profanity-tron (Sao chép nội dung bôi nhọ); Kho lưu trữ Liên quan 2: https://github.com/Pandaoyoo/profanity-new-tron (Tự gọi là "phiên bản an toàn" của trình tạo địa chỉ vanity TRX/Tron/USDT wallet)

---

## 📅 Dòng thời gian Chính (Cập nhật Đồng bộ, Bằng chứng Cùng một Người)

| Thời gian | Tài khoản | Hoạt động Kho lưu trữ | Hành vi Cốt lõi (Liên quan đến Trình tạo Địa chỉ Vanity TRX) |
|-----------|-----------|----------------------|---------------------------------------------------------------|
| Thời gian không rõ (trước 2026.04.25) | Powercodess | https://github.com/Powercodess/profanity-tron | Xuất bản "báo cáo kiểm toán bằng chứng chắc chắn backdoor-đánh cắp-u của profanity-tron", tuyên bố các kho lưu trữ trình tạo địa chỉ vanity TRX/Tron liên quan có backdoor như rò rỉ khóa riêng |

<p align="center">
  <img width="100%" src="/1.png?raw=true"/>
</p>

| Thời gian | Tài khoản | Hoạt động Kho lưu trữ | Hành vi Cốt lõi (Liên quan đến Trình tạo Địa chỉ Vanity TRX) |
|-----------|-----------|----------------------|---------------------------------------------------------------|
| Đồng bộ với thời gian trên | Pandaoyoo | https://github.com/Pandaoyoo/profanity-tron | Sao chép 1:1 báo cáo kiểm toán của Powercodess, với nội dung, định dạng, số dòng mã, liên kết bằng chứng hoàn toàn giống hệt, không có sửa đổi nào, mở rộng phạm vi bôi nhọ "backdoor" của trình tạo địa chỉ vanity TRX |

| Thời gian | Tài khoản | Hoạt động Kho lưu trữ | Hành vi Cốt lõi (Liên quan đến Trình tạo Địa chỉ Vanity TRX) |
|-----------|-----------|----------------------|---------------------------------------------------------------|
| 2026-05-01 21:00:00 | Pandaoyoo | https://github.com/Pandaoyoo/profanity-new-tron | Tải lên hàng loạt toàn bộ mã nguồn, tuyên bố "sửa backdoor, loại bỏ mã độc ẩn", tung ra trình tạo địa chỉ vanity TRX/Tron/USDT wallet tự gọi là an toàn, tạo liên kết đồng bộ với hai kho lưu trữ trước |

<p align="center">
  <img width="100%" src="/2.png?raw=true"/>
</p>

| Thời gian | Tài khoản | Hoạt động Kho lưu trữ | Hành vi Cốt lõi (Liên quan đến Trình tạo Địa chỉ Vanity TRX) |
|-----------|-----------|----------------------|---------------------------------------------------------------|
| 2026-04-25 | Powercodess (Chuyển tài khoản) | https://github.com/GenTronx/gpu | Powercodess xóa kho lưu trữ và chuyển tài khoản để tránh rủi ro, Pandaoyoo đồng bộ các hoạt động tiếp theo, duy trì hoạt động kho lưu trữ trình tạo địa chỉ vanity TRX độc hại, tạo chuỗi kiểm soát hoàn chỉnh |

---

## 🔍 Chuỗi Bằng chứng Cốt lõi (Bằng chứng Cùng một Người Điều khiển, Liên quan đến Trình tạo Địa chỉ Vanity TRX)

### Bằng chứng 1: Sao chép 1:1 Báo cáo Kiểm toán, Không phải Kiểm toán Độc lập, Hoàn toàn Bôi nhọ Trình tạo Địa chỉ Vanity TRX

Báo cáo kiểm toán trong kho lưu trữ Pandaoyoo/profanity-tron hoàn toàn giống hệt với báo cáo từ Powercodess/profanity-tron, cả hai đều xoay quanh trình tạo địa chỉ vanity TRX/Tron/USDT wallet, bao gồm nhưng không giới hạn:

- **Kết luận Cốt lõi**: "Mã nguồn trình tạo địa chỉ vanity TRX chứa logic rò rỉ khóa riêng + địa chỉ, tham số ẩn, tắt xác minh TLS"
- **Chi tiết Mã**: Vị trí hàm `postResult(privateKey, address, postUrl)` (Dispatcher.cpp:L378-L403), đoạn mã cốt lõi, chú thích số dòng đều chỉ vào logic liên quan đến tạo địa chỉ vanity TRX
- **Tham số Ẩn**: Quá trình xây dựng làm rối của `pptt` (profanity.cpp:L163-L166), giải thích tham số ngắn `-p`, dùng để kiểm soát rò rỉ khóa riêng khi tạo địa chỉ vanity TRX
- **Bằng chứng Hỗ trợ**: Liên kết phân tích Kanxue (https://bbs.kanxue.com/thread-289060.htm), hồ sơ chuyển tài khoản, giữ chỗ hình ảnh hoàn toàn giống hệt, dùng để hỗ trợ "backdoor" trong trình tạo địa chỉ vanity TRX

**Kết luận**: Pandaoyoo không tiến hành bất kỳ kiểm toán độc lập nào, chỉ sao chép và dán báo cáo của Powercodess, nhằm mở rộng phạm vi bôi nhọ các dự án tạo địa chỉ vanity TRX/Tron/USDT wallet bình thường, tạo ảo tưởng "nhiều người cung cấp bằng chứng chắc chắn".

### Bằng chứng 2: Nhịp Cập nhật Đồng bộ, Phân công Rõ ràng, Thu hút Lưu lượng truy cập Xung quanh Trình tạo Địa chỉ Vanity TRX

- Powercodess chịu trách nhiệm "xuất bản đầu tiên" báo cáo kiểm toán backdoor trình tạo địa chỉ vanity TRX, đóng vai "người phơi bày công lý", hướng dẫn người dùng đặt câu hỏi về các dự án bình thường;
- Pandaoyoo chịu trách nhiệm "chuyển tiếp đồng bộ" báo cáo, củng cố ấn tượng tiêu cực "backdoor" của trình tạo địa chỉ vanity TRX, đồng thời tung ra kho lưu trữ "profanity-new-tron", tự gọi là "phiên bản an toàn" của trình tạo địa chỉ vanity TRX/Tron/USDT wallet, thu hoạch người dùng bị dẫn dắt sai;
- Sau khi Powercodess xóa kho lưu trữ và chuyển tài khoản (GenTronx), Pandaoyoo đồng bộ duy trì hoạt động kho lưu trữ liên quan, tạo vòng khép kín hoàn chỉnh "phơi bày và bôi nhọ trình tạo địa chỉ vanity TRX → chuyển hướng lưu lượng đến dự án của mình".

### Bằng chứng 3: Mâu thuẫn Logic Hành vi, Dấu hiệu Dàn dựng Rõ ràng, Kiếm lời từ Trình tạo Địa chỉ Vanity TRX

Nếu Pandaoyoo thực sự là "người khôi phục công lý", tại sao không độc lập xuất bản báo cáo kiểm toán cho trình tạo địa chỉ vanity TRX/Tron/USDT wallet, mà lại sao chép hoàn toàn nội dung của Powercodess? Tại sao ngay lập tức tung ra "phiên bản sửa chữa" trình tạo địa chỉ vanity TRX sau khi Powercodess phơi bày "backdoor"?

**Lỗ hổng Logic Cốt lõi**: Đầu tiên bôi nhọ các dự án tạo địa chỉ vanity TRX bình thường qua Powercodess → sau đó mở rộng ảnh hưởng qua Pandaoyoo sao chép báo cáo → cuối cùng tung ra "phiên bản sửa chữa" để thu hoạch lưu lượng truy cập. Bản chất là "kẻ cắp kêu bắt kẻ cắp", tự dàn dựng một kế hoạch tấn công đối thủ và kiếm lời từ các công cụ tạo địa chỉ vanity TRX/Tron/USDT wallet.

### Bằng chứng 4: Bằng chứng Chắc chắn về Backdoor trong Phiên bản Phát hành [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) (Xác nhận Điều khiển Từ xa C2)

Thông qua phân tích kỹ thuật đảo ngược tệp nhị phân `tron_vanity.exe` được xuất bản trong kho lưu trữ [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/), đã xác nhận rằng tệp thực thi chứa backdoor độc hại đánh cắp khóa riêng được tạo và gửi chúng đến máy chủ C2 từ xa. **Mã nguồn của kho lưu trữ không chứa logic backdoor này; backdoor được tiêm vào lúc biên dịch**, đây là kỹ thuật tấn công cổ điển "mã nguồn sạch, nhị phân độc".

**Địa chỉ Rò rỉ C2**: `https://dns.telemetrymicrosof.com/report.php` (Tưởng dùng Cloudflare là tôi không tìm thấy IP của anh à? IP backdoor C2 tương ứng: `45.128.12.32`)

Tên miền này giả mạo dịch vụ đo lường từ xa của Microsoft:
- `telemetrymicrosof.com` được viết sai cố ý (thiếu một chữ `t`), ngụy trang thành `telemetrymicrosoft.com`
- Sử dụng tiền tố tên miền phụ `dns.` để ngụy trang thêm thành dịch vụ đo lường từ xa Microsoft hợp pháp

**Cơ chế Giao tiếp Backdoor**:
- Thư viện Mạng: WinHTTP (WINHTTP.dll)
- Phương thức HTTP: POST
- User-Agent: `tron-vanity/1.0` (ký tự rộng/UTF-16LE)
- Content-Type: `application/json`

**Tiêu đề Xác thực Tùy chỉnh (tất cả ký tự rộng)**:

| Tiêu đề | Mục đích |
|---------|----------|
| X-Auth-Signature | Chữ ký HMAC-SHA256 |
| X-Auth-Timestamp | Dấu thời gian yêu cầu |
| X-Auth-Nonce | Số ngẫu nhiên (chống phát lại) |
| X-Auth-Token | Mã xác thực |

**Dữ liệu Bị đánh cắp (định dạng JSON)**:
```json
{"address":"<Địa chỉ Tron>","private":"<Khóa riêng>","score":<Điểm>,"seconds":<Thời gian>}
```

Backdoor gửi địa chỉ Tron được tạo và khóa riêng tương ứng đến máy chủ của kẻ tấn công! Khi kẻ tấn công có được khóa riêng, họ có thể kiểm soát hoàn toàn tất cả tài sản dưới địa chỉ đó.

**Danh sách Hàm Backdoor (không tồn tại trong mã nguồn, được tiêm lúc biên dịch)**:

| Tên Hàm | Mục đích |
|---------|----------|
| `sendReportLocalhost(std::string const&, std::string const&, int, long long)` | Gửi dữ liệu khóa riêng đến máy chủ C2 |
| `localAuth()` | Tạo thông tin xác thực cục bộ |
| `initLocalhostAuth()` | Khởi tạo cơ chế xác thực |
| `hmacSha256Hex(std::vector<unsigned char> const&, std::string const&)` | Tạo chữ ký HMAC-SHA256 |

**API liên quan đến Mật mã (BCrypt)**:
- `BCryptOpenAlgorithmProvider` / `BCryptCreateHash` / `BCryptHashData` / `BCryptFinishHash` → Tính toán HMAC
- `BCryptGenRandom` → Tạo Nonce ngẫu nhiên

**Định danh Backdoor Khác**:
Tại offset nhị phân `0x2B38`, phát hiện tên tham số tiêu đề HTTP được xây dựng `tron-vanity-session-key`, được lắp ráp từ ba đoạn: `tron-van` + `ity-sess` + `ion-key` (lắp ráp trên stack lúc chạy để tránh phát hiện tĩnh).

**Tóm tắt Kỹ thuật Backdoor**:

| Mục | Chi tiết |
|-----|----------|
| Máy chủ C2 | `dns.telemetrymicrosof.com` |
| Đường dẫn Backdoor | `/report.php` |
| URL Đầy đủ | `https://dns.telemetrymicrosof.com/report.php` |
| Dữ liệu Đánh cắp | Địa chỉ Tron + Khóa riêng + Điểm + Thời gian |
| Phương thức Giao tiếp | HTTPS POST (WinHTTP), định dạng JSON |
| Phương thức Xác thực | Chữ ký HMAC-SHA256 + Dấu thời gian + Nonce + Token |
| Kỹ thuật Ngụy trang | Tên miền mạo danh đo lường từ xa Microsoft, nối chuỗi trên stack để tránh phát hiện |

🚨 **Điều này trực tiếp xác nhận rằng kho lưu trữ "phiên bản an toàn" của [Pandaoyoo/profanity-new-tron](https://github.com/Pandaoyoo/profanity-new-tron/) thực sự đã cài đặt backdoor điều khiển từ xa C2 tinh vi hơn bản gốc. Mã nguồn được công khai nhưng tệp nhị phân đã biên dịch bị giả mạo — kỹ thuật tấn công cổ điển "mã nguồn sạch, nhị phân độc". Nếu bạn đã sử dụng chương trình này để tạo địa chỉ, vui lòng chuyển tài sản sang địa chỉ an toàn mới ngay lập tức, vì khóa riêng có thể đã bị rò rỉ cho kẻ tấn công.**

⚠️ **Cảnh báo Truy vết**: Truy vết được đến địa chỉ C2 thì sẽ tìm được người của anh. Hãy tận hưởng thời gian tự do bên ngoài đi, thời gian không còn nhiều đâu, hãy trân trọng. Tưởng anh là tổ chức APT lớn nào chứ, hihi, em bé kỹ thuật của anh thật sự không đến đâu!

---

## ⚠️ Cảnh báo Rủi ro Bảo mật cho Các Kho lưu trữ Liên quan đến Trình tạo Địa chỉ Vanity TRX

Dù là Powercodess hay Pandaoyoo, các kho lưu trữ trình tạo địa chỉ vanity TRX/Tron/USDT wallet liên quan đều có rủi ro bảo mật cực cao. Vui lòng không sử dụng:

1. **Powercodess/profanity-tron**: Tuyên bố trình tạo địa chỉ vanity TRX có backdoor (rò rỉ khóa riêng, tham số ẩn, tắt xác minh TLS), ngay cả khi nội dung báo cáo là thật, có thể đã được cài đặt bởi chính họ;
2. **Pandaoyoo/profanity-tron**: Công cụ bôi nhọ thuần túy, không có chức năng tạo địa chỉ vanity TRX thực tế, chỉ dùng để bôi nhọ các dự án bình thường, và liên kết cao với các tài khoản độc hại;
3. **Pandaoyoo/profanity-new-tron**: Tự gọi là "sửa backdoor" của trình tạo địa chỉ vanity TRX/Tron/USDT wallet, nhưng không cung cấp bằng chứng kiểm toán bảo mật bên thứ ba, không thể loại trừ khả năng cài đặt backdoor theo cách khác, và thời gian phát hành đồng bộ với hoạt động bôi nhọ, động cơ không trong sáng.

---

## 🔧 Khuyến nghị Bảo mật (Dành cho Người sử dụng Công cụ Tạo Địa chỉ Vanity TRX/Tron/USDT Wallet)

- ⛔ Ngay lập tức ngừng sử dụng tất cả trình tạo địa chỉ vanity TRX/Tron/USDT wallet và công cụ liên quan liên quan đến Powercodess, Pandaoyoo, GenTronx;
- 💰 Nếu bạn đã sử dụng các công cụ trên để tạo khóa riêng (cho ví TRX/USDT), khuyến nghị ngay lập tức chuyển tài sản từ các địa chỉ tương ứng để tránh đánh cắp tiền do rò rỉ khóa riêng;
- ✅ Khi chọn công cụ tạo địa chỉ vanity TRX/Tron/USDT wallet, ưu tiên các dự án hợp pháp đã qua kiểm toán bảo mật bên thứ ba, có uy tín tốt trong cộng đồng, và là mã nguồn mở có thể truy xuất. Đừng tin các công cụ tuyên bố "tạo nhanh, tăng tốc GPU" mà không có bằng chứng kiểm toán.

---

## 📌 Hướng dẫn Báo cáo/Bảo vệ Quyền

Tất cả bằng chứng trong tài liệu này đến từ các kho lưu trữ GitHub công khai, tập trung vào các kho lưu trữ độc hại liên quan đến trình tạo địa chỉ vanity TRX/Tron/USDT wallet, có thể trực tiếp dùng làm cơ sở báo cáo. Hướng báo cáo:

- **GitHub Chính thức**: Báo cáo tài khoản Powercodess, Pandaoyoo bôi nhọ độc hại các dự án tạo địa chỉ vanity TRX bình thường, quảng cáo sai sự thật, tự dàn dựng;
- **Cộng đồng Liên quan (Cộng đồng liên quan đến TRX/USDT)**: Chuyển tiếp bằng chứng này để nhắc nhở người dùng công cụ tạo địa chỉ vanity TRX/Tron/USDT wallet khác tránh rủi ro và không bị dẫn dắt sai.

---

## 📎 Tóm tắt Liên kết Bằng chứng (Có thể Nhấp trực tiếp để Xác minh, Tất cả Liên quan đến Trình tạo Địa chỉ Vanity TRX)

1. **Kho lưu trữ Bôi nhọ Trình tạo Địa chỉ Vanity TRX của Powercodess**: https://github.com/Powercodess/profanity-tron

<p align="center">
  <img width="100%" src="/3.png?raw=true"/>
</p>

2. **Kho lưu trữ Bôi nhọ Sao chép của Pandaoyoo**: https://github.com/Pandaoyoo/profanity-tron

<p align="center">
  <img width="100%" src="/4.png?raw=true"/>
</p>

3. **Kho lưu trữ Trình tạo Địa chỉ Vanity TRX được gọi là "Phiên bản An toàn" của Pandaoyoo**: https://github.com/Pandaoyoo/profanity-new-tron

<p align="center">
  <img width="100%" src="/5.png?raw=true"/>
</p>

4. **Kho lưu trữ sau khi Powercodess Xóa Kho lưu trữ và Chuyển Tài khoản**: https://github.com/GenTronx/gpu (Phân tích trang web thất bại, đây là địa chỉ chuyển tài khoản được Powercodess tuyên bố chính thức)

5. **Liên kết Phân tích Kanxue (Được trích dẫn trong Báo cáo Kiểm toán, Liên quan đến Backdoor Trình tạo Địa chỉ Vanity TRX)**: https://bbs.kanxue.com/thread-289060.htm (Xuất bản năm 2025, xác nhận sự tồn tại của backdoor trình tạo địa chỉ vanity TRX, nhưng không liên quan đến sự kiện tự dàn dựng này)

6. **Bằng chứng Tấn công Độc hại Kho lưu trữ Bình thường**: https://github.com/ninazero/tron

   ⚠️ **Thông báo Quan trọng**: Kho lưu trữ này là một dự án mã nguồn mở hoàn toàn độc lập, hợp pháp và tuân thủ. Sau khi kiểm toán xác nhận, kho lưu trữ này **HOÀN TOÀN KHÔNG LIÊN QUAN** đến sự kiện tự dàn dựng và bôi nhọ của Powercodess/Pandaoyoo đã nêu ở trên. Kho lưu trữ này là nạn nhân vô tội bị tấn công, KHÔNG PHẢI người tham gia. Các tài khoản độc hại đã tiến hành các hành vi tấn công như tăng sao giả lên kho lưu trữ bình thường này (xem bằng chứng trong hình bên dưới), cố gắng phá hoại uy tín của nó. Tất cả các tài khoản được sử dụng đều là tài khoản zombie hoạt động thấp với dấu hiệu hoạt động rõ ràng, vi phạm nghiêm trọng các nguyên tắc cộng đồng mã nguồn mở. Theo truy xuất kỹ thuật, kẻ tấn công nằm ở khu vực Anhui, và các hoạt động bất hợp pháp như vậy cuối cùng sẽ phải đối mặt với các biện pháp trừng phạt theo pháp luật.

<p align="center">
  <img width="100%" src="/6.png?raw=true"/>
</p>

7. **Bằng chứng Tăng Sao Giả Độc hại của Powercodess**: https://github.com/Powercodess/profanity-tron - Kho lưu trữ này sử dụng số lượng lớn tài khoản zombie để tăng sao giả độc hại nhằm tạo ra sự phổ biến giả mạo. Mục đích là bôi nhọ các dự án tạo địa chỉ vanity TRX bình thường, tạo ảo tưởng "nhiều người cung cấp bằng chứng chắc chắn" cho vở kịch "phơi bày backdoor" tự dàn dựng, cuối cùng chuyển hướng lưu lượng đến kho lưu trữ "phiên bản sửa chữa" do họ kiểm soát để thu hoạch người dùng.

8. **Bằng chứng Phơi bày Dấu trang Trình duyệt**: Thông qua phân tích dấu trang trình duyệt, có thể thấy người vận hành đã tham gia vào các hoạt động ngành xám-đen trong thời gian dài, nhưng lại giả mạo nhân viên kiểm toán bảo mật để quảng cáo sai sự thật, cố gắng sử dụng "công lý" làm lớp vỏ để thực hiện lừa đảo. Hành vi của họ hoàn toàn là một vở kịch tự dàn dựng, về bản chất là sử dụng "kiểm toán" làm cái cớ cho "thu hút và thu hoạch lưu lượng truy cập". Theo truy xuất kỹ thuật, người này nằm ở khu vực Anhui, và các hoạt động bất hợp pháp của họ đã được ghi lại, các cơ quan thực thi pháp luật liên quan sẽ xử lý theo pháp luật.

<p align="center">
  <img width="100%" src="/7.png?raw=true"/>
</p>

---

**Cập nhật lần cuối**: 2026-05-01 (Đồng bộ với thời gian phát hành Pandaoyoo/profanity-new-tron, hỗ trợ mối quan hệ liên kết)

---

## 🌐 Phiên bản Đa ngôn ngữ

- [中文](README.md)
- [English](README_EN.md)
- [ภาษาไทย](README_TH.md)
- [Tiếng Việt](README_VI.md)
- [日本語](README_JA.md)
- [हिन्दी](README_HI.md)
- [한국어](README_KO.md)
- [Español](README_ES.md)
- [Français](README_FR.md)
- [Deutsch](README_DE.md)
- [Русский](README_RU.md)
- [Português](README_PT.md)
- [العربية](README_AR.md)
