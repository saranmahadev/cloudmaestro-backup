## Automated Deployment | Task - 7

## Introduction
Took my time to get into this Phase, I had my semester lined up and busy with other work and finally got over all the other work and moving forward. In this task, I am using Terraform. 

### Why Terraform?
As I was working on AWS on the previous tasks, This time also I decided to get into AWS and I was learning AWS CloudFormation to do the work. AWS CloudFormation looked fine but I did that work before and I dont want to do it again for the blog, so I decided to learn a fresh tool called Terraform.

### Terraform 
Terraform is a interesting tool which helps us to manage the entire lifecycle of infrastructure using infrastructure as code.It has very simple CLI and uses Hashicorp Configuration Language to do the work and also it had a excellent [documentation](https://www.terraform.io/docs/).

### Hands On:
Since this is my first time on Terraform, I decided to do a simple beginner level project of deploying a t2.micro instance in aws.

- I referred the documentation and wrote the script as given and I took my time to learn and did the work.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1628841067647/hSADzNmjU.png)

- After the script was written, I initialized terrform on the folder using the command.
```
terraform init
```
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1628841167696/Mqhv0IC-c.png)

- After the intialisation, To look into the resources that are going to deployed, I used the command
```
terraform plan
```
and since it had a long output, I was unable to capture the output but showed that it will create my instance.

- After that I applied the **main.tf** and deployed the instance using the command
```
terraform apply
```
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1628842372365/t5asoUj3k.png)
![8FQ9M67n-.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1628842863028/_KUEbhYoQ.png)

- After the deployment, I decied to delete the resource, so used the command
```
terraform destory
```
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1628842697429/FY5McZv6u.png)
 

## Conclusion
Loved the learning and in future you can expect more projects on Terraform, I might even create a series on terraform. Lets not decide the future...In present, terraform was awesome and I really liked it!