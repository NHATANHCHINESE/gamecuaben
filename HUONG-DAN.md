# Đưa Vườn nhỏ của bé lên GitHub Pages

Gói này chứa bản hoàn chỉnh 20 chủ đề × 20 tranh, bao gồm Gia đình của bé, lựa chọn Việt–Anh, nhạc/hiệu ứng, bảng vẽ và nút sắp xếp tranh. `index.html` đã chứa sẵn toàn bộ hình ảnh, font, nhạc và các bản ghi có sẵn; không cần thư mục assets hoặc cài thư viện.

## Tải lên

1. Nếu tải file ZIP, hãy giải nén trước. GitHub Pages cần file `index.html`, không chạy trò chơi trực tiếp từ ZIP.
2. Tạo một repository mới, ví dụ `vuon-nho-cua-be`, để tránh ghi đè trang web đang có. Với tài khoản GitHub Free, dùng repository Public nếu muốn bật Pages.
3. Trong repository, chọn **Add file → Upload files**. Tải các file `index.html`, `.nojekyll`, `FONT-LICENSE.txt` và hướng dẫn này lên thư mục gốc của nhánh `main`. Nếu máy ẩn `.nojekyll`, bạn có thể tạo file rỗng tên `.nojekyll` bằng **Add file → Create new file**. Xác nhận lưu thay đổi.
4. Vào **Settings → Pages**. Ở **Build and deployment**, chọn **Source: Deploy from a branch**, nhánh **main**, thư mục **/ (root)** rồi **Save**.
5. Khi GitHub báo xuất bản xong, dùng **Visit site** để lấy đường dẫn. Mở đường dẫn đó bằng Safari trên iPad. Có thể dùng **Chia sẻ → Thêm vào Màn hình chính**.

File `index.html` khoảng 19 MiB, thấp hơn giới hạn tải bằng trình duyệt 25 MiB mỗi file của GitHub. Nếu repository đã có cấu hình Pages hoặc nhánh khác, chọn đúng nhánh/thư mục chứa file index.html. Không đặt toàn bộ thư mục GitHub-Pages-BEN lồng bên trong thư mục gốc nếu đang chọn / (root).

Đường dẫn sau khi xuất bản do GitHub cung cấp, thường có dạng `https://TEN-TAI-KHOAN.github.io/TEN-REPOSITORY/`. Đây là dạng minh họa, chưa phải một đường dẫn đã được tạo. GitHub Pages thông thường cung cấp trang công khai trên Internet.

## Chơi trên iPad

- Dùng đường dẫn website bằng Safari; trình xem trước HTML trong ứng dụng Tệp có thể không chạy trò chơi.
- Nhạc và lời đọc bắt đầu sau khi chạm. Có nút VI / EN, nhạc và loa riêng.
- Lời chào tiếng Việt có sẵn gọi tên Ben. Các từ mới và tiếng Anh dùng giọng đọc phù hợp có trên thiết bị; khả năng đọc ngoại tuyến phụ thuộc giọng đã cài.
- Thứ tự tranh, lựa chọn và tranh vẽ được lưu trên trình duyệt/thiết bị đang chơi. Chúng không đồng bộ giữa iPad và máy tính hoặc giữa đường dẫn cũ và GitHub Pages.
- Để sắp xếp tranh: mở chủ đề → nút danh sách nhỏ ở góc trên phải → ↑/↓ → Lưu thứ tự.

## Hướng dẫn chính thức

- Tạo trang: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- Cấu hình nguồn xuất bản: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Tải file: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

Bản đóng gói đã kiểm tra dữ liệu 20×20, 400 vùng hiển thị tranh, tài nguyên nhúng và hoạt động trong trình duyệt ở khổ iPad ngang/dọc. Chưa thử trực tiếp trên iPad vật lý. Gói này không chứa thông tin đăng nhập hoặc mã truy cập Sites.
