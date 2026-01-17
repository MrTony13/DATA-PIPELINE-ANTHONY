# IAM & Security

## Approach
Each Lambda function uses a least-privilege IAM role.

## Permissions Used
- s3:GetObject
- s3:PutObject

Permissions are scoped to specific buckets only, following AWS security best practices.
