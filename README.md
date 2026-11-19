# Birthday Wishes

## Cấu hình biến môi trường trên máy chủ

Thiết lập các biến sau trong phần Environment của dịch vụ lưu trữ (ví dụ Render):

- `SUPABASE_URL`: Project URL của Supabase.
- `SUPABASE_SECRET_KEY`: Secret key của Supabase (chỉ lưu trên máy chủ, tuyệt đối không đưa lên GitHub hoặc mã trình duyệt).
- `ADMIN_PASSWORD`: Mật khẩu quản trị do bạn tự đặt, nên dài và không dùng lại mật khẩu ở nơi khác.

Không tải tệp `.env` thật lên GitHub. Chỉ tải `.env.example`.

## Chạy cục bộ

1. Cài Node.js.
2. Cài các biến môi trường nêu trên.
3. Chạy `npm start`.

Trang gửi lời chúc: `/`
Trang quản trị: `/admin`

Trang quản trị được xác thực ở máy chủ; danh sách và thao tác xóa lời chúc yêu cầu phiên đăng nhập hợp lệ.
