# Responsive

- Thiết kế web đáp ứng trên mọi thiết bị
- Dựa theo kích thước màn hình để thay đổi giao diện
- Sử dụng css thông qua at-rule @media (Media queries)
- Bản chất của responsive là ẩn hiện

# Breakpoint

- Điểm dùng tọa độ mà tại đó giao diện sẽ được thay đổi
- Không có break-point cố định trong mọi dự án
- Chỉ có các break-point phổ biến

Ví dụ:

- 576px
- 768px
- 992px
- 1200px
- 1400px

# Meta viewport

- Đảm bảo tỉ lệ của khung nhìn khi các bạn chuyển sang thiết bị có kích thước màn hình khác

# Media queries

css
@media all|screen|print and (min-width: giatri) and (max-width: giatri) {
Selector {
code css
}
}

# Trường phái responsive

1. Destop first: Đi từ màn hình lớn nhất

```
<= 1399.98px
<= 1199.98px
<= 991.98px
<= 767.98px
<= 575.98px
```

2. Mobile first

```
>= 576px
>= 768px
>= 992px
>= 1200px
>= 1400px
```
