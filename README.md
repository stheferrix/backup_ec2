# Steps:

1 - Create Role IAM

2 - Create Policy IAM (snapshot and iam)

3 - Associate Policy to Role created

4 - Configure TAG on EC2 instance:

Key: Backup
Value: True

5 - Configure Lambda function with python 2.7 and role created before.

6 - Create a schedule on Cloudwatch to execute Lambda functions

7 - To set cron follow the documentation: https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/ScheduledEvents.html#CronExpressions
