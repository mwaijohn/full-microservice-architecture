# full-microservice-architecture
Full micro services app

### Departments service:

Create new department and retrieve department by id

### User service:

Add new users together with their departments. To show the name of user departments. Department is retrieved from user department service.

### Service registry:

A eureka server that monitors all microservices in the entire architecture. Eureka

### Hystrix-dashboard:

Show microservices stats.

### cloud-gateway microservice:

Creates a common gateway to relevant microservices. Routes API requests based on their path.

### Cloud-config-server:

Loads eureka configurations
https://github.com/mwaijohn/config-server





