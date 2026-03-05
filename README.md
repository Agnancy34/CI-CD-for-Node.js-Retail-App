# CI-CD-for-Node.js-Retail-App

### **Group No:** D06 - Group 10  
### **Project No:** DO-39

---

## Project Description
This project focuses on designing and implementing a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Node.js-based retail application. The goal is to automate the entire software development lifecycle, from code integration to deployment, ensuring faster delivery and improved reliability.

The system uses modern DevOps tools such as Git, Docker, GitHub Actions or Jenkins, and Kubernetes to automate tasks like code building, testing, containerization, and deployment. Whenever developers push code to the repository, the CI/CD pipeline automatically triggers processes that test the application, build Docker images, and deploy the application to a containerized environment.

By integrating these tools, the project demonstrates how organizations can achieve continuous integration, automated testing, and scalable deployment, which are essential practices in modern software development.

## Project Overview

The CI/CD pipeline for the Node.js Retail Application is designed to streamline and automate the software delivery process. In traditional development workflows, deploying applications manually can be time-consuming and prone to errors. This project eliminates manual intervention by implementing an automated workflow.

The development process begins when a developer pushes code changes to the GitHub repository. The CI pipeline automatically runs tests and verifies the integrity of the code. If the tests pass successfully, the application is packaged into a Docker container, which ensures that the application runs consistently across different environments.

The Docker image is then pushed to a container registry such as Docker Hub. The CD pipeline subsequently deploys the application to a Kubernetes cluster, where it runs in scalable containers. This approach ensures reliable, efficient, and repeatable deployment.

Overall, the project demonstrates a complete DevOps workflow that enhances code quality, deployment speed, and system scalability.

## Objectives

The primary objectives of this project are:

• To design and implement an automated CI/CD pipeline for a Node.js retail application.
• To ensure automatic testing and validation of code during development.
• To containerize the application using Docker for environment consistency.
• To automate the build and deployment process using GitHub Actions or Jenkins.
• To deploy the application in a Kubernetes cluster for scalable and reliable execution.
• To demonstrate the importance of DevOps practices in modern software development.
• To reduce manual errors and increase development efficiency through automation.

##  Tech Stack

| Category | Tools/Technologies Used |
| :--- | :--- |
| **IaC & Orchestration** | Terraform, Kubernetes (K8s), Docker |
| **CI/CD & Automation** | GitHub Actions, Git |
| **Backend (Control Plane)** | Node.js, Express.js |
| **Database & Auth** | MongoDB (Mongoose), JWT, Bcrypt |
| **Frontend/Templating** | EJS (Embedded JavaScript) |
| **Environment Mgmt** | Dotenv, Cookie-parser, Multer |

## Key Features
The project includes several important DevOps features that improve the development and deployment process:

1. Automated CI Pipeline
Whenever code is pushed to the repository, the CI pipeline automatically starts and performs tasks such as installing dependencies and running tests.

2. Automated Unit Testing
The pipeline ensures that the application is tested automatically to detect errors before deployment.

3. Docker Containerization
The application is packaged into Docker containers, ensuring that it runs consistently across different environments.

4. Automated Image Build and Push
The pipeline automatically builds Docker images and pushes them to Docker Hub.

5. Continuous Deployment
After successful builds, the application is automatically deployed to a Kubernetes cluster.

6. Scalability and Reliability
Using Kubernetes allows the application to scale efficiently and maintain high availability.

7. Faster Development Lifecycle
Automation significantly reduces deployment time and increases development productivity.

## 👥 Team Members

| No. | Name | Enrollment No |
|-----|------|---------------|
| 1 | MOHIT MEHARDE | EN22CS301609 |
| 2 | NAMAN MANGROLIYA | EN22CS301628 |
| 3 | NANCY AGRAWAL | EN22CS301634 |
| 4 | MAHIMA SAHU | EN22CS301570 |
| 5 | NIHARIKA PANWAR | EN22CS301645 |
| 6 | NIKHIL GARG | EN22CS301646 |

## Conclusion
The CI/CD pipeline for the Node.js Retail Application demonstrates how modern DevOps practices can improve the software development lifecycle. By automating the processes of code integration, testing, containerization, and deployment, the project ensures faster delivery of reliable software.

The integration of tools such as Docker, GitHub Actions/Jenkins, and Kubernetes enables seamless collaboration between development and operations teams. This automated pipeline reduces human errors, improves code quality, and ensures consistent deployments.

Overall, the project highlights the importance of DevOps automation in modern software engineering and provides a practical example of building a scalable and efficient CI/CD system.