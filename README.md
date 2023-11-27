# Beginner-Guide-to-Deploying-an-End-to-End-Pipeline-from-GitHub-to-EC2-with-Jenkins.

In this lab I will be guiding you through the process of setting up a robust Continuous Integration/Continuous Deployment (CI/CD) pipeline using Amazon EC2, Terraform, Jenkins, and GitHub. By the end of this lab, you will have a fully functional environment where code changes from your GitHub repository trigger an automated deployment to an EC2 instance.

Lab Objectives:
---

1.	EC2 Instance Creation with Terraform:
Our journey begins with the creation of an EC2 instance on Amazon Web Services (AWS) using Terraform.
2.	Installation of Jenkins and Apache Web Server:
Once the EC2 instance is up and running, we'll leverage our Terraform script to install Jenkins and Apache Web Server on the instance. 
3.	Configuration of CI/CD Pipeline:
With the infrastructure in place, we'll configure Jenkins to create a CI/CD pipeline. 
4.	GitHub Integration:
To achieve seamless automation, we'll integrate Jenkins with GitHub. 
5.	Deployment to EC2 Instance:
The final step involves Jenkins deploying your application to the EC2 instance.

Prerequisites:
---

Before we dive in, make sure you have the following prerequisites in place:
+ An AWS account with appropriate IAM permissions.
+ Terraform installed on your local machine.
+ A GitHub repository containing the code you want to deploy.


