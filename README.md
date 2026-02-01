# High Availability Game Web Application on AWS

## Objective
Deploy a highly available web application using Ubuntu EC2, Nginx,
Application Load Balancer, Auto Scaling Group, S3, and CloudWatch.

## Architecture
User → ALB → Auto Scaling Group → EC2 (Ubuntu + Nginx)

## Services Used
- Amazon EC2
- Amazon S3
- Application Load Balancer
- Auto Scaling Group
- Amazon CloudWatch

## Outcome
The application remains available during instance or AZ failure.
