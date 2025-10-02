# Intro to using cloud (with a few fun examples)

## Prerequisites

- Docker or podman
- go

### Basic Setup

 1. Create an AWS account and create multiple users 
 2. Setup MFA (extremely importatant to secure your account)
    - NEVER expose your cloud API keys

### Agents

1. AWS Core Services 
    Go into AWS and try using each of the following services:
    - S3 (Simple Storage Service)
        - create a bucket and add an object to it
    - EC2 (Amazon Elastic Compute - Virtual Machines)
        - create a VM and connect to it
    - SQS (Simple Queue Service)
        - don't need to actually use this, just understand why it was so impactful 
2. Extended Services
    - RDS (Relational Database Service) & DynamoDb
    - Lambda (Serverless Functions)
3. Deployment with Cloud
    - Barebones 
        - create a VM, download code, and then run from VM
    - Images
        - create an image
        - upload to image registry
        - deploy using ECS (Elastic Container Service)

