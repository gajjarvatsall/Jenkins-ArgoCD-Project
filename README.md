# Jenkins Pipeline for Java based application using Maven, SonarQube, Argo CD and Kubernetes

![Screenshot 2023-03-28 at 9 38 09 PM](https://user-images.githubusercontent.com/43399466/228301952-abc02ca2-9942-4a67-8293-f76647b6f9d8.png)

- **Source Code Management**: Git repository for version control.
- **Jenkins CI/CD Pipeline**: Automates the build, test, and deployment process.
- **Maven Build**: Builds the Java application using Maven.
- **SonarQube Analysis**: Analyzes code quality and provides feedback.
- **Automated Testing**: Runs unit and integration tests to validate the application.
- **Container Image to Docker Hub**: Builds and pushes the container image to Docker Hub.
- **Deployment via Argo CD**: Deploys the application to Kubernetes using Argo CD.

## Benefits

- **Automated Build and Test**: Ensures continuous integration and testing with every change.
- **Code Quality Checks**: Analyzes code quality with SonarQube to maintain high standards.
- **Containerized Deployments**: Simplifies deployment by using Docker containers.
- **Automated Rollouts and Rollbacks**: Allows easy and quick deployment rollouts and rollbacks with Argo CD.

## Getting Started

To get started, follow these steps:

1. **Configure Jenkins, SonarQube, Argo CD**:
   - Install and configure Jenkins, SonarQube, and Argo CD.
   - Set up the necessary plugins in Jenkins (e.g., Maven, SonarQube Scanner, Docker).
   - Configure SonarQube in Jenkins for code analysis.
   - Set up Argo CD for continuous deployment.

2. **Set Up Webhooks to Trigger Pipeline**:
   - Configure Git webhooks to trigger Jenkins builds automatically on code changes.


## Special Thanks
Special thanks to [Abhishek Veeramalla](https://github.com/iam-veeramalla) for the Jenkins and Argo CD guidance.


