# spring-cloud-gateway-demo
This article aims to provide a working example of spring cloud gateway integration with spring cloud. To get started with this project just checkout the project and import into your favourite IDE and run the main class.
The complete explanation is provided on my blog - [Spring Cloud Tutorial](https://www.devglan.com/spring-cloud/spring-cloud-tutorial)
This project uses Spring Boot 2.1.5.RELEASE


Call first service, second services via Gateway, Gateway will route requests respective micro services:

http://localhost:8088/api/v1/first/test
http://localhost:8088/api/v1/second/test