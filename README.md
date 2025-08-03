# project13-serverless-api-lambda-gateway
Serverless REST API built using AWS Lambda and API Gateway with CI/CD-ready structure.
# Project 13: Serverless API Deployment (Lambda + API Gateway)


This project demonstrates the creation, configuration, deployment, and testing of a **serverless RESTful API** using **AWS Lambda** and **Amazon API Gateway**. It is part of my Cloud Security & DevSecOps portfolio to showcase real-world implementation of secure, scalable serverless architecture using infrastructure automation and monitoring tools on AWS.

---

## 📖 Project Summary

- **API Name:** `project13-hello-api`
- **Lambda Function:** `project13-hello-lambda`
- **Route:** `/project13-hello-lambda`
- **Method:** `ANY`
- **Invoke URL:** [Click to View Output](https://htjvbpmjd1.execute-api.us-east-1.amazonaws.com/project13-hello-lambda)
- **Output:** `"Hello from Lambda"`
- **Region:** `us-east-1 (N. Virginia)`
- **Architecture Type:** Serverless (Fully Managed)

---

## 🎯 Objectives

- Deploy a fully functional Lambda-based API endpoint.
- Integrate Lambda with API Gateway using REST API routes.
- Automate deployment using `$default` stage.
- Verify permission, routing, and API execution.
- Showcase end-to-end serverless app lifecycle.

---

## 🔧 Tools & Services Used

| Service           | Purpose                                        |
|-------------------|------------------------------------------------|
| AWS Lambda        | Host function code triggered by HTTP requests |
| API Gateway       | Expose Lambda via HTTP/REST endpoint          |
| CloudWatch        | Monitor Lambda execution & logs               |
| IAM               | Manage access between API Gateway and Lambda  |
| GitHub            | Version control and documentation             |

---

## 🛠️ Implementation Steps

1. **Lambda Creation:**
   - Created a simple function returning `"Hello from Lambda"` in Python.
   - Tested standalone output.

2. **API Gateway Setup:**
   - Created `project13-hello-api` using HTTP API type.
   - Added route `/project13-hello-lambda` with method `ANY`.
   - Attached integration to `project13-hello-lambda`.

3. **Deployment:**
   - Created and deployed default stage (`$default`).
   - Enabled **automatic deployment** on updates.

4. **Permissions:**
   - Verified Lambda’s resource policy allows invocation by API Gateway.
   - Used CLI or console integration tab to check permission bindings.

5. **Invoke API:**
   - Accessed public HTTP endpoint.
   - Verified response: `"Hello from Lambda"`

---

## ✅ Skills & Competencies Demonstrated

- API Gateway Routing and Integration
- Lambda Function Security and Permissions
- Serverless Deployment Strategy
- IAM Role Trust Relationships
- HTTP Endpoint Validation
- Monitoring & Debugging via Logs
- Real-World Serverless Patterns

---

## 📷 Screenshots

> All screenshots for setup and test outputs are available in the attached ZIP:
- [📦 Download Screenshots](./project13-serverless-api-lambda-gateway.zip)

---

## 📁 Repository Structure

```plaintext
project13-serverless-api-lambda-gateway/
├── lambda-function-code/
│   └── index.py
├── screenshots/
│   ├── integration-setup.png
│   ├── route-config.png
│   ├── stage-deployment.png
│   └── output-verification.png
├── README.md
└── project13-serverless-api-lambda-gateway.zip

