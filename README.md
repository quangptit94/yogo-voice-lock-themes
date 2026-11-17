# Yogo AI Voice Lock – themes

Ảnh hình nền màn khoá (1080x2400, WebP) cho app AI Voice Lock Screen.

App tải qua CDN jsDelivr, theo **tag phiên bản** của repo này (hiện tại `v1`):

- `themes.json` – danh sách theme theo thứ tự hiển thị trong app:
  `https://cdn.jsdelivr.net/gh/quangptit94/yogo-voice-lock-themes@v1/themes.json`
- `themes/` – ảnh theme:
  `https://cdn.jsdelivr.net/gh/quangptit94/yogo-voice-lock-themes@v1/themes/<tên file>`

Repo phải để **Public** thì jsDelivr mới phục vụ được.

## Thêm / đổi theme

jsDelivr lưu cache nội dung của một tag gần như vĩnh viễn, nên **không sửa lại tag `v1`**.

1. Thêm file vào `themes/` và thêm tên file vào `themes.json`, commit lên `main`.
2. Tạo tag mới (`v2`, `v3`...) rồi push tag.
3. Đổi tag trong app (`WallpaperImageCache.THEME_REPO_RAW_URL`) và ra bản app mới.
