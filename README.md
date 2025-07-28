# BTL-OOP
Bài tập lớn OOP nhóm 11
HƯỚNG DẪN SỬ DỤNG ỨNG DỤNG QUẢN LÝ ĐỐI TƯỢNG ĐẶC BIỆT
===============================================================

CÁCH CHẠY ỨNG DỤNG:
1. Giải nén file nhom11de13
2. Vào thư mục Project java, vào tiếp thư mục DTDBv1
3. Double click vào file "ChayUngDung.bat" để khởi động ứng dụng
4. Hoặc double click vào file "ChayTrucTiep.bat" (chạy nhanh)

YÊU CẦU HỆ THỐNG:
- Máy tính phải cài đặt Java (JRE) phiên bản 8 trở lên
- Nếu chưa cài Java, vui lòng tải từ: https://www.java.com/download/

CÁC FILE QUAN TRỌNG:
- ChayUngDung.bat: File batch để khởi động ứng dụng (có thông báo)
- ChayTrucTiep.bat: File batch chạy nhanh (không có thông báo)
- target/QuanLyDoiTuongDacBiet-1.0-SNAPSHOT.jar: File ứng dụng chính
- lib/: Thư mục chứa các thư viện cần thiết
- jcalendar-1.4.jar: Thư viện date picker
- jaxb-api.jar, jaxb-impl.jar, activation.jar, istack-commons.jar: Thư viện JAXB cho Java mới
- lib/unknown/binary/*/SNAPSHOT/*.jar: Các thư viện khác (TimingFramework, KGradientPanel, v.v.)
- lib/unknown/binary/mysql-connector-java-5.1.23-bin/SNAPSHOT/*.jar: MySQL connector cho database
- lib/unknown/binary/TimingFramework-0.55/SNAPSHOT/*.jar: Thư viện animation cho giao diện
- TimingFramework.jar: File TimingFramework đã copy ra thư mục gốc

LƯU Ý:
- Ứng dụng sử dụng classpath để load tất cả dependencies
- Đã khắc phục lỗi "ClassNotFoundException: com.toedter.calendar.JDateChooser"
- Đã khắc phục lỗi "ClassNotFoundException: javax.xml.bind.JAXBException"
- Đã khắc phục lỗi "ClassNotFoundException: com.sun.istack.Pool"
- Đã khắc phục lỗi "ClassNotFoundException: org.jdesktop.animation.timing.TimingTarget"
- Đã thêm MySQL connector để hỗ trợ kết nối database
- Đã thêm các thư viện UI (KGradientPanel, AbsoluteLayout) cho giao diện
- Đã thêm TimingFramework cho animation và hiệu ứng
- Sử dụng thư viện JAXB riêng để tương thích với Java mới (Java 9+)
- Tất cả chức năng trong ứng dụng giờ đây sẽ hoạt động bình thường
- KHÔNG xóa hoặc di chuyển các file .jar trong thư mục này
 
