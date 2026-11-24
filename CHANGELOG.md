# Nhật ký thay đổi — DF Code Garena

## 1.0.0

Bản hiện tại. Chỉ chạy trên trang đổi code Garena.

Nhập code

- Dán danh sách, mở file .txt, hoặc bấm Demo Code. Bỏ dòng trống, dòng chú thích, code trùng. Nhận code dán kèm số thứ tự, nhãn, emoji, ngoặc.
- Code có ký tự sai (chữ Kirin, Hy Lạp, số La Mã, chữ toàn chiều rộng, chữ kiểu, gạch dài, Telex/VNI, ký tự đặc biệt) không được nhập. Nút Sửa tự động sửa những code sửa được và nói rõ khi chỉ là đoán.
- Bỏ qua code đã có trong log: dùng được hoặc lỗi thì không nhập lại, chưa rõ thì nhập lại. Nút Thử lại code lỗi đưa đúng các code lỗi vào ô.
- Bắt đầu, tạm dừng, tiếp tục, dừng. Đang nghỉ thì dừng ngay và giữ số giây còn lại. Đang gửi một code thì gửi xong rồi mới dừng. Đóng popup không làm dừng.
- Ước tính giờ xong, hạn mức còn lại, và số code lần này sẽ nhập.

Bảo vệ tài khoản

- Bật (mặc định): nghỉ ngẫu nhiên 20–30 giây, tối đa 30 code mỗi lần và mỗi 60 phút, nghỉ 60 giây giữa hai lần bấm Bắt đầu. Không giới hạn theo ngày.
- Tắt: nghỉ cố định 5–60 giây hoặc ngẫu nhiên 10–15 giây, tối đa 100 code mỗi lần và mỗi 60 phút, có hỏi lại.
- 5 lỗi liên tiếp thì tự nghỉ 30,0–60,0 giây (có một số lẻ) rồi nhập tiếp.
- Dừng hẳn khi trang báo quá nhanh, captcha, xác minh, khóa tài khoản, HTTP 403/429, hai lỗi máy chủ liên tiếp, mất đăng nhập, hoặc không đọc được kết quả.

Nhật ký

- Ghi nguyên câu trên trang và câu máy chủ, kèm mã số. Token, email, liên kết và dãy số dài bị ẩn.
- Dùng được, đã dùng, lỗi, chưa rõ. Đã dùng là code đã được sử dụng (câu “đã được sử dụng” hoặc mã 400068). Code hết hạn và code sai vẫn là lỗi. Lọc và chép từng dòng. Giữ tối đa 5000 lượt.
- Mỗi lần bấm Bắt đầu được lưu thành một lần chạy, tối đa 30 lần, chỉ trên máy này. Mỗi lần chạy xuất CSV riêng và thử lại đúng code lỗi của lần đó. Code đã dùng không bị đưa vào thử lại.
- Xuất CSV để mở bằng Excel. Tải log lên đọc được CSV này và file .txt xuất từ trước.

Biểu tượng

- Xanh lá khi bình thường. Đỏ khi lần chạy có code lỗi hoặc chưa rõ. Số trên biểu tượng là số code còn lại.
