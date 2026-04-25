# ⚙️ Deployment Guide

## 📌 Prerequisites
- AWS Account
- AWS CLI installed
- IAM permissions configured

---

## 🚀 Steps

### 1. Deploy Static Website (S3)
- Create S3 bucket
- Enable static hosting
- Upload website files

---

### 2. Launch EC2 Instance
- Choose Ubuntu AMI
- Install Python and Flask
- Deploy application

---

### 3. Configure IAM
- Create roles for EC2 and Lambda
- Attach required policies

---

### 4. Deploy Lambda Function
- Create Lambda function
- Upload Python script
- Assign IAM role

---

### 5. Setup DynamoDB
- Create table
- Define primary key

---

### 6. Configure CloudWatch
- Create dashboard
- Setup alarms

---

## ✅ Verification
- Access S3 website
- Check EC2 endpoint
- Monitor logs in CloudWatch
