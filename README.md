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

add zipkin server to monitor logs

docker run -d -p 9411:9411 openzipkin/zipkin

https://youtu.be/BnknNTN8icw

### Services URLs

config server url = http://localhost:9296

cloud gateway url = http://localhost:9191

service registry url = http://localhost:8761

department service url = http://localhost:9001

user service url = http://localhost:9002

### end points

https://www.getpostman.com/collections/c26778c7eec72911f135
