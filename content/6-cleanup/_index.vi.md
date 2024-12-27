---
title: "Dọn dẹp tài nguyên"
date: "`r Sys.Date()`"
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

### Xóa Các Tài Nguyên Chúng Ta Đã Tạo

Sau khi hoàn thành việc triển khai và thử nghiệm Amazon CloudFront, nếu bạn muốn dọn dẹp và xóa các tài nguyên đã tạo, hãy thực hiện các bước sau để đảm bảo rằng các tài nguyên không còn tồn tại và bạn không bị tính phí cho những tài nguyên không cần thiết.

1. **Xóa CloudFront Distribution**:
   - Truy cập vào **AWS Management Console** và vào **CloudFront**.
   - Tìm và chọn **CloudFront Distribution** mà bạn đã tạo trong quá trình thực hành.
   - Chọn **Actions** và sau đó chọn **Disable** để vô hiệu hóa distribution.
   - Sau khi trạng thái của distribution chuyển thành **Disabled**, chọn **Delete** để xóa hoàn toàn distribution.

2. **Xóa S3 Bucket**:
   - Truy cập vào **Amazon S3** trong AWS Management Console.
   - Chọn **S3 Bucket** mà bạn đã sử dụng làm origin trong CloudFront.
   - Đảm bảo rằng bucket đã được rỗng (delete tất cả các đối tượng trong bucket).
   - Sau khi bucket trống, chọn **Delete** và xác nhận để xóa bucket.

3. **Xóa AWS Web Application Firewall (WAF)**:
   - Truy cập vào **AWS WAF** trong AWS Management Console.
   - Chọn **Web ACLs** và tìm **Web ACL** mà bạn đã tạo để bảo vệ CloudFront.
   - Chọn **Delete** để xóa Web ACL và tất cả các quy tắc bảo vệ đã cấu hình.

4. **Xóa CloudWatch Log Group**:
   - Truy cập vào **Amazon CloudWatch** trong AWS Management Console.
   - Chọn **Logs** từ menu bên trái và tìm **Log Group** mà bạn đã tạo để theo dõi các log từ CloudFront.
   - Chọn **Log Group** tương ứng và chọn **Delete** để xóa log group.

5. **Xóa Các Tài Nguyên Khác (nếu có)**:
   - Nếu bạn đã tạo các tài nguyên khác trong quá trình thực hành, chẳng hạn như các CloudFront SSL Certificates, IAM roles, hoặc các resource liên quan, hãy đảm bảo rằng chúng cũng được xóa.
   - Đảm bảo rằng tất cả các tài nguyên không cần thiết đã được xóa để tránh bị tính phí.

### Kết luận:
Sau khi thực hiện các bước trên, tất cả các tài nguyên mà bạn đã tạo trong bài thực hành này sẽ được xóa và bạn sẽ không còn bị tính phí cho những tài nguyên không sử dụng nữa. Đây là bước quan trọng để dọn dẹp môi trường làm việc của bạn và đảm bảo việc quản lý tài nguyên AWS hiệu quả.
