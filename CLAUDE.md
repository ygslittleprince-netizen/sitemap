# Dự án: Sitemap TCBS — Backlog bài viết & Audit SEO/GEO

Repo này chứa (1) các báo cáo audit SEO/GEO cho trang tcbs.com.vn, và (2) backlog bài viết
cho mục "Khám phá & Chia sẻ" của TCBS. Trang chính publish qua GitHub Pages tại
https://ygslittleprince-netizen.github.io/sitemap/

## Quy ước thư mục backlog

Mỗi bài viết nằm trong: `backlog/<danh-mục-slug>/<bài-viết-slug>/`
- 5 danh mục hợp lệ, không được tự bịa thêm: `co-phieu`, `trai-phieu`, `phai-sinh`,
  `chung-chi-quy`, `chung-quyen`
- Mỗi thư mục bài viết chỉ chứa: `index.html` (bản mockup xem trước) và ảnh (nếu có) —
  tất cả để **phẳng cùng cấp**, không tạo subfolder `images/` (dễ vỡ khi upload qua
  GitHub web UI).
- **Không tạo `README.md` trong thư mục bài viết.** Toàn bộ README trong `backlog/` đã
  được gỡ bỏ. Phần frontmatter / ghi chú / schema trước đây nằm trong README thì nay chỉ
  giữ ở bản nháp trong chat, không lưu thành file.

## Khi được yêu cầu viết bài

Dùng skill `tcbs-content-writer` (đã có trong `.claude/skills/`). Luôn trình bày bản nháp
trong chat trước, chờ tôi duyệt nội dung, rồi mới tạo file thật.

## Quy trình xuất bản — RẤT QUAN TRỌNG

1. Nháp bài trong chat → chờ tôi duyệt nội dung chữ.
2. Sau khi duyệt, tạo file thật (`index.html` + ảnh) đúng thư mục backlog.
3. **Không bao giờ tự ý chạy `git push` lên nhánh `main`.** Luôn dừng lại, tạo commit +
   pull request để tôi xem lại lần cuối trên GitHub rồi tự tay merge.
4. **Tuyệt đối không được ghi đè `index.html` ở thư mục gốc repo** — đó là trang chủ
   sitemap thật, không phải mockup bài viết.
5. Sau khi merge, có thể cập nhật mục "Backlog bài viết" trong `index.html` gốc để thêm
   link bài mới — kèm thẻ tình trạng và thẻ số từ (`.tag-wordcount`, định dạng nghìn
   kiểu Việt Nam, ví dụ `1.461 từ`), không còn link README đi kèm. Đây cũng là thay đổi
   cần tôi duyệt qua PR, không tự làm trực tiếp.

## Báo cáo hằng tuần

Khi được yêu cầu "tổng hợp báo cáo tuần", đọc `git log` từ đầu tuần đến nay, liệt kê:
bài nào đã merge/lên trang, bài nào đang chờ duyệt (PR mở), và đề xuất ưu tiên tuần tới
dựa trên phần "Đề xuất ưu tiên chỉnh sửa" trong `index.html`.
