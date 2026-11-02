# 🏸 Xếp Sân Cầu Lông

Web app chạy trên điện thoại để xếp cặp đánh đôi cho nhóm 4–20 người. Chỉ 1 file `index.html`, không cần server, dữ liệu lưu ngay trên máy (localStorage).

## Tính năng
- **Danh sách người chơi**: thêm nhanh nhiều tên (dán từ Zalo, mỗi dòng 1 tên), tích ✓ người có mặt hôm nay, chấm trình độ 1–5.
- **Xếp sân tự động** theo vòng, 1–5 sân:
  - Ai chơi ít trận hơn được ưu tiên vào sân → số trận đều nhau, không ai nghỉ 2 vòng liền (nếu có thể).
  - Tránh ghép lại cùng đồng đội và hạn chế gặp lại cùng đối thủ.
  - Chế độ **Cân trình**: tổng trình 2 đội gần bằng nhau, 4 người trên sân gần trình nhau. Chế độ **Ngẫu nhiên**: bỏ qua trình độ.
  - Người đến muộn được tính "bù trận" để không bị dồn đánh liên tục.
- **Xem trước các vòng sau** (2–8 vòng, chỉnh trong ⚙️): lịch dự kiến giữ nguyên khi sang vòng mới, tự tính lại nếu có người đến/về, đổi chỗ hoặc đổi cài đặt. Chạm vào tên để xem người đó đánh / nghỉ vòng nào.
- **Đổi chỗ thủ công**: chạm 2 người để hoán đổi (kể cả người đang nghỉ).
- **Gửi nhóm**: chia sẻ / copy vòng hiện tại hoặc cả lịch dự kiến để dán vào Zalo, Messenger.
- **Ghi & sửa kết quả** (tuỳ chọn): chọn đội thắng hoặc nhập tỉ số, sửa được cả các vòng đã xong (tab Thống kê → Lịch sử → chạm vào trận); bảng xếp hạng tính thắng + hiệu số (HS) và **thống kê**: số trận, thắng, nghỉ; lịch sử các vòng.

## Cách dùng
1. Tab **Người chơi**: thêm tên, tích người có mặt, chọn trình độ.
2. Tab **Xếp sân**: chọn số sân, bấm **Xếp vòng 1**. Không ưng thì bấm **Xếp lại**.
3. Đánh xong bấm **Vòng tiếp** để sang vòng mới.
4. Hết buổi: tab **Thống kê** → **Bắt đầu buổi mới**.

## Đưa lên mạng (miễn phí) với GitHub Pages
Repo → **Settings → Pages** → Source: *Deploy from a branch* → chọn branch, thư mục `/ (root)` → Save.
Sau 1–2 phút mở `https://<tên-github>.github.io/badminton_tool/` trên điện thoại, chọn **Thêm vào màn hình chính** để dùng như app.
