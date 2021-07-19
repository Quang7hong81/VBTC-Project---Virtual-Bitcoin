---
layout: post
title:   Phí Maker / Taker (Bài hướng dẫn 1)
date:   2020-11-10 10:48:00 +0700
---
## Phí Maker / Taker (Bài hướng dẫn 1)

Phí giao dịch Maker và Taker hiện tại trên VBTC ở các mức sau:

> Phí Maker: 0,00%
Phí Taker: 0,25%

#### Nếu bạn chưa hiểu hết về thuật ngữ phí maker và taker, vui lòng đọc tiếp:

**Phí maker (0,00%)** được áp dụng khi bạn *cung cấp* thanh khoản cho sổ lệnh thay vì *lấy đi* thanh khoản.
Đây là trường hợp khi bạn đặt lệnh mua mà nó không khớp (khi bạn đang mua) với bất kì lệnh bán nào ("lifting the ask") hay khi bạn đang bán mà không khớp với bất cứ lệnh mua nào ("hitting the bid").

**Phí taker (0,25%)** được áp dụng khi bạn *lấy đi* thanh khoản khỏi sổ lệnh thay vì *tạo thêm* thanh khoản cho sổ lệnh.
Đây là trường hợp khi bạn đặt lệnh mua mà không khớp lệnh bán nào ("lifting the ask") hoặc khi bạn đang bán mà không được khớp với lệnh mua có sẵn nào ("hitting the bid").

#### Ví dụ hình ảnh:

Trong ảnh chụp màn hình bên dưới, bất kì lệnh mua nào dưới 355,999,900VNĐ/BTC và lệnh bán nào trên 354,000,000 VNĐ sẽ được đặt vào sổ lệnh dưới dạng "lệnh maker" (và cần ai đó khớp lệnh với bạn).

![](https://blog.vbtc.exchange/assets/posts/2020-11-10-maker-taker-fee-tutorial-1/maker-taker-fee-screenshot.png)

Trong ảnh chụp màn hình bên trên, lệnh mua nào ngay tại hoặc trên 355,999,900VNĐ/BTC, cũng như lệnh bán nào ngay tại hoặc dưới 354,000,000 VNĐ sẽ được đưa vào sổ lệnh dưới dạng "lệnh taker" (và được khớp ngay lập tức).

#### Tìm hiểu thêm:

Trong khi lệnh maker thường có phí rẻ hơn, nó có chi phí dạng khác:

Lệnh taker thường được khớp ngay lập tức vì bạn đang lấy lệnh mua/bán được người khác đặt sẵn ra khỏi sổ lệnh, với lệnh maker thì bạn phải đợi ai đó để mua/bán với mức giá bạn chỉ định.

Điều này dẫn đến đôi khi giá thị trường sẽ di chuyển xa khỏi vùng giá ban đầu của lệnh bạn đặt. Và kết quả đôi khi sẽ tốn chi phí hơn lệnh taker khớp ngay lúc đó.

Loại lệnh nào phù hợp với bạn phụ thuộc vào tuỳ chọn thời gian/mức độ mong muốn được khớp lệnh của bạn. Cũng như là chiến lượt giao dịch tổng thể.

*10.11.2020 - phí giao dịch trên VBTC đã luôn giữ nguyên từ nhiều năm nay.*
