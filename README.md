[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jzfQvm5J)
# Project
Starter code of COMP4651 group project

### Group 23 project deployment and setup
We use the AWS Cloudformation service to model and set up AWS resources.
We create a template in YAML or JSON that describes all the AWS resources that we want to create (like Amazon EC2 instances or Amazon RDS DB instances), and CloudFormation takes care of provisioning and configuring those resources for you. That allows people to not individually create and configure AWS resources and figure out what's dependent on what; CloudFormation handles that. 

We have submitted some YAML cloudformation templates to launch multiple AWS services according to our projects' configuration (EC2 instances with Certificate Manager, and Elastic Load Balancer between the deployed EC2 instances as well as the Cognito creation and setup with a fixed Login URL to register and be able to use it in SSO)
