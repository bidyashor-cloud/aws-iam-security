# IAM Groups

## Admins
- Attached Policy: AWS managed `AdministratorAccess`
- Purpose: Full administrative access to the AWS account

## Developers
- Attached Policies:
  - EC2LimitedAccessPolicy
  - S3ReadOnlyPolicy
  - RDSReadOnlyPolicy
- Purpose: Limited access for application development and operations
- Restrictions:
  - No IAM management access
  - No billing or account-level permissions
