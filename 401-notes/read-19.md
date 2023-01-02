<!-- @format -->

# Readings: AWS: Events

## Reading

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

#### What is the difference betweeen SQS and SNS?

SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications, while SNS is a fully managed messaging service that enables you to send messages to multiple recipients.

#### What are some use cases for both SNS and SQS?

SNS is useful for delivering messages to multiple recipients through various endpoints such as mobile devices, email addresses, and webhooks, while SQS is useful for decoupling components of a distributed application, load balancing workloads, providing a failover mechanism, and enabling asynchronous communication.

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A&ab_channel=BeABetterDev)

#### Describe how to use SQS and SNS in a “fanout” pattern.

Subscribe the SQS queues to the SNS topic, configure the SNS topic to publish messages to the SQS queues, publish a message to the SNS topic, and retrieve and process the message from the SQS queues.

#### Explain how “push notifications” work, using SNS.

Create an SNS topic and register the app with SNS to receive push notifications, setup the pushing message handler and the push notification handler.

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI&ab_channel=AWSOnlineTechTalks)

#### How might a large scale, distributed application make use of a Queue system like SQS?

It allows different components to operate independently and asynchronously, distributing workloads evenly, and providing a mechanism for failover by enabling asynchronous communication and load balancing.

Reflection

#### What are your learning goals after reading and reviewing the class README?

SNS and SQS are fascinating topics that I am hoping to have a firm understanding of how they work, the use-cases, and situations I would prefer each. 