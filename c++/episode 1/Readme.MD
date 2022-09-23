Line 1: `#include <iostream>` là một thư viện tệp tiêu đề cho phép chúng tôi làm việc với các đối tượng đầu vào và đầu ra, chẳng hạn như cout (được sử dụng trong dòng 5). Tệp tiêu đề bổ sung chức năng cho các chương trình C ++.

Line 2: `using namespace std` có nghĩa là chúng ta có thể sử dụng tên cho các đối tượng và biến từ thư viện chuẩn.

> Đừng lo lắng nếu bạn không hiểu về cách thức `#include <iostream>` và `using namespace std` hoạt động của nó. Chỉ cần nghĩ về nó như một cái gì đó (hầu như) luôn xuất hiện trong chương trình của bạn.

Dòng 3: Một dòng trống. C ++ bỏ qua khoảng trắng. Nhưng chúng tôi sử dụng nó để làm cho mã dễ đọc hơn.

Dòng 4: Một thứ khác luôn xuất hiện trong chương trình C ++, đó là int main(). Đây được gọi là một hàm . Bất kỳ mã nào bên trong dấu ngoặc nhọn của nó {}sẽ được thực thi.

Dòng 5: `cout` (phát âm là "see-out") là một đối tượng được sử dụng cùng với toán tử chèn ( `<<`) để xuất / in văn bản. Trong ví dụ của chúng tôi, nó sẽ xuất ra "Hello World".

> Lưu ý: Mọi câu lệnh C ++ đều kết thúc bằng dấu chấm phẩy ;.

>Lưu ý: Phần thân của `int main()` cũng có thể được viết là: `int main () { cout << "Hello World! "; return 0; }`

Hãy nhớ rằng: Trình biên dịch bỏ qua khoảng trắng. Tuy nhiên, nhiều dòng làm cho mã dễ đọc hơn.

Dòng 6: `return 0` kết thúc chức năng chính.

Dòng 7: Đừng quên thêm dấu ngoặc nhọn đóng `}` để thực sự kết thúc hàm main.