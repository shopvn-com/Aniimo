ANIIMO — GIAO DIỆN ĐÃ TINH CHỈNH (GITHUB PAGES)

CẤU TRÚC
- index.html: trang web chính
- style.css: giao diện desktop/mobile
- script.js: gói nạp, tạo đơn demo, tra cứu và tài khoản demo
- assets/: hình nền, ảnh đại diện và ảnh QR thanh toán

ĐƯA LÊN GITHUB PAGES
1. Tạo một repository GitHub mới.
2. Giải nén ZIP và tải toàn bộ nội dung bên trong thư mục này lên repository.
   Lưu ý: index.html phải nằm ở thư mục gốc của repository, không nằm trong một thư mục con.
3. Vào Settings > Pages.
4. Ở mục Build and deployment chọn Deploy from a branch.
5. Chọn branch main và folder /(root), sau đó Save.
6. Chờ GitHub Pages xuất bản website và dùng đường link GitHub cấp để chia sẻ.

ĐÃ TINH CHỈNH
- Header sticky, điều hướng rõ ràng và dễ dùng.
- Hero, thẻ dịch vụ, các khối nội dung, form và footer đồng bộ phong cách.
- Danh sách gói nạp dễ quét, bộ lọc rõ ràng, thẻ giá nhất quán.
- Bố cục QR và thông tin thanh toán responsive.
- Modal đăng nhập/đăng ký, form và trạng thái focus dễ nhìn hơn.
- Thông báo thao tác dạng toast thay cho alert gây gián đoạn.
- Tối ưu hiển thị trên desktop, tablet và điện thoại.
- Thêm metadata chia sẻ link, favicon, skip link và hỗ trợ giảm chuyển động.

GIỚI HẠN QUAN TRỌNG CỦA GITHUB PAGES
Đây là website tĩnh. Tài khoản, đơn hàng và lịch sử lưu bằng localStorage/sessionStorage của trình duyệt hiện tại:
- Không đồng bộ giữa các máy hoặc giữa các khách hàng.
- Người dùng có thể xóa dữ liệu trình duyệt.
- Không có Admin online dùng chung dữ liệu.
- Không có xác nhận tiền tự động hoặc tự động nạp vật phẩm.
- Mã QR là ảnh tĩnh; khách phải tự kiểm tra người nhận, số tiền và nội dung.
- Không nên xem thông tin xác thực client-side là bảo mật production.

TRƯỚC KHI NHẬN TIỀN THẬT
Cần triển khai backend/API, cơ sở dữ liệu, xác thực tài khoản phía máy chủ, trang Admin có phân quyền,
HTTPS, nhật ký giao dịch, sao lưu và tích hợp webhook/API thanh toán chính thức.
Không yêu cầu khách cung cấp mật khẩu hoặc OTP tài khoản game.
