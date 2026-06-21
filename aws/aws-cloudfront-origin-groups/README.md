Understanding CloudFront Origin Groups

Overview

This lab demonstrates how to configure Amazon CloudFront with Origin Groups to provide failover between an S3 bucket and an EC2 instance. Content is served from the primary S3 origin, with automatic failover to the EC2 origin if the primary becomes unavailable.

Services Used


Amazon CloudFront
Amazon S3
Amazon EC2
Amazon Web Services (VPC)


Steps Performed


Created a public S3 bucket and uploaded an index.html file
Launched an Amazon Linux 2 EC2 instance with a Bash script serving index2.html
Created a CloudFront distribution with S3 as the primary origin
Created a second CloudFront distribution with EC2 as the origin
Configured a CloudFront Origin Group combining both origins with failover
Tested content delivery via CloudFront distribution domain URLs


Outcome

Lab validation passed ✅ — 100%Understanding CloudFront Origin Groups

Overview

This lab demonstrates how to configure Amazon CloudFront with Origin Groups to provide failover between an S3 bucket and an EC2 instance. Content is served from the primary S3 origin, with automatic failover to the EC2 origin if the primary becomes unavailable.

Services Used


Amazon CloudFront
Amazon S3
Amazon EC2
Amazon Web Services (VPC)


Steps Performed


Created a public S3 bucket and uploaded an index.html file
Launched an Amazon Linux 2 EC2 instance with a Bash script serving index2.html
Created a CloudFront distribution with S3 as the primary origin
Created a second CloudFront distribution with EC2 as the origin
Configured a CloudFront Origin Group combining both origins with failover
Tested content delivery via CloudFront distribution domain URLs


Outcome

Lab validation passed ✅ — 100%