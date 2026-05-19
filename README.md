# AWS Multi-AZ Architecture Project

## Architecture Overview
A highly available, scalable web application infrastructure on AWS.

## Components Built
- VPC with public and private subnets across 2 AZs
- Internet Gateway + NAT Gateways (one per AZ)
- Application Load Balancer (Internet-facing)
- EC2 instances in private subnets
- Auto Scaling Group (min=2, max=4)
- S3 Gateway Endpoint
- CloudWatch Alarms + SNS notifications
- VPC Flow Logs + Network ACLs

## Region
AWS Asia Pacific (Mumbai) - ap-south-1

## Live Demo
ALB DNS: project-alb-110472371.ap-south-1.elb.amazonaws.com
