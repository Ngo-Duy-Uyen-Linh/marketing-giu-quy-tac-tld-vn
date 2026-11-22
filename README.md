<!-- TẠO TỰ ĐỘNG bằng dong-bo.cjs từ marketing-skills-tld-vn. Không sửa ở đây. -->
# marketing-giu-quy-tac-tld-vn: Marketing: giữ quy tắc nội dung

Bản 0.6.1. Hỗ trợ tổ chức kiểm bài đăng, kịch bản, ảnh, chú thích theo bộ quy tắc nội dung trước khi đăng, chỉ ra chỗ cần sửa và chuyển người duyệt khi cần.

Gói này là một vai trong bộ **Marketing-skills-tld-vn**, tách riêng để nhân sự AI chỉ nạp kỹ năng của đúng vai mình, đỡ tốn chi phí mỗi lượt chạy. Dùng được trong Claude Code và nạp được vào hệ thống quản trị Thế Là Được.

## Kỹ năng
- `kiem-noi-dung-theo-quy-tac`
- `bo-giong-van-may`

## Các vai khác của bộ
- `marketing-nghien-cuu-tld-vn`: nghiên cứu và kế hoạch
- `marketing-sang-tao-tld-vn`: sáng tạo nội dung
- `marketing-binh-luan-tld-vn`: trả lời bình luận và xử lý sự cố

## Cấu trúc
```
quy-tac-chung.md        quy tắc mọi kỹ năng làm theo
skills/<tên>/SKILL.md   kỹ năng (dạng Claude Code)
ky-nang/<tên>/SKILL.md  bản cho hệ thống quản trị
goi.json, vai-tro.md    tệp cho hệ thống quản trị
bai-kiem-tra/           tình huống kiểm tra vào việc của vai này
tai-lieu-to-chuc/       tệp mẫu để tổ chức điền rồi nạp vào kho tri thức
```

Mọi tệp trong gói được sinh tự động từ bản gốc; sửa ở bản gốc. Nguồn tham khảo và giấy phép: `NOTICE.md`.
