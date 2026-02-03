**A simple Spring Boot project to understand the operation and communication of microservices.**

Microservices added:
- Patient-Service: Handles all the CRUD operations for fetching, modifying, and deleting users.
- Billing-Service: Handles billing purposes for users.
- Api-Gateway: Handles all external requests to one point and then forwards those requests to the appropriate microservice, which improves security by not exposing all the internal ports to an outside request.
- Auth-Service: Handles the authorization of users to log in to the system by generating tokens using JWT.

Technologies and Dependencies Used: 
- Java 21
- Spring Boot v3.4.1
- Docker
- gRPC
- Kakfa
- Spring Cloud
- Maven
