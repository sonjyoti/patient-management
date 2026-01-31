**A simple Spring Boot project to understand the operation and communication of microservices.**

Microservices added:
- Patient service: Handles all the CRUD operations for fetching, modifying, and deleting users.
- Billing service: Handles billing purposes for users.
- Api-Gateway: Handles all external requests to one point and then forwards those requests to the appropriate microservice, which improves security by not exposing all the internal ports to an outside request.

Technologies and Dependencies Used: 
- Java 21
- Spring Boot v3.4.1
- Docker
- gRPC
- Kakfa
- Spring Cloud
- Maven
