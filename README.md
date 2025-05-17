# 🌱 What If Chain Reactions

**What If Chain Reactions** is a collaborative storytelling web app where users create branching narratives based on imaginative "What if?" scenarios. Each scenario can lead to endless possible storylines, shaped by user-generated replies.

> Example:  
> ❓ *What if humans could breathe underwater?*  
> ➡️ Someone replies with *Cities would form under the ocean*  
> ➡️ Another adds *Coral reefs would become metropolises*  
> ➡️ And so on...

---

## 🚀 Tech Stack

### 🖥️ Frontend
- [V0.dev](https://v0.dev) – For designing UI components (React + Tailwind)
- Hosted on **Amazon S3 + CloudFront**

### ⚙️ Backend
- **AWS Lambda** – Serverless compute functions
- **API Gateway** – RESTful API endpoints
- **DynamoDB** – Fast and scalable NoSQL database
- **CloudWatch** – Logs and metrics

### 🧱 Infra
- **AWS SAM CLI** – Deploy and manage serverless infrastructure
- (Later stages) **Cognito**, **SES**, **SQS**, **Neptune**, **Step Functions**

---

## 🗂️ Features

### MVP:
- Create new “What if” questions (root nodes)
- Reply to any existing node to create a new branch
- View full threads as branching stories
- Explore recent or popular chains

### Future Enhancements:
- User login via Cognito
- Email notifications for replies (SES/SNS)
- Graph-style story visualization (D3.js or React Flow)
- Moderation queue for flagged content (SQS)

---

## 📁 Project Structure

