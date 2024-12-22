# workshop-html

Description:
This project is an entry point to actually solving a real problems. A simple html website that I can experiment with in my freetime. Goal: integrate tools and technologies to build and deploy a full stack solution.

Resources:
Python : Will be using Python to make a small backend for storing data coming in from contacts form. 
Terraform : Infrastructure in AWS will be provisioned with Terraform and an Nginx server will be setup to serve the website
AWS : Will be using AWS ECS running in Fargate
Ansible : Later configurations will be experimented

Objectives:
Build a static website with html and css for learning and axperimentation
Create a backend to handle contact form submissions
Automate infrastructure deployment with Terraform
Deploy the html. backend and Nginx server on ECS with Fargate
Experiment with Ansible for configuration. Maybe enhance something and see it working

For my memory (steps for creation):
1. Terraform main.tf:
   Provision ECS cluster with Fargate tasks
   Deploy an Nginx Docker container to serve the html files on ECS fargate
   
2. Jenkins:
   Jenkins will be part of the CI/CD pipeline and will be installed on an EC2 -> will be used for later development (will be created in the same script along other resources using Terraform)
   
3. Docker with AWS:
   After building Docker image with Nginx inside push to ECR for use in ECS Fargate

4. Configuration management with Ansible:
   Later experiment with Ansible to manage configurations and automate tasks
   Add details later!
