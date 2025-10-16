# Dusty Thrifts CI/CD Deployment

This project demonstrates a fully automated CI/CD pipeline using AWS services.

## Tools Used
- **AWS CodePipeline**: Continuous deployment automation.
- **Amazon S3**: Static website hosting.
- **AWS SNS**: Deployment alerts.
- **GitHub**: Source control and version tracking.

## How It Works
1. Changes pushed to the `main` branch on GitHub automatically trigger CodePipeline.
2. CodePipeline retrieves the latest code and deploys it to the S3 bucket.
3. SNS sends a notification when the deployment succeeds or fails.

## Outcome
The Dusty Thrifts site is automatically updated every time code is pushed, ensuring rapid, reliable deployments with rollback protection via S3 versioning.
