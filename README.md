# AWS IAM Security Management

## Overview
This project demonstrates AWS IAM best practices by implementing users, groups, and custom IAM policies to enforce least-privilege access across AWS services.

## IAM Design
- Admin users are granted full access using AWS managed policies
- Developer users are restricted using custom policies
- Permissions are assigned via groups, not directly to users

## Services Covered
- Amazon EC2 (limited operational access)
- Amazon S3 (read-only access)
- Amazon RDS (read-only access)
- AWS IAM administration

## Security Principles
- Least privilege
- Separation of duties
- Group-based access control
- No hardcoded credentials

## Author
Bidyashor Chingtham
