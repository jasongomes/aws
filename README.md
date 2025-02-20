# AWS Cloud Resume Challenge



![architecture diagram](https://github.com/user-attachments/assets/902a6b78-f8d1-4355-af91-5b96c944f235)




Welcome to my AWS Cloud Resume Challenge project! This project demonstrates the deployment of a serverless personal resume site using AWS services, following the architecture displayed in the diagram. 

---

## Table of Contents

- [About the Challenge](#about-the-challenge)
- [Architecture Overview](#architecture-overview)
- [Prerequisites](#prerequisites)


---

## About the Challenge

The **AWS Cloud Resume Challenge** is a hands-on project that demonstrates your ability to design, build, and deploy a modern, serverless web application on AWS. This implementation uses:
- **Static Website** hosted on S3
- **CloudFront** for global CDN distribution and HTTPS
- **Route 53** for custom domain and DNS management
- **AWS Lambda** for serverless backend logic
- **DynamoDB** for dynamic data storage (e.g., visitor count)

---

## Architecture Overview

### Key Components:
1. **Users** interact with the website via a browser.
2. **Website** is a static frontend hosted on an **S3 Bucket**.
3. **CloudFront** provides CDN caching and HTTPS.
4. **Route 53** manages the custom domain and DNS settings.
5. **Lambda** functions handle backend logic, directly interacting with:
6. **DynamoDB**, which stores dynamic data (e.g., visitor counts).

---

## Prerequisites

Before getting started, ensure you have the following:

- **AWS Account** with permissions for S3, CloudFront, Route 53, Lambda, DynamoDB, and IAM.
- **A Registered Domain Name** in Route 53.
- **AWS CLI** installed and configured on your local machine.
- **IaC Tool** of your choice (AWS SAM, Terraform, or CDK).
- **Git** for version control.
- **GitHub Account** for CI/CD automation using GitHub Actions.


