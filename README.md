# Secure Training Portal — AWS Cloud Architecture Project

## Project Overview

This project presents a proposed secure and scalable AWS cloud architecture for a fictional training company providing an online portal for registered participants.

The design focuses on application hosting, private document storage, participant records, network security and controlled administrative access.

## Business Requirements

- 100 registered participants
- Approximately 20 concurrent users
- Public website accessible over HTTPS
- Private participant database
- Secure document uploads and storage
- Restricted administrator access
- Least-privilege application permissions

## Proposed AWS Services

| AWS Service | Purpose |
|---|---|
| Amazon VPC | Network isolation |
| Application Load Balancer | Public HTTPS entry point |
| Amazon ECS with AWS Fargate | Application hosting |
| Amazon RDS | Participant database |
| Amazon S3 | Private document storage |
| AWS IAM | Identity and access management |
| AWS Certificate Manager | HTTPS certificates |
| Amazon CloudWatch | Monitoring and logging |
| AWS Systems Manager | Controlled administration |

## Security Design

The proposed architecture separates public-facing services from private application and database resources.

It uses HTTPS, private subnets, IAM roles, least-privilege permissions, multi-factor authentication and private S3 storage.

## Project Deliverables

- [View the project website](https://goldenboy125.github.io/secure-training-portal/)
- [Download the AWS Design Report](Secure_Training_Portal_Report.pdf)
- [View the AWS Architecture Diagram](Architecture_Diagram.png)

## Project Scope

This is an architecture and security design exercise. It documents a proposed AWS solution and does not claim that a production application has been deployed.

## Author

Wale Eniade

**Project:** Cloud Computing — Week 2 Practical Project  
**Date:** 28 November 2026
