# 📊 Customer Management Portal

A robust, full-stack customer management dashboard crafted to provide seamless user registration, profile management, and actionable insights. Built with a modern technology stack, it emphasizes security, scalability, and automated deployment pipelines.

---

## ✨ Key Features
- **User Authentication:** Secure registration and login flows using JWT (JSON Web Tokens).
- **Profile Management:** Seamless upload and storage of profile pictures via AWS S3.
- **Customer Insights:** An intuitive dashboard providing at-a-glance data visualizations.
- **Robust Security:** Powered by Spring Security 6 with strict CORS policies and endpoint protection.
- **Automated CI/CD:** Continuous integration and deployment via GitHub Actions.
- **Containerized Environments:** Fully Dockerized setup for consistent local testing and production deployment.

## 💻 Tech Stack

**Frontend:**
- React.js
- JavaScript
- Component-based Architecture

**Backend:**
- Java & Spring Boot 3
- Spring Data JPA / JDBC
- Spring Security 6

**Database & Storage:**
- PostgreSQL
- Flyway (Database Migrations)
- AWS S3 (Cloud Storage)

**DevOps & Infrastructure:**
- Docker & Docker Compose
- GitHub Actions (CI/CD)
- AWS IAM, EC2, and Elastic Beanstalk (Hosting & Security)

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- Java JDK
- Node.js & npm
- Docker & Docker Compose
- PostgreSQL

### Local Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/DevanshXerc90/Springboot-React-Fullstack.git
   cd Springboot-React-Fullstack
   ```

2. **Run with Docker (Recommended):**
   The easiest way to spin up the entire environment (database, backend, frontend) is using Docker Compose.
   ```bash
   docker-compose up --build
   ```

3. **Manual Setup (Backend):**
   Navigate to the `backend` directory, configure your database credentials, and run the server.

4. **Manual Setup (Frontend):**
   Navigate to the `frontend` directory, install dependencies, and start the development server:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## 🏗️ Architecture Overview
This application is decoupled into independent layers:
- **Authentication Service:** Manages JWT generation, validation, and user sessions.
- **Customer Service:** Handles CRUD operations for customers, including S3 image integration.
- **Security Configuration:** Ensures state-of-the-art protection across all API endpoints.

## 👨‍💻 Author
Created and maintained by **[DevanshXerc90](https://github.com/DevanshXerc90)**.

---
*If you find this project helpful, please consider giving it a ⭐!*
