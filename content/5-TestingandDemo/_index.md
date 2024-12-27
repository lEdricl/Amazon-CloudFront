---
title: "Testing and Demo"
date: "`r Sys.Date()`"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---



1. **Check content load speed**:
   - **Use a browser to access the CloudFront URL**:  
     Access the CloudFront URL (provided when you create the CloudFront Distribution) through your browser to check if the content is being served correctly from CloudFront. The URL will look like `d12345abcde.cloudfront.net`.

   - **Measure load speed from different locations**:  
     You can check the load speed from different regions around the world to see how well CloudFront performs. Use the following online tools:
     - **Pingdom**:  
       Visit [Pingdom](https://www.pingdom.com/) and enter the CloudFront URL to check the load speed from different locations.
     - **GTmetrix**:  
       Visit [GTmetrix](https://www.gtmetrix.com/) and enter the CloudFront URL to test the page load performance from global locations. This tool provides metrics such as page load time, server response speed, and performance score.

   - **Steps to use GTmetrix**:
     - Go to the GTmetrix website.
     - Enter the CloudFront URL into the search bar and click **Test your site**.
     - Choose the **Test Location** to test from different countries or regions.
     - Wait a few minutes for the tool to measure and analyze the page load time.
     - Review metrics such as **Page Speed Score**, **Fully Loaded Time**, **Total Page Size**, and **Requests** to assess CloudFront's performance.

2. **Analyze the results**:
   - Compare the page load time from nearby and distant regions. CloudFront will help reduce page load times from remote locations by caching content at edge locations closer to the end users.
   - If there are delays, review your CloudFront configuration, such as cache settings, or check if there are any issues with content distribution from the origin.
