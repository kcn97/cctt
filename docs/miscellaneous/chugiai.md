---
tags:
  - Reference
---

# Chú giải

```
[Di chuột vào đây](https://example.com "Tôi là một chú giải!")
``` 

[Di chuột vào đây](https://example.com "Tôi là một chú giải!")

***

```
[Di chuột vào đây][example]

  [example]: https://example.com "Tôi là một chú giải!"
```

[Di chuột vào đây][example]

  [example]: https://example.com "Tôi là một chú giải!"

***

``` 
:material-information-outline:{ title="Thông tin quan trọng" }
```
:material-information-outline:{ title="Thông tin quan trọng" }

***

```
 Đặc tả HTML được duy trì bởi W3C.

*[HTML]: Hyper Text Markup Language (Ngôn ngữ đánh dấu siêu văn bản)
*[W3C]: World Wide Web Consortium (Liên minh World Wide Web)
```

 Đặc tả HTML được duy trì bởi W3C.

*[HTML]: Hyper Text Markup Language (Ngôn ngữ đánh dấu siêu văn bản)
*[W3C]: World Wide Web Consortium (Liên minh World Wide Web)

## Từ điển thuật ngữ

Extension Snippets có thể được sử dụng để triển khai một từ điển thuật ngữ đơn giản bằng cách di chuyển tất cả các từ viết tắt vào một file riêng biệt, và tự động thêm file này vào tất cả các trang với cấu hình sau:

```title="includes/abbreviations.md"
*[HTML]: Hyper Text Markup Language (Ngôn ngữ đánh dấu siêu văn bản)
*[W3C]: World Wide Web Consortium (Liên minh World Wide Web)
```

Rất khuyến khích đặt file Markdown chứa các từ viết tắt bên ngoài thư mục docs (ở đây, thư mục có tên includes được sử dụng), vì MkDocs có thể khiếu nại về file không được tham chiếu. 