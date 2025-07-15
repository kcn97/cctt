# Bắt đầu

Chào mừng bạn đến với dự án [CÔNG CỤ & THỦ THUẬT](https://github.com/kcn97/cctt) trên GitHub! Dự án này tập hợp các công cụ và thủ thuật hữu ích trong công việc hàng ngày.

Dự án bao gồm một website tài liệu được xây dựng bằng MkDocs-Material, giới thiệu các tính năng như menu điều hướng, tìm kiếm tùy chỉnh, và thiết kế responsive. Tôi đã tổ chức nội dung thành các chuyên mục khác nhau để dễ dàng tra cứu và sử dụng.

Dự án này được tạo ra nhằm mục đích chia sẻ kiến thức và kinh nghiệm, hy vọng sẽ hữu ích cho những ai quan tâm. Tôi sẽ tiếp tục cập nhật và bổ sung nội dung theo thời gian, vì vậy hãy thường xuyên ghé thăm để cập nhật những thông tin mới nhất!

Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, hãy thoải mái mở issue hoặc submit pull request. Cảm ơn bạn đã quan tâm đến dự án!

## Các chuyên mục chính

### 📚 [Danh mục](danhmuc.md)
Tổng hợp các danh mục và phân loại công cụ, thủ thuật.

### 🤝 [Cộng tác](congtac.md)
Các công cụ và phương pháp hỗ trợ cộng tác, làm việc nhóm.

### 📋 [Quản lý](quanly.md)
Thủ thuật quản lý dự án, tác vụ và tổ chức công việc.

### 📖 [Dạy học](dayhoc.md)
Công cụ và phương pháp hỗ trợ giảng dạy và học tập.

### ⚡ [Hiệu suất](hieusuat.md)
Các kỹ thuật tối ưu hóa hiệu suất làm việc.

### 🧹 [Dọn dẹp](dondep.md)
Công cụ và phương pháp dọn dẹp, tổ chức file và dữ liệu.

### 🤖 [AI & Hỗ trợ](aihotro.md)
Công cụ AI và các dịch vụ hỗ trợ thông minh.

!!! info "Tài liệu tham khảo"
        * [MkDocs](https://www.mkdocs.org)
        * [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/)
        * [Markdown](https://daringfireball.net/projects/markdown)

## Bắt đầu sử dụng

### Yêu cầu hệ thống

#### Python

Cài đặt [Python](https://www.python.org/) bằng package manager hoặc tải installer từ [python.org](https://www.python.org/downloads/) và chạy nó.

#### pip

Nếu bạn đang sử dụng Python phiên bản mới, [pip](https://pip.pypa.io/en/stable/installing/) thường được cài đặt mặc định. Tuy nhiên, bạn có thể cần nâng cấp pip lên phiên bản mới nhất:

    $ pip install --upgrade pip

Nếu cần cài đặt pip lần đầu, tải [get-pip.py](https://bootstrap.pypa.io/get-pip.py) và chạy lệnh sau:

    $ python get-pip.py

### Cài đặt MkDocs với MkDocs-Material

1. Cài đặt các package cần thiết bằng pip:

        $ pip install mkdocs-material mkdocs[i18n] mkdocs-glightbox mkdocs-git-revision-date-localized-plugin mkdocs-table-reader-plugin

2. Clone repository:

        $ git clone git@github.com:kcn97/cctt.git

3. Chuyển đến thư mục dự án:

        $ cd cctt

4. Chạy lệnh để khởi động server local:

        $ mkdocs serve

5. Mở [http://127.0.0.1:8000/](http://127.0.0.1:8000/) trong trình duyệt để xem trang chủ        

## Cấu trúc dự án

    mkdocs.yml    # File cấu hình chính.
    docs/
        index.md       # Trang chủ tài liệu.
        danhmuc.md     # Danh mục công cụ.
        congtac.md     # Cộng tác.
        quanly.md      # Quản lý.
        dayhoc.md      # Dạy học.
        hieusuat.md    # Hiệu suất.
        dondep.md      # Dọn dẹp.
        aihotro.md     # AI & Hỗ trợ.
        ...            # Các file markdown và tài nguyên khác.    
