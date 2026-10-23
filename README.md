# Demo trang Gửi yêu cầu báo giá thành công — Thiết bị mầm non Việt Mỹ

Trang Gửi yêu cầu báo giá thành công của site đang dựng (website-demo-02.thcmedia.vn/gui-yeu-cau-bao-gia-thanh-cong/) sau khi áp feedback dòng 209–213 tab "Review tổng thể website":

1. Mã yêu cầu + thời điểm gửi ngay dưới H1, nút "Chép mã" (dòng 213)
2. Khối "Yêu cầu của bạn" dưới mô tả: sản phẩm × số lượng × giá, tạm tính, thông tin người gửi (dòng 213)
3. Mô tả dưới heading: bỏ "Việt Mỹ Educational", mốc 15–30 phút + giờ làm việc 08:00–18:00, Thứ 2 – Thứ 7 (dòng 210)
4. 3 bước tiếp theo dùng text, không dùng H2; cả trang chỉ còn 1 H1 (dòng 212)
5. Hotline giữ 0902 333 196, chờ SEO xác nhận số (dòng 211)

Header, footer, thanh liên hệ nổi giữ nguyên như site. Phần mới chỉ gồm `<section id="quote-success">`, `<style id="vmx-change">` (dán cuối `page-quote-success.css`) và `<script id="vmx-page-js">`. Dữ liệu trong khối "Yêu cầu của bạn" là 1 yêu cầu mẫu.

- Xem trực tiếp: https://lanvi-commits.github.io/demo-bao-gia-thanh-cong-thiet-bi-mam-non-viet-my/
- Trang mẫu, không phải site thật (có `noindex`). Form trong popup tư vấn không gửi đi đâu; `<script id="vmx-demo-guard">` chỉ dành cho demo, không đưa lên site.

`index.html` là bản build từ `Design UX-UI/brands/viet-my/nguyen-lieu/2026-10-23_bao-gia-thanh-cong-trang-build/` (sửa `section.html` / `change.css` / `page.js` → chạy `build.py` → commit + push). Đừng sửa tay `index.html`.
