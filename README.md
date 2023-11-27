# AWS-S3-Event-triggering
This project aims to automate the handling of new objects uploaded to an S3 bucket. It involves creating an IAM role, an S3 bucket, a Lambda function, an S3 event trigger, an SNS topic, and an email subscription.

![image](https://github.com/AjayAjex/AWS-S3-Event-triggering/assets/106955998/b1cacfdc-465b-4446-a147-ef5fba0a3252)

This project aims to automate the handling of new objects uploaded to an S3 bucket. It involves creating an IAM role, an S3 bucket, a Lambda function, an S3 event trigger, an SNS topic, and an email subscription.

When a new object is uploaded to the S3 bucket, the S3 event trigger invokes the Lambda function. The Lambda function performs any necessary actions on the object, such as extracting metadata, validating format and content, or generating notifications. The Lambda function can then send a notification to the SNS topic. The SNS topic publishes a message to the subscribed email address, alerting the user of the new object and any actions taken.

