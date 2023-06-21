### Project Title: Spring Boot Microservice Architecture

# Overview

This project demonstrates the creation and implementation of a complete microservice architecture using Spring Boot. The architecture includes two microservices, a Service Registry, an API Gateway.

# Microservices

The architecture includes two microservices:

1 -  Department Service : Handles operations related to departments.




![image](https://github.com/ayoubterari/microservices-Spring-boot/assets/65574293/0244aefb-d52f-49dc-8527-ad29fd77bba7)






2 -  User Service: Manages user-related operations. Each user is associated with a department.




![image](https://github.com/ayoubterari/microservices-Spring-boot/assets/65574293/36406105-462e-441b-855d-9a63c83e3243)




# Service Registry

The Service Registry keeps track of all the microservices and their statuses. It provides a system-wide view of all active microservices.

![microservices](https://github.com/ayoubterari/microservices-Spring-boot/assets/65574293/f14dfcfc-d10c-4efb-bea0-8166915082bb)



# API Gateway

The API Gateway manages all the requests to the microservices. It acts as a single entry point for all requests, which are then routed to the appropriate microservices.



![image](https://github.com/ayoubterari/microservices-Spring-boot/assets/65574293/a046e19e-f3a8-49e2-ae16-99725fd4dbb9)

