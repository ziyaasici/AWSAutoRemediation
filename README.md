# AWS Auto Remediation w/Lambda Function Project
This project simlates/automates remediation actions for AWS resources using AWS CloudFormation template, Lambda function, Auto Scaling groups, CloudWatch Alarms, and SNS topics.

# Overview
The project consists of an AWS CloudFormation template that define the infrastructure components and configurations:

- VPC Configurations: Defines the VPC, internet gateway, subnets, and route tables.
- Security Group Configurations: Creates security groups for EC2 instances.
- Launch Template Configurations: Defines launch templates for production and development auto-scaling groups.
- Auto Scaling Configurations: Creates auto-scaling groups for both production and development environments.
- SNS & Alarm Configurations: Sets up SNS topics and CloudWatch alarms for monitoring and notifications.
- Lambda Configurations: Defines a Lambda function to update desired capacity for auto-scaling groups dynamically.

# Usage
Customize the parameters and configurations in CloudFormation template as needed.
Ensure that your AWS IAM user or role has sufficient permissions to create and manage the resources defined in the templates.
Monitor the AWS CloudFormation stack events and CloudWatch alarms for any issues or notifications.
