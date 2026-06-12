# BÁO CÁO HOÀN THÀNH GIT SAFETY FOUNDATION

**Họ và tên:** Huỳnh Nhật Quốc
**Kết quả học tập:** Đã hoàn thành đầy đủ hai lộ trình GitHub Foundations trên Microsoft Learn.
Dòng này là của nhánh feature-3.
## Quá trình học và thực hành
Trong giai đoạn đầu, đã hoàn thành các nội dung học tập trên Microsoft Learn và tìm hiểu các khái niệm cơ bản của Git và GitHub như Repository, Commit, Branch, Pull Request cũng như quy trình quản lý phiên bản mã nguồn.

Sau khi hoàn thành phần lý thuyết, tiến hành tạo repository cá nhân trên GitHub và kết nối với môi trường local. Đồng thời thực hành làm việc với nhiều branch khác nhau để hiểu rõ hơn quy trình phát triển tính năng và cách cộng tác trong dự án.

Bên cạnh các thao tác cơ bản, cũng thực hiện một số tình huống nâng cao như tạo xung đột trên file *nhatky.txt* để thực hành xử lý conflict và sử dụng lệnh *git revert* nhằm hoàn tác một commit bị lỗi nhưng vẫn đảm bảo giữ lại lịch sử thay đổi của repository.

## Một số lệnh Git đã sử dụng
- `git clone <url>` : Sao chép repository từ GitHub về máy.
- `git checkout -b <tên_nhánh>` : Tạo branch mới và chuyển sang nhánh đó.
- `git checkout <tên_nhánh>` : Chuyển đổi giữa các branch.
- `git add .` : Đưa các thay đổi vào vùng Staging.
- `git commit -m "message"` : Tạo commit và lưu lại thay đổi.
- `git pull origin <tên_nhánh>` : Cập nhật dữ liệu mới từ GitHub về máy.
- `git push origin <tên_nhánh>` : Đẩy các thay đổi từ local lên GitHub.
- `git reset --hard origin/main` : Đồng bộ lại trạng thái local với branch chính.
- `git revert <commit_id>` : Hoàn tác một commit bằng cách tạo commit đảo ngược.
- `git log --oneline` : Kiểm tra lịch sử commit dưới dạng rút gọn.

## Sử dụng Git khi Vibe Code với AI
Khi làm việc với AI, tốc độ tạo mã nguồn nhanh hơn rất nhiều nhưng cũng dễ phát sinh lỗi hoặc làm ảnh hưởng đến các chức năng đang hoạt động ổn định. Vì vậy, Git sẽ được sử dụng như một công cụ hỗ trợ kiểm soát thay đổi và đảm bảo an toàn cho dự án.

Trước khi sử dụng AI để phát triển một tính năng mới, sẽ tạo branch riêng thay vì thao tác trực tiếp trên branch `main`. Các thay đổi sẽ được commit thường xuyên với nội dung rõ ràng để dễ theo dõi và quay lại khi cần.

Trong trường hợp AI sinh ra code gây lỗi hoặc làm hệ thống hoạt động không như mong muốn, có thể sử dụng `git revert` hoặc các phương pháp rollback để khôi phục lại phiên bản ổn định trước đó.

Ngoài ra, Pull Request sẽ được sử dụng để kiểm tra các thay đổi trước khi hợp nhất vào branch chính, từ đó hạn chế rủi ro và giúp quá trình phát triển trở nên an toàn hơn.
