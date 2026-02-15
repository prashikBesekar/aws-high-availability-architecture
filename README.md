#AWS Highly Available Web Architecture

## Project Overview
This project demonstrates deployment of a highly available and scalable web application architecture on Amazon Web Services (AWS). The system is designed to automatically recover from failures and scale based on demand.

## Architecture
User → Application Load Balancer → Auto Scaling EC2 Instances → S3 → CloudWatch Monitoring

## Services Used
- EC2 (Compute)
- Application Load Balancer
- Auto Scaling Group
- S3 Static Website Hosting
- IAM Roles & Policies
- CloudWatch Monitoring

## Key Features
- High availability using multiple EC2 instances
- Fault tolerance using health checks
- Automatic scaling using Auto Scaling Group
- Secure access using IAM roles
- Monitoring using CloudWatch alarms

## Steps Performed
1. Launched EC2 instances and installed Nginx
2. Configured Security Groups and networking
3. Created Application Load Balancer and Target Group
4. Created AMI and Launch Template
5. Configured Auto Scaling Group
6. Hosted static website on S3
7. Implemented IAM roles for EC2 to S3 access
8. Configured CloudWatch monitoring and alarms

## Outcome
The system automatically replaces unhealthy instances and distributes traffic evenly across healthy servers ensuring high availability.
