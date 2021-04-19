# AWS Lambda

AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

The Lambda functions can perform any kind of computing task, from serving web pages and processing streams of data to calling APIs and integrating with other AWS services.

The concept of “serverless” computing refers to not needing to maintain your own servers to run these functions. AWS Lambda is a fully managed service that takes care of all the infrastructure for you. And so “serverless” doesn’t mean that there are no servers involved: it just means that the servers, the operating systems, the network layer and the rest of the infrastructure have already been taken care of, so that you can focus on writing application code.

## Term

Server Instances  : server machine run in the cloud

Containers : Containers offer a logical packaging mechanism in which applications can be abstracted from the environment in which they actually run. 
 
Cloud Services : The term "cloud services" refers to a wide range of services delivered on demand to companies and customers over the internet. These services are designed to provide easy, affordable access to applications and resources, without the need for internal infrastructure or hardware. From checking email to collaborating on documents, most employees use cloud services throughout the workday, whether they’re aware of it or not.

Cloud Architecture :  refers to the various building components that make up a cloud. The cloud, in this context, means a service often rented from a provider of computing power, storage, or business applications. You can easily imagine the cloud as a vast space with resources that you have access to from the ground. This conceptual view of the cloud ties with the majority of its characteristics.

AWS : AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services


EC2/Beanstalk vs Heroku

## Questions : 

### What’s the difference between a FIFO and a standard queue?

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing

### How can the server be assured a message was properly received?

using validatores middlewares

## What classic design pattern is best represented by event driven programming?

Observer

### How do you test an event driven system?

by mocking events
