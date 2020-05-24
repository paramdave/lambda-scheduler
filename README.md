## lambda-scheduler
AWS CloudWatch scheduled event will trigger AWS Lambda function
Lambda function will publish a message to SNS topic 

## AWS Services
SNS (Email)
Lambda (Node JS)
IAM

## Cloudwatch Event Cron
```
cron(0 12 */7 * ?) //removing second's measure as CW doesn't support seconds as per my best knowledge.

```
