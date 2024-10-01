# DevOps Portfolio: NodeJS CI/CD Pipeline with Jenkins, Docker, and AWS Deployment

Welcome to my **DevOps Portfolio**! This repository showcases my work on implementing a full **CI/CD pipeline** for a **NodeJS application** using **Jenkins**, **Docker**, and **AWS**. It demonstrates my ability to integrate various DevOps tools and best practices to automate application deployment and infrastructure management.

## Overview

This project highlights:
- **Automated CI/CD Pipeline** using **Jenkins**.
- **Containerization** with **Docker**.
- **Automated testing**, **building**, and **deployment** of the application.
- **Deployment to AWS EC2** instance using **Docker Compose**.
- **Branch-based logic** to handle feature development and production releases.

By visiting this repository, you'll get a glimpse of my technical skills in building scalable, automated DevOps workflows.

---

## Features

### 1. NodeJS Application
The core of this project is a **NodeJS** application. The app lists developers and their associated projects, serving as a simple example of a web application that can be deployed via **Docker** containers.

### 2. CI/CD Pipeline with Jenkins
The Jenkins pipeline is designed to:
- **Run tests** to ensure the codebase remains stable.
- **Build Docker images** and push them to a Docker registry.
- **Deploy the application** to an **AWS EC2 instance** using **Docker Compose**.
- Handle **branch-specific workflows**: only the `master` branch gets deployed, while other branches run tests.

### 3. Dockerized Deployment
The application is containerized using **Docker**. This ensures that the application can be easily deployed across various environments with consistent behavior.

### 4. Deployment to AWS
The NodeJS application is deployed on an **AWS EC2 instance**. The pipeline automates the deployment process using **SSH** to connect to the EC2 instance and run the Dockerized application.

### 5. Branch-Based Pipeline Logic
- **Master branch**: Executes the full CI/CD pipeline, including testing, building, and deploying the application.
- **Other branches**: Run tests only, without deployment.

### 6. Automated Webhook Trigger
A **webhook** triggers the pipeline automatically when code is pushed to the repository, ensuring that all updates are continuously integrated and deployed.

---

## Technologies Used
- **Jenkins**: CI/CD pipeline automation.
- **Docker**: Containerization of the application.
- **Docker Compose**: For managing multi-container Docker applications.
- **AWS EC2**: Cloud infrastructure for hosting the NodeJS application.
- **AWS CLI**: Used for managing AWS resources programmatically.
- **Git**: Version control for code management.

---

## Future Enhancements

- **Auto-scaling**: Implement AWS auto-scaling groups
- **Load Balancing**: Add an AWS Load Balancer for high availability.
- **Monitoring and Alerts**: Integrate tools for real-time monitoring and alerting in case of pipeline or deployment failures.
- **Kubernetes Integration**: Extend deployment strategy to Kubernetes for better scaling and management.

---

## Conclusion

This repository showcases my expertise in setting up a CI/CD pipeline with **Jenkins** for a **NodeJS** project, complete with Dockerization, automated testing, and version control. I hope this project demonstrates my DevOps skills and serves as a valuable addition to my portfolio.

**Thank you for visiting my repository! 😊**
