## Assignment 2.15: AWS Secrets Manager

**Q1. What is needed to authorize your EC2 to retrieve secrets from the AWS Secret Manager?**
- We will need to create an IAM policy with the relevant permissions to Secret Manager to attach to EC2 execution role in order for EC2 to retrieve secrets from the AWS Secret Manager.<br><br>  

**Q2. Derive the IAM policy (i.e. JSON)? Using the secret name `prod/cart-service/credentials`, derive a sensible ARN as the specific resource for access**
