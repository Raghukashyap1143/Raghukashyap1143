## Exercise2: Setting up Docker through Instance terminal
## Task 1: Download and Create new Docker image
1. Enter ***sudo su*** to switch to root user
2. Enter ***yum install docker*** command to install docker
3. Enter ***docker ps -a*** to view empty docker intially
4. Pull any docker image by ***docker pull nginx*** command

![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-1.png)

## Exercise3: Create and pull view commands through ECR console

## Task 1: Create repository and push view commands
1. In new window go to ECR console and create new public repository
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-2.png)
2. Give unique name for repository and click on create
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-3.png)
3. Select created repository and click on ***view push commands***
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-4.png)
4. You will be displayed with four testing commands
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-5.png)
5. Run all four commands in instance , by changing name to docker image
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ter-6.png)
