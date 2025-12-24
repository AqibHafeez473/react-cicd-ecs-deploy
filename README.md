# React CI/CD & Containerization Project

This project demonstrates the creation of a **CI/CD pipeline** for a React application, containerized using Docker and deployed to AWS ECS (Fargate) with automated build, test, and deployment workflows.

## Features
- Automated build and test with **GitHub Actions**
- Docker containerization
- Deployment to **AWS ECS Fargate**
- Versioned Docker images pushed to **Amazon ECR**
- CloudWatch logging integration
- Secure authentication using **OIDC with AWS IAM**

## Project Architecture

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/738a95ab-f054-4516-acfa-69cacb7dc969" />


## Getting Started

### Prerequisites
- Node.js & npm
- Docker
- AWS CLI configured
- GitHub Actions access

### Setup & Run Locally
```bash
git clone <repo-url>
cd react-ci-cd
npm install
npm start

⚠️ Note: Deployment steps are currently failing because AWS resources were intentionally destroyed to avoid cost.

