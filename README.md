
```markdown
# 🌐 Hosting Static and Dynamic Websites using AWS

## 📌 Project Overview
This project demonstrates how to build and deploy a scalable web application using AWS cloud services. It combines both static and dynamic content delivery using a serverless and cloud-native architecture.

---

## 🚀 Architecture Components

### 🔹 AWS Amplify
Used for hosting and deploying the front-end (HTML, CSS, JavaScript). Provides:
- Continuous deployment
- Global CDN
- Fast content delivery

### 🔹 AWS Lambda
Implements backend logic using serverless functions:
- Processes user requests
- Handles business logic
- No server management required

### 🔹 API Gateway
Acts as a bridge between frontend and backend:
- Exposes secure REST APIs
- Routes requests to Lambda functions

### 🔹 DynamoDB
NoSQL database used for:
- Storing application data
- Fast and scalable data access

### 🔹 IAM (Identity and Access Management)
Ensures secure access:
- Role-based permissions
- Least privilege access

### 🔹 Amazon Cognito
Handles authentication:
- User sign-up/login
- Secure access control

---

## 🏗️ Architecture Flow

1. User accesses frontend via Amplify
2. Frontend sends API request via API Gateway
3. API Gateway triggers Lambda function
4. Lambda processes request and interacts with DynamoDB
5. Response is sent back to frontend

---

## ✨ Key Features
- Serverless architecture
- Fully scalable backend
- Secure authentication system
- Cost-efficient deployment
- High availability

---

## 💰 Benefits

### Scalability
Automatically handles increasing traffic using AWS infrastructure.

### Cost Efficiency
Pay-as-you-go model reduces unnecessary expenses.

### Security
IAM roles and API Gateway ensure secure communication.

### Performance
Low latency with CDN and DynamoDB.

---

## 📁 Project Structure

```

aws-cloud-web-app/
│
├── frontend/        # Amplify hosted files
├── lambda/          # Lambda functions
├── api/             # API Gateway configs
├── database/        # DynamoDB schema
├── iam/             # IAM policies
└── docs/            # Documentation

```

---

## ⚙️ Deployment Steps

1. Deploy frontend using AWS Amplify
2. Create Lambda functions
3. Configure API Gateway endpoints
4. Setup DynamoDB tables
5. Configure IAM roles and permissions
6. Enable authentication using Cognito

---

## 📊 Results
- Successfully deployed a scalable web application
- Achieved secure backend integration
- Implemented real-time serverless processing
- Reduced infrastructure management overhead

---

## 🧠 Learning Outcomes
- Hands-on experience with AWS services
- Understanding of serverless architecture
- Cloud security and IAM implementation
- Full-stack cloud deployment

---

## 👨‍💻 Author
Rohan Sharma
```
