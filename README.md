# git-safety-foundation
# Nhật ký học tập của tôi.
* Học Git là gì.
Dùng `git revert` hoặc `git reset` để khôi phục nhanh khi AI sinh code lỗi.
- Kiểm tra code qua Pull Request trước
## Các lệnh Git đã sử dụng:
1. `git init`: Khởi tạo kho lưu trữ.
2. `git add .`: Thêm file vào staging.
3. `git commit -m "..."`: Lưu thay đổi.
## Vibe Code với AI:
- Tôi sẽ sử dụng Git như một "phanh an toàn" trước khi merge code do AI sinh ra.
- Mỗi đoạn code từ AI sẽ được commit vào một nhánh riêng (feature branch).
- Nếu AI tạo lỗi, tôi sẽ dùng `git revert` để quay lại phiên bản ổn định.
