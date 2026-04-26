# 📸 Photo Filter Free - Studio Edition (v7.0)

![Photo Filter Studio Banner](https://raw.githubusercontent.com/trietpko2002/Free-Photo-Filtering-Software-By-Triet-Vo/refs/heads/main/1.png)

## 📖 Giới Thiệu Phần Mềm (Introduction)

**Photo Filter Studio** là một phần mềm mã nguồn mở (100% Miễn phí) được thiết kế đặc biệt dành cho các Nhiếp ảnh gia, Thợ chụp sự kiện, và các Studio chụp ảnh thẻ / hồ sơ. 

**❓ Phần mềm này giải quyết vấn đề gì?**
Sau mỗi buổi chụp sự kiện hay kỷ yếu, thợ ảnh thường phải đối mặt với hàng ngàn bức ảnh (bao gồm cả file RAW và Video rất nặng). Việc xem lại (Culling) và chép file sang các thư mục phân loại bằng File Explorer mặc định của Windows cực kỳ chậm chạp và dễ bị đơ máy.

**💡 Giải pháp từ Photo Filter Studio:**
Phần mềm mang đến một quy trình làm việc (Workflow) khép kín, tập trung vào **Tốc độ** và **Sự ổn định**. Với công nghệ "Anti-Freeze" và bộ phím tắt tối ưu, bạn có thể lướt xem ảnh tốc độ cao và phân loại hàng trăm file chỉ trong chớp mắt mà không lo giật lag. Ở phiên bản Studio, phần mềm còn đóng vai trò như một trạm thu nhận ảnh trực tiếp từ máy ảnh (Live-Shoot), giúp thợ ảnh thẻ đổi tên và trả file cho khách chỉ trong vài giây.

---

## 🚀 Nhật Ký Cập Nhật (Changelog v6.0 ➔ v7.0)

Quá trình nâng cấp biến một công cụ lọc ảnh cơ bản thành giải pháp toàn diện cho Studio:

* **[v7.0] - Ra tính năng mới : Đánh giá hình ảnh bằng AI - Sử dụng mô hình của Groq AI để dùng đánh giá hình ảnh theo cảm nhận của AI.
* **[v6.5] - Hệ thống Auto-Update OTA:** Tích hợp mô-đun kiểm tra phiên bản tự động từ GitHub. Phần mềm tự tải `.exe` mới, chạy script ngầm để ghi đè và khởi động lại, giúp người dùng luôn có bản mới nhất chỉ với 1-click.
* **[v6.4] - Cảnh Báo Trùng Lặp (Duplicate Warning):** Thêm cơ chế thông minh phát hiện file đã tồn tại ở thư mục đích. Cung cấp tùy chọn "Bỏ qua" hoặc "Tạo bản sao mới" để tránh việc vô tình copy đè hoặc copy 2 lần gây đầy rác ổ cứng. Tối ưu hóa lại Layout màn hình Welcome rộng rãi, không bị đè chữ.
* **[v6.2 - v6.3] - Nâng cấp Nút Workflow & Giao diện:** Thêm tính năng thay đổi linh hoạt toàn bộ từ ngữ và giao diện dựa trên Mode đang chọn (Màu sắc nút bấm, tự động chuyển chế độ COPY/CUT).
* **[v6.1] - Ra mắt Chế độ Chụp Ảnh Thẻ (Tethering Mode):** * **Live-Shoot:** Giám sát thư mục máy ảnh thời gian thực, ảnh vừa chụp tự động bắn thẳng lên màn hình Preview.
  * **Smart Rename:** Tích hợp thanh nhập tên ngay trên màn hình. Nhập tên khách (VD: `NguyenVanA`), khi xuất ảnh sẽ tự động đổi tên thành `NguyenVanA.jpg`, nếu xuất nhiều ảnh sẽ tự thêm hậu tố `_1`, `_2`. Tự động xóa tên sau khi xuất xong để đón khách tiếp theo.
* **[v6.0] - Bản Base Ổn định:** Phân loại 5 thư mục bằng phím tắt, đọc Exif/RAW, chặn giật lag khi chuyển file số lượng lớn.

---

## ✨ Tính Năng Cốt Lõi (Core Features)

* **🚀 Phân loại Siêu tốc:** Gán sẵn 5 thư mục đích (Tương ứng phím tắt `1` đến `5`). Nhấn `Enter` để lập tức dời/copy ảnh.
* **🎛️ Hai Chế độ Xử lý:**
  * `COPY (Ctrl+C)`: Trả ảnh cho khách nhưng vẫn giữ lại bản gốc an toàn trên thẻ nhớ.
  * `CUT (Ctrl+X)`: Vừa phân loại vừa dọn dẹp thẻ nhớ ngay lập tức.
* **🎥 Hỗ trợ Đa Định dạng:** Đọc mượt mà `JPG`, `PNG`, ảnh `RAW` từ máy cơ (`CR2`, `NEF`, `ARW`, `DNG`) và phát trực tiếp Video (`MP4`, `MOV`).
* **💽 Giám sát Thẻ nhớ An toàn:** Hiển thị dung lượng ổ đĩa/thẻ SD theo thời gian thực và tích hợp nút **Eject (Rút thẻ an toàn)**.
* **🔒 Bảo mật App Lock:** Khóa phần mềm bằng Master Password để bảo vệ dự án.

---

## ⌨️ Cẩm Nang Phím Tắt (Shortcuts)

| Phím tắt | Chức năng |
| :--- | :--- |
| `Ctrl + C` | Chuyển sang chế độ **COPY** (Sao chép) |
| `Ctrl + X` | Chuyển sang chế độ **CUT** (Di chuyển) |
| `1, 2, 3, 4, 5` | Chọn nhanh thư mục đích tương ứng (F1 -> F5) |
| `Enter` | Xuất/Dời ảnh vào thư mục đã chọn |
| `Mũi tên ⬆ / ⬇` | Lướt xem ảnh trên danh sách |
| `Space (Dấu cách)` | Phát / Tạm dừng Video |
| `Ctrl + Click chuột` | Bôi đen, chọn nhiều file cùng lúc |

---

## 🛠️ Công Nghệ Sử Dụng (Tech Stack)
* **Ngôn ngữ:** Python 3.x
* **Giao diện (GUI):** PyQt6
* **Xử lý Media:** PyQt6.QtMultimedia, Pillow (để đọc thông số Exif).
* **Kiến trúc hệ thống:** * `QFileSystemWatcher` (Giám sát file thời gian thực).
  * `QThread` (Download & Cập nhật đa luồng).
  * Tương tác API REST (GitHub API).

---

## ☕ Ủng Hộ Tác Giả (Donate)

**Photo Filter Studio** được phát triển hoàn toàn miễn phí vì cộng đồng Nhiếp ảnh Việt Nam. Nếu công cụ này giúp bạn về sớm hơn sau mỗi show chụp, hãy ủng hộ tác giả một ly cà phê nhé! ❤️

*(Mã QR Donate VietQR được tích hợp trực tiếp ngay tại trang chủ của phần mềm).*

**Tác giả:** Triet Vo  
**Phiên bản hiện tại:** v6.5 STABLE STUDIO  
**Mã nguồn / Góp ý:** Hãy tạo một [Issue](https://github.com/trietpko2002/Free-Photo-Filtering-Software-By-Triet-Vo/edit/main/README.md) nếu bạn phát hiện lỗi hoặc muốn đóng góp tính năng mới!
