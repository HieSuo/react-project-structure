# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Project Stucture:
node_moudles
public
src
--/assets
--/components: 
    Chứa các thành phần components có thể tái sử dụng, được chia sẻ giữa nhiều phần khác nhau của ứng dụng.
    Những thành phần này thường là các KHỐI XÂY DỰNG NHỎ giúp xây dựng giao diện
--/context:
    Đây là nơi quản lý trạng thái toàn cục (Global state) bằng ContextAPI hoặc logic liên quan đến Redux.
    Thư mục này đjăc biệt hữu ích khi cần chia sẻ trạng thái giữa nhiều thành phần trong ứng dụng.
--/data:
    Chứa dữ liệu tĩnh hoặc các mô hình dữ liệu (data model) mà ứng dụng sử dụng.
    Ví dụng: danh sách sản phẩm, cấu hình, hoặc dữ liệu mẫu, mock data.
--/features:
    Tổ chức các mô-đun theo tính năng, nhóm các thành phần kiểu dáng, và logic liên quan với nhau.
    Cách tổ chức này giúp phân chia rõ ràng từng chức năng trong ứng dụng.
--/pages:
    Chứa các thành phần cấp trang, thường được sử dụng trong cấu trúc định tuyến của React-Router hoặc Next.Js.
    Đây là nơi bạn định nghĩa các trang như trang chủ, trang chi tiết sản phẩm, hoặc trang liên hệ.
--/hooks:
    Lưu trữ các hooks tùy chỉnh trong React.
    Những hooks này giúp đóng góp logic tái sử dụng.
    Ví dụ:L hooks để xử lý biểu mẫu hoặc kết nối API.
--/layouts:
    Gồm các thành phần định hình cấu trúc ứng dụng, như header, footer, hoặc các trình bao (layout wrapper).
    Đây là nơi bạn quản lý giao diện chung cho toàn bộ ứng dụng.
--/lib:
    Chứa các thư viện bên ngoài, tiện ích, hoặc các tích hợp với hệt thống khác.
    Những phần này thường là các công cũ hỗ trợ cho logic ứng dụng.
--/services:
    Quảng lý các cuộc gọi API, kết nối với các dịch vụ bên ngoài, hoặc tích hợp với thư viện bên thứ ba.
    Đây là nơi bạn xử lý dữ liệu đến và đi từ máy chủ.
--/styles:
    Lưu trữ các tệp CSS, SCSS, hoặc các tệp kiểu dáng toàn cục và kiểu dáng riêng dành cho từng thành phần.
    Giúp quản lý và tái sử dụng các quy tắc kiểu dáng dễ dàng.
--/utils:
    Chứa các hàm tiện ích và các helper dùng chung cho toàn bộ ứng dụng.
    Ví dụ: Định dạng ngày tháng, xử lý chuỗi, hoặc kiểm tra dữ liệu đầu vào.
----