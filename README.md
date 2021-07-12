# This is Spring Boot app REST API, using SPRING DATA REST and all CRUD methods with database.We was using POSTMAN REST CLIENT to test all HTTP REQUEST METHODS (GET,POST,PUT,DELETE).SPRING DATA REST leverages your existing JpaRepository 
and Spring will give you REST CRUD implementation automatically(for free).
SPRING DATA REST will expose endpoints for free.First of all SPRING DATA REST will scan your project for JpaRepository, 
after that will expose REST APIs for each entity type for your JpaRepository.We only need 3 things:
1.Your entity Employee, 2.JpaRepository and 3. MAVEN POM dependency for spring-boot-starter-data-rest.
Now we don't need REST CONTROLLER LAYER AND SERVICE LAYER, so we deleted them.This way we can minimize our code.
