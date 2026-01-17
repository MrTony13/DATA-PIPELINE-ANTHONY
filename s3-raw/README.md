# S3 Raw Bucket

## Purpose
This bucket stores incoming raw data from the backend application.

## Configuration Steps
1. Created an S3 bucket with versioning disabled
2. Enabled S3 Event Notification:
   - Event type: ObjectCreated (PUT)
   - Destination: Processing Lambda

## Result
Uploading an object to this bucket automatically triggers data processing.
