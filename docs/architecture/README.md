# SIGMA AWS Cloud Solution

## Architecture Documentation

This directory contains the architecture documentation for the SIGMA end-to-end AWS cloud deployment project.

### Project Architecture

The planned request flow is:

Browser → Amazon CloudFront → Application Load Balancer → Amazon EC2

Amazon S3 will store static assets. GitHub Actions will support automated deployments, while Amazon CloudWatch will provide monitoring and logging.

### Documentation

- Architecture diagram
- AWS service configuration
- Security design and traffic flow
- Deployment and testing notes

> Note: This describes the planned architecture. Services will be marked as deployed only after implementation and verification.
