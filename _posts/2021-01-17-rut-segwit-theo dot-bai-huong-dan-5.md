---
layout: post
title:   Rút SegWit Theo Đợt (Bài Hướng Dẫn 5)
date:   2021-01-17 20:55:00 +0700
---
Xin chúc mừng! Bạn đã mua Bitcoin đầu tiên của mình trên VBTC và hiện đang tìm cách rút Bitcoin ra khỏi sàn.

Nhưng khoan đã... Phí rút 0.001 BTC cho các giao dịch onchain là gì?

Nếu bạn chỉ mua một lượng nhỏ Bitcoin và chủ yếu muốn chuyển nó cho người dùng hoặc dịch vụ Bitcoin khác, bạn có thể cân nhắc rút bằng [Mạng Lightning](https://blog.vbtc.exchange/2020/how-to-withdraw-bitcoin-lightning-network-tutorial-3).

Tuy nhiên - nếu bạn đang muốn nhận Bitcoin trên chuỗi và không gấp, bạn hiện có thể sử dụng tùy chọn rút tiền “SegWit theo đợt” để tiết kiệm đáng kể 80% phí rút tiền [hiện tại là 0,0002 BTC mỗi lần rút].

VBTC sẽ xử lý các khoản rút tiền đã lên lịch chờ này theo cách thủ công vào mỗi cuối tuần để tối thiểu hóa [phí giao dịch phải trả] (http://mempool.space).

Trong bài viết này, chúng ta sẽ tìm hiểu cách bạn có thể tiết kiệm 80% chi phí rút tiền thông qua tùy chọn rút tiền “Mức độ khẩn cấp thấp - SegWit theo đợt”.

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image1.jpg)

#### Không vội vàng? Chọn rút tiền SegWit theo đợt!

Nếu bạn không cần nhận Bitcoin của mình gấp trong khối tiếp theo được đào (khoảng 10 phút), thì bây giờ bạn có thể chọn các tùy chọn rút tiền SegWit theo đợt.

Rút tiền tức thì được gửi dưới dạng một giao dịch duy nhất, vào thời điểm bạn xác nhận việc rút tiền, với một khoản phí cao để nhận được xác nhận nhanh - Còn rút tiền theo đợt SegWit sẽ tìm cách tối thiểu hóa chi phí giao dịch cần thiết.

VBTC có thể cung cấp giải pháp này nhờ:
- Gộp nhiều lần rút tiền vào một giao dịch duy nhất
- Canh chỉnh thời gian gửi giao dịch có lượng tồn đọng giao dịch thấp trong [Mempool](http://mempool.space)
- Sử dụng địa chỉ hiệu quả hơn [[bc1… - còn được gọi là “Địa chỉ SegWit gốc’](https://en.bitcoin.it/wiki/Invoice_address)]

Hiện tại, việc rút tiền SegWit theo đợt được xử lý vào mỗi cuối tuần.

Thời gian giới hạn nhất định được đưa vào thanh toán hàng tuần là vào mỗi **Thứ Sáu, 6 giờ chiều múi giờ Việt Nam**.
 
#### Làm gì để nhận được tiền rút từ SegWit?

Trước hết, bạn cần ví hỗ trợ SegWit và cung cấp cho VBTC khi gửi yêu cầu rút tiền với địa chỉ SegWit gốc hợp lệ (địa chỉ “bc1…”, để biết thêm thông tin, bạn có thể đọc mục Bitcoin Wiki trên [Bech32](https://en.bitcoin.it/wiki/Bech32 "Bech32")*).

Trên VBTC, hãy chuyển đến “Rút tiền” và nhấp vào “Rút Bitcoin”.

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image3.jpg)

Chọn tùy chọn “Bitcoin (Mức độ khẩn cấp thấp để giảm phí - Thanh toán hàng tuần qua Segwit theo đợt)”

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image1.jpg)

Nhập số lượng Bitcoin bạn muốn rút và sao chép địa chỉ SegWit gốc của bạn vào ô tương ứng. *

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image2.jpg)

Và thế là hoàn tất!

Vì việc rút tiền được đội ngũ chúng tôi xử lý thủ công để bảo mật, nên việc rút tiền không diễn ra ngay lập tức nhưng thường sẽ đến ví của bạn vào mỗi cuối tuần, trong quá trình xử lý các khoản rút SegWit được lên lịch của khách hàng.
 
**Địa chỉ không phải bc1… sẽ bị tính thêm phụ phí 0.00005 BTC vì không sử dụng định dạng giao dịch hiệu quả nhất về không gian khối.*

---

*Nếu bạn muốn tìm hiểu thêm về quá trình xử lý giao dịch Bitcoin, cách sử dụng mempool và “thị trường phí” và sống tại Việt Nam, chúng tôi gợi ý bạn nên tham gia [cộng đồng Bitcoin tại Sài Gòn](http://bitcoinsaigon.org/), nơi nhiều doanh nhân đang xây dựng các dịch vụ khác nhau trên Mạng Bitcoin.*