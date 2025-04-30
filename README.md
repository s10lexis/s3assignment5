# AWS Serverless File Upload Notification System

This project implements a real-world AWS serverless architecture that reacts to file uploads in S3, sends alerts via Slack and SNS, and stores metadata in DynamoDB.

## 🧱 Architecture Overview

- **S3**: Stores uploaded files
- **Lambda**: Processes upload events
- **SNS**: Sends email notifications
- **Slack Webhook**: Posts alerts to a Slack channel
- **DynamoDB**: Stores file metadata
- **CloudWatch**: Logs Lambda execution

## 📂 Project Structure
