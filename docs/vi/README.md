# Showcase frontend MemeMap

Repo này chứa showcase frontend static trong `mememap-frontend`.

- `index.html`: trang chính song ngữ, đăng nhập demo và hồ sơ.
- `landing.html`: bản đồ MapLibre, ghim, hồ sơ, bảng xếp hạng và Admin demo.
- `assets/css/`: CSS dùng chung, trang chính, bản đồ và Admin.
- `assets/js/api.js`: bộ điều hợp session chạy trong trình duyệt. Không dùng API máy chủ hoặc database.

| Tài liệu | Nội dung | Bản tiếng Anh |
## Tài khoản demo

| Username | Mật khẩu | Vai trò |
| --- | --- | --- |
| `guest` | `guest123` | Người dùng demo |
| `admin-demo` | `admin123` | Admin demo |

Trạng thái được lưu trong `sessionStorage` của tab hiện tại. Không dùng các thông tin này cho production.

## Chạy

```sh
python3 -m http.server 6767
```

Mở `http://localhost:6767`. Ứng dụng Python/SQLite full-stack được duy trì riêng trong repo `mememap`. Ghi chép lịch sử vẫn nằm trong `docs/vi/history/`.
