# Biểu Đồ Vàng - GitHub Pages Static

Bộ code này được chuyển từ HTML gốc sang dạng chạy trực tiếp trên GitHub Pages.

## Cách dùng

1. Tạo repository mới trên GitHub.
2. Upload toàn bộ file trong thư mục này lên repo:
   - `index.html`
   - `assets/fix.css`
   - `assets/app.js`
   - `.nojekyll`
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**.
5. Chọn branch `main`, folder `/root`, rồi Save.

## Đã fix

- Xóa Cloudflare Rocket Loader, Beacon và email decode script gây lỗi trên GitHub.
- Sửa script bị đổi type `...-text/javascript` khiến JavaScript không chạy.
- Giữ lại giao diện, SEO meta, Open Graph, Twitter card, schema JSON-LD.
- Thêm JS static cho mobile menu, submenu, search, lọc bảng, nút xem thêm, lazy image và modal chart.
- Thêm CSS override để không bị overlay loading che màn hình.
- Thêm `.nojekyll` để GitHub Pages không xử lý Jekyll.

## Ghi chú

Trang vẫn dùng một số asset gốc từ `bieudovang.com` như logo, ảnh thương hiệu và CSS giao diện.
