# Udacity Project 2: Deploy a high-availability web app using CloudFormation

In this project, i have  deployed web servers for a highly available web app using CloudFormation. write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software. The procedure you follow here will become part of your portfolio of cloud projects. You’ll do it exactly as it’s done on the job - following best practices and scripting as much as possible. 

cripts
The project require to create a networking infrastructure, virtual machines, and file storage system in order to upload and test a web application. I created 5 Cloud Formation scripts and supporting bash scripts in order to simply create whole infrastructure whenever its needed, and after the job is done, to easily discard it.

Usage
It is tested for Ubuntu18.

Ensure that you have the least AWS CLI installed.

aws --version
Usage:

./create.sh (stackName) (script.yml) (parameters.json)
Example:

./create.sh Udagram infra/servers.yaml servers/infra.json
It creates a CloudFormation stack named Udagram, with infrastructure described in .yaml and .json files, AWS-region is specified in the bash script.

