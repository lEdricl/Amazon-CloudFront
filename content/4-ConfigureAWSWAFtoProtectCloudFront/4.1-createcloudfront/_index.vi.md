---
title : "Tạo CloudFront Distribution"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 4.1 </b> "
---

1. Truy cập Amazon CloudFront từ AWS Console [giao diện quản trị của dịch vụ Amazon CloudFront ](https://us-east-1.console.aws.amazon.com/cloudfront/v4/home?region=ap-southeast-1).
  + Click chọn **Create a CloudFront Distribution**.
  
  ![S3](/images/4.s3/Screenshot.png)

2. Ở trang Create Distribution.
  + Ở mục **Origin**, nhập thông tin S3 Bucket làm nguồn gốc (Origin).
  ![S3](/images/4.s3/Screenshot1.png)


3. tiếp theo.
  + Ở mục **Name**, nhập tên cho Distribution (ví dụ:bucket-cloudfront-workshop).
  + Click chọn **Legacy access identities**
  + Click chọn **Yes,updata the bucket policy**
  + Click chọn **Create new OAI**
  ![S3](/images/4.s3/Screenshot2.png)


4. tiếp tục chọn **Create**.
  
  ![S3](/images/4.s3/Screenshot3.png)  

5. Ở mục**Web Application Firewall (WAF)**.
  + Click chọn **Enable securtity protetions**.
  ![S3](/images/4.s3/Screenshot4.png) 

1. Cuối cùng chọn **Create Distribution**.

  ![S3](/images/4.s3/Screenshot5.png) 