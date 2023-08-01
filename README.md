# Microservice Demo

## Function-Driven Service Splitting:
- Breaking down the application into independent services based on distinct business functions, such as order service, user service, and payment service.
- Key points:
  - Single Responsibility Principle: Ensure that each service has a clear and well-defined responsibility, focusing on a specific business domain or function. Avoid creating services that are too broad or have overlapping responsibilities.
  - Loose Coupling: Aim for loose coupling between services to maintain independence and minimize dependencies. Avoid creating tightly coupled services that can lead to cascading changes and complexities.
  - Domain-Driven Design: Apply principles of Domain-Driven Design to identify bounded contexts and define clear domain boundaries. Align services with these bounded contexts to promote better understanding and maintenance.
 
## RESTful API Remote Communication:
  -   Using HTTP and RESTful API to enable remote communication between microservices. Each microservice exposes APIs to expose its functionality and allows interaction using standard HTTP methods like GET, POST, PUT, DELETE.
