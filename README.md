# https://github.com/roryp/java-spring-boot



# Swagger + SpringFox + SpringBoot example

This is a simple example to demonstrate Swagger with Spring Boot.  The integration
is handled by SpringFox, a 3rd party library for enabling Swagger on Spring MVC projects.

For more information on SpringFox, pleas visit [http://springfox.io](http://springfox.io)

To run this do the following:

- `mvn clean package`
- `java -jar target/swaggerhub-spring-boot-sample-1.0.0-SNAPSHOT.jar`


- To check if it's working: http://localhost:8080/v2/pets/1
- To get to swagger json: http://localhost:8080/v2/swagger.json
- To get to swagger UI: http://localhost:8080/v2/index.html

# LAB

Your task is to build a RESTful Pet Store API, which must fulfill the requirements listed below. The three resources that need to be modeled are the pets, the store, and the users. 

Use your best judgment.

The api must be able to:

- add a new pet to the Store.
- update an existing pet, both with complete and with partial data. 
- find a pet by id.
- find pets by a status.
- upload an image for the pet.
- return an aggregated list of the number of pets per status.
- place an order for a pet.
- cancel an order for a pet.
- find an order by its id.
- create a user
- find a user by user name
- delete a user
- update a user
- let a user log in
- let a user log out