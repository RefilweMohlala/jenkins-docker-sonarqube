#Jenkins & SonarQube Integration

##Overview
This project demonstrates the integration of Jenkins and SonarQube to automate code analysis and build pipelines. Jenkins is used to run automated builds, while SonarQube analyzes code quality. The setup includes creating an EC2 instance, configuring Jenkins, and integrating SonarQube.

##Steps
1.Create EC2 Instance: Launch an EC2 instance and install Jenkins.
2.Configure Jenkins: Set up Jenkins with the necessary plugins and create a pipeline.
3.Integrate GitHub: Connect Jenkins to GitHub to automate code building and deployment.
4.Set Up SonarQube: Install and configure SonarQube to analyze code quality.
5.Run Build & Analysis: Trigger the pipeline from GitHub to run Jenkins, perform the code analysis via SonarQube, and deploy the application.

##Screenshots
SonarQube Analysis Success: Screenshot showing the successful code analysis result.
Jenkins Build Success: Screenshot showing a successful Jenkins build.

##Tools Used
-Jenkins
-SonarQube
-GitHub

##Cleanup
-EC2 Instances and associated resources (like EBS) were terminated.
-Jenkins and SonarQube configurations have been cleaned.

##Conclusion
This setup provides a streamlined approach to automating code analysis and continuous integration with Jenkins and SonarQube.
