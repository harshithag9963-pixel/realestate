# 🏠 Real Estate Analytics Platform

![React](https://img.shields.io/badge/React-18-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![AWS](https://img.shields.io/badge/Cloud-AWS-orange)
![Docker](https://img.shields.io/badge/Containerized-Yes-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A **data-driven Real Estate Analytics Platform** built with **React.js**, **Node.js**, and **MongoDB**, providing insights on property listings, pricing trends, and customer engagement.  
Deployed on **AWS** with **Docker** containers and **CI/CD** automation for seamless scalability and performance.

---

## 🚀 Features

- 📈 **Property Analytics Dashboard** – View market trends and price insights in real time  
- 🏢 **Dynamic Search & Filters** – Filter properties by price, location, or type  
- 💬 **User Interaction** – Buyers and sellers can chat or send inquiries  
- 🔐 **Authentication & Authorization** – Secure JWT-based login system  
- ☁️ **Cloud Deployment** – Hosted on AWS EC2 with CloudWatch monitoring  
- 🐳 **Dockerized Microservices** – Modular backend and frontend services  
- 🧠 **Automated Observability Pipelines** – Real-time error tracking and uptime monitoring

  ```

## 🧱 Architecture Overview

```mermaid
flowchart TD
    A[React Frontend] -->|REST API Calls| B[Node.js Backend (Express)]
    B --> C[(MongoDB Database)]
    B --> D[(Analytics Engine / CloudWatch)]
```


