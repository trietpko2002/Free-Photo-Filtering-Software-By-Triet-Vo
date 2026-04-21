# 📸 Photo Filter Free - Studio Edition (v6.5)

**Photo Filter Free** là giải pháp phần mềm mã nguồn mở (100% Miễn phí) được thiết kế đặc biệt dành cho các Nhiếp ảnh gia, Thợ chụp sự kiện và Studio chụp ảnh thẻ. Phần mềm giúp tối ưu hóa quy trình lọc ảnh (culling), phân loại và trả ảnh với tốc độ siêu tốc mà không gây giật lag (Anti-Freeze).

---

## 🔥 Tính năng Mới Nổi bật (Cập nhật v6.5 STUDIO)

* **📸 Chế độ Chụp Liên Kết (Live-Shoot / Tethering):** Phần mềm tự động giám sát thư mục máy ảnh. Ngay khi bạn bấm máy, ảnh sẽ tự động được tải lên phần mềm và hiển thị ngay lập tức mà không cần F5.
* **🏷️ Đổi Tên Thông Minh (Smart Rename):** Dành riêng cho Studio chụp ảnh thẻ. Nhập tên khách hàng (VD: `NguyenVanA`), khi xuất ảnh phần mềm sẽ tự động đổi tên file. Nếu bôi đen nhiều ảnh, hệ thống tự động đánh số thứ tự (`NguyenVanA_1`, `NguyenVanA_2`).
* **🛡️ Cảnh Báo Trùng Lặp (Duplicate Warning):** Ngăn chặn việc xuất nhầm 1 file 2 lần vào cùng một thư mục, giúp tiết kiệm dung lượng ổ cứng và tránh rác dữ liệu.
* **🔄 Chuyển Đổi Workflow Nhanh:** 1-Click để chuyển đổi giữa 2 chế độ làm việc: **Lọc Ảnh Chung** (Sự kiện/Phóng sự) và **Chụp Ảnh Thẻ** (Tối ưu cho việc đổi tên và dời file tức thì).

---

## ✨ Tính năng Cốt lõi

* **🚀 Phân loại Siêu tốc:** Gán sẵn 5 thư mục đích (Tương ứng phím `1` đến `5`). Nhấn `Enter` để lập tức dời/copy ảnh.
* **🎛️ Hai Chế độ Xử lý (COPY & CUT):** * `COPY (Ctrl+C)`: Trả ảnh cho khách nhưng vẫn giữ lại bản gốc an toàn trên thẻ nhớ.
    * `CUT (Ctrl+X)`: Dọn dẹp thẻ nhớ ngay trong lúc phân loại.
* **🎥 Hỗ trợ Đa Định dạng:** Đọc mượt mà các định dạng `JPG`, `PNG`, ảnh `RAW` (CR2, NEF, ARW, DNG) và phát trực tiếp Video (`MP4`, `MOV`).
* **💽 Giám sát Thẻ nhớ An toàn:** Hiển thị dung lượng thẻ nhớ theo thời gian thực và có nút **Eject (Rút thẻ an toàn)** ngay trên giao diện để tránh hỏng dữ liệu.
* **🔒 Bảo mật App Lock:** Đặt mật khẩu khóa phần mềm để bảo vệ các thư mục dự án nhạy cảm/riêng tư khỏi người lạ.

---

## ⌨️ Cẩm nang Phím tắt (Shortcuts)

| Phím tắt | Chức năng |
| :--- | :--- |
| `Ctrl + C` | Chuyển sang chế độ **COPY** (Sao chép) |
| `Ctrl + X` | Chuyển sang chế độ **CUT** (Di chuyển) |
| `1, 2, 3, 4, 5` | Chọn nhanh thư mục đích tương ứng (F1 -> F5) |
| `Enter` | Xuất/Dời ảnh vào thư mục đã chọn |
| `Mũi tên ⬆ / ⬇` | Lướt xem ảnh trên danh sách |
| `Space (Dấu cách)` | Phát / Tạm dừng Video |
| `Ctrl + Click` | Bôi đen, chọn nhiều file cùng lúc |

---

## 🛠️ Công nghệ sử dụng (Tech Stack)
* **Ngôn ngữ:** Python 3.x
* **Giao diện (GUI):** PyQt6
* **Xử lý Media:** PyQt6.QtMultimedia, Pillow (đọc Exif)
* **Hệ thống file:** `QFileSystemWatcher` (Giám sát thời gian thực), thư viện `shutil`, `os`.

---

## ☕ Ủng hộ Tác giả (Donate)

Phần mềm được phát triển hoàn toàn miễn phí vì cộng đồng Nhiếp ảnh. Nếu công cụ này giúp ích cho luồng công việc của bạn, hãy ủng hộ tác giả một ly cà phê nhé! ❤️
Mã QR Donate (VietQR) được tích hợp trực tiếp ngay tại trang chủ của phần mềm.

**Tác giả:** Triet Vo  
**Phiên bản:** v6.5 STABLE STUDIO
