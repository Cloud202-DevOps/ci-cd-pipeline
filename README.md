# CI/CD Pipeline
## Task-01: Creating a Continuous Delivery Pipeline with GitHub Actions

### Description

This guide outlines setting up a CI/CD pipeline for deploying a Node.js application using Docker and GitHub Actions on an EC2 instance.

### Steps

1. **Setup Project Directory**
   - Create and initialize a new Node.js project.
   - Install Express and create basic application files.

2. **Create Dockerfile**
   - Write a Dockerfile to containerize the Node.js application.

3. **Push Code to GitHub**
   - Create a GitHub repository and push your project.

4. **Set Up GitHub Actions Workflow**
   - Configure GitHub Actions to build and push the Docker image to DockerHub.

5. **Deploy to EC2**
   - Launch an EC2 instance.
   - Set up a self-hosted runner on EC2.
   - Create a deployment workflow for continuous deployment.

6. **Configure Nginx**
   - Install and configure Nginx as a reverse proxy for the Docker container.

### Summary
- Build a Node.js app, containerize with Docker, and automate CI/CD with GitHub Actions.
- Deploy the container to an EC2 instance and use Nginx for routing.

---

## Task-02: Provisioning AWS Resources with CloudFormation Using GitHub Actions

### Description

Automate the provisioning of AWS resources using CloudFormation and GitHub Actions with a GitHub-hosted runner.

### Steps

1. **Setup IAM User for GitHub Actions**
   - Create an IAM user with necessary permissions.
   - Store AWS credentials as GitHub Secrets.

2. **Create CloudFormation Template**
   - Define AWS resources (e.g., EC2 instance, IAM user) in a CloudFormation template.

3. **Create GitHub Actions Workflow**
   - Set up a workflow to deploy the CloudFormation stack using GitHub Actions.

4. **Run and Monitor Workflow**
   - Push changes to trigger the workflow.
   - Monitor the workflow execution and verify resource provisioning in AWS.

### Summary
- Use GitHub Actions to deploy AWS resources defined in a CloudFormation template.
- Automate provisioning and manage infrastructure as code.

