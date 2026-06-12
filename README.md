# BÁO CÁO HOÀN THÀNH PROJECT: GIT SAFETY FOUNDATION

## 1. Thông tin cá nhân

* **Họ và tên học viên:** Huỳnh Nhật Quốc
* **Trạng thái:** Đã hoàn thành hai lộ trình Microsoft Learn theo yêu cầu.

## 2. Nhật ký quá trình học và thực hành Git


### Giai đoạn 1: Học lý thuyết trên Microsoft Learn

Đã hoàn thành các module được giao trên Microsoft Learn, qua đó nắm được những kiến thức cơ bản về Git và GitHub như Repository, Commit, Branch, Pull Request và quy trình quản lý phiên bản mã nguồn.


### Giai đoạn 2: Thực hành với GitHub Repository

Tạo một GitHub repository cá nhân và kết nối giữa môi trường local với remote repository trên GitHub. Trong quá trình thực hành, đã tạo các nhánh riêng để mô phỏng việc phát triển tính năng độc lập và làm quen với quy trình làm việc theo GitHub Flow.


### Giai đoạn 3: Thực hành các tình huống nâng cao

Chủ động tạo tình huống xung đột (Conflict) trên file *nhatky.txt* và tiến hành xử lý conflict để hiểu rõ hơn cách hợp nhất các thay đổi giữa các nhánh. Bên cạnh đó, cũng thực hành sử dụng lệnh `git revert` để hoàn tác một commit bị lỗi mà vẫn giữ nguyên lịch sử phát triển của dự án.



## 3. Danh sách các lệnh Git đã sử dụng

Trong quá trình thực hành, đã sử dụng các lệnh Git cơ bản sau:




* `git clone <url>`             : Sao chép repository từ GitHub về máy tính cá nhân.
* `git checkout -b <tên_nhánh>` : Tạo nhánh mới và chuyển sang nhánh đó.
* `git checkout <tên_nhánh>`    : Chuyển đổi giữa các nhánh.
* `git add .`                   : Đưa các thay đổi vào vùng Staging.
* `git commit -m "tin_nhắn"`    : Lưu lại thay đổi với nội dung mô tả cụ thể.
* `git pull origin <tên_nhánh>` : Cập nhật phiên bản mới nhất từ GitHub về máy.
* `git push origin <tên_nhánh>` : Đẩy các thay đổi từ máy cá nhân lên GitHub.
* `git reset --hard origin/main`: Đồng bộ lại trạng thái local với nhánh chính trên GitHub khi cần thiết.
* `git revert <commit_id>`      : Hoàn tác một commit bằng cách tạo thêm commit đảo ngược.
* `git log --oneline`           : Xem lịch sử commit dưới dạng rút gọn.


* `git clone <url>`: Sao chép repository từ GitHub về máy tính cá nhân.
* `git checkout -b <tên_nhánh>`: Tạo nhánh mới và chuyển sang nhánh đó.
* `git checkout <tên_nhánh>`: Chuyển đổi giữa các nhánh.
* `git add .`: Đưa các thay đổi vào vùng Staging.
* `git commit -m "tin_nhắn"`: Lưu lại thay đổi với nội dung mô tả cụ thể.
* `git pull origin <tên_nhánh>`: Cập nhật phiên bản mới nhất từ GitHub về máy.
* `git push origin <tên_nhánh>`: Đẩy các thay đổi từ máy cá nhân lên GitHub.
* `git reset --hard origin/main`: Đồng bộ lại trạng thái local với nhánh chính trên GitHub khi cần thiết.
* `git revert <commit_id>`: Hoàn tác một commit bằng cách tạo thêm commit đảo ngược.
* `git log --oneline`: Xem lịch sử commit dưới dạng rút gọn.


## 4. Thu hoạch: Sẽ sử dụng Git như thế nào khi Vibe Code với AI?

Khi tham gia khóa học Vibe Code với AI, tốc độ sinh code của AI rất nhanh nhưng cũng tiềm ẩn nguy cơ tạo ra lỗi hoặc ảnh hưởng đến những phần chức năng đang hoạt động ổn định. Vì vậy, Git sẽ được sử dụng như một công cụ đảm bảo an toàn cho quá trình phát triển.

* **Tạo nhánh riêng trước khi làm việc với AI:** Trước khi nhờ AI hỗ trợ viết tính năng mới, sẽ tạo một branch riêng thay vì thao tác trực tiếp trên nhánh `main`.

* **Commit thường xuyên với nội dung rõ ràng:** Sau mỗi phần chức năng được AI hỗ trợ và kiểm tra hoạt động ổn định, sẽ tạo commit để lưu lại các mốc quan trọng.

* **Sử dụng Revert hoặc Rollback khi xảy ra lỗi:** Nếu code do AI sinh ra gây lỗi hoặc làm ảnh hưởng đến hệ thống, có thể nhanh chóng quay lại trạng thái ổn định trước đó.

* **Kiểm tra thay đổi thông qua Pull Request:** Trước khi hợp nhất vào nhánh chính, sẽ sử dụng Pull Request để xem lại các thay đổi, từ đó giảm thiểu rủi ro và đảm bảo tính ổn định của dự án.
