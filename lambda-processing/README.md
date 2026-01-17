# Processing Lambda

## Purpose
This Lambda aggregates and transforms raw data uploaded to the Raw S3 bucket.

## Configuration Steps
1. Created a Lambda function (Python runtime)
2. Attached IAM role with:
   - s3:GetObject on Raw bucket
   - s3:PutObject on Consumption bucket
3. Configured S3 Raw bucket as trigger

## Output
Aggregated files are written to the Consumption/Aggregation S3 bucket.
