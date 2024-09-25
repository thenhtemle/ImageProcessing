# ImageProcessing
Trong đồ án này, yêu cầu thực hiện các chức năng xử lý ảnh cơ bản sau khi nắm được khái niệm lưu trữ ảnh dưới dạng ma trận các điểm ảnh.
<font style='color:red'>**CHỈ ĐƯỢC PHÉP**</font> sử dụng các thư viện sau: `PIL`, `numpy`, `matplotlib`.
Cụ thể, nếu đề yêu cầu sinh viên cài đặt chức năng nào đó, thì sinh viên phải **thực sự cài đặt chức năng** đó mà không phải gọi hàm có sẵn.

- Đối với thư viện PIL và Matplotlib, sinh viên chỉ được sử dụng các hàm sau:
    - `PIL` (`open(), save()` từ `Image`) để đọc và ghi
    - `Matplotlib` (`imshow()` từ `pyplot`) để hiển thị ảnh
    - <ins>Lưu ý:</ins> <font style='color:red'>sử dụng các hàm khác (ngoài các hàm liệt kê trên)</font> $\to$ <font style='color:red'> NHẬN ĐIỂM 0 CHO TOÀN BỘ ĐỒ ÁN</font>

- Được phép sử dụng thư viện `NumPy` tùy ý

<ins>Lưu ý:</ins> Để được **điểm tối đa** cho từng chức năng, thời gian thực thi của mỗi chức năng phải nằm trong khoảng thời gian chấp nhận được. Ví dụ với chức năng làm mờ (phức tạp nhất) có thời gian thực thi trên ảnh với kích thước $512 \times 512$ là dưới 15 giây.
