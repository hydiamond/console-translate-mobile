# Phụ đề trên TV LG · LG TV (webOS)

Dùng được với TV LG chạy webOS. Có hai cách: **không cần cài** (trình duyệt của TV) hoặc **cài app lên TV** từ điện thoại.

*Works with LG TVs running webOS: either the TV's web browser (nothing to install) or the TV app installed from your phone.*

## Cách 1: Không cần cài (trình duyệt TV)

1. Trên TV LG, mở **trình duyệt web** và gõ địa chỉ hiện ở thẻ *Không cần cài* trong app (địa chỉ kết thúc bằng `/tv`).
2. Chọn **cổng HDMI** của máy chơi game ngay trong trang. TV hiện **mã 8 ký tự**.
3. Trên điện thoại, nhập mã ở mục **Kết nối TV** rồi bấm *Kết nối TV*.

Phụ đề qua trình duyệt có thể chậm hơn một chút so với app cài trên TV.

## Cách 2: Cài app lên TV LG từ điện thoại

Không cần máy tính.

1. Bật **Developer Mode** trên TV LG (cài app *Developer Mode* từ LG Content Store, đăng nhập tài khoản LG Developer, bật *Dev Mode Status* và *Key Server*). Xem trang hướng dẫn của LG: https://webostv.developer.lge.com/develop/getting-started/developer-mode-app
2. Ghi lại **địa chỉ IP** và **khoá** (passphrase) hiện trong app Developer Mode.
3. Điện thoại và TV dùng **chung một mạng Wi-Fi**.
4. Trong app trên điện thoại: *Phụ đề trên TV › LG › **Cài app lên TV LG***, nhập IP và khoá.
5. **Không bấm nút Home** trên remote khi đang cài.

Developer Mode của LG hết hạn sau một thời gian; mở app Developer Mode để gia hạn khi cần.

## Gặp lỗi

| Mã lỗi | Ý nghĩa | Cách xử lý |
|---|---|---|
| LG-INPUT | Địa chỉ hoặc khoá TV bị thiếu hoặc sai định dạng | Kiểm tra IP và khoá trong app Developer Mode trên TV |
| LG-KEY | TV từ chối khoá | Mở app Developer Mode, đọc lại khoá và nhập lại |
| LG-SSH | Điện thoại không kết nối được tới TV | Dùng chung Wi-Fi, bật *Key Server* trong app Developer Mode |
| LG-UPLOAD | Gửi file app lên TV không thành công | Giữ TV bật và gần router, rồi thử lại |
| LG-INSTALL | TV không cài được app | Giải phóng bộ nhớ TV, tắt bật lại TV rồi thử lại |
| LG-LAUNCH | App đã cài nhưng chưa mở được | Mở Console Translate từ danh sách app trên TV |
| LG-EXPIRED | Developer Mode đã hết hạn | Mở app Developer Mode để gia hạn, rồi cài lại |

*Turn on LG Developer Mode, note the TV's IP and passphrase, keep phone and TV on the same Wi-Fi, then tap "Install app on LG TV" in the phone app. Don't press Home while installing.*

---

[← Phụ đề trên TV](TV.md) · [Hướng dẫn sử dụng](GUIDE.md) · Hỗ trợ: https://consoletranslate.asia/
