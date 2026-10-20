# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session5_Ex7
## Phần 1: Phân Tích Vấn Đề
* **Nguyên nhân gây ra lỗi (`Cannot find path`):** 
  Khi gõ lệnh `cd Menu Thang 9` mà không có dấu ngoặc kép, Terminal hiểu các khoảng trắng là dấu phân cách giữa các tham số độc lập. Thay vì nhận diện đây là một thư mục duy nhất, hệ thống hiểu lầm đang truyền vào 3 tham số (`Menu`, `Thang`, `9`), dẫn đến lỗi không tìm thấy đường dẫn.
  
## Phần 2: Hoàn Thiện Bài Làm
Các cách viết lệnh `cd` chuẩn xác để truy cập vào thư mục có chứa khoảng trắng:

* Cách 1 (Khuyên dùng trên Windows):** Sử dụng dấu ngoặc kép để bảo vệ chuỗi ký tự.

 cd "Menu Thang 9"

* Cách 2 (Sử dụng ký tự thoát khoảng trắng): Dùng dấu gạch chéo ngược (\) trước mỗi khoảng trắng.


 cd ./Menu\Thang\9
