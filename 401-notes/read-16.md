<!-- @format -->

# Readings: AWS: Cloud Servers

## Reading

[AWS EC2](https://aws.amazon.com/ec2/)

#### What is an EC2 Instance?

Its a virtual online server that can run applications in AWS.

#### Name 2 use cases for EC2.

- Web application hosting

- Data Processing

#### Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

It offers a high level of integration with other AWS services.
Being a fully managed container makes it easier to deploy and run and manage applications at scale.

[EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg&ab_channel=Academind)

#### Where can we find EC2 on the AWS Console?

On the top menu, hover over the "Services" menu and click on "EC2" in the "Compute" category. You can also simply search for EC2 using the search bar at the top.

#### Explain the general difference between T2 Micro and XL.

provide a balance of compute, memory, and network resources. T2 Micro instances are suitable for a wide range of workloads, including web servers, development environments, and small databases.

XL instances are a type of EC2 instance that are designed for high performance computing (HPC) workloads, such as simulations, modeling, and data analysis. XL instances have a large number of CPU cores, a large amount of memory, and high-performance networking, making them well-suited for tasks that require a lot of computing power.

#### Explain a “Compute Cycle” to a non-technical friend.

To understand how a compute cycle works, it's helpful to think of a computer as a machine that can perform a series of tasks or operations. The CPU is the "brain" of the computer, and it is responsible for executing the instructions that tell the computer what to do.
The speed at which a computer can perform compute cycles is measured in hertz (Hz), which is a unit of frequency.

[Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0&ab_channel=AmazonWebServices)

#### What is Elastic Beanstalk?

Elastic Beanstalk is a service that makes it easy to deploy and scale web applications on AWS. It handles the underlying infrastructure and enables you to focus on writing code.

#### Describe the relationship between EC2 and Elastic Beanstalk.

The relationship between EC2 and Elastic Beanstalk is that Elastic Beanstalk uses EC2 instances as the underlying infrastructure to run your applications. When you deploy an application to Elastic Beanstalk, the service creates and manages the necessary EC2 instances for you. You can choose the type of EC2 instance that you want to use, such as T2 Micro or XL, and Elastic Beanstalk will automatically launch and configure the instances for you.

#### Name some benefits of using Elastic Beanstalk.

- Elastic Beanstalk is fully managed, so you don't have to worry about managing the underlying infrastructure. This includes tasks such as capacity provisioning, load balancing, auto-scaling, and application health monitoring.

- Elastic Beanstalk supports a wide variety of programming languages and platforms, so you can use the tools and technologies that you are most familiar with.

- Elastic Beanstalk integrates with other AWS services, so you can easily build, deploy, and scale applications that use other AWS services, such as Amazon Simple Storage Service (S3), Amazon Relational Database Service (RDS), and Amazon DynamoDB.
