---
title: "Clean up resources"
date: "`r Sys.Date()`"
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

### Delete the Resources We Created

After completing the deployment and testing of Amazon CloudFront, if you wish to clean up and delete the resources created during the practice, follow these steps to ensure the resources are removed and avoid being charged for unnecessary ones.

1. **Delete the CloudFront Distribution**:
   - Go to the **AWS Management Console** and navigate to **CloudFront**.
   - Find and select the **CloudFront Distribution** that you created during the practice.
   - Click on **Actions** and select **Disable** to disable the distribution.
   - Once the distribution status changes to **Disabled**, click **Delete** to permanently delete the distribution.

2. **Delete the S3 Bucket**:
   - Go to **Amazon S3** in the AWS Management Console.
   - Select the **S3 Bucket** you used as the origin in CloudFront.
   - Ensure that the bucket is empty (delete all objects within the bucket).
   - After the bucket is empty, click **Delete** and confirm to delete the bucket.

3. **Delete the AWS Web Application Firewall (WAF)**:
   - Go to **AWS WAF** in the AWS Management Console.
   - Select **Web ACLs** and find the **Web ACL** you created to protect CloudFront.
   - Click **Delete** to remove the Web ACL and all associated protection rules.

4. **Delete CloudWatch Log Group**:
   - Go to **Amazon CloudWatch** in the AWS Management Console.
   - Select **Logs** from the left menu and find the **Log Group** created to monitor CloudFront logs.
   - Select the corresponding **Log Group** and click **Delete** to remove the log group.

5. **Delete Other Resources (if applicable)**:
   - If you created any other resources during the practice, such as CloudFront SSL certificates, IAM roles, or other related resources, ensure they are also deleted.
   - Make sure that all unnecessary resources are removed to prevent any ongoing charges.

### Conclusion:
Once these steps are completed, all the resources you created during this practice will be deleted, and you will no longer incur charges for unused resources. This is an important step to clean up your working environment and ensure efficient AWS resource management.
