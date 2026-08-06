# Quy chuẩn chính tả viết tài liệu

Tài liệu "PFÉIV" cần được viết theo quy chuẩn chính tả như sau:

## Văn bản

- Văn bản đúng quy tắc chính tả và ngữ pháp Việt Nam hiện hành.
- Sử dụng ``` `` ``` và `''` để viết dấu ngoặc kép.
- Đảm bảo kí hiệu thống nhất trong tài liệu, trong đó bao gồm tên, kiểu hoa/thường, kiểu phông, kích cỡ, vân vân. Khi có thể, sử dụng những định dạng đã có trong `main.tex`.
- Chỉ sử dụng màu đen và những màu đã được định nghĩa sẵn trong `main.tex` để viết và vẽ (ngoài trừ hình ảnh ngoài).
- Đại từ nhân xưng: Khi cần ngôi thứ nhất, dùng "tác giả". Khi cần ngôi thứ hai, dùng "bạn đọc". Khi cần ngôi thứ nhất số nhiều mà bao gồm cả người đọc, dùng "chúng ta". Ví dụ điển hình: không viết `Ta có`, mà viết `Chúng ta có`.
- Chú thích tên bảng và tên hình cần phải có dấu chấm cuối câu.

## Toán học

- Với bài yêu cầu chứng minh, thì phải kết bằng "điều phải chứng minh" hoặc những câu mang ý nghĩa tương đương.
- Kí hiệu số bằng hàm `num{}` từ thư viện `sinunitx`. Trong trường hợp cần viết số thập phân mà không dùng được hàm `num{}`, đặt dấu phẩy trong ngoặc kép như trong $1{,}23$ (`1{,}23`).
- Kí hiệu tập hợp bằng kiểu liệt kê phần tử hay viết bộ số thì phân cách các phần tử bằng dấu `;`, kể cả các phần tử có phải là số hay không. Ví dụ: tập hợp $\left\{0; 1; 2\right\}$ hay bộ số $\left(a; b; c\right)$.
- Không viết dấu $\pm$ (`\pm`) hay $\mp$ (`\mp`).
- Khi viết bản thân hàm số, dùng nguyên tên hàm $f$ thay vì $f(x)$. Khi viết giá trị của hàm số thì dùng $f(x)$ thay vì $f$.
- Khi viết tọa độ của điểm trên đồ thị, luôn viết tọa độ trong dấu ngoặc đơn, kể cả khi trong tọa độ chỉ có 1 phần tử. Ví dụ: $(1)$, $(2; 3)$, $(4; 5; 6)$.
- Không chồng dấu kéo theo ($\implies$) hay dấu đẳng giá ($\iff$). Dưới đây là một ví dụ về cách viết bị cấm 
$$
2(x + 1) = 8 \iff x + 1 = 4 \iff x = 3.
$$
Ví dụ cho cách viết đúng, có thể viết lại như sau:
$$
\begin{aligned}
2(x + 1) = 8 &\iff x + 1 = 4; \\
2(x + 1) = 8 &\iff x = 3 && \left(\text{để ý cách dùng dấu câu và vị trí của chúng}\right),
\end{aligned}
$$
hoặc viết như sau (nhưng hạn chế)
$$
\begin{aligned}
2(x + 1) &= 8; \\
x + 1 &= 4; \\
x &= 3,
\end{aligned}
$$
hoặc sử dụng lời văn ngắn gọn để thay thế.
- Công thức toán viết liền đoạn hoặc đặt riêng một dòng vẫn là một phần cấu trúc ngữ pháp của câu văn. Do đó, ở cuối công thức trưng bày cần phải có dấu phẩy `,`, dấu chấm phẩy `;` hoặc dấu chấm `.` tùy thuộc vào vai trò của công thức đó trong câu.
- Không viết chữ nghiêng mặc định của môi trường toán cho các từ ngữ giải thích hoặc tên viết tắt. Cần đưa chúng về phông đứng bằng lệnh `\text{}` hoặc `\mathrm{}`. Ví dụ: viết $x_{\text{max}}$ (`x_{\text{max}}`) hoặc $x_{\mathrm{max}}$ (`x_{\mathrm{max}}`) thay vì viết $x_{max}$ (chữ $max$ bị nghiêng và rời rạc).

## Lập trình $\LaTeX$

- Đánh tên thành phần: Với những thành phần có `\label{}` thì đặt tên theo quy tắc sau: "Kiểu thành phần"`:`"Đường dẫn đến tệp chứ thành phần"`:`"Tên thành phần". Ví dụ: `fig:ham_so:ham_so_cap:x_2`. Viết thế này để tránh xung đột tên giữa các thành phần có cùng tên ở những tệp khác nhau.
