## Amazon EC2

## Amazon EC2

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) Cloud. Amazon EC2 is easy to launch as many or as few virtual servers as you need and will be able to configure security and networking, and manage storage as needed.

## Accessing EC2

There are two ways to access EC2:

- Web-Based User Interface  and
- Command Line Interface

### Web-Based User Interface

The AWS Management Console is the Web-Based User Interface where you can fire up an instance using graphical user interface.

### Command Line Interface

- AWS Command Line Interface(CLI)

AWS Provides a set of different commands to access their different products 

Example:
```
$ aws ec2 create-security-group --group-name my-sg --description "My security group
``` 
The above example creates an security group of name "my-sg" with a description of "My Security Group". Similarly AWS Provides different commands for different Services. 

## Pricing

Amazon EC2 provides the following purchasing options for instances:

- On-Demand Instances
Pay for the instances that you use by the second, with no long-term commitments or upfront payments. [More](https://aws.amazon.com/ec2/pricing/on-demand/)

- Savings Plans
Making a commitment to a consistent amount of usage, in USD per hour, for a term of 1 or 3 years.[More](https://aws.amazon.com/savingsplans/)

- Reserved Instances
Making a commitment to a specific instance configuration, including instance type and Region, for a term of 1 or 3 years.[More](https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/)

> **Remember**:   Savings Plan is a commitment to a **consistent amount of usage ** where Reserved Plan  is a commitment to **a specific instance configuration**.

- Spot Instances
Request unused EC2 instances, which can reduce your Amazon EC2 costs significantly.[More](https://aws.amazon.com/ec2/spot/pricing/)
---

To Be Continued...





