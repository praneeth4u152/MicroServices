Establishing Communication between Microservices

Centralized Microservice Configuration with Spring Cloud Config Server

Using Spring Cloud Bus to exchange messages about Configuration updates

Simplify communication with other Microservices using Feign REST Client

Implement client side load balancing with Ribbon

Implement dynamic scaling using Eureka Naming Server and Ribbon

Implement API Gateway with Zuul

Implement Distributed tracing with Spring Cloud Sleuth and Zipkin

Implement Fault Tolerance with Hysterix

Configuration Management
Spring Cloud Config Server : Provides configuration corresponding to different environments of all services and is maintained in git repository

Dynamic Scale Up and Scale Down
Eurekha Naming Server : All services gets registered in Eurekha Naming Server. When a service want to call another service it checks in Eurekha Naming Server

Client Side Load Balancing is wih Ribbon

Feign is used to wriht Rest Clients

Visibility and Monitoring
Zipkin Distributed Tracing server : Spring cloud sleuth is used to assign a ID across multiple components and Zipking server is used to trace based on assignment

Netflix Zuul API gateway

Fault Tolerence with Hysterix to provide default response if a service is down

