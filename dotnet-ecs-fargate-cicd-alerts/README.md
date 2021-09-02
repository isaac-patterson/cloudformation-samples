# .NET WebApi AWS Fargate Task with build/deploy pipelines and alerts

Place all files in your dotnet API 

## Template prereqs:
- An ECR repository setup through the AWS CLI (not supported by cloudformation)
- Git hub repo
- Github access token stored in AWS SSM

## Template input (passed from root stack):
- ECS Service with a security group
- Subnets & VPC
- Loadballancer using path based routing
- SNS Topic for cloudwatch alarms


