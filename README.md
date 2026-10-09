# KEN XNX CAD Studio V0.5.0 · Project Hub

Trang chủ danh mục dự án KEN XNX. Trang sử dụng GitHub Pages và tự đọc danh sách repository công khai của tài khoản `brokennguyenhp`, sau đó lọc những repository có tên hoặc mô tả liên quan đến KEN XNX / CAD Studio.

## Roadmap
- **V0.2 — CAD tương tác:** kéo thả máy, nối điểm đầu/cuối băng tải, chỉnh vị trí và xuất bản vẽ.
- **V0.3 — Đọc hồ sơ:** nhập Catalogue, Invoice, Packing List, bản vẽ và liên kết chứng cứ với từng thiết bị.
- **V0.4 — Xuất hồ sơ Hải quan:** tạo báo cáo phân tích KEN XNX và Mẫu 01 ở trạng thái DRAFT / READY WITH CONDITIONS.
- **V0.5 — Automation:** GitHub Actions, snapshot/phiên bản, audit log và giao diện phân quyền demo.

## Deploy GitHub Pages
1. Mở **Settings → Pages** của repository.
2. Trong **Build and deployment**, chọn **Source: GitHub Actions**.
3. Vào **Actions** và chạy workflow **Deploy KEN XNX Project Hub** nếu nó chưa tự chạy sau commit.
4. Trang sẽ được công bố tại địa chỉ GitHub Pages hiển thị trong Settings → Pages.

Workflow triển khai nằm tại `.github/workflows/pages.yml`.

## Tự cập nhật danh mục
Trang lấy dữ liệu qua GitHub public API khi được mở. Khi tạo repository công khai mới có tên hoặc mô tả chứa **KEN XNX**, **KEN-XNX**, **CAD Studio** hoặc **XNX CAD**, nó sẽ tự xuất hiện ở danh mục khi tải lại trang, không cần upload lại `index.html` mỗi lần. Repository private không xuất hiện qua API công khai này.

## Lưu ý
Đây là trang danh mục dự án, không phải bằng chứng mọi chức năng của CAD Studio đã hoàn thiện. Danh sách động chỉ truy xuất metadata repository công khai. Các phân tích HS và biểu mẫu Hải quan vẫn cần kiểm tra nguồn chứng cứ và phê duyệt chuyên môn.
