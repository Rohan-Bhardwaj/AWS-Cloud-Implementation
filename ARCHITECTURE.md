# 🏗️ System Architecture

## 📌 Components

### 1. Amazon S3
- Hosts static website files (HTML, CSS, JS)
- Provides high durability and availability

### 2. Amazon EC2
- Runs a Flask-based web application
- Handles dynamic requests

### 3. AWS Lambda
- Automates EC2 instance management
- Executes serverless functions

### 4. Amazon DynamoDB
- Stores application data
- Provides low-latency NoSQL database services

### 5. AWS IAM
- Manages access control and permissions
- Ensures secure communication between services

### 6. Amazon CloudWatch
- Monitors logs and metrics
- Generates alerts

---

## 🔄 Data Flow
1. User accesses static website via S3
2. Dynamic requests are routed to EC2
3. EC2 interacts with DynamoDB
4. Lambda automates backend processes
5. CloudWatch monitors all services

---
