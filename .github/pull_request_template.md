# Fixel check list

## Component

- [ ]  Kiểm tra xem CSS có đang bị ghi đè lên layout gốc mà không tùy chỉnh component hiện tại
- [ ]  Tạo dummy data cho các component để hỗ trợ việc hiển thị sample
- [ ]  Tái sử dụng những component đã tồn tại
- [ ]  Kiểm tra tính đồng nhất giữa component và thiết kế (figma)
- [ ]  Kiểm tra inject event giao tiếp giữ parent & child component. Dùng console.log() để hiển thị việc thực hiện thành công event
- [ ]  Nếu component phức tạp có thể chia nhỏ
- [ ]  Nếu sử dụng thư viện ngoài trong trường hợp install mới so với thư viện hiện có của khách:
    - [ ]  Kiểm tra xem thư viện còn được hỗ trợ từ nhà điều hành không
    - [ ]  Kiểm tra license có sẵn cho mục đích thương mại hay không

## HTML

- [ ]  Kiểm tra với markupLint
- [ ]  Kiểm tra cấu trúc ngữ nghĩa của các thành phần
- [ ]  Không được đặt CSS inline
- [ ]  Kiểm tra trùng lặp ID

## CSS

- [ ]  Sử dụng Slot để tạo các lớp cục bộ
- [ ]  Khi tạo util class phải follow theo quy tắc giãn cách khoảng trắng
- [ ]  Bạn đã follow theo quy tắc BEM chưa
- [ ]  Kiểm tra xem có styles không sử dụng nào không ?
- [ ]  Đặt tên class name có match với component naming từ figma

## CODE

- [ ]  Kiểm tra xem bị lặp IDS không?
- [ ]  Customize component phải check ảnh hưởng của nó tới các thành phần khác (Kiểm tra hàng ngang)
- [ ]  Kiểm tra lỗi chính tả
- [ ]  commit / push phải trực quan các action thực hiện
- [ ]  Loại bỏ những câu lệnh không cần thiết
- [ ]  Loại bỏ comment code
- [ ]  Kiểm tra cách đặt tên biến, tên hàm (không sử dụng từ viết tắt)
- [ ]  Loại bỏ console.log để gỡ lỗi
- [ ]  Kiểm tra lỗi và warnning trong trình duyệt
- [ ]  Các EventListener có được xóa đúng các chưa? tránh hiện thực memories leak
- [ ]  Sử dụng let thay vì sử dụng keyword var để khai báo biến
- [ ]  Không sử dụng biến toàn cục, sử dụng biến cục bộ với phạm vi nhỏ nhất càng tốt