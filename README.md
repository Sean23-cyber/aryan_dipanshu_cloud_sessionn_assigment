# 🚀 DropClone - Cloud Storage Application

**Live Demo:** [http://65.0.45.247/](http://65.0.45.247/)  
**Status:** 🟢 Active Development  
**Last Updated:** November 3, 2025  

---

## 📄 Overview

**DropClone** is a cloud-based file storage and management system that provides users with secure file upload, download, sharing, and versioning capabilities — similar to Dropbox.  
Built with **React**, **Node.js**, and **AWS (S3, DynamoDB, Cognito)**, it demonstrates modern full-stack web development and cloud-native architecture practices.

---

## 🌐 Live Preview

👉 **Access the deployed version here:** [http://65.0.45.247/](http://65.0.45.247/)

---

## ✨ Key Features

- 🔒 **Secure Authentication** using AWS Cognito (Sign-up, Login, Email Verification)
- ☁️ **File Uploads** directly to AWS S3 via Multer-S3 streaming
- 🗂️ **File Management** (list, download, share, delete)
- 📦 **File Versioning** with AWS S3
- 📊 **Metadata Storage** in DynamoDB (filename, size, timestamp, etc.)
- ⚙️ **RESTful APIs** built with Express.js
- 🧠 **Scalable & Serverless Architecture** leveraging AWS infrastructure

---

## 🧱 System Architecture

### 🔹 Frontend (React 19.2.0)
- React Router DOM 7.9.3 (Client-side routing)
- Axios (HTTP client)
- Lucide React (Icons)
- React Hot Toast (Notifications)
- AWS Amplify (Cognito Integration)

### 🔹 Backend (Node.js + Express 4.18.2)
- Express with CORS & dotenv
- AWS SDK v3:
  - `@aws-sdk/client-s3`
  - `@aws-sdk/client-dynamodb`
  - `@aws-sdk/client-cognito-identity-provider`
- Multer & Multer-S3 for file upload handling
- JWT authentication with Cognito tokens

### 🔹 Cloud Services (AWS)
| Service | Purpose |
|----------|----------|
| **AWS Cognito** | Authentication & user management |
| **AWS S3** | File storage with versioning |
| **AWS DynamoDB** | File metadata storage |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/dropclone.git
cd dropclone
