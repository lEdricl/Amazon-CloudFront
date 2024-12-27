---
title: "Kiểm Tra và Demo"
date: "`r Sys.Date()`"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---
1. **Kiểm tra tốc độ tải nội dung**:
   - **Sử dụng trình duyệt để truy cập URL CloudFront**:  
     Truy cập vào URL CloudFront (được cung cấp khi bạn tạo CloudFront Distribution) bằng trình duyệt của bạn để kiểm tra xem nội dung có được phân phối đúng từ CloudFront không. URL sẽ có dạng như `d12345abcde.cloudfront.net`.

   - **Đo tốc độ tải từ các địa điểm khác nhau**:
     Bạn có thể kiểm tra tốc độ tải từ các khu vực khác nhau trên thế giới để xem hiệu suất của CloudFront có tối ưu không. Sử dụng các công cụ trực tuyến sau:
     - **Pingdom**:  
       Truy cập [Pingdom](https://www.pingdom.com/) và nhập URL CloudFront để kiểm tra tốc độ tải từ các địa điểm khác nhau.
     - **GTmetrix**:  
       Truy cập [GTmetrix](https://www.gtmetrix.com/) và nhập URL CloudFront để kiểm tra hiệu suất tải trang từ các địa điểm toàn cầu. Công cụ này cung cấp các chỉ số như thời gian tải trang, tốc độ phản hồi của máy chủ và điểm hiệu suất.

   - **Các bước sử dụng công cụ GTmetrix**:
     - Truy cập vào trang GTmetrix.
     - Nhập URL CloudFront vào ô tìm kiếm và nhấn **Test your site**.
     - Chọn **Test Location** để kiểm tra từ các quốc gia hoặc khu vực khác nhau.
     - Đợi vài phút để công cụ đo lường và phân tích tốc độ tải trang.
     - Kiểm tra các chỉ số như **Page Speed Score**, **Fully Loaded Time**, **Total Page Size**, và **Requests** để đánh giá hiệu quả của CloudFront.

2. **Phân tích kết quả**:
   - So sánh thời gian tải trang từ các khu vực gần và xa. CloudFront sẽ giúp giảm thời gian tải trang từ các vị trí xa bằng cách lưu trữ các bản sao của nội dung tại các edge locations gần người dùng cuối.
   - Nếu có sự chậm trễ, kiểm tra lại cấu hình của CloudFront, chẳng hạn như cache settings, hoặc nếu có vấn đề với việc phân phối nội dung từ origin.
