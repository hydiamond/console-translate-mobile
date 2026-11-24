# Phụ đề trên TV Samsung · Samsung TV (Tizen)

Dùng được với TV Samsung **đời 2017 trở lên** (Tizen 3 trở lên). Có hai cách: **trình duyệt của TV** hoặc **cài app lên TV** từ điện thoại.

*Works with Samsung TVs from 2017 on (Tizen 3+): either the TV's web browser or the TV app installed from your phone.*

## Cách 1: Trình duyệt TV

1. Trên TV Samsung, mở **trình duyệt web** và gõ địa chỉ hiện ở thẻ *Mở bằng trình duyệt TV* trong app (địa chỉ kết thúc bằng `/tv`).
2. Trang hiện **mã 8 ký tự** trên nền đen.
3. Trên điện thoại, nhập mã ở mục **Kết nối TV** rồi bấm *Kết nối TV*.

Với trình duyệt, phụ đề hiện trên **nền đen**, chưa đè lên hình HDMI.

Nếu TV tự đổi cổng khi bật máy chơi game, tắt **Anynet+ (HDMI-CEC)** trong cài đặt TV.

## Cách 2: Cài app lên TV Samsung từ điện thoại

1. Bật **chế độ nhà phát triển** trên TV: vào *Apps*, bấm lần lượt `1 2 3 4 5` trên remote, bật *Developer mode*. Xem trang hướng dẫn của Samsung: https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html
2. Ở ô **Host PC IP**, nhập **địa chỉ IP của điện thoại** (xem trong cài đặt Wi-Fi của điện thoại), rồi khởi động lại TV.
3. Điện thoại và TV dùng **chung một mạng Wi-Fi**.
4. Trong app trên điện thoại: *Phụ đề trên TV › Samsung › **Cài app lên TV Samsung***. App lấy chứng chỉ ký từ Samsung (cần đăng nhập tài khoản Samsung miễn phí) và cài app lên TV.
5. Cài xong, có thể tắt chế độ nhà phát triển nếu không dùng nữa.

## Gặp lỗi

| Mã lỗi | Ý nghĩa | Cách xử lý |
|---|---|---|
| SS-INPUT | Địa chỉ TV bị thiếu hoặc sai định dạng | Kiểm tra IP của TV trong *Cài đặt › Mạng* |
| SS-HOSTIP | TV không nhận điện thoại là Host PC IP | Nhập IP điện thoại vào *Host PC IP* rồi khởi động lại TV |
| SS-CONNECT | Điện thoại không kết nối được tới TV | Dùng chung Wi-Fi và bật chế độ nhà phát triển |
| SS-CERT | Không lấy được chứng chỉ ký, hoặc TV từ chối chứng chỉ | Đặt đồng hồ TV ở chế độ tự động, kiểm tra mạng rồi thử lại |
| SS-INSTALL | TV không cài được app | Giải phóng bộ nhớ TV rồi thử lại |
| SS-REMOVE | TV còn giữ bản cũ ký bằng chứng chỉ khác | Xoá Console Translate trên TV (giữ nút OK trên app, chọn Xoá) rồi cài lại. Cũng xảy ra khi cài lại app điện thoại hoặc đổi điện thoại |
| SS-LOGIN | Đăng nhập dịch vụ chứng chỉ không thành công | Đăng nhập lại rồi thử lại |

*Turn on Developer mode on the TV (Apps, then 1-2-3-4-5), enter the phone's IP as Host PC IP and restart the TV, keep both on the same Wi-Fi, then tap "Install app on Samsung TV" in the phone app.*

---

[← Phụ đề trên TV](TV.md) · [Hướng dẫn sử dụng](GUIDE.md) · Hỗ trợ: https://consoletranslate.asia/
