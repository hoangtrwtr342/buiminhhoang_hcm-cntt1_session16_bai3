# Bài 3 : Xây dựng Không gian Cộng tác Doanh nghiệp


## 1. Bẫy dữ liệu: Ép rep phá vỡ Flow State (Tập trung code)

   1. Giải pháp: Áp dụng Async-First (Giao tiếp bất đồng bộ).
      
   2. Quy định thời gian phản hồi (SLA): Không khẩn cấp thì trả lời sau 2–4 tiếng hoặc theo khung giờ check tin nhắn cố định.
      
   3. Tôn trọng trạng thái Do Not Disturb (DND) khi thành viên đang viết code.

## 2. Sơ đồ về kiến trúc kênh

| Tên kênh | NỘI DUNG |
|:--|:--:|
|  📢 THÔNG BÁO |  Thông báo chung, deadline, lịch họp dự án    |
|  ⚙️ KỸ THUẬT | Bàn về cảm biến, vi điều khiển, mạch điện bãi đỗ xe.  |
|  ☕ TÁN GẪU| Tán gẫu, gửi ảnh chế (meme), giải trí ngoài lề.   |

## 3. Bản quy ước giao tiếp: 3 quy tắc vàng

1. Quy tắc No-Hello: Không nhắn cụt lủn "Alo/Cậu ơi" rồi chờ phản hồi. Gom [Chào] + [Vấn đề/Log lỗi] + [Hạn chót/Hành động cần làm] vào đúng 1 tin nhắn duy nhất.

2. Kỷ luật Thread: Khung chat chính chỉ đăng tiêu đề bài toán mới. Mọi thảo luận, trao đổi chi tiết bắt buộc bấm Reply in Thread để không làm trôi tin nhắn.

3. Sử dụng Mention có trách nhiệm:

    - Cấm @all / @channel ở các kênh kỹ thuật và chitchat (chỉ Lead dùng ở kênh thông báo khi có sự cố khẩn cấp).

    - Chỉ tag đúng người phụ trách
