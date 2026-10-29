# SIGMA | End-to-End AWS Cloud Solution

A collaborative cloud engineering project focused on designing and deploying a secure, scalable, and highly available web application on Amazon Web Services (AWS).

## Project Overview

SIGMA is building a web application architecture designed to improve performance, availability, security, and deployment consistency while keeping costs under control.

The project uses AWS services alongside GitHub for version control and collaboration, and Trello for project management.

## Architecture

**Planned request flow:**

Browser → Amazon CloudFront → Application Load Balancer (ALB) → Amazon EC2

Supporting services:

- **Amazon S3:** Static asset storage
- **AWS Certificate Manager (ACM):** TLS certificates
- **AWS IAM:** Access control and least privilege
- **Amazon CloudWatch:** Monitoring and logging
- **AWS Budgets:** Cost alerts
- **GitHub Actions:** Continuous integration and deployment

> Project status: Development in progress. Services and deployment stages will be marked complete only after implementation and verification.

## Project Objectives

- Improve web application performance using a CDN.
- Distribute incoming traffic through an Application Load Balancer.
- Prepare for scaling and improved availability.
- Apply secure access controls and HTTPS.
- Establish a structured Git collaboration workflow.
- Automate deployments and monitor application health.
- Track AWS costs and stay within the agreed budget.

## Project Milestones

1. **Environment Setup:** AWS, IAM, CLI, GitHub, and Trello.
2. **Application Deployment:** Web application, EC2, target group, and ALB.
3. **Security and CloudFront:** HTTPS, TLS, access restrictions, and caching.
4. **CI/CD and Monitoring:** GitHub Actions, CloudWatch, and AWS Budgets.
5. **Presentation and Showcase:** Architecture walkthrough, testing, and lessons learned.

## Repository Structure

```text
.
├── app/
│   └── index.html
├── docs/
│   └── architecture/
│       └── README.md
├── scripts/
│   └── README.md
└── README.md
```

## Team Workflow

- `main`: Stable project code.
- `develop`: Integration branch.
- `feature/*`: Individual development tasks.
- Pull requests: Review changes before merging into shared branches.

## Security and Cost Management

- Never commit AWS credentials, private keys, passwords, or tokens.
- Apply least-privilege IAM permissions.
- Restrict network access to only the ports and sources required.
- Monitor AWS spending and configure budget alerts.
- Verify Free Tier eligibility and current service charges before provisioning resources.

## Current Status

The repository structure and starter web application are being prepared. AWS infrastructure deployment, security validation, CI/CD, and the final live demonstration remain subject to implementation and testing.

## Learning Resources

- [Amazon CloudFront](https://docs.aws.amazon.com/cloudfront/)
- [Elastic Load Balancing](https://docs.aws.amazon.com/elasticloadbalancing/)
- [Amazon EC2](https://docs.aws.amazon.com/ec2/)
- [Amazon S3](https://docs.aws.amazon.com/s3/)
- [AWS IAM](https://docs.aws.amazon.com/iam/)
- [GitHub Actions](https://docs.github.com/en/actions)

---

SIGMA Group | AWS Cloud Engineering Project
