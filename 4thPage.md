## Exercise4: Creating task definition
## Task 1: Creating task definition and copying ECR URL
1. Goto ECS and from side bar select ***Task definition*** and click new task definition
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-1.png) 
2. Give name for new Task definition
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-2.png)
3. In container section paste the ECR URL and provide name for it then click on create
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-3.png)
## Exercise5: Creating Cluster and Service
## Task 1: Creating cluster and launching new service in it
1. From side bar click on ***clusters*** and create new cluster
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ec4.png)
2. Provide unique name and click on create cluster
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-5.png)
3. Go back under created cluster click on ***create*** service option
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-6.png)
4. Here select created task definition under ***Family*** section and click on create
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-7.png)
5. After waiting of few minutes you can see your service is running successfully
![image](https://ganes1233e3edjenjjd.s3.ap-south-1.amazonaws.com/ecs-8.png)
