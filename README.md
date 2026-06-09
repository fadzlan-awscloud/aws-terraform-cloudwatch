# AWS Terraform CloudWatch Lab
This project deploys:
- EC2 Instance
- Security Group
- CloudWatch Alarm

The alarm monitors EC2 CPU utilization and triggers when CPU exceeds 70%.

Technologies:
- AWS
- Terraform
- CloudWatch

## Overview
This project demonstrates AWS monitoring and operational visibility using CloudWatch and Systems Manager.

## Components:
EC2
CloudWatch Metrics
CloudWatch Alarms
CloudWatch Logs
Systems Manager Session Manager

## Objectives
Monitor infrastructure health
Create alerting mechanisms
Centralize logs
Practice cloud operations

## Architecture
For Cloudwatch lab
EC2
 │
 ▼
CloudWatch Metrics
 │
 ▼
CloudWatch Alarm
 │
 ▼
SNS Notification

## Validation
Generated CPU load
Triggered CloudWatch alarms
Reviewed CloudWatch logs
Accessed EC2 through Session Manager

## Lessons Learned
Monitoring concepts
Alerting mechanisms
Operational visibility
Log analysis
Secure administration without SSH
Incident investigation
