# Cloud Security Labs

Hands-on AWS and Azure cloud security labs completed on [Whizlabs](https://www.whizlabs.com/), covering network security, identity and access management, encryption, monitoring, compliance, and more. These labs were part of the tasks completed on the Virtually Testing Foundation (VTF) Cloud security track internship

Each lab folder contains screenshots evidencing successful completion, with validation scores of 100% where applicable.

---

## About

**Author:** Olakunle Mogaji  
**Role:** SOC Analyst → Cloud Security & DevSecOps Engineer (in progress)  
**GitHub:** [github.com/qoonleyh](https://github.com/qoonleyh)  
**LinkedIn:** [linkedin.com/in/mustapha-mogaji-9215aa108](https://linkedin.com/in/mustapha-mogaji-9215aa108)

---

## Repository Structure

```
Cloud-Security-Labs/
├── azure/        # 18 Azure security labs
└── aws/          # 29 AWS security labs
```

---

## Azure Labs (18)

| # | Lab | Key Services |
|---|-----|-------------|
| 1 | [Azure Private Link Service (ARM Template)](./azure/azure-private-link-service-arm-template/) | Private Link, ARM, Load Balancer |
| 2 | [Azure Private Link Service (Bicep)](./azure/azure-private-link-service-bicep/) | Private Link, Bicep, Load Balancer |
| 3 | [Azure Private Endpoint (Bicep)](./azure/azure-private-endpoint-bicep/) | Private Endpoint, Bicep, VNet |
| 4 | [Azure Firewall DNAT Policy](./azure/azure-firewall-dnat-policy/) | Azure Firewall, DNAT, VNet |
| 5 | [Azure Firewall Policy via Portal](./azure/azure-firewall-policy-portal/) | Azure Firewall, Firewall Policy |
| 6 | [Azure Front Door (ARM & Bicep)](./azure/azure-front-door-arm-bicep/) | Front Door, WAF, ARM, Bicep |
| 7 | [Azure Service Endpoints for Storage](./azure/azure-service-endpoints-storage/) | Service Endpoints, Storage, VNet |
| 8 | [Azure Key Vault Key Rotation](./azure/azure-key-vault-key-rotation/) | Key Vault, Key Rotation, Automation |
| 9 | [Azure SQL Database Security](./azure/azure-sql-database-security/) | SQL Database, TDE, Auditing |
| 10 | [Microsoft Sentinel](./azure/azure-microsoft-sentinel/) | Sentinel, Log Analytics, KQL |
| 11 | [Microsoft Sentinel Logic App](./azure/azure-microsoft-sentinel-logic-app/) | Sentinel, Logic Apps, SOAR |
| 12 | [Microsoft Sentinel Content Hub](./azure/azure-microsoft-sentinel-content-hub/) | Sentinel, Content Hub, Analytics Rules |
| 13 | [NSG Rules for IIS](./azure/azure-nsg-rules-iis/) | NSG, IIS, Virtual Machine |
| 14 | [NSG VM-to-VM](./azure/azure-nsg-vm-to-vm/) | NSG, VNet, Virtual Machines |
| 15 | [VM Disk Encryption](./azure/azure-vm-disk-encryption/) | Disk Encryption, Key Vault, VM |
| 16 | [Encrypt and Decrypt Data at Rest](./azure/azure-encrypt-decrypt-data-at-rest/) | Storage Encryption, Key Vault |
| 17 | [Resource Locks](./azure/azure-resource-locks/) | Resource Locks, RBAC, ARM |
| 18 | [Application Gateway WAF](./azure/azure-application-gateway-waf/) | Application Gateway, WAF, VNet |

---

## AWS Labs (29)

| # | Lab | Key Services |
|---|-----|-------------|
| 1 | [ALB Advanced Request Routing](./aws/aws-alb-advanced-request-routing/) | ALB, EC2, ELB |
| 2 | [ALB Bastion Host](./aws/aws-alb-bastion-host/) | ALB, EC2, Bastion |
| 3 | [ALB Path Based Routing Challenge](./aws/aws-alb-path-based-routing-challenge/) | ALB, EC2, Target Groups |
| 4 | [ALB Path Based Routing](./aws/aws-alb-path-based-routing/) | ALB, EC2, Listener Rules |
| 5 | [CloudFront Origin Groups](./aws/aws-cloudfront-origin-groups/) | CloudFront, S3, EC2 |
| 6 | [CloudWatch Agent on EC2](./aws/aws-cloudwatch-agent-ec2/) | CloudWatch, EC2, IAM |
| 7 | [CloudWatch CloudTrail Alerts](./aws/aws-cloudwatch-cloudtrail-alerts/) | CloudWatch, CloudTrail, SNS |
| 8 | [CloudWatch Events EC2 SNS](./aws/aws-cloudwatch-events-ec2-sns/) | CloudWatch Events, EC2, SNS |
| 9 | [Cognito User Pool Challenge](./aws/aws-cognito-user-pool-challenge/) | Cognito, User Pools, MFA |
| 10 | [Cognito User Pool](./aws/aws-cognito-user-pool/) | Cognito, User Pools, IAM |
| 11 | [Config Security Group Compliance](./aws/aws-config-security-group-compliance/) | AWS Config, Security Groups |
| 12 | [GuardDuty Intro](./aws/aws-guardduty-intro/) | GuardDuty, CloudTrail, S3 |
| 13 | [Inspector EC2 Vulnerabilities](./aws/aws-inspector-ec2-vulnerabilities/) | Inspector, EC2, SSM |
| 14 | [Inspector SSM Patching](./aws/aws-inspector-ssm-patching/) | Inspector, SSM, EC2 |
| 15 | [Lambda DynamoDB Secrets Manager](./aws/aws-lambda-dynamodb-secrets-manager/) | Lambda, DynamoDB, Secrets Manager |
| 16 | [Macie S3 Sensitive Data](./aws/aws-macie-s3-sensitive-data/) | Macie, S3, IAM |
| 17 | [NAT Gateway VPC Challenge](./aws/aws-nat-gateway-vpc-challenge/) | NAT Gateway, VPC, EC2 |
| 18 | [Resilient Architecture RDS SNS](./aws/aws-resilient-architecture-rds-sns/) | RDS, SNS, Multi-AZ |
| 19 | [S3 Cross Region Replication](./aws/aws-s3-cross-region-replication/) | S3, CRR, IAM |
| 20 | [S3 KMS CloudTrail](./aws/aws-s3-kms-cloudtrail/) | S3, KMS, CloudTrail |
| 21 | [S3 Presign URL](./aws/aws-s3-presign-url/) | S3, Pre-signed URLs, IAM |
| 22 | [Site-to-Site VPN](./aws/aws-site-to-site-vpn/) | VPN, VPC, Customer Gateway |
| 23 | [SQS VPC Interface Endpoint](./aws/aws-sqs-vpc-interface-endpoint/) | SQS, VPC Endpoint, EC2 |
| 24 | [SSM Parameter Store](./aws/aws-ssm-parameter-store/) | SSM, Parameter Store, EC2 |
| 25 | [Systems Manager Apache](./aws/aws-systems-manager-apache/) | Systems Manager, EC2, Apache |
| 26 | [Trusted Advisor Security](./aws/aws-trusted-advisor-security/) | Trusted Advisor, IAM, S3 |
| 27 | [VPC Endpoint Service](./aws/aws-vpc-endpoint-service/) | VPC Endpoint, NLB, PrivateLink |
| 28 | [VPC Flow Logs](./aws/aws-vpc-flow-logs/) | VPC Flow Logs, CloudWatch, S3 |
| 29 | [WAF Block Web Traffic](./aws/aws-waf-block-web-traffic/) | WAF, ALB, EC2 |

---

## Skills & Tools

**Cloud Platforms:** AWS · Microsoft Azure  
**Security Services:** AWS GuardDuty · AWS Macie · AWS Inspector · AWS Config · Microsoft Sentinel · Azure Firewall · Azure WAF  
**Networking:** VPC · Subnets · Security Groups · NACLs · Site-to-Site VPN · VPC Endpoints · Azure NSG · Azure Private Link  
**Identity & Access:** IAM · AWS Cognito · Azure Key Vault · AWS Secrets Manager · AWS SSM Parameter Store  
**Monitoring & Logging:** CloudWatch · CloudTrail · VPC Flow Logs · Log Analytics · KQL  
**Infrastructure as Code:** ARM Templates · Bicep  
**Automation:** Azure Logic Apps · AWS Lambda  

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| SC-200: Microsoft Security Operations Analyst | Microsoft | 2026 |
| ISC2 Certified in Cybersecurity (CC) | ISC2 | 2022 |
| AWS Cloud Practitioner | AWS | 2023 |
| AZ-900: Azure Fundamentals | Microsoft | 2024 |
| Cisco CyberThreat Management | Cisco | 2022 |
