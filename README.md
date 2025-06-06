# 🤖 ng-mission-assist

**ng-mission-assist** is a secure, AI-enabled frontend built with Angular that allows field agents and analysts to interact with a natural language assistant for summarizing reports, generating data briefs, and automating operational workflows. It integrates with **embedded LLM models** via **AWS Lambda** functions for lightweight, scalable inference.

The platform is designed with a modern and responsive UI, secure authentication, and full audit logging to ensure all AI interactions are traceable and compliant.

## 📌 Features

- 🧠 **AI Assistant Interface**:
  - Natural language query box with dynamic suggestions
  - Use cases: report summarization, brief generation, workflow triggers

- 🔐 **Security & Logging**:
  - OAuth2-secured login and role-based access
  - Full interaction audit trails logged via AWS CloudWatch

- 🌩️ **Cloud Integration**:
  - Model inference via AWS Lambda + API Gateway
  - Audit logs and usage metrics stored in DynamoDB

## 🧰 Tech Stack

- **Frontend**: Angular, TailwindCSS, ngx-toastr
- **AI Inference**: AWS Lambda, Python (LLM wrappers)
- **Security**: OAuth2, AWS IAM, HTTPS
- **Logging**: CloudWatch, DynamoDB

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/ng-mission-assist.git
cd ng-mission-assist
npm install
ng serve
