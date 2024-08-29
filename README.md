# counter-service-cicd-demo
CICD demo for testing purposes

# Project Overview
The goal of this project is to develop a simple service named counter-service.

# Key Features
Counter Management: The service will maintain a counter that tracks the number of POST requests it has served.
Web Page Interface: The counter's value will be displayed on a web page and returned for every GET request received.
Requirements
Code Simplicity: The implementation should be as straightforward as possible while being well-documented and robust.
Port Exposure: The counter-service must be accessible via port 80.
Docker Integration: Build the counter-service into a Docker image and deploy it as a Docker container on an EC2 instance.
Service Downtime: Short service downtime is acceptable during redeployment.
CI/CD Pipeline: Upon commit and push, the code should pass CI/CD processes and be deployed as a running Docker container on the EC2 instance.
Code Quality and Security: Integrate SonarCloud for code quality analysis and Snyk for vulnerability scanning into the CI pipeline.
CI/CD Process
SonarCloud: Analyze the code for quality issues and maintainability.
Snyk: Scan for vulnerabilities and ensure dependencies are secure.

This demo includes the following services

![image](https://github.com/user-attachments/assets/67ef1574-3c9c-4b2b-8d40-5ffd3be3f60f)
