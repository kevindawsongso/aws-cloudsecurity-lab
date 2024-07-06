# AWS Cloud Cybersecurity Home Lab

## Overview
Welcome to my AWS Cloud Cybersecurity Home Lab repository! This lab is designed to enhance my skills and knowledge in cloud-based cybersecurity, focusing on various AWS services and tools. The lab includes honeypot deployment, network traffic monitoring, and threat detection and analysis.

## AWS Services Used
- **EC2:** Hosting T-Pot honeypot instance.
- **Security Hub:** Centralized view of security alerts and compliance status.
- **CloudWatch:** Monitoring and logging of VPC flow logs and other metrics.
- **IAM:** Identity and Access Management for securing AWS resources. Idenities managed for users and service inegrations
- **CloudTrail:** Logging of AWS API calls for auditing and compliance to ensure secure access control between services.
- **S3:** Storage for logs and other data.
- **Billing and Cost Management:** Monitoring AWS usage and expenses.
- **IAM Identity Center:** Centralized identity management.
- **Guard Duty:** Threat detection and monitoring of T-Pot instance for malicious activity.
- **Detective:** Detailed analysis and investigation of potential security issues to aid with threat hunting.

## Lab Components

### T-Pot Honeypot Deployment
- **Objective:** Deploy a T-Pot honeypot on an EC2 instance to attract and log malicious activities.
- **Setup:**
  - Deployed T-Pot on an EC2 instance.
  - Segmented network traffic using both subnets and security groups.

### VPC Flow Logs to CloudWatch
- **Objective:** Monitor and log network traffic within the VPC.
- **Setup:**
  - Configured VPC flow logs to send data to AWS CloudWatch.
  - Set up CloudWatch dashboards and alarms for real-time monitoring.

### Threat Detection and Analysis
- **Objective:** Detect and analyze potential threats using AWS security services.
- **Setup:**
  - Enabled AWS Guard Duty for continuous threat detection.
  - Used AWS Detective for detailed analysis and investigation of security findings.

## Projects and Achievements

### Project: Honeypot Deployment
- **Objective:** Deploy and configure a T-Pot honeypot for intrusion detection.
- **Setup:**
  - Deployed on an EC2 instance.
  - Configured network segmentation with subnets and security groups.
- **Outcome:** Successfully attracted and logged malicious activities.

### Project: VPC Flow Logs Monitoring
- **Objective:** Monitor network traffic using VPC flow logs.
- **Setup:**
  - Configured VPC flow logs to feed data to CloudWatch.
  - Set up dashboards and alarms for real-time monitoring.
- **Outcome:** Achieved comprehensive network visibility and proactive monitoring.

### Project: Threat Detection and Analysis
- **Objective:** Enhance threat detection and incident analysis.
- **Setup:**
  - Enabled Guard Duty for continuous monitoring.
  - Used Detective for in-depth analysis of security findings.
- **Outcome:** Strengthened threat detection and response capabilities.

## Certifications
- Microsoft Certified: Azure Fundamentals
- ISC2 Certified in Cyber Security
- CompTIA Security+
- CompTIA A+
- CompTIA Network+

## Future Plans
- **Expand Lab:** Add more AWS services and integrate with on-premises components.
- **Automation:** Develop Lambda functions for automated incident response.
- **Reporting:** Implement comprehensive security reporting and dashboards.

## Contact
Feel free to reach out if you have any questions or suggestions!

[Email](mailto:your-email@example.com) | [LinkedIn](https://www.linkedin.com/in/your-profile)
