# ⚡ AWS Lambda Serverless Function

## 📌 Project Overview
My first serverless function built with 
Python and deployed on AWS Lambda.

## ☁️ AWS Services Used
- **AWS Lambda** — Serverless function
- **Python 3.14** — Programming language
- **CloudWatch** — Logs and monitoring

## 🚀 What This Function Does
- Accepts a name as input
- Returns a personalized message
- Runs completely serverless on AWS Cloud

## 📥 Sample Input
```json
{
  "name": "Abhi"
}
```

## 📤 Sample Output
```json
{
  "statusCode": 200,
  "body": {
    "message": "Hello Abhi! This is Abhi's first Lambda function running on AWS Cloud!",
    "service": "AWS Lambda",
    "region": "Mumbai",
    "language": "Python"
  }
}
```

## 🛠️ What I Learned
- Creating Lambda functions
- Writing Python serverless code
- Testing Lambda with test events
- Serverless architecture concepts

## 👨‍💻 Author
**Abhi** — Cloud Developer
AWS Academy Cloud Foundations & Architecture Certified
