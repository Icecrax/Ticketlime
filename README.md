# What I learned:
* Working with Spring Boot
* Working with Angular and Typescript
* Testing with JUnit
* Dependency Injection
* Building a REST API
* Working as part of team, SCRUM development

# Task:
Develope a REST based website for buying, selling and reserving tickets for different events.

## How to use:

Under `http://localhost:4200/` is the website locally accessible.

Backend can be started via `./mvnw spring-boot:run`

Frontend can be started via `ng serve`

If the database wasn't generated, then restart the backend with either one of those two commands:

`./mvnw spring-boot:run -Dspring-boot.run.profiles=generateData`
`./mvnw spring-boot:run -Dspring-boot.run.profiles=generatePerformanceTestData`

Login as admin: username=`admin` & password=`password`
Login as regular user: username=`user` & password=`password`

Under `http://localhost:8080/swagger-ui.html` is the SwaggerUI for the documention accessible.

Under `http://localhost:8080/h2-console` is the database accessible. As a path you have to enter `jdbc:h2:file:<abolutePathToProject>/database/backend` and as username=`admin` & password=`password`
    
**Note: The name is deliberately misspelled. On this task I worked in a team of 6 people. There are still some things on the design which weren't completely finished**

