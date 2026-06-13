# Quy chuẩn chính tả viết tài liệu

Tài liệu "Ôn tập Vật Lí" cần được viết theo quy chuẩn chính tả như sau:

## Văn bản

- Văn bản đúng quy tắc chính tả và ngữ pháp Việt Nam hiện hành.
- Sử dụng ``` `` ``` và `''` để viết dấu ngoặc kép.
- Đảm bảo kí hiệu thống nhất trong tài liệu, trong đó bao gồm tên, kiểu hoa/thường, kiểu phông, kích cỡ, v.v. Tốt nhất, định nghĩa định dạng trong `main.tex` và sử dụng từ đó.
- Đại từ nhân xưng: Khi dùng ngôi thứ nhất mà không chỉ bạn đọc, dùng "tác giả". Khi dùng ngôi thứ hai, dùng "bạn đọc". Khi dùng ngôi thứ nhất số nhiều mà bao gồm cả người đọc, dùng "chúng ta".
- Chú thích tên bảng và tên hình cần phải có dấu chấm cuối câu.

## Toán học
- Với bài yêu cầu chứng minh, thì phải kết bằng "điều phải chứng minh" hoặc những câu mang ý nghĩa tương đương.
- Số thập phân kí hiệu bằng dấu phẩy (","). Để làm như vậy, hàm `num{}` từ thư viện `sinunitx` được sử dụng.
- Kí hiệu tập hợp bằng kiểu liệt kê phần tử hay viết bộ số thì phân cách các phần tử bằng dấu `;`, kể cả các phần tử có phải là số hay không. Ví dụ: tập hợp $\left\{0; 1; 2\right\}$ hay bộ số $\left(a; b; c\right)$.
- Không viết dấu $\pm$ (`\pm`).
- Khi viết bản thân hàm số, dùng nguyên tên hàm $f$ thay vì $f(x)$. Khi viết giá trị của hàm số thì dùng $f(x)$ thay vì $f$.
- Khi viết tọa độ của điểm trên đồ thị, luôn viết tọa độ trong dấu ngoặc đơn, kể cả khi trong tọa độ chỉ có 1 phần tử. Ví dụ: $(1)$, $(2; 3)$, $(4; 5; 6)$.

## Lập trình $\LaTeX$

- Đánh tên thành phần: Với những thành phần có `\label{}` thì đặt tên theo quy tắc sau: "Kiểu thành phần"`:`"Đường dẫn đến tệp chứ thành phần"`:`"Tên thành phần". Ví dụ: `fig:ham_so:ham_so_cap:x_2`. Viết thế này để tránh xung đột tên giữa các thành phần có cùng tên ở những tệp khác nhau.
