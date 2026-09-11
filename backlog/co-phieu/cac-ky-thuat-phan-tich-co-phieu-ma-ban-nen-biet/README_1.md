---
title: "Các kỹ thuật phân tích cổ phiếu mà bạn nên biết"
category: "Cổ phiếu"
status: "draft"
priority: "P1"
source_url: "https://www.tcbs.com.vn/thong-tin/co-phieu/cac-ky-thuat-phan-tich-co-phieu-ma-ban-nen-biet/"
target_url: "https://www.tcbs.com.vn/thong-tin/co-phieu/cac-ky-thuat-phan-tich-co-phieu-ma-ban-nen-biet/"
focus_keyword: "kỹ thuật phân tích cổ phiếu"
secondary_keywords:
  - "phân tích cơ bản"
  - "phân tích kỹ thuật"
  - "chỉ số P/E P/B ROE EPS"
  - "đường MA"
  - "chỉ báo RSI"
  - "MACD"
  - "mô hình giá"
  - "khối lượng giao dịch"
long_tail_keywords:
  - "Phân tích cơ bản và phân tích kỹ thuật khác nhau như thế nào?"
  - "Các chỉ số phân tích cổ phiếu cơ bản là gì?"
  - "Người mới bắt đầu nên học phân tích cổ phiếu từ đâu?"
  - "MACD RSI là gì trong phân tích kỹ thuật?"
byline: "Do Đội ngũ nội dung TCBS biên soạn"
last_updated: "2026-09-11"
notes: >
  Viết lại toàn bộ từ bài gốc TCBS (~350 từ, đánh giá "Yếu"/P1 trong
  content-hub-benchmark, mục "Cần viết lại" chuyên mục Cổ phiếu). Giữ nguyên
  title/URL gốc để không mất tín hiệu xếp hạng đã có. Không cannibalize với
  "Cách lựa chọn chiến lược đầu tư cổ phiếu phù hợp cho từng nhà đầu tư"
  (bài đó về chọn CHIẾN LƯỢC đầu tư; bài này về CÔNG CỤ/kỹ thuật phân tích
  để ra quyết định). Theo yêu cầu người duyệt (11/09/2026): đã bỏ mục so
  sánh "nên chọn phân tích cơ bản hay kỹ thuật" và mục "cách kết hợp cả hai
  trong thực tế"; không thêm mục "Bài viết liên quan" (đã cập nhật skill
  tcbs-content-writer để từ nay không tự thêm mục này theo mặc định nữa).
  Công thức 4 chỉ số cơ bản (P/E, P/B, ROE, EPS) là công thức tài chính phổ
  thông, không phải số liệu riêng của TCBS, không cần đội sản phẩm xác nhận.
  CTA trỏ về https://tcinvest.tcbs.com.vn/ (URL xác nhận được từ tài liệu dự
  án) — nếu TCBS muốn CTA trỏ về trang mở tài khoản riêng, cần đội sản phẩm
  xác nhận URL trước khi publish.
---

# Các kỹ thuật phân tích cổ phiếu mà bạn nên biết

**Meta description:** Tổng hợp 9 kỹ thuật phân tích cổ phiếu quan trọng: 4 chỉ số cơ bản (P/E, P/B, ROE, EPS) và 5 công cụ kỹ thuật (MA, RSI, MACD...), kèm công thức và cách áp dụng thực tế.

![Nhà đầu tư phân tích biểu đồ giá cổ phiếu trên nền tảng giao dịch của TCBS (Techcom Securities)](bieu-do-gia-co-phieu-tcbs.png)
*Biểu đồ giá dạng nến trên nền tảng giao dịch TCBS — công cụ cơ bản của phân tích kỹ thuật.*

Phân tích cổ phiếu là quá trình đánh giá một doanh nghiệp niêm yết và biến động giá cổ phiếu của nó để đưa ra quyết định mua, bán hoặc nắm giữ. Có hai trường phái chính: **phân tích cơ bản** (đánh giá giá trị thực của doanh nghiệp qua báo cáo tài chính) và **phân tích kỹ thuật** (dự đoán xu hướng giá qua biểu đồ và khối lượng giao dịch trong quá khứ). Bài viết này tổng hợp 9 kỹ thuật cụ thể thuộc cả hai trường phái, kèm công thức và cách áp dụng.

