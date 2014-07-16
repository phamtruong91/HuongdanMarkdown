Hướng dẫn sử dụng Markdown
================

---
##Nội dung trình bày
1. Các thẻ tiêu đề
1. Đoạn văn bản
1. Trình bày theo danh sách
1. Liên kết
1. Chèn hình ảnh
1. Hiển thị code


1) Các Thẻ Tiêu Đề: h1, h2, h3, h4…
---

Markdown sử dụng kí tự # để bắt đầu cho các thẻ tiêu đề, dựa vào số lượng kí tự # liền nhau sẽ hiển thị ra HTML tương ứng.

Dòng lệnh:
```sh
# Thẻ H1

## Thẻ H2

### Thẻ H3

#### Thẻ H4
```
Kết quả là:
#Thẻ H1

##Thẻ H2

###Thẻ H3

####Thẻ H4

2) Đoạn Văn Bản
----

Tất cả nội dung văn bản không cần nằm trong thẻ nào hết, mặc định Markdown sẽ chuyển nội dung vào trong thẻ p của HTML

* Sử dụng kí tự _ hoặc * để in nghiêng: 
```sh
_in nghiêng_
*chữ in nghiêng*
```

    Kết quả:

    _in nghiêng_

    *chữ in nghiêng*

- Sử dụng kí tự __ hoặc để ** in đậm:

    ```sh
    __in đậm__
    **chữ in đậm**
    ```
    Kết quả:

    __in đậm__

    **chữ in đậm**

* Tạo đường kẻ gạch ngang

    Bạn gõ "---" hoặc "***" hoặc "___"

    Kết quả:

---

***

___



3) Trình bày theo danh sách
---

- Sử dụng kí tự * hoặc - đầu mỗi nội dung cần hiển thị

    ```sh
    * Nội dung 1
    
    * Nội dung 2
    
    * Nội dung 3
    ```
    Kết quả: 

    * Nội dung 1

    * Nội dung 2

    * Nội dung 3

- Danh Sách Có Sắp Xếp
    
    ```sh
    1. Nội dung 1
    
    1. Nội dung 2
    
    1. Nội dung 3
    
    1. Nội dung 4
    ```

    Kết quả:

    1. Nội dung 1
    1. Nội dung 2
    1. Nội dung 3
    1. Nội dung 4


Liên Kết
---

Để tạo liên kết bạn gõ như sau:

    ```sh
    [tên link](https://github.com)
    
    [tên link với chú thích](https://github.com "Website github")
    ```

Thay tên link là Github ta được kết quả:

[Github](https://github.com)

[Github](https://github.com "Website github")


Chèn Hình Ảnh
---

Cấu trúc như sau: bắt đầu bằng kí tự !

```sh
![Nội dung trong thẻ Alt](Đường Dẫn "Nội dung trong thẻ Title")
```


![Smile](http://i.imgur.com/MJ622DW.jpg "Smile")
