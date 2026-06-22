Azure Application Gateway WAF

Overview

This lab demonstrates how to deploy an Azure Application Gateway with Web Application Firewall (WAF) to protect web applications from common exploits and vulnerabilities such as SQL injection and cross-site scripting (XSS).

Services Used


Azure Application Gateway
Azure Web Application Firewall (WAF)
Azure Virtual Network (VNet)
Azure Virtual Machines
Azure Public IP


Steps Performed


Created a VNet with dedicated subnets for the Application Gateway and backend VMs
Deployed backend web server VMs
Created an Application Gateway with WAF enabled in Prevention mode
Configured WAF policy with OWASP rule sets
Configured backend pools, HTTP settings, listeners, and routing rules
Tested WAF by sending malicious requests and verifying they were blocked
Reviewed WAF logs in Azure Monitor


Outcome

Lab validation passed ✅ — 100%