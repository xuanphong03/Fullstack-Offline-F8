# float

- gồm 2 giá trị là left và right
- phần tử có float được nổi lên trên
- thu gọn phần tử về phía phải / trái
- làm cho chiều dài, chiều rộng của phần tử = content
  Khi một thành phần được CSS float là left hoặc right thì tất cả các thẻ cùng cấp phía sau nó sẽ được tràn lên phía trên và lấp đầy chỗ trống của hàng chứa thẻ được CSS float left hoặc right.
  Thuộc tính Clear ngăn chặn thành phần A chiếm vùng không gian của thành phần B (với thành phần B là thành phần sử dụng float)

clearfix: .clearfix::after { content: ""; clear: both; display: table;}
