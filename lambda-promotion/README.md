# Promotion Lambda

## Purpose
Applies business rules and promotional logic to aggregated data.

## Configuration Steps
1. Created Lambda function (Python runtime)
2. IAM permissions:
   - s3:GetObject from Consumption bucket
   - s3:PutObject to Promotion bucket
3. Triggered automatically via S3 events

## Output
Final promotion results are stored in the Promotion S3 bucket.
