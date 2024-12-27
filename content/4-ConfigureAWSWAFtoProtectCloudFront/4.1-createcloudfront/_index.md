---
title : "Create CloudFront Distribution"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 4.1 </b> "
---

1. Access Amazon CloudFront from the AWS Console [management interface of Amazon CloudFront service](https://us-east-1.console.aws.amazon.com/cloudfront/v4/home?region=ap-southeast-1).
  + Click on **Create a CloudFront Distribution**.
  
  ![S3](/images/4.s3/Screenshot.png)

2. On the Create Distribution page.
  + In the **Origin**, enter the information for the S3 Bucket as the origin.
  ![S3](/images/4.s3/Screenshot1.png)

  3. Next.
  + In the **Name**, enter a name for the Distribution (ex: bucket-cloudfront-workshop).
  + Click **Legacy access identities**
  + Click **Yes,updata the bucket policy**
  + Click **Create new OAI**
  ![S3](/images/4.s3/Screenshot2.png)


4. Continue by selecting **Create**.
  
  ![S3](/images/4.s3/Screenshot3.png)  

5. In the **Web Application Firewall (WAF)**.
  + Click **Enable securtity protetions**.
  ![S3](/images/4.s3/Screenshot4.png) 

6. Finally, select **Create Distribution**.

  ![S3](/images/4.s3/Screenshot5.png) 