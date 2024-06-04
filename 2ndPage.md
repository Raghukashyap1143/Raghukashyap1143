# Introduction to ECS (Elastic Container Service)

## Lab Duration : 1hr

## What is AWS ECS used for?:
Amazon ECS offers a fully managed container orchestration solution, streamlining the process for organizations to develop, deploy, and manage containerized applications of any scale on AWS. This can be achieved using either traditional Amazon Elastic Cloud Compute (EC2) instances or leveraging serverless computing with AWS Fargate.

## Key Learnings:
In this hands-on lab, you will be learning the following:

* Understanding ***ECS and ECR*** Dashboard and its features
* Creating a container image for use on Amazon ECS
* Pushing docker image to the Amazon ECR repository
* Creating blueprint for your application i.e Task definition
* logical grouping of tasks or services i.e ECS Clusters

## Hands-on Labs

* ***[Exercise1](#exercise1-launching-of-linux-ec2-instance):*** Launching of Linux EC2 Instance
* ***[Exercise2](#exercise2-setting-up-docker-through-instance-terminal):*** Setting up Docker through Instance terminal
* ***[Exercise3](#exercise3-create-and-pull-view-commands-through-ecr-console):*** Create and pull view commands through ECR console
* ***[Exercise4](#exercise4-creating-task-definition):*** Creating task definition
* ***[Exercise5](#exercise5-creating-cluster-and-service):*** Creating cluster

# Exercise1: Launching of Linux EC2 Instance

This exercise will help you to launch Instance and what all parameters to be considered.

Here we are selecting the linux instance. where With larger instances, you can launch more tasks at the same time. With smaller instances, you can scale out in a more fine-grained way to save costs. we can create multiple Auto Scaling groups where each group has a different instance type for different applications.

## Task 1: Launching an EC2 Instance
1. Select EC2 service from home console or you can find it from all service list
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-1.png)
2. Select on ***Launch Instances*** to create new instance
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-2.png)
3. Provide unique name for instance and create or select key pairs
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-3.png)
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-4.png)
4. Select default VPC and select Enable option for ***Auto-assign public IP***
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-5.png)
5. Then click on ***Launch Instance***
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-6.png)
6. Now click on ***Connect*** then you will redirect to Linux terminal
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-7.png)
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec2-8.png)
