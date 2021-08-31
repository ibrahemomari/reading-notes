# AWS: Events

These events are designed to educate you about AWS products, services, and solutions and help you develop the skills to design, deploy, and operate infrastructure and applications. Event content is delivered by subject matter experts from AWS, our partners, and our customers, who share how they have successfully built solutions on AWS.

---

# Review, Research, and Discussion

#### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

They are both ways you can implement an API. Within an Express Server you define your routes and write the logic for them. With AWS API Gateway, you set up your routes and then implement the functionality using lamda functions.

#### List the AWS Database offerings and talk about the pros and cons of each

AWS database offerings include:

1. RDS

1. DynamoDB

1. ElastiCache

1. Neptune

1. Amazon QLDB

1. Amazon DocumentDB

1. Amazon Keyspaces

1. Amazon Timestream

They are each comparable to different db services. RDS is similar to oracle SQL, DynamoDB is similar to MongoDB, Aurora is MySQL, postrgeSQL compatible, etc.

Pros: They are scalable, managed, secure, easy to work with, and scalable

Cons: The only major con I can see is the cost.

#### What’s the difference between a FIFO and a standard queue?
A FIFO queue is first in first out and a standard queue provides at least once delivery and isn't neccessarily ordered.


#### How can the server be assured a message was properly received?
Logging and using timestamps and checking whether it was delivered based on the response sent from the endpoint.


---
Document the following Vocabulary Terms
===

**Serverless API**
An API that lives in the cloud and is created using cloud services.

**Triggers**
Essentially a connection between resources. When something happens to a resource, it triggers an action to be taken.

**Dynamo vs Mongo**
Dynamo is like the AWS version of Mongo. Mongo is open source and uses JSON objects, whereas Dynamo uses tables. MongoDB is less restrictive of data types and size.

**Dynamoose vs Mongoose**
Dynamoose is a modeling tool used for dynamo and mongoose is used for mongo.


---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com