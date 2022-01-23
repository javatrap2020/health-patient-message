# Health Patient Message

This project has Spring-boot, MySQL and MongoDb database

# Run

!!!! `application.properties setting for your databases`

`mvn clean`

`mvn package`

`mvn spring-boot:run`

Navigate to `http://localhost:8080/`

Postman GET  `localhost:8080/api/patients`
 {
        "firstName": "Java",
        "lastName": "Trap",
        "email": "java@gmail.com",
        "message": "Hello World"
 }