## Hai trường phái phân tích cổ phiếu

| | 📊 Phân tích cơ bản | 📈 Phân tích kỹ thuật |
|---|---|---|
| Trả lời câu hỏi | Nên mua cổ phiếu nào? | Nên mua/bán vào lúc nào? |
| Dữ liệu sử dụng | Báo cáo tài chính, vĩ mô, ngành | Biểu đồ giá, khối lượng giao dịch |
| Khung thời gian | Trung và dài hạn | Ngắn và trung hạn |
| Phù hợp với | Nhà đầu tư tích lũy dài hạn | Nhà đầu tư theo dõi sát thị trường |

## Phân tích cơ bản là gì? 4 chỉ số cốt lõi cần nắm

Phân tích cơ bản xoay quanh việc trả lời một câu hỏi duy nhất: doanh nghiệp này đáng giá bao nhiêu, và giá cổ phiếu hiện tại đang cao hơn, thấp hơn hay tương đương giá trị đó? Bốn chỉ số dưới đây là công cụ định lượng phổ biến nhất để trả lời câu hỏi này.

### 1. P/E (Price-to-Earnings — Hệ số giá trên lợi nhuận)

> **Công thức:** P/E = Thị giá cổ phiếu ÷ EPS

P/E cho biết nhà đầu tư đang trả bao nhiêu đồng cho mỗi đồng lợi nhuận doanh nghiệp tạo ra. P/E cao thường phản ánh kỳ vọng tăng trưởng lớn của thị trường, nhưng cũng có thể là dấu hiệu cổ phiếu đang bị định giá quá cao. Nên so sánh P/E với trung bình ngành và P/E lịch sử của chính cổ phiếu đó thay vì nhìn con số đơn lẻ.

### 2. P/B (Price-to-Book — Hệ số giá trên giá trị sổ sách)

> **Công thức:** P/B = Thị giá cổ phiếu ÷ Giá trị sổ sách mỗi cổ phiếu

P/B so sánh giá thị trường với giá trị tài sản ròng ghi trên sổ sách kế toán của doanh nghiệp. Chỉ số này đặc biệt hữu ích với các ngành có tài sản hữu hình lớn như ngân hàng, bất động sản, sản xuất.

### 3. ROE (Return on Equity — Tỷ suất lợi nhuận trên vốn chủ sở hữu)

> **Công thức:** ROE = (Lợi nhuận sau thuế ÷ Vốn chủ sở hữu bình quân) × 100%

ROE đo lường hiệu quả doanh nghiệp sử dụng vốn của cổ đông để tạo ra lợi nhuận. ROE càng cao và càng ổn định qua nhiều năm càng cho thấy doanh nghiệp có lợi thế cạnh tranh bền vững.

### 4. EPS (Earnings per Share — Lợi nhuận trên mỗi cổ phiếu)

> **Công thức:** EPS = (Lợi nhuận sau thuế − Cổ tức ưu đãi) ÷ Số lượng cổ phiếu lưu hành bình quân

EPS cho biết mỗi cổ phiếu đang nắm giữ tương ứng với bao nhiêu đồng lợi nhuận, và là đầu vào trực tiếp để tính P/E.

### Ngoài chỉ số, phân tích cơ bản còn cần xem gì?

- Chất lượng báo cáo tài chính qua nhiều năm (dòng tiền kinh doanh có đi cùng lợi nhuận kế toán hay không, tỷ lệ nợ vay, khả năng thanh toán)
- Năng lực và uy tín của ban lãnh đạo, lịch sử thực hiện cam kết với cổ đông
- Vị thế cạnh tranh của doanh nghiệp trong ngành, thị phần và rào cản gia nhập ngành
- Bối cảnh vĩ mô và chu kỳ ngành: lãi suất, tỷ giá, chính sách quản lý ngành

## Phân tích kỹ thuật là gì? 5 công cụ phổ biến

Nếu phân tích cơ bản trả lời "mua cổ phiếu nào", phân tích kỹ thuật trả lời "mua và bán vào lúc nào". Phương pháp này dựa trên giả định rằng mọi thông tin đã phản ánh vào giá, và giá di chuyển theo các xu hướng có thể nhận diện qua biểu đồ.

### 1. Đường trung bình động (MA — Moving Average)

