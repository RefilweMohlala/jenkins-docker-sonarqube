# Jenkins & SonarQube Integration

## Overview
This project demonstrates the integration of Jenkins and SonarQube to automate code analysis and build pipelines. Jenkins is used to run automated builds, while SonarQube analyzes code quality. The setup includes creating an EC2 instance, configuring Jenkins, and integrating SonarQube.

## Steps
1.Create EC2 Instance: Launch an EC2 instance and install Jenkins.
2.Configure Jenkins: Set up Jenkins with the necessary plugins and create a pipeline.
3.Integrate GitHub: Connect Jenkins to GitHub to automate code building and deployment.
4.Set Up SonarQube: Install and configure SonarQube to analyze code quality.
5.Run Build & Analysis: Trigger the pipeline from GitHub to run Jenkins, perform the code analysis via SonarQube, and deploy the application.

## Screenshots
SonarQube Project Dashboard
![SonarQube Project Dashboard](https://github.com/user-attachments/assets/2a00a1b4-cf2f-4787-b3be-7121a2ce4a7f)
SonarQube Quality Gate Results
![SonarQube Quality Gate Results](https://github.com/user-attachments/assets/e3b997f7-a7f2-41fa-9f6a-bc36a3257650)
Jenkins Log Output
![Jenkins Log Output](https://github.com/user-attachments/assets/2929a3e0-2748-4b5d-b93c-88f255bc5a2e)
Jenkins Dashboard
![Jenkins Dashboard](https://github.com/user-attachments/assets/49911d9c-0e8f-47ee-b327-e33e8c67e550)

## Tools Used
-Jenkins
-SonarQube
-GitHub

## Cleanup
-EC2 Instances and associated resources (like EBS) were terminated.
-Jenkins and SonarQube configurations have been cleaned.

## Conclusion
This setup provides a streamlined approach to automating code analysis and continuous integration with Jenkins and SonarQube.
