# Swagger + SpringFox + SpringBoot example

This is a simple example to demonstrate Swagger with Spring Boot.  The integration
is handled by SpringFox, a 3rd party library for enabling Swagger on Spring MVC projects.

For more information on SpringFox, pleas visit [http://springfox.io](http://springfox.io)

This demo is from [this repo](https://github.com/swagger-api/swagger-samples/tree/master/java/java-spring-boot)

To run this do the following:

- `mvn clean package`
- `java -jar target/swaggerhub-spring-boot-sample-1.0.0-SNAPSHOT.jar`


- To check if it's working: http://localhost:8080/v2/pets/1
- To get to swagger json: http://localhost:8080/v2/swagger.json
- To get to swagger UI: http://localhost:8080/v2/index.html