MA là giá đóng cửa trung bình của một cổ phiếu trong một số phiên giao dịch gần nhất (ví dụ MA20, MA50, MA200), giúp làm mượt biến động giá ngắn hạn để nhìn rõ xu hướng chính. Khi giá cắt lên trên đường MA dài hạn, đó thường được xem là tín hiệu xu hướng tăng đang hình thành, và ngược lại.

### 2. Chỉ số sức mạnh tương đối (RSI)

RSI dao động trong khoảng 0-100, thường tính theo chu kỳ 14 phiên. RSI trên 70 thường được xem là vùng quá mua, RSI dưới 30 thường được xem là vùng quá bán. RSI nên được dùng cùng các tín hiệu khác thay vì làm căn cứ duy nhất.

### 3. MACD (Moving Average Convergence Divergence)

MACD là hiệu số giữa hai đường trung bình động hàm mũ (thường là EMA 12 và EMA 26 phiên), đi kèm một đường tín hiệu (thường là EMA 9 phiên). Khi MACD cắt lên trên đường tín hiệu, đây thường được đọc là tín hiệu mua; khi cắt xuống, thường được đọc là tín hiệu bán.

### 4. Mô hình giá (Chart Patterns)

Là các hình dạng lặp lại trên biểu đồ giá dùng để dự đoán hướng đi tiếp theo, ví dụ mô hình vai đầu vai, hai đỉnh/hai đáy (đảo chiều), hay mô hình cờ và tam giác (tiếp diễn xu hướng). Mô hình giá thường đáng tin cậy hơn khi đi kèm khối lượng giao dịch xác nhận.

### 5. Khối lượng giao dịch (Volume)

Khối lượng đo lường số lượng cổ phiếu được giao dịch trong một phiên, dùng để xác nhận độ tin cậy của một xu hướng giá. Một nhịp tăng giá đi kèm khối lượng tăng mạnh thường được xem là xu hướng có lực đỡ thực sự.

## Những sai lầm thường gặp khi phân tích cổ phiếu

- Chỉ nhìn một chỉ số đơn lẻ (ví dụ chỉ xem P/E thấp) mà bỏ qua bối cảnh ngành và chất lượng lợi nhuận
- Dùng chỉ báo kỹ thuật máy móc mà không đặt trong bối cảnh xu hướng chung của thị trường
- Bỏ qua yếu tố dòng tiền kinh doanh, chỉ nhìn lợi nhuận kế toán trên báo cáo
- Không đặt ngưỡng cắt lỗ rõ ràng trước khi vào lệnh, dẫn đến giữ cổ phiếu thua lỗ quá lâu
- Nhầm lẫn giữa "cổ phiếu tốt" (doanh nghiệp tốt) và "thời điểm mua tốt" (giá hợp lý) — đây là hai câu hỏi khác nhau cần hai công cụ khác nhau để trả lời

## Câu hỏi thường gặp (FAQ)

**Phân tích cơ bản và phân tích kỹ thuật khác nhau ở điểm nào?**
Phân tích cơ bản đánh giá giá trị thực của doanh nghiệp qua báo cáo tài chính và yếu tố vĩ mô để trả lời "nên mua cổ phiếu nào". Phân tích kỹ thuật dựa vào biểu đồ giá và khối lượng giao dịch lịch sử để trả lời "nên mua hoặc bán vào lúc nào".

**Nhà đầu tư mới nên bắt đầu từ phân tích nào?**
Nên bắt đầu từ phân tích cơ bản để hiểu doanh nghiệp mình đang đầu tư, sau đó học thêm các công cụ kỹ thuật cơ bản như MA và khối lượng giao dịch để hỗ trợ chọn thời điểm giải ngân.

**Có thể kết hợp cả hai phương pháp không?**
Có, đây là cách tiếp cận phổ biến của nhà đầu tư có kinh nghiệm: dùng phân tích cơ bản để chọn cổ phiếu, dùng phân tích kỹ thuật để chọn thời điểm vào và ra lệnh.

**Chỉ số nào quan trọng nhất khi phân tích cơ bản?**
Không có chỉ số nào quan trọng nhất tuyệt đối. P/E và P/B cho biết mức định giá, ROE cho biết hiệu quả sử dụng vốn, EPS cho biết đà tăng trưởng lợi nhuận. Nhà đầu tư nên xem xét đồng thời cả bốn chỉ số trong bối cảnh ngành.

