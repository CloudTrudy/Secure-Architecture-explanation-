# AWS Security Monitoring and Threat Detection Architecture

This project demonstrates an AWS Security Monitoring and Threat Detection 
architecture designed to protect cloud-based applications through layered 
security controls, continuous monitoring, and automated threat response.

---

## Architecture Overview

The architecture is organised into four key areas:

- Business Users — Identity and access management for application users
- Logging & Storage — Centralised, encrypted audit logging
- Threat Detection — Continuous monitoring for suspicious activity
- Response — Automated alerting when threats are detected

---

## Services Used

This architecture is designed for organisations that need to protect their 
cloud environment against threats such as ransomware, data breaches, and 
unauthorised access. It provides a layered security approach, combining 
identity management, encryption, continuous monitoring, and automated 
alerting to detect and respond to suspicious activity before it causes harm.

The architecture uses 11 AWS services working together to provide secure 
access, continuous monitoring, and automated threat response. The services 
are grouped into four areas:

### Identity & Access
- AWS IAM Identity Center — Centralised user access management
- Amazon Cognito — User authentication for the application

### Application Layer
- Amazon API Gateway — Secure entry point for API requests
- AWS Lambda — Serverless compute for business logic
- Amazon DynamoDB — NoSQL database, encrypted with AWS KMS

### Logging & Storage
- AWS CloudTrail — Records all API activity across the account
- Amazon S3 — Stores CloudTrail logs, encrypted with AWS KMS

### Threat Detection
- Amazon GuardDuty — Intelligent threat detection
![Architecture Diagram](.diagram.png)
