# Web/app học tập — Hóa học 9, Ôn tập kiểm tra giữa kì I

**Ôn tập kiểm tra giữa kì I — Phạm vi: Bài 1, 18–22** (Kim loại, phi kim và hợp chất hữu cơ)
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Hệ thống kiến thức, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Tính hấp phụ của bột than gỗ (Bài 21, Hình 21.1) — 4 bước.
2. Đinh sắt trong dung dịch copper(II) sulfate (Bài 18–19) — 4 bước.

Khóa đáp án trắc nghiệm: **1A 2C 3C 4B 5C 6A 7B 8D 9C 10A** (ACCBCABDCA).

## Trạng thái lưu điểm: CHỜ /exec

Bản này **chưa có** link Web App Apps Script để gửi điểm về Google Sheets
(registry chưa có webAppUrl cho khóa `hoa9-ontap-gki`). Học sinh vẫn làm bài
và tự chấm điểm ngay trên trang; điểm cao nhất lưu trên máy học sinh
(localStorage). Khi có link /exec, bổ sung khối fetch gửi điểm vào hàm chấm
bài trong `index.html` là dùng được ngay.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_OnTap_GKI.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script nhận kết quả về tab KetQua (dùng khi deploy Web App).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo giáo viên (PNG 500×500).
