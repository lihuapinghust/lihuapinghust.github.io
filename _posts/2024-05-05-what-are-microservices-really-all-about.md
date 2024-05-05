---
title: What Are Microservices Really All About?
date: 2024-05-05 14:06:00 +0800
categories: [Tech Inteview Prep]
tags: [Fullstack]
pin: false
---

[Original Youtube Video](https://www.youtube.com/watch?v=lTAcCNbJ7KE)

## **Overview of Microservices Architecture**
* **Definition and Use**: Microservices architecture involves building scalable applications composed of many loosely coupled services. Each service handles a specific function and can be independently deployed.
* **Communication**: Services communicate via well-defined interfaces, using methods like remote procedure calls (RPC), event streaming, or message brokers.

## **Key Components**
* **API Gateway**: Manages incoming requests and routes them to appropriate microservices.
* **Service Registry and Discovery**: Helps locate and route to the relevant microservices.
* **Identity Provider**: Manages authentication and authorization of requests.
* **Monitoring and Alerting Systems**: Monitor the health of services and alert for issues.
* **DevOps Tooling**: Facilitates deployment and troubleshooting.

## **Benefits of Microservices**
* **Scalability**: Each service can be scaled independently.
* **Flexibility**: Due to the loose coupling and small service areas, systems are more resilient to failures.
* **Speed and Independence**: Teams can develop, deploy, and scale their services independently.

## **Challenges**
* **Database Decoupling**: Splits a monolithic database into separate units, which complicates maintaining data integrity as it shifts the responsibility to the application layer.
* **Operational Complexity**: Requires more resources and management compared to monolithic architectures.

## **Ideal Use-Case**
* **Suitable for Large Teams**: Provides team independence and allows for parallel development and deployment.
* **Not Ideal for Startups**: The complexity and costs are generally high, making it less suitable for smaller teams or startups.

## **Recommendation for Startups**
* **Prepare for Future Growth**: Design functions with well-defined interfaces to facilitate a future transition to microservices if needed.

This summary breaks down the key points about microservices architecture, its components, benefits, challenges, and recommendations for implementation.