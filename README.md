# Mua VPS Nhật Bản: Bảng giá thật của GreenCloud, cách chọn line IIJ hay SoftBank và những hạn chế cần biết trước khi đặt hàng

Mua VPS Nhật Bản hiện nay có một lựa chọn rất rẻ mà ít bài viết tiếng Việt nào nhắc tới: GreenCloudVPS, với gói KVM tại Tokyo khởi điểm **25 USD/năm** — khoảng 640.000đ theo tỷ giá hiện tại, tức chưa tới 1.800đ mỗi ngày — cho 1 core, 2GB RAM, ổ NVMe 25GB và cổng mạng 10Gbps. Cùng tầm cấu hình đó nếu mua theo gói tháng của các nhà cung cấp hướng tới thị trường Việt Nam, mức giá thường dao động từ 100.000đ/tháng trở lên, và cổng mạng chỉ có 100 Mbps.

Bài viết này tập trung vào ba việc: liệt kê các gói VPS Tokyo đang mở bán của GreenCloud kèm giá đã kiểm chứng, giải thích sự khác nhau giữa hai line IIJ và SoftBank, và chỉ ra những hạn chế mà bạn chỉ thấy khi đọc kỹ trang đặt hàng — điều mà phần lớn các bài giới thiệu VPS Nhật bỏ qua.

> **Chọn nhanh:** Đa số người cần một VPS Nhật giá thấp để chạy bot, proxy riêng, web nhỏ hoặc chứa dữ liệu thì gói **KVM 1 core · 2GB RAM · 25 USD/năm** là điểm khởi đầu hợp lý nhất. Cần nhiều RAM và CPU hơn thì lên gói 4 core · 8GB (68 USD/năm). Bạn có thể 👉 [xem các gói VPS Nhật Bản đang mở bán của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679) để kiểm tra tồn kho trước khi đọc tiếp.

## Các gói VPS Nhật Bản đang bán của GreenCloud

GreenCloud là nhà cung cấp VPS của Mỹ, hoạt động từ 2013, có máy chủ tại khoảng 30 vị trí trên khắp thế giới. Riêng Tokyo, GreenCloud chia thành hai line mạng riêng biệt: **SoftBank** (đi qua upstream xTom Japan, AS3258) và **IIJ**. Các gói đều dùng công nghệ ảo hóa KVM, bảng điều khiển VirtFusion, hệ điều hành Linux, kèm 1 IPv4 và IPv6.

Dòng đang được chú ý nhất tại Tokyo là **Premium KVM Sale** (đợt bổ sung hàng gần nhất vào giữa tháng 10/2026), dùng CPU AMD EPYC Milan và ổ NVMe RAID10:

| Gói | Line | Cấu hình | Lưu lượng/tháng | Giá/năm | Đặt hàng |
| --- | --- | --- | --- | --- | --- |
| Premium KVM 1 | IIJ hoặc SoftBank (cùng giá) | 1 core · 2GB RAM · 25GB NVMe | 750GB | 25 USD | [ Đặt gói Premium KVM 1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Premium KVM 2 | IIJ hoặc SoftBank (cùng giá) | 2 core · 3GB RAM · 35GB NVMe | 1TB | 35 USD | [ Đặt gói Premium KVM 2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Premium KVM 3 | IIJ hoặc SoftBank (cùng giá) | 4 core · 8GB RAM · 60GB NVMe | 2TB | 68 USD | [ Đặt gói Premium KVM 3](https://greencloudvps.com/billing/aff.php?aff=6679) |

Ngoài dòng trên, Tokyo còn có **Storage KVM Sale** — dòng dành cho nhu cầu chứa dữ liệu lớn, cấu hình gồm ổ SSD NVMe cho hệ điều hành cộng thêm một ổ HDD dung lượng lớn riêng biệt:

| Gói | Line | Cấu hình | Lưu lượng (in+out) | Giá/năm | Đặt hàng |
| --- | --- | --- | --- | --- | --- |
| Storage 0.5TB | SoftBank hoặc IIJ (cùng giá) | 1 core · 2GB RAM · 520GB HDD | 1TB · cổng 10Gbps | 25 USD | [ Đặt gói Storage 0.5TB](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Storage 1TB | SoftBank hoặc IIJ (cùng giá) | 2 core · 3GB RAM · 1040GB HDD | 2TB · cổng 10Gbps | 45 USD | [ Đặt gói Storage 1TB](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Storage 2TB | SoftBank hoặc IIJ (cùng giá) | 4 core · 6GB RAM · 2060GB HDD | 4TB · cổng 10Gbps | 80 USD | [ Đặt gói Storage 2TB](https://greencloudvps.com/billing/aff.php?aff=6679) |

Vài gói khác tại Tokyo, mỗi gói phục vụ một nhu cầu khác nhau:

- **Gói KVM value 1 core · 1GB RAM · 15GB SSD**: 48 USD/năm, lưu lượng 750GB/tháng, chọn được cả line IIJ lẫn SoftBank. Lưu ý cùng mức giá này, các máy chủ ở châu Âu và Mỹ được cấp tới 1.5TB lưu lượng — GreenCloud quy định hạn mức thấp hơn cho các vị trí châu Á.
- **Budget KVM (line IIJ)**: 2 core Xeon E5 · 4GB RAM · 35GB SSD RAID-10 · 750GB lưu lượng · cổng 10Gbps, kèm 1 lần backup/snapshot miễn phí. Giá gói này thay đổi theo đợt mở bán, xem trực tiếp trên trang đặt hàng.
- **CN Premium Optimized Mini**: 1 core EPYC Milan · 2GB RAM · 20GB NVMe · 500GB lưu lượng · cổng 500Mbps, chạy trên line tối ưu cho Trung Quốc (CN2GIA / CU PREMIUM / CMIN2), có backup hằng ngày. Tại thời điểm tháng 10/2026, gói này đang hết hàng.
- **CN Premium Optimized 1**: 2 core EPYC Milan · 4GB RAM · 40GB NVMe · 1TB lưu lượng · cổng 1Gbps, cùng line tối ưu Trung Quốc, cho phép 1Gbps không giới hạn khi kết nối tới các máy chủ khác của GreenCloud trong hệ thống IIJ/Softbank.

Hai gói CN Premium hướng tới người dùng tại Trung Quốc đại lục; nếu đối tượng phục vụ của bạn ở Việt Nam hoặc quốc tế, chúng không có gì hơn hai line IIJ/SoftBank ngoài cái giá đắt hơn. Lưu ý chung cho cả hai bảng trên: cổng 10Gbps là thông số danh nghĩa của cổng mạng, không đồng nghĩa với tốc độ riêng tư dành riêng cho bạn.

## Tổng chi phí thực sự là bao nhiêu?

Đây là phần mà các bài viết tiếng Việt hiện có về VPS Nhật Bản gần như không tính kỹ. Giá niêm yết thấp chưa đủ; cần so theo chu kỳ thanh toán mà nhà cung cấp cho phép.

Lấy một điểm so sánh đã kiểm chứng: nhà cung cấp Cloud Cheap bán VPS Nhật Mini 1 core · 1GB RAM · 12GB SSD với giá 100.000đ/tháng và **chỉ cho thuê theo tháng** — tức 1.200.000đ nếu chạy đủ một năm, với cổng mạng 100 Mbps tải xuống và chỉ 10 Mbps tải lên. Gói Premium KVM của GreenCloud là 25 USD **một lần cho cả năm** (khoảng 640.000đ), RAM gấp đôi, ổ NVMe và cổng mạng lớn hơn hẳn.

So ở tầm cấu hình cao hơn, chênh lệch càng rõ: gói Global 2 vCores · 4GB RAM · 30GB SSD của Cloud Cheap tại Nhật là 250.000đ/tháng, tức 2.100.000đ/năm. Gói Premium KVM 2 của GreenCloud — 2 core · 3GB RAM · 35GB NVMe — là 35 USD/năm, khoảng 897.000đ, chưa bằng một nửa. Bù lại, Cloud Cheap cho thuê theo tháng và hỗ trợ Windows Server trên form đặt hàng, trong khi GreenCloud đánh thuế sự linh hoạt bằng chính sách "mua năm, không hoàn".

Một chi tiết về cách GreenCloud định giá: các con số tốt thường gắn với đợt bổ sung hàng hoặc các dịp khuyến mãi định kỳ (Holiday Sale, Black Friday, kỷ niệm thành lập) chứ không phải mã giảm giá cố định. Trong đợt khuyến mãi kỷ niệm năm 2025, gói 2 vCPU · 4GB RAM · 20GB ổ tại Tokyo từng được bán 22 USD/năm trên cả hai line. Đợt kỷ niệm tháng 11/2026, hai mã gói 1313 và 2222 bị cháy hàng ngay trong ngày đầu, lượt mua thêm không thành và xuất hiện chuyện bán lại giá cao hơn trên thị trường thứ cấp. Hàng tốt thường không tồn tại lâu.

## Line IIJ hay SoftBank — khác nhau ở đâu?

Khác nhau ở đường truyền ra ngoài, không phải ở cấu hình máy. Cùng một gói, cùng giá, bạn chỉ chọn được một trong hai line khi đặt hàng.

Về thông số thuần túy, bài đo quốc tế do pickmyvps công bố cuối tháng 11/2025 cho thấy SoftBank thắng rõ ở kết nối trong nước Nhật và hướng quốc tế: iPerf3 tới các node Tokyo của SoftBank đạt 5.500–8.000 Mbps, trong khi line IIJ thấp hơn đáng kể; tới Hong Kong, SoftBank đạt trên 3.700 Mbps so với 3.100–3.500 Mbps của các node GreenCloud Hong Kong. Kết luận nguyên văn của bài đo: tổng thể SoftBank có kết nối quốc tế tốt hơn.

Hướng về Trung Quốc đại lục thì phức tạp hơn. digvps — trang đo đạc chuyên về VPS Nhật — ghi nhận line IIJ của GreenCloud "biểu hiện ở hướng Telecom khá tệ", còn SoftBank đi ba mạng theo đường 163/CMI/4837, tương đương với sản phẩm Tokyo của v.ps. Bài đo của pickmyvps cũng xác nhận: giờ cao điểm tối, Telecom đi IIJ tốt hơn còn SoftBank gần như dùng không được; ngược lại China Unicom đi SoftBank ổn còn IIJ gần như nghẽn hoàn toàn.

Một điều cần nói thẳng: chưa tìm thấy số đo tốc độ riêng cho hướng Việt Nam đối với hai line này. Các bài đo nêu trên đều xoay quanh Trung Quốc và quốc tế. Điều duy nhất có thể khẳng định chắc là cả hai line đều nằm tại Tokyo, độ trễ tới Đông Nam Á thấp hơn hẳn so với máy chủ Mỹ/Châu Âu, và SoftBank là lựa chọn an toàn hơn nếu bạn quan tâm tốc độ quốc tế nói chung. Nếu nghiệp vụ của bạn nhạy cảm với giờ cao điểm, cách chắc chắn nhất là xin nhà cung cấp test IP của đúng máy chủ định mua rồi tự đo từ mạng nhà — chứ đừng lấy IP của机房 khác làm chuẩn.

## Những hạn chế nên biết trước khi bấm đặt hàng

Phần này đáng giá hơn mọi bảng cấu hình, vì GreenCloud không giấu chúng — chỉ là chúng nằm ở dòng chữ nhỏ trên trang đặt hàng mà ít ai đọc hết.

**1. Các gói Tokyo không hoàn tiền.** Cả dòng Premium KVM, Budget KVM lẫn CN Premium Optimized tại Tokyo đều ghi rõ "No refund/Money back on this plan" ngay trên trang đặt hàng. GreenCloud định giá rẻ theo kiểu bán theo đợt, và điều kiện đổi lại là bạn không được hối hận sau khi thanh toán. Đây là lý do lớn nhất để không "mua hớ" gói năm mà chưa chắc mình dùng gì.

**2. CPU thực nhận có thể khác quảng cáo, và mức độ chia sẻ tài nguyên cao.** Một bài đo trên node Tokyo SoftBank của dòng Storage ghi nhận máy thực nhận về là Xeon Platinum 8255C trong khi quảng cáo nói EPYC. digvps đánh giá hai gói Storage tham gia đo ở mức **E4 (tạm ổn)** — ngôn từ của họ thẳng thắn hơn: "xét theo điểm CPU, tình trạng bán quá tải khá rõ, tuy nhiên với định vị máy hàng loạt giá thấp thì mức hấp dẫn tổng thể vẫn có". Ngược lại, một bài đo độc lập tháng 11/2026 trên gói 2222 (SoftBank) cho kết quả tốt: Geekbench 5 đơn nhân 825/đa nhân 1332, băng thông bộ nhớ gần 40 GB/s. Tóm lại: chất lượng dao động theo lô hàng và thời điểm, đừng kỳ vọng hiệu năng riêng tư kiểu dedicated.

**3. Ổ cứng nhanh theo kiểu tuần tự, chậm theo kiểu ngẫu nhiên.** Cùng bài đo trên: đọc tuần tự đạt 3.101 MB/s nhưng đọc ngẫu nhiên 4K chỉ 18,6 MB/s (4.800 IOPS). Dịch file, chứa media, chạy web tĩnh rất sướng; còn database cần IOPS cao kiểu MySQL tải nặng thì đây không phải đất chơi của gói rẻ.

**4. Tồn kho Tokyo thường mảnh.** Tại thời điểm tháng 10/2026, gói CN Premium Mini Tokyo hiển thị hết hàng, còn các gói Premium KVM vừa bổ sung chỉ bán trong đợt — hết là phải chờ đợt sau. Hãy kiểm tra tồn kho trước và nhớ rằng chu kỳ thanh toán có thể khác nhau giữa các gói (ví dụ 8GB RAM ở Tokyo tính theo năm, ở Hong Kong và Singapore lại có bản tính theo quý).

**5. Băng thông châu Á thấp hơn Mỹ/Âu.** Ở tầm giá tương đương, máy tại Tokyo được 750GB–2TB lưu lượng tùy gói, trong khi đặt tại Anh, cùng giá, nhận tới 3–8TB. Dòng Storage Tokyo tương tự: 1TB–4TB tùy gói, đếm cả chiều vào lẫn chiều ra.

## IPv4 và IPv6 trên cùng một VPS có thể "thái cực" nhau

Đây là chi tiết gần như không bài tiếng Việt nào nhắc, nhưng nó quyết định trực tiếp việc bạn mua VPS Nhật để làm gì — nhất là với ai cần IP Nhật để xem nội dung bản địa hoặc gửi email.

Dữ liệu đo tháng 11/2026 trên line SoftBank của GreenCloud cho thấy:

- **IPv4** là IP phát lại đăng ký tại Đức (tổ chức xTom Japan, AS3258), dùng kiểu datacenter. Tin tốt: không bị gắn cờ proxy/VPN/Tor, blacklist bằng 0, và **cổng 25 dùng để gửi email hoạt động bình thường** — bài đo đã xác nhận gửi nhận thành công với Gmail, Outlook, Yahoo. Về giải trí: TikTok mở, ChatGPT mở theo vùng Nhật, nhưng Netflix chỉ xem được nội dung tự sản xuất.
- **IPv6** thì ngược lại hoàn toàn: đây là IP native đăng ký tại Tokyo, mở trọn Netflix, Disney+, YouTube và ChatGPT theo vùng Nhật, nhưng **TikTok chặn** và **cổng 25 bị khoá cứng**.

Nghĩa là gì trong thực tế? Nếu bạn mua VPS Nhật chủ yếu để gửi email, hãy dựa vào IPv4 và kiểm tra cổng 25 ngay sau khi cài đặt. Nếu để xem Netflix/Disney+ vùng Nhật, việc cấu hình ứng dụng đi qua IPv6 sẽ cho kết quả tốt hơn. Hai giao thức trên cùng một chiếc VPS hoạt động như hai danh tính khác nhau — biết điều này trước khi mua sẽ tránh được khá nhiều thời gian mày mò.

## So với VPS Nhật của các nhà cung cấp khác

Bức tranh tổng thể ở tầm giá cho người Việt như sau. Cloud Cheap bán gói Mini Nhật từ 100.000đ/tháng (1 core/1GB, cổng 100/10 Mbps, chỉ tính theo tháng) và gói Global từ 250.000đ/tháng (2 vCores/4GB, không công bố tốc độ cổng); điểm mạnh của họ là trả theo tháng và hỗ trợ Windows Server trên form đặt hàng. BandwagonHost có gói Tokyo CN2 GIA 2GB RAM · 2 core · 40GB SSD · 500GB lưu lượng, giá 89,99 USD/quý hoặc 899,99 USD/năm — đắt hơn GreenCloud khoảng hai chục lần theo năm, đổi lại là line tối ưu Trung Quốc sâu và chính sách chuyển máy chủ giữa các vị trí. Các nhà cung cấp Việt Nam như VPSTTT, Vietnix, ThueCloud cũng bán VPS Nhật nhưng hầu hết định giá theo tháng và nhắm vào nhu cầu IP quốc tế thông thường.

| Tiêu chí | GreenCloud Premium KVM 1 | Cloud Cheap Mini | Cloud Cheap Global (2vC/4GB) |
| --- | --- | --- | --- |
| Giá | 25 USD/năm (~640.000đ) | 100.000đ/tháng | 250.000đ/tháng (2.100.000đ/năm) |
| CPU · RAM | 1 core · 2GB | 1 core · 1GB | 2 vCores · 4GB |
| Ổ | 25GB NVMe RAID10 | 12GB SSD | 30GB SSD |
| Cổng mạng | 10Gbps (danh nghĩa) | 100 Mbps xuống / 10 Mbps lên | Không công bố |
| Lưu lượng | 750GB/tháng | 1TB/tháng | 2.000GB/tháng |
| Chu kỳ | Năm | Chỉ tháng | Tháng – năm |

Một chi tiết ít người biết: GreenCloud cũng có máy chủ tại Hà Nội và TP.HCM. Nếu mục tiêu của bạn chỉ là phục vụ người dùng trong nước với độ trễ thấp nhất, VPS trong nước sẽ hợp lý hơn VPS Nhật — VPS Nhật chỉ thắng khi bạn thực sự cần một IP Nhật Bản.

Mức giá của GreenCloud rẻ được một phần vì mô hình "bán quá tải có kiểm soát" nêu trên, và một phần vì chính sách không hoàn tiền. 👉 [Kiểm tra bảng giá và tồn kho Tokyo hiện tại của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679) trước khi quyết định, vì giá theo từng vị trí thay đổi theo từng đợt bán.

## Câu hỏi thường gặp

**Mua VPS Nhật Bản của GreenCloud có được hoàn tiền không?**
Không. Các gói Tokyo thuộc dòng Premium KVM, Budget KVM và CN Premium Optimized đều không hoàn tiền — điều kiện ghi rõ trên trang đặt hàng. Hãy coi đây là giao dịch một chiều và chỉ đặt khi đã chắc chắn nhu cầu.

**Thanh toán bằng cách nào?**
GreenCloud nhận PayPal, thẻ tín dụng và Alipay. Danh sách phương thức có thể thay đổi theo khu vực, nên xác nhận lại ở bước thanh toán trên trang đặt hàng.

**Người mới dùng được không?**
Được, miễn bạn quen thao tác với máy chủ Linux qua SSH. GreenCloud dùng KVM với bảng điều khiển VirtFusion, hỗ trợ cài lại hệ điều hành và quản lý backup ngay trên panel. Cách kết nối không khác gì VPS bất kỳ đâu: `ssh root@IP_VPS`.

**Ai không nên mua gói này?**
Ba nhóm: người cần database IOPS cao (ổ ngẫu nhiên chậm), người cần gửi khiếu nại hoàn tiền nếu không hài lòng (không có chính sách đó tại Tokyo), và người cần hàng luôn sẵn (tồn kho Tokyo theo đợt, phải chờ đợt bổ sung).

## Chọn gói nào theo nhu cầu của bạn?

- Cần giá rẻ nhất để chạy bot, webhook, proxy riêng hoặc web nhỏ → **Premium KVM 1, 25 USD/năm** (1 core/2GB/25GB NVMe), chọn SoftBank nếu ưu tiên tốc độ quốc tế.
- Cần nhiều dung lượng để chứa file, media, backup → **Storage 0.5TB, 25 USD/năm** với 520GB HDD, hoặc lên Storage 1TB/2TB nếu cần 1–2TB không gian.
- Cần nhiều CPU/RAM hơn cho web có database nhẹ → **Premium KVM 3 (68 USD/năm)** hoặc Budget KVM 4GB khi có hàng.
- Khách hàng chính nằm ở Trung Quốc đại lục → CN Premium Optimized, nhưng chấp nhận giá cao hơn và tình trạng thường xuyên hết hàng.
- Chỉ cần một IP Nhật nhẹ nhàng để xem nội dung bản địa → gói 1 core/1GB 48 USD/năm là đủ, đừng trả thêm cho cấu hình mình không dùng tới.

Việc cuối cùng trước khi bấm đặt: mở lại trang gói, xác nhận còn tồn kho, chu kỳ thanh toán đúng ý, và nhớ rằng đơn Tokyo không hoàn tiền — đúng gói, đúng line, rồi mới thanh toán. 👉 [Đặt gói VPS Tokyo của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679) khi bạn đã sẵn sàng.
