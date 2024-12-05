# Chương trình đơn giản

**1. Quy ước đặt tên**

- Các biến - hằng (const) - đối tương đặt tên theo quy chuẩn sau
  - aA -> zZ
  - 0 -> 9
  - dùng dấu "\_"

> **_NOTE:_**
>
> - Tên phải bắt đầu từ chữ cái
> - Để dễ hiểu và dễ nhớ , tên thường đặt theo 1 quy chuẩn và gợi nhớ ( có liên quan đến ngữ nghĩa của đối tượng)

**2. Khái niệm về nhập , xuất , tính toán**

- Nhận dữ liệu từ người dùng ( click chuột , bàn phím , thao tác nào đó để gửi tín hiệu cho máy tính) -> gọi là nhập dữ liệu

- Trả ra kết quả từ thao tác của người dùng -> xuất dữ liệu

- Tính toán hay xử lý dữ liệu nhập 1 cách thích hợp để ra được kết quả -> gọi là tính toán dữ liệu

```js
class Calculator {
    int add(int a, int b) {

      let current = 0;
      current = a + b;

      return current;
    }
}
```

**3. Các kiểu dữ liệu và phép toán**

**3.1 Kiểu số nguyên**

![alt text](image/bieu-dien-nhi-phan.png)
Link: https://rdsic.edu.vn/blog/toan/giai-ma-so-nguyen-khong-dau-nhung-bi-mat-quanh-so-hoc-nguyen-to-vi-cb.html

- Kiểu Char:

  - Phạm vi lưu trữ: 1-byte (8-bit)
  - khoảng từ -127 -> 127 ký tự

- Kiểu