**Phân tích kỹ thuật có áp dụng được cho mọi cổ phiếu không?**
Phân tích kỹ thuật hoạt động tốt hơn với cổ phiếu có thanh khoản cao. Với cổ phiếu thanh khoản thấp, tín hiệu kỹ thuật dễ bị nhiễu và kém tin cậy hơn.

## CTA

Sẵn sàng áp dụng các kỹ thuật phân tích này vào cổ phiếu thực tế? Tra cứu chỉ số & biểu đồ trên [TCInvest](https://tcinvest.tcbs.com.vn/).

## Schema đề xuất

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Các kỹ thuật phân tích cổ phiếu mà bạn nên biết",
  "description": "Tổng hợp 9 kỹ thuật phân tích cổ phiếu quan trọng: 4 chỉ số cơ bản (P/E, P/B, ROE, EPS) và 5 công cụ kỹ thuật (MA, RSI, MACD...), kèm công thức và cách áp dụng thực tế.",
  "author": { "@type": "Organization", "name": "TCBS - Techcom Securities" },
  "publisher": { "@type": "Organization", "name": "TCBS - Techcom Securities" },
  "mainEntityOfPage": "https://www.tcbs.com.vn/thong-tin/co-phieu/cac-ky-thuat-phan-tich-co-phieu-ma-ban-nen-biet/"
}
```

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Phân tích cơ bản và phân tích kỹ thuật khác nhau ở điểm nào?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Phân tích cơ bản đánh giá giá trị thực của doanh nghiệp qua báo cáo tài chính và yếu tố vĩ mô để trả lời 'nên mua cổ phiếu nào'. Phân tích kỹ thuật dựa vào biểu đồ giá và khối lượng giao dịch lịch sử để trả lời 'nên mua hoặc bán vào lúc nào'."
      }
    },
    {
      "@type": "Question",
      "name": "Nhà đầu tư mới nên bắt đầu từ phân tích nào?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Nên bắt đầu từ phân tích cơ bản để hiểu doanh nghiệp mình đang đầu tư, sau đó học thêm các công cụ kỹ thuật cơ bản như MA và khối lượng giao dịch để hỗ trợ chọn thời điểm giải ngân."
      }
    },
    {
      "@type": "Question",
      "name": "Có thể kết hợp cả hai phương pháp không?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Có, đây là cách tiếp cận phổ biến của nhà đầu tư có kinh nghiệm: dùng phân tích cơ bản để chọn cổ phiếu, dùng phân tích kỹ thuật để chọn thời điểm vào và ra lệnh."
      }
    },
    {
      "@type": "Question",
      "name": "Chỉ số nào quan trọng nhất khi phân tích cơ bản?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Không có chỉ số nào quan trọng nhất tuyệt đối. P/E và P/B cho biết mức định giá, ROE cho biết hiệu quả sử dụng vốn, EPS cho biết đà tăng trưởng lợi nhuận. Nhà đầu tư nên xem xét đồng thời cả bốn chỉ số trong bối cảnh ngành."
      }
    },
    {
      "@type": "Question",
      "name": "Phân tích kỹ thuật có áp dụng được cho mọi cổ phiếu không?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Phân tích kỹ thuật hoạt động tốt hơn với cổ phiếu có thanh khoản cao. Với cổ phiếu thanh khoản thấp, tín hiệu kỹ thuật dễ bị nhiễu và kém tin cậy hơn."
      }
    }
  ]
}
```

```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    { "@type": "ListItem", "position": 1, "name": "Trang chủ", "item": "https://www.tcbs.com.vn/" },
    { "@type": "ListItem", "position": 2, "name": "Thông tin", "item": "https://www.tcbs.com.vn/thong-tin/" },
    { "@type": "ListItem", "position": 3, "name": "Cổ phiếu", "item": "https://www.tcbs.com.vn/thong-tin/co-phieu/" },
    { "@type": "ListItem", "position": 4, "name": "Các kỹ thuật phân tích cổ phiếu mà bạn nên biết" }
  ]
}
```

## Ghi chú byline

Bài gốc không có byline hiển thị công khai (chỉ ẩn trong meta). Khi publish bản viết lại này, cần hiển thị byline công khai trên trang. Chưa có tên người kiểm duyệt cụ thể nên dùng tạm "Do Đội ngũ nội dung TCBS biên soạn".
