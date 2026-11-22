<img src="img/logo.svg" width="80" alt="HLV Sức Khỏe">

# hlvsuckhoe.com – Trang chủ HLV Sức Khỏe

Trang chủ chia sẻ kiến thức sức khỏe, vi chất, tập thể dục, tập thở, thiền, âm nhạc tự sáng tác và các chủ đề thiên văn, khoa học, lịch sử.

- Trang chủ: **https://hlvsuckhoe.com/** (hướng dẫn dùng trang: `hlvsuckhoe.com/#huong-dan`)
- Ứng dụng HLV Sức Khỏe: **https://app.hlvsuckhoe.com/** (repo `hlv-suc-khoe`)
- Ứng dụng tập thở BreathSync: **https://tho.hlvsuckhoe.com/** (repo `breathsync`)
- Ứng dụng Xưởng kính thiên văn: **https://thienvan.hlvsuckhoe.com/** (repo `xuong-kinh-thien-van`)
- Ứng dụng Tôi và Gia đình: sắp ra mắt (dự kiến `giadinh.hlvsuckhoe.com`)
- Liên hệ: nddzungx@gmail.com

Trang tĩnh một tệp `index.html`, không cần build. Tệp `CNAME` giữ tên miền – không xóa.
Ảnh: `img/logo.svg` (HLV), `img/logo-thienvan.svg`, `img/logo-breathsync.svg`, `img/logo-giadinh.svg` (logo tạm), `img/qr_ung_ho.png` (VietQR ủng hộ).

## Thư mục
- `counter/worker.js`, `counter/schema.sql` – bộ đếm truy cập (Cloudflare Worker + D1), không chạy trên GitHub, chỉ lưu ở đây để giữ bản gốc.
- `docs/HUONG_DAN.md` – hướng dẫn từng bước: tải lên, EmailOctopus, bộ đếm, Web Analytics, Tôi và Gia đình; tổng kết kinh nghiệm; hướng tiếp theo.

## Cấu hình nhanh (trong `index.html`, tìm bằng Ctrl + F)
- `DÁN MÃ EMAILOCTOPUS` – chỗ dán mã khung đăng ký
- `var COUNTER_URL` – địa chỉ Worker bộ đếm (để trống = ẩn)
- `var FAM_URL` – địa chỉ ứng dụng Tôi và Gia đình (để trống = "Sắp ra mắt")
- `CLOUDFLARE WEB ANALYTICS` – chỗ dán mã thống kê

## Phiên bản
- **1.2.0** (22/11/2026): mục **Nhận tin** (EmailOctopus, xác nhận 2 bước, lời hứa quyền riêng tư); **bộ đếm** Hôm nay · Cộng dồn · Đang xem; mục **Ứng dụng** có tiêu đề + thẻ **Tôi và Gia đình** (sắp ra mắt); **Hướng dẫn sử dụng trang** (nút ?, "Lần đầu ghé thăm", chân trang); menu thêm Ứng dụng, Nhận tin; sửa lỗi thẻ BreathSync dùng nhầm kiểu của khung thở.
- **1.1.1** (22/11/2026): cập nhật mô tả BreathSync 2.1.0 (nguồn số 011, 068, 117, 120, 121, 134, 135; có hướng dẫn sử dụng).
- **1.1.0** (22/11/2026): bỏ dải "bản nháp"; thêm mục **Giới thiệu** (Nguyễn Đức Dũng) và **Mời Dũng một ly cà phê** (VietQR + PayPal, nút chép); ghi chú **đặt bài hát riêng** trong mục Âm nhạc; thêm ứng dụng **BreathSync** (mục Thở & thiền, khối ứng dụng, chân trang, menu).
- **1.0.1**: mục Âm nhạc 20 bài, trình phát youtube-nocookie.

© 2026 Nguyễn Đức Dũng. Bảo lưu mọi quyền.
